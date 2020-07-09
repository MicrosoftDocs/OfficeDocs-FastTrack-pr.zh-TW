---
title: 來源環境預期
description: 使用 EMS 適用的 FastTrack 中心權益的來源環境需求
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: df1a9fc3bd1fc51936a3595f674b36ff66f442b5
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011019"
---
# <a name="source-environment-expectations"></a>來源環境預期

當您使用 [Enterprise Mobility + Security (EMS) 適用的 FastTrack 中心權益](EMS-fasttrack-benefit-for-EMS.md)來讓 Microsoft Azure Active Directory Premium、Microsoft Intune 和 Azure 資訊保護可供使用，您的環境必須符合下列各節中所述的預期。

您可能已在您的組織中有內部部署 Active Directory，想要將它與 Enterprise Mobility + Security (EMS) 或其使用來自單一主控台的豐富身分識別管理的任何個別服務整合。 Enterprise Mobility + Security (EMS) 適用的 FastTrack 中心權益包含可協助將 Azure Active Directory 與您的現有內部部署 Active Directory 環境整合。

下表顯示您現有的來源環境對於上線的預期。

|活動|來源環境預期|
|------------|----------------------------------|
|核心上線|Active Directory 樹系，功能樹系層級設定至 Windows Server 2008 以上，並使用下列樹系組態：<br /><br />- 單一 Active Directory 樹系<br />- 多個 Active Directory 樹系 </br></br>**附註**：對於所有多重樹系組態，Active Directory Federation Services (AD FS) 部署不在 FastTrack 中心權益的範圍內。|
|Azure AD Premium 上線|內部部署的 Active Directory 與其環境已針對 Azure AD Premium 備妥，其中包含已發現會防止與 Azure AD 和 Azure AD Premium 功能整合之問題的補救措施。|
|Intune 上線| 規劃使用 Intune 部署 WiFi 和 VPN 設定檔時，IT 系統管理員必須有已在其生產環境中可運作的現有憑證授權單位、WiFi 和 VPN 基礎結構。<br /><br /> **附註**: 服務權益不包含協助為其安裝或設定憑證授權單位、WiFi、VPN 基礎結構或使用 Intune 之 Apple MDM Push Certificates  |
|雲端附加設定管理員|利用雲端附加，IT 系統管理員必須負責準備內部部署環境，其中可能包括會防止您使用 Intune 雲端附加您設定管理員環境的補救措施。<br /><br />**附註**: FastTrack 服務權益不包含協助將設定管理員站台伺服器或將設定管理員用戶端設定或升級，以滿足對支援雲端附加所需的最低需求。 |
|Intune 與 Microsoft Defender 進階威脅防護 (ATP) 整合|**附註**：FastTrack 服務權益可協助您將 Intune 與 Microsoft Defender ATP 整合，並根據其 Windows 10 風險層級評估來建立裝置合規性原則。 服務權益不提供購買、授權或啟用方面的協助。 |
|Windows Autopilot|IT 系統管理員需負責向組織註冊他們的裝置，方法是讓硬體廠商代表他們上傳或是自行上傳其硬體識別碼到 Windows Autopilot 服務。 |
|使用 Intune 安全地部署 iOS 版和 Android 版Outlook|<br /><br />- 在 Office 365 適用的 Azure AD 中啟用使用者身分識別。<br />- 設定了獲指派使用者授權的 Exchange Online 或混合式 Exchange。<br />|
|Azure 資訊保護 (P2 或 EMS E5)|<br /><br />客戶應該已經： <br /> - 使用 Azure AD。<br />- 使用 Windows 或 iOS (其他作業系統不在範圍內)。<br /> - 使用不仰賴 Office 做為主要用戶端的 Office 2010 SP2 以上版本 Office 用戶端。 <br /> - 擁有其主要檔案共用位置。  <br /> - 已從 Active Directory Rights Management Services (AD RMS) 升級。 <br /> - 擁有經核准的分類法。 <br /> - 了解其受保護金鑰管理的任何法規限制。 <br />|
|Azure 資訊保護掃描器|<br /><br /> 客戶應該已經： <br /> - 使用 Windows Server 2012 R2 或 Windows Server 2016。<br /> - 擁有網際網路連線。 <br /> - 在本機或遠端執行個體中具備 Microsoft SQL Server 2012 以上版本。  <br /> - 已為其內部部署 Active Directory 建立服務帳戶，並與 Azure AD 同步處理。  <br /> - 已下載 AzInfoProtection.exe。 <br /> - 有針對自動分類/保護設定的標籤。<br />|

> [!NOTE]
> **想要深入了解？**
> [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>後續步驟

[EMS 適用的 FastTrack 中心權益上線階段](EMS-onboarding-phases.md)

