﻿---
title: DeploymentObject Class (Microsoft.Web.Deployment)
TOCTitle: DeploymentObject Class
ms:assetid: T:Microsoft.Web.Deployment.DeploymentObject
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentobject(v=VS.90)
ms:contentKeyID: 20209000
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Deployment.DeploymentObject
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentObject
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# DeploymentObject Class

Provides properties and methods for a deployment object.

## Inheritance Hierarchy

[System. . :: . .Object](https://msdn.microsoft.com/en-us/library/e5kfa45b\(v=vs.90\))  
  Microsoft.Web.Deployment..::..DeploymentObject  

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
PublicNotInheritableClassDeploymentObject _
    ImplementsIDisposable
'Usage
DiminstanceAsDeploymentObject
```

``` csharp
publicsealedclassDeploymentObject : IDisposable
```

``` c++
publicref classDeploymentObjectsealed : IDisposable
```

``` jscript
publicfinalclass DeploymentObject implementsIDisposable
```

The DeploymentObject type exposes the following members.

## Properties

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
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-absolutepath-property-microsoft-web-deployment.md">AbsolutePath</a></td>
<td>Gets the absolute path of the underlying deployment object.</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-attributes-property-microsoft-web-deployment.md">Attributes</a></td>
<td>Gets a DeploymentAttributeCollection instance that contains the attributes of the deployment object.</td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-basecontext-property-microsoft-web-deployment.md">BaseContext</a></td>
<td>Gets the <a href="deploymentbasecontext-class-microsoft-web-deployment.md">DeploymentBaseContext</a> associated with the current object.</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-isvalid-property-microsoft-web-deployment.md">IsValid</a></td>
<td></td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-keyattribute-property-microsoft-web-deployment.md">KeyAttribute</a></td>
<td>Gets the DeploymentAttribute used as the key in the current deployment object.</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-kind-property-microsoft-web-deployment.md">Kind</a></td>
<td></td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-linkname-property-microsoft-web-deployment.md">LinkName</a></td>
<td>Gets the link name of the current DeploymentObject instance.</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-name-property-microsoft-web-deployment.md">Name</a></td>
<td>Gets the name of the current DeploymentObject instance.</td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-parent-property-microsoft-web-deployment.md">Parent</a></td>
<td>Gets the parent DeploymentObject of the current DeploymentObject instance.</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-providercontext-property-microsoft-web-deployment.md">ProviderContext</a></td>
<td>Gets the <a href="deploymentprovidercontext-class-microsoft-web-deployment.md">DeploymentProviderContext</a> associated with the current object.</td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-streamrelativefilepath-property-microsoft-web-deployment.md">StreamRelativeFilePath</a></td>
<td>Gets a string that contains the stream relative file path associated with the current object.</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-summary-property-microsoft-web-deployment.md">Summary</a></td>
<td></td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubproperty(en-us,VS.90).gif" title="Public property" alt="Public property" /></td>
<td><a href="deploymentobject-syncparameters-property-microsoft-web-deployment.md">SyncParameters</a></td>
<td></td>
</tr>
</tbody>
</table>


Top

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
<td><a href="deploymentobject-dispose-method-microsoft-web-deployment.md">Dispose</a></td>
<td>Releases resources used by the current DeploymentObject instance.</td>
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
<td><a href="deploymentobject-getchildren-method-microsoft-web-deployment.md">GetChildren</a></td>
<td></td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/zdee4b3y(v=vs.90)">GetHashCode</a></td>
<td>(Inherited from <a href="https://msdn.microsoft.com/en-us/library/e5kfa45b(v=vs.90)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="deploymentobject-getstream-method-microsoft-web-deployment.md">GetStream</a></td>
<td></td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/dfwy45w9(v=vs.90)">GetType</a></td>
<td>(Inherited from <a href="https://msdn.microsoft.com/en-us/library/e5kfa45b(v=vs.90)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="deploymentobject-invoke-method-microsoft-web-deployment.md">Invoke</a></td>
<td>Executes a named <a href="deploymentmethod-class-microsoft-web-deployment.md">DeploymentMethod</a> from the <a href="deploymentmanager-class-microsoft-web-deployment.md">DeploymentManager</a>.</td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.protmethod(en-us,VS.90).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/57ctke0a(v=vs.90)">MemberwiseClone</a></td>
<td>(Inherited from <a href="https://msdn.microsoft.com/en-us/library/e5kfa45b(v=vs.90)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="deploymentobject-syncto-method-deploymentbaseoptions-deploymentsyncoptions-microsoft-web-deployment.md">SyncTo(DeploymentBaseOptions, DeploymentSyncOptions)</a></td>
<td>Synchronizes the current DeploymentObject instance by using the base options and synchronization options specified.</td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="deploymentobject-syncto-method-deploymentprovideroptions-deploymentbaseoptions-deploymentsyncoptions-microsoft-web-deployment.md">SyncTo(DeploymentProviderOptions, DeploymentBaseOptions, DeploymentSyncOptions)</a></td>
<td>Synchronizes the current DeploymentObject instance by using the provider options, base options and synchronization options specified.</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="deploymentobject-syncto-method-string-string-deploymentbaseoptions-deploymentsyncoptions-microsoft-web-deployment.md">SyncTo(String, String, DeploymentBaseOptions, DeploymentSyncOptions)</a></td>
<td>Synchronizes the current DeploymentObject instance by using the factory name, path, base options and synchronization options specified.</td>
</tr>
<tr class="odd">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="deploymentobject-syncto-method-deploymentwellknownprovider-string-deploymentbaseoptions-deploymentsyncoptions-microsoft-web-deployment.md">SyncTo(DeploymentWellKnownProvider, String, DeploymentBaseOptions, DeploymentSyncOptions)</a></td>
<td>Synchronizes the current DeploymentObject instance by using the well-known provider name, path, base options and synchronization options specified.</td>
</tr>
<tr class="even">
<td><img src="images/Dd565996.pubmethod(en-us,VS.90).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/7bxwbwt2(v=vs.90)">ToString</a></td>
<td>(Inherited from <a href="https://msdn.microsoft.com/en-us/library/e5kfa45b(v=vs.90)">Object</a>.)</td>
</tr>
</tbody>
</table>


Top

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
