---
title: "IAppHostPropertySchema::ValidationType Property | Microsoft Docs"
ms.custom: ""
ms.date: "10/07/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 3cbea5c1-7476-4c2e-6df3-b8187306a268
caps.latest.revision: 13
author: "shirhatti"
manager: "wpickett"
---
# IAppHostPropertySchema::ValidationType Property
Describes the type of validation that will be performed for the current property.  
  
## Syntax  
  
```cpp  
HRESULT get_ValidationType(  
   [out,  
   retval,  
   string] BSTR* pbstrValidationType  
);  
```  
  
#### Parameters  
 `pbstrValidationType`  
 A pointer to a `BSTR` that indicates the validation type. Valid values are "applicationPath", "applicationPoolName", "integerRange", "nonEmptyString", "siteName", "timeSpanRange", "requireTrimmedString" and "virtualDirectoryPath".  
  
## Return Value  
 An `HRESULT`. Possible values include, but are not limited to, those in the following table.  
  
|Value|Description|  
|-----------|-----------------|  
|S_OK|Indicates that the operation was successful.|  
  
## Remarks  
 Attribute validation is performed when XML is parsed and when the API makes a call to set a value in the configuration system.  
  
 The following table provides the available validation types.  
  
|Validation type|Description|  
|---------------------|-----------------|  
|applicationPoolName|Will fail validation if the property value contains any one of the following characters: `&#124;`<>&\\"/[]+=;:,?*@<br /><br /> The following example will cause validation failure if the property value includes one of the restricted characters.<br /><br /> `validationType="applicationPoolName"`<br /><br /> `validationParameter=""`|  
|integerRange|Syntax: `<minimum>,<maximum>[,exclude]`<br /><br /> Will fail validation if the property value is set to a value outside the specified range.<br /><br /> The following example will cause validation failure if the property is set to a value less than 1 or larger than 10.<br /><br /> `validationType="integerRange"`<br /><br /> `validationParameter="1,10,exclude"`|  
|nonEmptyString|Will fail validation if the property value is set to an empty string.<br /><br /> The following example will cause validation failure if the property value is set to an empty string.<br /><br /> `validationType="nonEmptyString"`<br /><br /> `validationParameter=""`|  
|siteName|Will fail validation if the property value contains any one of the following characters: `/\.?`<br /><br /> The following example will cause validation failure if the property value includes one of the restricted characters.<br /><br /> `validationType="siteName"`<br /><br /> `validationParameter=""`|  
|timeSpanRange|Syntax: `<minimum>,<maximum>,<granularity>[,exclude]`<br /><br /> Will fail validation if the property value is set to a value outside the specified range. A `<granularity>` value of 60 indicates that the time span represents seconds, and a value of 1 indicates that the time span represents minutes.<br /><br /> The following example will cause validation failure if the property is set to a value less than 1 or greater than 2592000.<br /><br /> `validationType="timeSpanRange"`<br /><br /> `validationParameter="1,2592000,60"`|  
|requireTrimmedString|Will fail validation if white space is found at the start or end the property value.<br /><br /> The following example will cause validation failure if the property value contains white space at the start or end of the value.<br /><br /> `validationType="requireTrimmedString"`<br /><br /> `validationParameter=""`|  
  
## Requirements  
  
|Type|Description|  
|----------|-----------------|  
|Client|-   [!INCLUDE[iis70](../../../wmi-provider/includes/iis70-md.md)] on [!INCLUDE[winvista](../../../wmi-provider/includes/winvista-md.md)]<br />-   [!INCLUDE[iis75](../../../wmi-provider/includes/iis75-md.md)] on [!INCLUDE[win7](../../../wmi-provider/includes/win7-md.md)]<br />-   [!INCLUDE[iis80](../../../wmi-provider/includes/iis80-md.md)] on [!INCLUDE[win8](../../../wmi-provider/includes/win8-md.md)]<br />-   [!INCLUDE[iis100](../../../wmi-provider/includes/iis100-md.md)] on [!INCLUDE[win10](../../../wmi-provider/includes/win10-md.md)]|  
|Server|-   [!INCLUDE[iis70](../../../wmi-provider/includes/iis70-md.md)] on [!INCLUDE[winsrv2008](../../../wmi-provider/includes/winsrv2008-md.md)]<br />-   [!INCLUDE[iis75](../../../wmi-provider/includes/iis75-md.md)] on [!INCLUDE[winsrv2008r2](../../../wmi-provider/includes/winsrv2008r2-md.md)]<br />-   [!INCLUDE[iis80](../../../wmi-provider/includes/iis80-md.md)] on [!INCLUDE[winsrv2012](../../../wmi-provider/includes/winsrv2012-md.md)]<br />-   [!INCLUDE[iis85](../../../wmi-provider/includes/iis85-md.md)] on [!INCLUDE[winsrv2012r2](../../../wmi-provider/includes/winsrv2012r2-md.md)]<br />-   [!INCLUDE[iis100](../../../wmi-provider/includes/iis100-md.md)] on [!INCLUDE[winsrv2016](../../../wmi-provider/includes/winsrv2016-md.md)]|  
|Product|-   [!INCLUDE[iis70](../../../wmi-provider/includes/iis70-md.md)], [!INCLUDE[iis75](../../../wmi-provider/includes/iis75-md.md)], [!INCLUDE[iis80](../../../wmi-provider/includes/iis80-md.md)], [!INCLUDE[iis85](../../../wmi-provider/includes/iis85-md.md)], [!INCLUDE[iis100](../../../wmi-provider/includes/iis100-md.md)]<br />-   [!INCLUDE[iisexp75](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/includes/iisexp75-md.md)], [!INCLUDE[iisexp80](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/includes/iisexp80-md.md)], [!INCLUDE[iisexp100](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/includes/iisexp100-md.md)]|  
|Header|Ahadmin.h|  
  
## See Also  
 [IAppHostPropertySchema Interface](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/iapphostpropertyschema-interface.md)   
 [IAppHostPropertySchema::ValidationParameter Property](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/iapphostpropertyschema-validationparameter-property.md)