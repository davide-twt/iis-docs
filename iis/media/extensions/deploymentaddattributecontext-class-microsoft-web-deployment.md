﻿---
title: DeploymentAddAttributeContext Class (Microsoft.Web.Deployment)
TOCTitle: DeploymentAddAttributeContext Class
ms:assetid: T:Microsoft.Web.Deployment.DeploymentAddAttributeContext
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentaddattributecontext(v=VS.90)
ms:contentKeyID: 20209314
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Deployment.DeploymentAddAttributeContext
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentAddAttributeContext
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# DeploymentAddAttributeContext Class

Provides a method that is used to add attributes in the context of a deployment provider.

## Inheritance Hierarchy

[System. . :: . .Object](https://msdn.microsoft.com/en-us/library/e5kfa45b\(v=vs.90\))  
  Microsoft.Web.Deployment..::..DeploymentAddAttributeContext  

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
PublicClassDeploymentAddAttributeContext
'Usage
DiminstanceAsDeploymentAddAttributeContext
```

``` csharp
publicclassDeploymentAddAttributeContext
```

``` c++
publicref classDeploymentAddAttributeContext
```

``` jscript
publicclass DeploymentAddAttributeContext
```

The DeploymentAddAttributeContext type exposes the following members.

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="deploymentaddattributecontext-add-method-microsoft-web-deployment.md">Add</a></td>
<td>Adds a deployment attribute data object to the current object.</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/bsc2ak47(v=vs.90)">Equals</a></td>
<td>(Inherited from <a href="https://msdn.microsoft.com/en-us/library/e5kfa45b(v=vs.90)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.protmethod(en-us,VS.90).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/4k87zsw7(v=vs.90)">Finalize</a></td>
<td>(Inherited from <a href="https://msdn.microsoft.com/en-us/library/e5kfa45b(v=vs.90)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/zdee4b3y(v=vs.90)">GetHashCode</a></td>
<td>(Inherited from <a href="https://msdn.microsoft.com/en-us/library/e5kfa45b(v=vs.90)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/dfwy45w9(v=vs.90)">GetType</a></td>
<td>(Inherited from <a href="https://msdn.microsoft.com/en-us/library/e5kfa45b(v=vs.90)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.protmethod(en-us,VS.90).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/57ctke0a(v=vs.90)">MemberwiseClone</a></td>
<td>(Inherited from <a href="https://msdn.microsoft.com/en-us/library/e5kfa45b(v=vs.90)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="deploymentaddattributecontext-setobjectexception-method-microsoft-web-deployment.md">SetObjectException</a></td>
<td>Specifies the deployment exception for the current object.</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/7bxwbwt2(v=vs.90)">ToString</a></td>
<td>(Inherited from <a href="https://msdn.microsoft.com/en-us/library/e5kfa45b(v=vs.90)">Object</a>.)</td>
</tr>
</tbody>
</table>


Top

## Remarks

An instance of this class is accepted by the [GetAttributes](deploymentobjectprovider-getattributes-method-microsoft-web-deployment.md) method of a [DeploymentObjectProvider](deploymentobjectprovider-class-microsoft-web-deployment.md) subclass. The deployment object provider can then set attributes within that context.

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
