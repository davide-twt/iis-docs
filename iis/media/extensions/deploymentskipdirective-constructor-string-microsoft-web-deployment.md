﻿---
title: DeploymentSkipDirective Constructor (String) (Microsoft.Web.Deployment)
TOCTitle: DeploymentSkipDirective Constructor (String)
ms:assetid: M:Microsoft.Web.Deployment.DeploymentSkipDirective.#ctor(System.String)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentskipdirective.deploymentskipdirective(v=VS.90)
ms:contentKeyID: 20208813
ms.date: 05/02/2012
mtps_version: v=VS.90
dev_langs:
- vb
- csharp
- c++
- jscript
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentSkipDirective..ctor
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# DeploymentSkipDirective Constructor (String)

Creates an instance of a [DeploymentSkipDirective](deploymentskipdirective-class-microsoft-web-deployment.md) object.

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
ProtectedSubNew ( _
    nameAsString _
)
'Usage
DimnameAsStringDiminstanceAs NewDeploymentSkipDirective(name)
```

``` csharp
protectedDeploymentSkipDirective(
    stringname
)
```

``` c++
protected:
DeploymentSkipDirective(
    String^ name
)
```

``` jscript
protectedfunctionDeploymentSkipDirective(
    name : String
)
```

#### Parameters

  - name  
    Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
    The name of the skip directive to create.  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[DeploymentSkipDirective Class](deploymentskipdirective-class-microsoft-web-deployment.md)

[DeploymentSkipDirective Overload](deploymentskipdirective-constructor-microsoft-web-deployment.md)

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
