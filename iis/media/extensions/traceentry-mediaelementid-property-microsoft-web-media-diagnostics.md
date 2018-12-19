﻿---
title: TraceEntry.MediaElementId Property  (Microsoft.Web.Media.Diagnostics)
TOCTitle: MediaElementId Property
ms:assetid: P:Microsoft.Web.Media.Diagnostics.TraceEntry.MediaElementId
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.diagnostics.traceentry.mediaelementid(v=VS.90)
ms:contentKeyID: 23961100
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.Diagnostics.TraceEntry.MediaElementId
- Microsoft.Web.Media.Diagnostics.TraceEntry.get_MediaElementId
- Microsoft.Web.Media.Diagnostics.TraceEntry.set_MediaElementId
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.Diagnostics.TraceEntry.get_MediaElementId
- Microsoft.Web.Media.Diagnostics.TraceEntry.MediaElementId
- Microsoft.Web.Media.Diagnostics.TraceEntry.set_MediaElementId
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# MediaElementId Property

Gets or sets the MediaElementId property.

**Namespace:**  [Microsoft.Web.Media.Diagnostics](microsoft-web-media-diagnostics-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration
PublicPropertyMediaElementIdAsString
'Usage
DiminstanceAsTraceEntryDimvalueAsStringvalue = instance.MediaElementId

instance.MediaElementId = value
```

``` csharp
publicstringMediaElementId { get; set; }
```

``` c++
public:
propertyString^ MediaElementId {
    String^ get ();
    voidset (String^ value);
}
```

``` jscript
function getMediaElementId () : Stringfunction setMediaElementId (value : String)
```

#### Property Value

Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
A string value that specifies the media element ID.  

## Version Information

#### Silverlight

Supported in: 4  

#### Silverlight for Windows Phone

Supported in: Windows Phone OS 7.0  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[TraceEntry Class](traceentry-class-microsoft-web-media-diagnostics_1.md)

[Microsoft.Web.Media.Diagnostics Namespace](microsoft-web-media-diagnostics-namespace_1.md)
