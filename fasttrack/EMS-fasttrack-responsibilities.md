---
title: FastTrack 責任
description: FastTrack 在客戶使用 EMS 適用的 FastTrack 中心權益時的責任
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 1/03/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 83ec2a98aae98d0146192d92580f6b672b999c62
ms.sourcegitcommit: d7f4c9eafe7855c6ae02c2bd0fe3b700c458007c
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/02/2020
ms.locfileid: "40928679"
---
# <a name="fasttrack-responsibilities"></a>FastTrack 責任

在上架期間 FastTrack 需擔負下列責任。

## <a name="general"></a>一般

-   如同詳細的階段說明中所列，針對必要的組態活動，為您提供遠端支援協助。

-   提供可用的文件、軟體工具以及管理主控台，以協助您減少或消除組態工作。

## <a name="initiate-phase"></a>起始階段

-   與您合作以開始上架。

-   定義您要上架的合格服務。

## <a name="assess-phase"></a>評估階段

-   提供管理概觀。

-   提供以下的相關指引：

    -   DNS、網路和基礎結構需求。

    -   用戶端需求 (網際網路瀏覽器、用戶端作業系統和服務的需求)。

    -   使用者身分識別與佈建。

    -   啟用所購買且定義要在上架中進行的合格服務。

-   建立修復服務活動的時間表。

-   同時針對 Intune 和 Azure AD Premium 提供修復檢查清單。

## <a name="remediate-phase"></a>修復階段

-   根據約定的時間表與您召開電話會議，以檢閱修復服務活動的進度，例如，在 Microsoft 雲端服務上架之前，引導您完成安裝先決條件。

## <a name="enable-phase"></a>啟用階段
提供以下的相關指引：

-   啟用 Microsoft 線上服務租用戶或訂用帳戶。

-   設定 TCP/IP 通訊協定和防火牆連接埠。

-   設定合格服務 DNS。

-   驗證 Microsoft 線上服務的連線。

-   對於單一樹系環境：

    -   在您的 Active Directory 網域服務 (AD DS) 和合格的 Microsoft 線上服務之間安裝目錄同步作業伺服器 (僅在需要時提供指引)。

    -   使用 Azure Active Directory Connect 工具設定受管理的驗證 (密碼雜湊同步處理或傳遞驗證)。 (僅在需要時提供指引)。

        > [!NOTE]
        > 開發及實作自訂規則延伸模組超出範圍。

-   對於目標為同盟身分識別時的單一樹系：若需要，在單一站台、容錯組態中，針對向 Intune 進行的本機網域驗證，安裝和設定 Active Directory Federation Services (AD FS)。

    > [!NOTE]
    > 對於所有多重樹系組態，AD FS 部署超出範圍。

-   測試單一登入 (SSO) 功能 (若已部署)。

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>啟用階段 - Microsoft Azure Active Directory Premium

提供以下的相關指引：

- 啟用 Azure AD Premium 租用戶。

- 設定防火牆連接埠。

- 設定合格服務 DNS。

- 驗證 Azure AD Premium 服務的連線。

- 對於單一樹系環境：

  -   若需要，在您的 Active Directory 網域服務 (AD DS) 和 Azure AD Connect 之間安裝目錄同步處理。

  -   使用 Azure AD Connect 工具，設定驗證方法 (密碼雜湊同步處理或傳遞驗證)。

- 對於多重樹系環境：

  -   安裝針對多重樹系案例設定的 Azure AD Connect 同步處理。
