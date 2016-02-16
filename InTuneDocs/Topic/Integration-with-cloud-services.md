---
title: Intune integration with Microsoft cloud services and products
ms.custom: na
ms.reviewer: na
ms.service: microsoft-intune
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: 
ms.assetid: 
author: Staciebarker
---
# Intune integration with Microsoft cloud services and products

##Integration with other Microsoft cloud services

[!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] shares a common foundation with other Microsoft cloud services. When you use the same account to subscribe to multiple cloud services, those services use the same Microsoft Azure AD infrastructure, and they are tenants of Azure AD. Azure AD provides the core directory and identity management capabilities for Microsoft cloud services.

Learn more about [administering Azure AD ](http://technet.microsoft.com/library/hh967611.aspx) in the TechNet Library.

## Integration with other Microsoft products
You can use [!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)] as a stand-alone cloud service or as a cloud service that is integrated with other products. Presently, only [!INCLUDE[cmshort](../Token/cmshort_md.md)] can be integrated directly with [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)].

The decision to integrate [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] with [!INCLUDE[cmshort](../Token/cmshort_md.md)] is a permanent choice that requires you to set the mobile device management authority from the [!INCLUDE[cmshort](../Token/cmshort_md.md)] console and not from within the [!INCLUDE[wit_icp_1](../Token/wit_icp_1_md.md)]. After the mobile device management authority is set, you cannot change or reverse this configuration.

When you use [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] with [!INCLUDE[cmshort](../Token/cmshort_md.md)], you do not use the [!INCLUDE[wit_adminconsole](../Token/wit_adminconsole_md.md)] to manage [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] and instead use the [!INCLUDE[cmshort](../Token/cmshort_md.md)] console. [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] still uses its cloud storage in Azure to host software that you deploy to devices that you manage with [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)].

For more information, see [Manage Mobile Devices with Configuration Manager and Microsoft Intune](http://msdn.microsoft.com/library/2c6bd0e5-d436-41c8-bf38-30152d76be10) in the [!INCLUDE[cm5short](../Token/cm5short_md.md)] SP1 documentation.

### See also
[What to know before you set up Microsoft Intune](../Topic/What-to-know-before-setting-up-Microsoft-Intune.md)