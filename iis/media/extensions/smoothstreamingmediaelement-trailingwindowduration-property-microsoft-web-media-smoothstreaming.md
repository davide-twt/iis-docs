﻿---
title: SmoothStreamingMediaElement.TrailingWindowDuration Property  (Microsoft.Web.Media.SmoothStreaming)
TOCTitle: TrailingWindowDuration Property
ms:assetid: P:Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.TrailingWindowDuration
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.smoothstreaming.smoothstreamingmediaelement.trailingwindowduration(v=VS.90)
ms:contentKeyID: 23961274
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.TrailingWindowDuration
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.get_TrailingWindowDuration
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.set_TrailingWindowDuration
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.get_TrailingWindowDuration
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.set_TrailingWindowDuration
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.TrailingWindowDuration
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# TrailingWindowDuration Property

Gets or sets the trailing window duration.

**Namespace:**  [Microsoft.Web.Media.SmoothStreaming](microsoft-web-media-smoothstreaming-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration
PublicPropertyTrailingWindowDurationAsDuration
'Usage
DiminstanceAsSmoothStreamingMediaElementDimvalueAsDurationvalue = instance.TrailingWindowDuration

instance.TrailingWindowDuration = value
```

``` csharp
publicDurationTrailingWindowDuration { get; set; }
```

``` c++
public:
propertyDurationTrailingWindowDuration {
    Durationget ();
    voidset (Durationvalue);
}
```

``` jscript
function getTrailingWindowDuration () : Durationfunction setTrailingWindowDuration (value : Duration)
```

#### Property Value

Type: [System.Windows. . :: . .Duration](https://msdn.microsoft.com/en-us/library/ms602372\(v=vs.90\))  
A duration object.  

## Version Information

#### Silverlight

Supported in: 4  

#### Silverlight for Windows Phone

Supported in: Windows Phone OS 7.0  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[SmoothStreamingMediaElement Class](smoothstreamingmediaelement-class-microsoft-web-media-smoothstreaming_1.md)

[Microsoft.Web.Media.SmoothStreaming Namespace](microsoft-web-media-smoothstreaming-namespace_1.md)