- 單一與多重樹系環境：
  - 設定 Azure Active Directory 通過驗證 (如有必要)。
  - 設定 Azure Active Directory 無縫單一登入 (SSO)，(如有必要)。
    > [!NOTE]
    > 如果在您的 Active Directory 之間有樹系信任且正確配置了名稱尾碼路由，則會支援多重樹系環境的Azure Active Directory 通過驗證。 其他代理程式可安裝在多個內部部署伺服器，以提供高可用性的登入要求。

  - 如需詳細資訊，請參閱 [：快速入門](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites)與 [Azure Active Directory 無縫單一登入：快速入門](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites)。
  - 如需通過驗證的詳細資訊，請參閱＜[Azure Active Directory 傳遞驗證：目前的限制](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations)＞。
  - 如需無縫 SSO 問題的詳細資訊，請參閱 [Azure Active Directory 無縫單一登入疑難排解](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso)。

      > [!NOTE]
      > 密碼雜湊同步處理和密碼回寫支援多重樹系。 不過，不支援其他回寫案例。

  - 在內部部署 Active Directory 樹系與 Microsoft Azure Active Directory Premium 目錄 (Azure Active Directory) 之間設定同步處理。

    > [!NOTE]
    > 開發及實作自訂規則延伸模組超出範圍。

- 對於目標為同盟身分識別時的單一樹系：

  -   在單一站台、容錯組態中，針對向 Azure AD Premium 進行的本機網域驗證，安裝和設定 AD FS (若需要)。

  > [!NOTE]
  > 對於所有多重樹系組態，AD FS 部署超出範圍。

- 測試 SSO 功能 (若已部署)。

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>啟用階段 - Azure AD Premium - 使用 Azure AD Connect 與 AD FS

提供以下設定的相關指引：

- 使用者佈建，包括授權。

- Azure AD Connect 目錄同步處理 (透過密碼回寫和密碼雜湊同步處理)。

  - Azure Active Directory 自助式密碼重設 (SSPR)。

  - Azure Multi-Factor Authentication。

  - 從 [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/)，最多三個 (3) 或多個軟體即服務 (SaaS) 應用程式與單一登入 (SSO) 整合。

  - 使用者自動佈建預先整合的 SaaS 應用程式 (如[應用程式整合教學課程清單](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list)所列) 僅限於向外佈建。

  - 自訂登入畫面，包括商標、文字和影像。

  - 自助式群組及動態群組 (群組)。

  - Azure Active Directory 應用程式 Proxy。

  - Azure Active Directory Connect Health。

  - Azure Active Directory 條件式存取。

  - Azure Active Directory 使用規定。

  - Azure Active Directory Identity Protection。

  - Azure Active Directory Privileged Identity Management。

  - Azure Active Directory 存取權檢閱。

### <a name="enable-phase---intune"></a>啟用階段 - Intune

> [!IMPORTANT]
> FastTrack 不支援 Windows 10 傳統電腦管理與 Intune。 FastTrack 僅透過 Intune 行動裝置管理 (MDM)，支援 Windows 10 管理。

提供以下的相關指引：

-   利用內部部署 Active Directory 或雲端身分識別 (Azure Active Directory)，設定 Intune 所使用的身分識別。

-   授權使用者。

-   將使用者新增到您的 Intune 訂用帳戶、定義 IT 系統管理員角色，以及建立使用者和裝置群組。

-   根據您的管理需求，設定行動裝置管理 (MDM) 授權，包括：

    -   將 Intune 設定為您的 MDM 授權。

    -   設定用於驗證 MDM 管理原則的測試群組。

    -   瀏覽 Intune 系統管理入口網站，以找出使用者和裝置的相關資訊。

    -   設定 Intune 角色 (技術支援人員、系統管理員等等)

    -   設定 MDM 管理原則和服務，例如：

        -   透過網頁連結、MSI 及/或深層連結，針對每個支援的平台進行應用程式部署。

        -   在 Windows 10 裝置上部署 Office 專業增強版。

        -   用於應用程式部署的大量採購方案，包括 Apple 的 VPP、商務用 Windows 市集，以及 Google 的 Play for Work Store。

        -   部署電子郵件、無線網路和 VPN 設定檔 (如果貴組織中有現有的憑證授權單位、Wi-Fi 或 VPN 基礎結構)。

        -   設定 Microsoft Intune Exchange Connector (如果適用)。

        -   用於支援的裝置平台的裝置組態設定檔。

    -   設定條件式存取原則。

    -   針對每個支援的平台，設定及部署 Intune 應用程式保護原則。

    -   準備 Intune 應用程式保護原則適用的企業營運 (LOB) 應用程式，並提供可用選項的指引。

    -   使用 Microsoft Intune 服務，將每個受支援平台的裝置註冊到 Intune 或 Configuration Manager。

    -   連線到 Intune 資料倉儲。

    -   整合 Intune 與：
        -   用於遠端協助的 Team Viewer (需要有 Team Viewer 訂用帳戶)。

        -   Mobile Threat Defense 合作夥伴解決方案 (需要有 Mobile Threat Defense 合作夥伴解決方案訂用帳戶)。

        -   電信費用管理解決方案 (需要有電信費用管理解決方案訂用帳戶)。

        -   Windows Defender 進階威脅防護 (需要有 Windows E5 或 Microsoft 365 E5 授權)。

    -   針對適用的受支援平台，設定軟體更新。

    -   用於使用者採用計劃的資源。

