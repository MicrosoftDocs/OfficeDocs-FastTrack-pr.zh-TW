---
title: FastTrack 責任
description: 當客戶使用 FastTrack Center 權益 ems FastTrack 的責任
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 9b766eea35cb1c22906bf68733c1b19471858fb9
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513832"
---
# <a name="fasttrack-responsibilities"></a>FastTrack 責任

上架期間 FastTrack 需擔負下列責任。

## <a name="general"></a>一般

-   提供遠端支援協助您針對必要的組態活動如需詳細的階段說明中所列。

-   提供可用文件、 軟體工具和系統管理主控台來幫助您減少或消除組態工作。

## <a name="initiate-phase"></a>起始階段

-   與您合作以開始上架。

-   定義您要上架的合格服務。

## <a name="assess-phase"></a>評估階段

-   提供管理概觀。

-   提供以下的相關指引：

    -   DNS、 網路和基礎結構需求。

    -   用戶端需求 （網際網路瀏覽器、 用戶端作業系統和服務的需求）。

    -   使用者身分識別與佈建。

    -   啟用所購買且定義要在上架一部分的合格服務。

-   建立修復服務活動的時間表。

-   Intune 和 Azure AD Premium 提供修復檢查清單。

## <a name="remediate-phase"></a>修復階段

-   保留與您進行電話會議同意的排程，以審視修復活動的進度，例如引導您完成安裝先決條件先前上架的 Microsoft 雲端服務。

## <a name="enable-phase"></a>啟用階段
提供以下的相關指引：

-   啟動您的 Microsoft online 服務租用戶或訂閱。

-   設定 TCP/IP 通訊協定和防火牆連接埠。

-   設定合格服務 DNS。

-   驗證對 Microsoft 線上服務的連線。

-   單一樹系環境：

    -   安裝目錄同步處理伺服器之間您 Active Directory 網域服務 (AD DS) 和合格 Microsoft 線上服務 （僅限指引如有必要）。

    -   使用 Azure Active Directory Connect 工具設定受管理的驗證 （密碼雜湊同步處理或通過驗證）。 （僅限指引如有必要）。

        > [!NOTE]
        > 開發並實作自訂規則延伸模組的會超出範圍。

-   單一樹系中目標為同盟身分識別時： 安裝和設定 Active Directory Federation Services (AD FS) 的本機網域驗證使用 Intune 在單一站台、 容錯組態中，如有必要。

    > [!NOTE]
    > 對於所有多重樹系組態，AD FS 部署是在範圍外。

-   測試單一登入 (SSO) 功能，若已部署。

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>啟用階段-Microsoft Azure Active Directory 進階版

提供以下的相關指引：

- 啟動您的 Azure AD Premium 租用戶。

- 設定防火牆連接埠。

- 設定合格服務 DNS。

- 驗證對 Azure AD Premium 服務的連線。

- 單一樹系環境：

  -   如有必要，請安裝目錄同步處理 Active Directory 網域服務 (AD DS) 與 Azure AD Connect，之間。

  -   使用 Azure AD Connect 工具設定驗證方法 （密碼雜湊同步處理或通過驗證）。

- 多重樹系環境：

  -   安裝 Azure AD Connect 同步處理，設定多個樹系案例中。
- 單一與多重樹系環境：
  - 設定 Azure Active Directory 通過驗證 (如有必要)。
  - 設定 Azure Active Directory 無縫單一登入 (SSO)，(如有必要)。
    > [!NOTE]
    > 如果在您的 Active Directory 之間有樹系信任且正確配置了名稱尾碼路由，則會支援多重樹系環境的Azure Active Directory 通過驗證。 其他代理程式可安裝在多個內部部署伺服器，以提供高可用性的登入要求。

  - 如需詳細資訊，請參閱 [：快速入門](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites)與 [Azure Active Directory 無縫單一登入：快速入門](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites)。
  - 如需通過驗證的詳細資訊，請參閱 [。目前限制](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations)。
  - 如需無縫 SSO 問題的詳細資訊，請參閱 [Azure Active Directory 無縫單一登入疑難排解](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso)。

      > [!NOTE]
      > 密碼雜湊同步處理與密碼回寫支援多個樹系。 不過，不支援其他案例中回寫。

  - 設定內部部署 Active Directory 樹系和 Microsoft Azure Active Directory Premium directory (Azure Active Directory) 之間的同步處理。

    > [!NOTE]
    > 開發並實作自訂規則延伸模組的會超出範圍。

