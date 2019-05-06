---
title: Copy applications
titleSuffix: Configuration Manager
description: Copy applications to create duplicates in Configuration Manager
ms.date: 05/06/2019
ms.prod: configuration-manager
ms.technology: configmgr-app
ms.topic: conceptual
#ms.assetid: cc230ff4-7056-4339-a0a6-6a44cdbb2857
author: ChrisKibble
#ms.author: aaroncz
#manager: dougeby
#ms.collection: M365-identity-device-management
---

# Copy Applications in Configuration Manager

*Applies to: System Center Configuration Manager (Current Branch)*

Configuration Manager applications can be copied (duplicated) when could be useful when creating a new application to test something or when a similar application must be created.

## <a name="bkmk_copy"></a> Copy an application  

1. Within the Configuration Manager console, right click on the application that you would like to copy.

2. Select the **Copy** option that appears on the pop-up menu.

    > [!TIP]  
    >  The Copy command is also available on the ribbon under the Application section.

3. A new application will be created that has the text **-copy** appended to the application name.  While most of the application metadata will be copied into the new application, any deployments of the application are not.

