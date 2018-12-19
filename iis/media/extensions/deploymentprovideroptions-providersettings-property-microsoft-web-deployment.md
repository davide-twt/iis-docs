﻿---
title: DeploymentProviderOptions.ProviderSettings Property  (Microsoft.Web.Deployment)
TOCTitle: ProviderSettings Property
ms:assetid: P:Microsoft.Web.Deployment.DeploymentProviderOptions.ProviderSettings
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentprovideroptions.providersettings(v=VS.90)
ms:contentKeyID: 20209279
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Deployment.DeploymentProviderOptions.ProviderSettings
- Microsoft.Web.Deployment.DeploymentProviderOptions.get_ProviderSettings
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentProviderOptions.get_ProviderSettings
- Microsoft.Web.Deployment.DeploymentProviderOptions.ProviderSettings
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# ProviderSettings Property

Gets the [DeploymentProviderSettingCollection](deploymentprovidersettingcollection-class-microsoft-web-deployment.md) associated with the factory of the current object.

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
PublicReadOnlyPropertyProviderSettingsAsDeploymentProviderSettingCollection
'Usage
DiminstanceAsDeploymentProviderOptionsDimvalueAsDeploymentProviderSettingCollectionvalue = instance.ProviderSettings
```

``` csharp
publicDeploymentProviderSettingCollectionProviderSettings { get; }
```

``` c++
public:
propertyDeploymentProviderSettingCollection^ ProviderSettings {
    DeploymentProviderSettingCollection^ get ();
}
```

``` jscript
function getProviderSettings () : DeploymentProviderSettingCollection
```

#### Property Value

Type: [Microsoft.Web.Deployment. . :: . .DeploymentProviderSettingCollection](deploymentprovidersettingcollection-class-microsoft-web-deployment.md)  
The [DeploymentProviderSettingCollection](deploymentprovidersettingcollection-class-microsoft-web-deployment.md) associated with the factory of the current object.  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[DeploymentProviderOptions Class](deploymentprovideroptions-class-microsoft-web-deployment.md)

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
