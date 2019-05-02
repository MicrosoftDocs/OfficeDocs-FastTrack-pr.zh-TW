---
title: 來源環境預期
description: 使用 FastTrack Center 權益 ems 來源環境需求
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a512e97f48df7fc3040478f4e35fe0c357ef7ce3
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513148"
---
# <a name="source-environment-expectations"></a>來源環境預期

當您要準備好使用 Microsoft Azure Active Directory 進階版、 Microsoft Intune 和 Azure 資訊保護使用[用於 Enterprise Mobility + Security (EMS) 的 FastTrack Center 權益](EMS-fasttrack-benefit-for-EMS.md)時，您的環境必須符合預期下列各節所述。

您可能已經有您想要整合與 Enterprise Mobility + Security (EMS) 或任何使用透過單一主控台的豐富型身分識別管理其個別服務的組織中的內部部署 Active Directory。 適用於 Enterprise Mobility + Security (EMS) 的 FastTrack 中心權益包含協助您與您現有的內部部署 Active Directory 環境整合 Azure Active Directory。

下表顯示登入您現有來源環境預期。

|Activity|來源環境預期|
|------------|----------------------------------|
|核心登入|Active Directory 樹系，功能樹系層級設定至 Windows Server 2008 以上，使用下列樹系組態：<br /><br />-單一 Active Directory 樹系<br />對多個 Active Directory 樹系 </br></br>**附註**： 對於所有多重樹系組態，Active Directory Federation Services (AD FS) 部署是在 FastTrack Center 權益的範圍。|
|Azure AD Premium 登入|Azure AD Premium，其中包含已識別的問題，導致與 Azure AD 整合的補救已經準備內部部署 Active Directory 和其環境與 Azure AD Premium 功能。|
|Intune 登入| IT 系統管理員必須擁有現有的憑證授權單位、 WiFi 和 VPN 基礎結構規劃部署使用 Intune WiFi 和 VPN 設定檔時，已使用其實際執行環境中。<br /><br /> **附註**： 服務權益不包括設定，或設定憑證授權單位、 WiFi，VPN 基礎結構的協助，或 Apple MDM 推入的憑證  |
|Comanagement|使用 Comanagement IT 系統管理員負責準備內部部署環境，其中可能包含修復問題使您從同時管理使用 Configuration Manager 和 Intune 的 Windows 10 裝置。<br /><br />**附註**： FastTrack 服務權益不包括設定，或將 Configuration Manager 站台伺服器及/或 Configuration Manager 用戶端升級至 Windows 10 裝置支援 Comanagement 所需的最低需求的協助。 |
|Intune 整合 Windows Defender 進階威脅防護 (Windows Defender ATP)|Windows Defender ATP 訂閱已啟動並設定您的公司安全性需求為基礎。<br /><br />**附註**： FastTrack 服務權益提供協助整合 Intune 與 Windows Defender ATP，以及建立裝置合規性原則根據其 Windows 10 風險層級評定。 FastTrack 服務權益不購買、 授權、 啟動，或使用 Windows Defender ATP 和其資訊安全中心主控台上提供的協助。 |
|Windows Autopilot|IT 系統管理員負責註冊其組織其裝置所需硬體供應商上傳其代理其硬體識別碼或上傳其本身恢復 Windows Autopilot 服務。 |
|部署 Outlook for iOS 和 Android 安全地使用 Intune|<br /><br />啟用 Azure AD 中 Office 365 的使用者身分識別。<br />Exchange Online 或混合式 Exchange 設有指派使用者授權。<br />|
|Azure 資訊保護 （P2 或 EMS E5）|<br /><br />客戶應該已經： <br /> -使用 Azure AD。<br />-使用 [Windows] 或 [iOS （其他 OSs 會超出範圍）。<br /> -使用 Office 用戶端比 Office 2010 SP2 更新不依賴 Office Online 做為主要用戶端。 <br /> -有其主要的檔案共用位置。  <br /> -已升級從 Active Directory Rights Management Services (AD RMS)。 <br /> -已核准的分類分類。 <br /> -了解其受保護的金鑰管理任何法規限制。 <br />|
|Azure 資訊保護掃描器|<br /><br /> 客戶應該已經： <br /> -使用 Windows Server 2012 R2 或 Windows Server 2016。<br /> -具有網際網路連線。 <br /> -本機或遠端執行個體中具有 Microsoft SQL Server 2012 +。  <br /> -已建立其內部部署 Active directory 並同步處理與 Azure AD 的服務帳戶。  <br /> -已下載 AzInfoProtection.exe。 <br /> -已設定為自動分類/保護的標籤。<br />|

> [!NOTE]
> **想要了解更多？**
> [企業行動力 + 安全性](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>後續步驟

[適用於 EMS 上架階段 FastTrack 中心權益](EMS-onboarding-phases.md)