- 設定 Windows AutoPilot：

    - 設定並安裝 Windows Autopilot 適用的 Microsoft Intune。

    - 設定 Azure AD 動態群組

    - 將公司商標新增至 Azure AD。

    - 建立裝置並將其指派至 Windows Autopilot 設定檔 (例如，限制本機系統管理員帳戶建立的 Windows Autopilot 設定檔)。

    - 自訂全新體驗 (OOBE)，以符合組織的需求。

    - 在 Azure AD 和 Intune 中設定 MDM 自動註冊。

    > [!NOTE]
    > 在 Intune 之外設定 Windows Autopilot 超出 FastTrack 權益的範圍。

### <a name="enable-phase---co-management"></a>啟用階段 - 共同管理

提供以下的相關指引：

-   授權使用者。

-   將使用者新增到您的 Intune 訂用帳戶、定義 IT 系統管理員角色，以及建立使用者和裝置群組 (如果未安裝 Intune)。

-   設定 Azure Active Directory 以進行 MDM 自動註冊。

-   設定混合式 Azure Active Directory Join。

-   設定雲端管理閘道。

-   將使用者新增到您的 Intune 訂用帳戶、定義 IT 系統管理員角色，以及建立使用者和裝置群組。

-   準備 Intune (如果未安裝 Intune)：

    -   根據您的管理需求，設定行動裝置管理 (MDM) 授權，包括：

    -   將 Intune 設定為您的 MDM 授權。

    -   設定用於驗證 MDM 管理原則的測試群組。

    -   瀏覽 Intune 系統管理入口網站，以找出使用者和裝置的相關資訊。

    -   設定 Intune 角色 (技術支援人員、系統管理員等等)

    -   針對每個支援的平台，設定及部署 Intune 應用程式保護原則。

    -   將 Windows 10 裝置註冊到 Intune。

- 在 Configuration Manager 主控台中，啟用共同管理。

- 將工作負載切換到 Intune。

- 監控您環境中的共同管理活動。

### <a name="enable-phase--azure-information-protection"></a>啟用階段 – Azure 資訊保護

提供以下的相關指引： 

- 啟用並設定客戶租用戶。

- 建立及設定標籤和原則。

- 將資訊保護套用至文件。 

- 在 Windows 上執行的 Office 應用程式中，使用 Azure 資訊保護用戶端自動分類資訊並加上標籤 (例如 Word、PowerPoint、Excel 和 Outlook)。

- 透過 Azure 資訊保護掃描器使用待用檔案。

- 使用 Exchange Online 郵件流程規則監視傳輸中的電子郵件。

系統也會將指引提供給想要使用 Microsoft Azure Rights Management Services (Azure RMS)、Office 365 郵件加密 (OME)，以及資料外洩防護 (DLP) 套用保護的客戶。

> [!NOTE]
> **想要深入了解？** 請參閱 [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)。

## <a name="next-steps"></a>後續步驟

[EMS 適用的 FastTrack 權益 - 您的責任](EMS-your-responsibilities.md)
