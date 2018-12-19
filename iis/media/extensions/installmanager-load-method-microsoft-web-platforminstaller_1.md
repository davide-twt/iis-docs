﻿---
title: InstallManager.Load Method () (Microsoft.Web.PlatformInstaller)
TOCTitle: Load Method ()
ms:assetid: M:Microsoft.Web.PlatformInstaller.InstallManager.Load(System.String)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.platforminstaller.installmanager.load(v=VS.90)
ms:contentKeyID: 22049786
ms.date: 05/02/2012
mtps_version: v=VS.90
dev_langs:
- vb
- csharp
- c++
- jscript
api_location:
- Microsoft.Web.PlatformInstaller.dll
api_name:
- Microsoft.Web.PlatformInstaller.InstallManager.Load
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# Load Method ()

Loads a collection of installers from the file at the given location.

**Namespace:**  [Microsoft.Web.PlatformInstaller](microsoft-web-platforminstaller-namespace.md)  
**Assembly:**  Microsoft.Web.PlatformInstaller (in Microsoft.Web.PlatformInstaller.dll)

## Syntax

``` vb
'Declaration
PublicSubLoad ( _
    fileLocationAsString _
)
'Usage
DiminstanceAsInstallManagerDimfileLocationAsString

instance.Load(fileLocation)
```

``` csharp
publicvoidLoad(
    stringfileLocation
)
```

``` c++
public:
voidLoad(
    String^ fileLocation
)
```

``` jscript
publicfunctionLoad(
    fileLocation : String
)
```

#### Parameters

  - fileLocation  
    Type: String  
    The location of the file that contains a list of installers to load.  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see <https://msdn.microsoft.com/en-us/library/8skskf63(v=vs.90)>.

## See Also

#### Reference

[InstallManager Class](installmanager-class-microsoft-web-platforminstaller.md)

[InstallManager Members](installmanager-members-microsoft-web-platforminstaller.md)

[Load Overload](installmanager-load-method-microsoft-web-platforminstaller.md)

[Microsoft.Web.PlatformInstaller Namespace](microsoft-web-platforminstaller-namespace.md)
