

---
title: Domain names for Microsoft Intune
ms.custom: na
ms.reviewer: na
ms.service: microsoft-intune
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: 
ms.assetid: 
author: Staciebarker
---
# Domain names for Microsoft Intune

When your organization signs up for a cloud-based service from Microsoft like [!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)], you’re given an initial domain name that looks like the following: **contoso.onmicrosoft.com**. In this example, **contoso** is the domain name that you chose when you signed up, and **onmicrosoft.com** is the suffix assigned to accounts you add to your subscription. After you complete the sign-up process, you cannot change that domain name. However, as a global administrator, you can add your own custom domain names for your organization to use with the service, or you can remove domains that you’ve added previously.

By default, when you use the onmicrosoft domain, each user you import receives the **onmicrosoft.com** suffix for their user principal name (UPN).

To use a domain name that you own rather than the one that you were given at sign-up, you can add the domain name to Azure AD. After you add the domain, and it has been verified that you own it, you can create accounts and groups that include the domain name by changing DNS resource records at your DNS hosting provider. To simplify management of user accounts when you plan to use a custom domain, [Step 2: Configure a custom domain name](../Topic/Get-started-with-a-paid-subscription-to-Microsoft-Intune.md#BKMK_ConfigureDomain) to your subscription before you begin to synchronize users from your local Active Directory.

Because the information about configuring domain names and DNS resource records for [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] is the same as for other Azure AD tenants, use the information and procedures found under [Internet domain management](http://technet.microsoft.com/library/hh969248.aspx), which include:

-   [Add your domain](http://technet.microsoft.com/library/hh969247.aspx)

-   [DNS Basics](http://technet.microsoft.com/library/jj151795.aspx)

-   [Locate your domain services or buy a new domain](http://technet.microsoft.com/library/jj151801.aspx)

-   [Work with domain names and DNS records](http://technet.microsoft.com/library/jj151817.aspx)

-   [Verify a domain](http://technet.microsoft.com/library/jj151788.aspx)

-   [Troubleshoot issues after changing your domain name](http://technet.microsoft.com/library/jj151793.aspx)

After you review the information about domains and DNS resource records, return to this topic to continue learning about [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)].

### See also
[What to know before you set up Microsoft Intune](../Topic/What-to-know-before-setting-up-Microsoft-Intune.md)</br>
[Network infrastructure requirements for Microsoft Intune](../Topic/Network-infrastructure-requirements-for-Microsoft-Intune.md)