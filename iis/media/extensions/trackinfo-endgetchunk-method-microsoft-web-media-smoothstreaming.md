﻿---
title: TrackInfo.EndGetChunk Method  (Microsoft.Web.Media.SmoothStreaming)
TOCTitle: EndGetChunk Method
ms:assetid: M:Microsoft.Web.Media.SmoothStreaming.TrackInfo.EndGetChunk(System.IAsyncResult)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.smoothstreaming.trackinfo.endgetchunk(v=VS.90)
ms:contentKeyID: 31469216
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.SmoothStreaming.TrackInfo.EndGetChunk
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.SmoothStreaming.TrackInfo.EndGetChunk
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# EndGetChunk Method

Method to complete the action of [BeginGetChunk](trackinfo-begingetchunk-method-microsoft-web-media-smoothstreaming_1.md).

**Namespace:**  [Microsoft.Web.Media.SmoothStreaming](microsoft-web-media-smoothstreaming-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration
PublicOverridableFunctionEndGetChunk ( _
    arAsIAsyncResult _
) AsChunkResult
'Usage
DiminstanceAsTrackInfoDimarAsIAsyncResultDimreturnValueAsChunkResultreturnValue = instance.EndGetChunk(ar)
```

``` csharp
publicvirtualChunkResultEndGetChunk(
    IAsyncResultar
)
```

``` c++
public:
virtualChunkResult^ EndGetChunk(
    IAsyncResult^ ar
)
```

``` jscript
publicfunctionEndGetChunk(
    ar : IAsyncResult
) : ChunkResult
```

#### Parameters

  - ar  
    Type: [System. . :: . .IAsyncResult](https://msdn.microsoft.com/en-us/library/ft8a6455\(v=vs.90\))  
    An [IAsyncResult](https://msdn.microsoft.com/en-us/library/ft8a6455\(v=vs.90\)) object from [BeginGetChunk](trackinfo-begingetchunk-method-microsoft-web-media-smoothstreaming_1.md).  

#### Return Value

Type: [Microsoft.Web.Media.SmoothStreaming. . :: . .ChunkResult](chunkresult-class-microsoft-web-media-smoothstreaming_1.md)  
A [ChunkResult](chunkresult-class-microsoft-web-media-smoothstreaming_1.md) object.  

## Examples

The following example loops through tracks and calls the EndGetChunk(IAsyncResult) method on each track. This method completes an asynchronous process started by [BeginGetChunk(TimeSpan, AsyncCallback, Object)](trackinfo-begingetchunk-method-microsoft-web-media-smoothstreaming_1.md). The [ChunkResult](chunkresult-class-microsoft-web-media-smoothstreaming_1.md) indicates success or failure. If the method succeeds, the [ChunkResult](chunkresult-class-microsoft-web-media-smoothstreaming_1.md) contains the Base64-encoded data. For the complete example and more information, see [Timeline Markers and Events (IIS Smooth Streaming)](timeline-markers-and-events.md).

``` 
    foreach (TrackInfo trackInfo in streamInfo.SelectedTracks)
    {
        ChunkResult chunkResult = trackInfo.EndGetChunk(argAR);

        if (chunkResult.Result == ChunkResult.ChunkResultState.Succeeded)
        {
            System.Text.Encoding enc = System.Text.Encoding.UTF8;
            int length = (int)chunkResult.ChunkData.Length;
            byte[] rawData = new byte[length];
            chunkResult.ChunkData.Read(rawData, 0, length);
            String text = enc.GetString(rawData, 0, rawData.Length);
            TimelineMarker newMarker = new TimelineMarker();
            newMarker.Text = text;
            newMarker.Time = chunkResult.Timestamp;

            SmoothPlayer.Markers.Add(newMarker);
        }
    }
```

## Version Information

#### Silverlight

Supported in: 4  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[TrackInfo Class](trackinfo-class-microsoft-web-media-smoothstreaming_1.md)

[Microsoft.Web.Media.SmoothStreaming Namespace](microsoft-web-media-smoothstreaming-namespace_1.md)