- 當目標是在單一樹系同盟身分識別：

  -   安裝和設定 AD FS 的本機網域驗證與 Azure AD Premium，在單一站台、 容錯組態 （如有必要）。

  > [!NOTE]
  > 對於所有多重樹系組態，AD FS 部署是在範圍外。

- 測試 SSO 功能 （若已部署）。

### <a name="enable-phase---azure-ad-premium--with-azure-ad-connect-and-ad-fs"></a>啟用階段-Azure AD Premium-Azure AD Connect 與 AD FS

提供有關設定指引︰

- 使用者佈建，包括授權。

- Azure AD Connect 目錄同步處理 （使用密碼回寫和密碼雜湊同步處理）。

  - Azure Active Directory 自助密碼重設 (SSPR)。

  - Azure 多重要素驗證。

  - 最多三個 (3) 或多個軟體即服務 (SaaS) 應用程式整合搭配單一登入 (SSO) 從[Azure Active Directory 服務商場](https://azure.microsoft.com/marketplace/active-directory/)。

  - 自動使用者佈建預先整合的 SaaS 應用程式所列在[應用程式整合教學課程清單](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list)，限制為僅限輸出的佈建。

  - 自訂登入畫面，其中包括標誌、 文字和影像。

  - 自助服務和動態群組 （群組）。

  - Azure Active Directory 應用程式 Proxy。

  - Azure Active Directory Connect Health。

  - Azure Active Directory 條件式存取。

  - 使用 azure Active Directory 規定。

  - Azure Active Directory Identity Protection。

  - Azure Active Directory 特殊權限的身分識別管理。

  - Azure Active Directory 存取評論。

### <a name="enable-phase---intune"></a>啟用階段-Intune

> [!IMPORTANT]
> FastTrack 不支援使用 Intune Windows 10 傳統電腦管理。 FastTrack 只支援透過 Intune 行動裝置管理 (MDM) 的 Windows 10 管理。

提供的**指引**：

-   設定可用於由 Intune，利用您內部部署 Active Directory 或雲端設定身分識別 (Azure Active Directory) 來識別。

-   授權您的使用者。

-   將使用者新增至您 Intune 訂用帳戶、 定義 IT 系統管理員角色，並建立使用者和裝置群組。

-   設定您的行動裝置管理 MDM） 授權單位，請根據您管理的需求，包括：

    -   將 Intune 設定為 MDM 授權單位。

    -   設定要用來驗證 MDM 管理原則的測試群組。

    -   瀏覽 Intune 系統管理入口網站，以找出使用者和裝置上的資訊。

    -   設定 Intune 角色 （說明 desk 運算子、 系統管理員）

    -   設定 MDM 管理原則和等服務：

        -   每個應用程式部署支援的平台透過 web 連結、 MSI 和/或深層連結。

        -   部署 Office 專業增強版至 Windows 10 裝置上。

        -   針對應用程式部署，包括 Apple 的磁碟區購買程式 VPP、 商務、 Windows 市集和 Google Play 工作存放區。

        -   部署的電子郵件、 無線網路和 VPN 設定檔如果貴組織中有現有的憑證授權單位、 Wi-fi 或 VPN 基礎結構。

        -   設定 Microsoft Intune Exchange 連接器 （於適用時）。

        -   支援的裝置平台的裝置設定設定檔。

    -   條件式存取原則設定。

    -   設定及部署每個支援的平台的 Intune 應用程式保護原則。

    -   準備-營運 (LOB) 應用程式上可用的選項的指引，Intune 應用程式保護原則。

    -   註冊裝置的每個支援您的 Intune 或 Configuration Manager 與 Microsoft Intune 服務平台。

    -   連線到 Intune 資料倉儲。

    -   整合與 Intune:
        -   遠端協助 」 的小組檢視器 （小組檢視器訂閱是必要的）。

        -   行動裝置威脅防護協力廠商解決方案 （行動威脅防護協力廠商解決方案訂閱是必要的）。

        -   電信費用管理解決方案 （電信費用管理方案訂閱是必要的）。

        -   Windows Defender 進階威脅防護 （Windows 版 E5 或 Microsoft 365 E5 授權所需）。

    -   設定適用於支援的平台的軟體更新。

    -   使用者採用規劃的資源。

- Windows Autopilot 設定：

    - 設定並針對 Windows Autopilot 安裝 Microsoft Intune。

    - 設定 Azure AD 動態群組

    - 新增公司商標至 Azure AD。

    - 建立和指派給 Windows Autopilot 設定檔 （例限制本機系統管理員帳戶建立 Windows Autopilot 設定檔） 的裝置。

    - 自訂擴充的-全新體驗 (OOBE)，以符合組織的需求。

    - 在 Azure AD 中設定的 MDM 自動註冊和 Intune。

    > [!NOTE]
    > 設定 Windows Autopilot 外 Intune 是 FastTrack 權益的範圍。

### <a name="enable-phase---co-management"></a>啟用階段-共同撰寫管理

提供以下的相關指引：

-   授權您的使用者。

-   將使用者新增至您 Intune 訂用帳戶、 定義 IT 系統管理員角色，並建立使用者和裝置群組 （如果未安裝 Intune）。

-   設定 Azure Active Directory 的 MDM 自動註冊。

-   設定混合式 Azure [Active Directory 加入。

-   設定雲端管理閘道。

-   將使用者新增至您 Intune 訂用帳戶、 定義 IT 系統管理員角色，並建立使用者和裝置群組。

-   （如果未安裝 Intune），請準備 Intune:

    -   設定您的行動裝置管理 MDM） 授權單位，請根據您管理的需求，包括：

    -   將 Intune 設定為 MDM 授權單位。

    -   設定要用來驗證 MDM 管理原則的測試群組。

    -   瀏覽 Intune 系統管理入口網站，以找出使用者和裝置上的資訊。

    -   設定 Intune 角色 （說明 desk 運算子、 系統管理員）

    -   設定及部署每個支援的平台的 Intune 應用程式保護原則。

    -   註冊您的 Intune Windows 10 裝置。

- 啟用 Configuration Manager 主控台中的共同管理。

- 切換到 Intune 的工作負載。

- 監視環境中的共同管理活動。

### <a name="enable-phase--azure-information-protection"></a>啟用階段 – Azure 資訊保護

提供支援： 

- 自動分類和標籤 Office 應用程式 （如 Word、 PowerPoint、 Excel 和 Outlook） 中的資訊的客戶在 Windows 上執行，並使用 Azure 資訊保護用戶端。 
- 使用 Azure 資訊保護掃描器靜態檔案。
- 使用 Exchange Online 的郵件流程規則的傳輸中的電子郵件。 

要套用保護使用 Microsoft Azure Rights Management Services (Azure RMS)、 Office 365 郵件加密 (OME)，以及資料外洩防護 (DLP) 的客戶也提供支援。 

客戶如何提供下列項目的指引： 

- 啟動並設定其租用戶。
- 建立及設定標籤和原則。
- 將資訊保護套用至文件。 

> [!NOTE]
> **想要了解更多？** 請參閱[Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)。

## <a name="next-steps"></a>後續步驟

[適用於 EMS-您的責任的 FastTrack 權益](EMS-your-responsibilities.md)
