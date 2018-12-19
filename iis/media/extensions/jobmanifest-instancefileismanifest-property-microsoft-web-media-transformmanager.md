﻿---
title: JobManifest.InstanceFileIsManifest Property  (Microsoft.Web.Media.TransformManager)
TOCTitle: InstanceFileIsManifest Property
ms:assetid: P:Microsoft.Web.Media.TransformManager.JobManifest.InstanceFileIsManifest
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.jobmanifest.instancefileismanifest(v=VS.90)
ms:contentKeyID: 35520582
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.JobManifest.get_InstanceFileIsManifest
- Microsoft.Web.Media.TransformManager.JobManifest.InstanceFileIsManifest
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.Common.dll
api_name:
- Microsoft.Web.Media.TransformManager.JobManifest.get_InstanceFileIsManifest
- Microsoft.Web.Media.TransformManager.JobManifest.InstanceFileIsManifest
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# InstanceFileIsManifest Property

Gets a value that indicates whether the file that initiates job creation is a SMIL 2.0-compliant manifest.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.Common (in Microsoft.Web.Media.TransformManager.Common.dll)

## Syntax

``` vb
'Declaration
PublicReadOnlyPropertyInstanceFileIsManifestAsBooleanGet
'Usage
DiminstanceAsJobManifestDimvalueAsBooleanvalue = instance.InstanceFileIsManifest
```

``` csharp
publicboolInstanceFileIsManifest { get; }
```

``` c++
public:
propertyboolInstanceFileIsManifest {
    boolget ();
}
```

``` fsharp
memberInstanceFileIsManifest : bool
```

``` jscript
function getInstanceFileIsManifest () : boolean
```

#### Property Value

Type: [System. . :: . .Boolean](https://msdn.microsoft.com/en-us/library/a28wyd50\(v=vs.90\))  
true if the file that initiates job creation is a SMIL 2.0-compliant manifest; otherwise, false.  

## See Also

#### Reference

[JobManifest Class](jobmanifest-class-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
