---
title: FastTrack Center 權益概觀
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see FastTrack Center Benefit for Office 365.
ms.openlocfilehash: 3537f6effa5bd2c65f542496ea42ab70075621ce
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011331"
---
# <a name="fasttrack-center-benefit-overview"></a>FastTrack Center 權益概觀

With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see [FastTrack Center Benefit for Office 365](O365-fasttrack-benefit-for-office-365.md).
  
我們將說明下列主題：
- [FastTrack 處理程序](O365-fasttrack-process.md) 
- [來源環境預期](O365-source-environment-expectations.md)
- [上架及移轉階段](O365-onboarding-and-migration.md)
- [資料移轉](O365-data-migration.md)
- [FastTrack 責任](O365-fasttrack-responsibilities.md)
- [您的責任](O365-your-responsibilities.md) 
- [附錄 A：FastTrack 中心其他權益](O365-fasttrack-additional-benefits.md)
- [附錄 B：FastTrack 中心 HIPAA 商業夥伴合約](O365-hipaa-business-associate-agreement.md)
- [附錄 C：適用於 Office 365 US Government 的 FastTrack 中心權益概觀](US-Gov-appendix-overview.md)
    
Your Office 365 tenant is created at the completion of onboarding. Licensed users can access Office 365 by using one of the following identity options:
- 包含唯一 Office 365 帳戶的雲端身分識別。
- Synchronized Identities with Office 365 accounts synchronized from your on-premises Active Directory with Azure Active Directory Connect (Password Hash Sync or Pass-through Authentication). These are for customers with:
  - 單一 Active Directory 樹系環境。
  - Supported multi-forests Active Directory topology. For supported topologies, see [Source Environment Expectations](O365-source-environment-expectations.md).
- 包含下列情況的 Office 365 帳戶同盟身分識別：
  - 針對具有下列組態的客戶，從 Active Directory 與 Azure Active Directory Connect 工具進行同步處理︰
      - 單一 Active Directory 樹系設定。
      - 單一 Active Directory 帳戶樹系 (也稱為 「 登入樹系 」) 和單一 Active Directory 資源樹系設定。
  - 使用屬於下列項目的內部部署 Active Directory Federation Services (AD FS) 基礎結構進行設定：
      - 從您的內部部署 Active Directory 與 Windows Server 2012 R2 開始的 AD FS 角色同盟。
      - 在必要時，Windows Server 2012 R2 開始的 Windows 應用程式 Proxy (WAP) 角色會用來將您的內部部署 AD FS 基礎結構發佈到網際網路。
    > [!NOTE]
    > AD FS 和 WAP 部署和設定是從您的內部部署環境，使用 [Azure AD Connect 設定精靈](https://go.microsoft.com/fwlink/?linkid=844794)來完成。 
  
- 取得授權的使用者現在可以存取「[合格服務與計劃](M365-eligible-services-and-plans.md)」。

