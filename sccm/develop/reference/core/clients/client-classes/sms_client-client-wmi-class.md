---
title: "SMS_Client Class"
titleSuffix: "Configuration Manager"
ms.date: "09/20/2016"
ms.prod: "configuration-manager"
ms.technology: configmgr-sdk
ms.topic: conceptual
ms.assetid: f5101684-bce9-4752-8742-31f01f36ff0c
author: aczechowski
ms.author: aaroncz
manager: dougeby
ms.collection: M365-identity-device-management
---
# SMS_Client Client WMI Class

The `SMS_Client` class is a client Windows Management Instrumentation (WMI) class, in Configuration Manager, that represents the client and facilitates manipulation and retrieval of client information.  

 The following syntax is simplified from Managed Object Format (MOF) code and includes all inherited properties.  

## Syntax  

```
Class SMS_Client
{
      Boolean AllowLocalAdminOverride;  
      UInt32 ClientType;  
      String ClientVersion;  
      Boolean EnableAutoAssignment;  
};
```

## Methods

The following table shows the methods in `SMS_Client`.

|Method|Description|  
|------------|-----------------|  
|[EvaluateMachinePolicy Method in Class SMS_Client](../../../../../develop/reference/core/clients/client-classes/evaluatemachinepolicy-method-in-class-sms_client.md)|Initiates the evaluation of the policy assigned to a specified computer or device.|  
|[GetAssignedSite Method in Class SMS_Client](../../../../../develop/reference/core/clients/client-classes/getassignedsite-method-in-class-sms_client.md)|Gets the current assigned site of the client.|  
|[RequestMachinePolicy Method in Class SMS_Client](../../../../../develop/reference/core/clients/client-classes/requestmachinepolicy-method-in-class-sms_client.md)|Initiates a request for machine policy.|  
|[ResetPolicy Method in Class SMS_Client](../../../../../develop/reference/core/clients/client-classes/resetpolicy-method-in-class-sms_client.md)|Resets the policy on a client.|  
|[SetAssignedSite Method in Class SMS_Client](../../../../../develop/reference/core/clients/client-classes/setassignedsite-method-in-class-sms_client.md)|Sets the client's assigned site.|  
|**SetClientProvisioningMode**|Reserved.|  
|[SetGlobalLoggingConfiguration Method in Class SMS_Client](../../../../../develop/reference/core/clients/client-classes/setgloballoggingconfiguration-method-in-class-sms_client.md)|Defines the default logging configuration.|  
|[TriggerSchedule Method in Class SMS_Client](../../../../../develop/reference/core/clients/client-classes/triggerschedule-method-in-class-sms_client.md)|Triggers the client to execute the specified schedule.|

## Properties

|Property |Data type |Access type |Qualifiers |Reserved |
|---------|---------|---------|---------|---------|
|AllowLocalAdminOverride |Boolean |Read/Write |None |Yes |
|ClientType |UInt32 |Read/Write |None|Yes. Always 1|
|ClientVersion |String|Read/Write |None| Version number of the client|
|EnableAutoAssignment |Boolean |Read/Write |None |`true` if automatic assignment is enabled|

## Requirements

### Runtime Requirements

 For more information, see [Configuration Manager Client Runtime Requirements](../../../../../develop/core/reqs/client-runtime-requirements.md).  

### Development Requirements

 For more information, see [Configuration Manager Client Development Requirements](../../../../../develop/core/reqs/client-development-requirements.md).  

## See Also

 [Client Framework and Data Transfer Client WMI Classes](../../../../../develop/reference/core/clients/client-classes/client-framework-and-data-transfer-client-wmi-classes.md)
