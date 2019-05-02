---
title: 上架及移轉階段
description: FastTrack Center 權益的階段
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: e51f030b-8b08-4fea-96c9-d4ded435a264
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: eb7f106437f51283b36185bd8e19ab8821ba0f4f
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513466"
---
# <a name="onboarding-phases"></a>上架階段

當您使用的[合格服務與計劃](M365-eligible-services-and-plans.md)來取得 Microsoft Azure Active Directory 進階版、 Microsoft Intune 和 Azure 資訊保護供使用，有數個階段程序中。 下列各節說明每個階段的上架程序。

上架有四個主要階段：

![FastTrack 上架程序的四個階段](./media/O365-Onboarding-Phases.png)


## <a name="initiate-phase"></a>起始階段

購買適當數目的授權之後，請遵循指引来關聯至現有的租用戶或新租用戶的授權的購買確認電子郵件。 Microsoft 然後驗證您的資格的 FastTrack Center 權益，並嘗試連絡您提供上架協助。

> [!NOTE]
> 您也可以要求[FastTrack Center](https://go.microsoft.com/fwlink/?linkid=780698)協助，如果您已準備好部署這些服務的組織。

### <a name="to-request-assistance"></a>若要要求協助

1. 登入 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)。
2. 選取 [FastTrack]****。
3. 選取 [服務]****。
4. 完成的**要求協助使用 Microsoft 365 表單**。

一旦上架權益啟動，我們會將設定線上會議的排程。

> [!NOTE]
> 如果您有 Microsoft 合作夥伴列在您的 Office 365 租用戶，您無法看到此選項。 請洽詢您的 Microsoft 合作夥伴的協助。

Microsoft 合作夥伴也可以取得說明透過[FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)代表客戶。 To do so:

1. 登入 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)。
2. 選取 [FastTrack]****。
3. 選取 [我的客戶]****。
4. 搜尋您的客戶或從客戶清單中選取他們。
5. 選取 [服務]****。
6. 完成的**要求協助使用 Microsoft 365 表單**。

一旦上架支援啟動時，FastTrack 會設定與您討論上架程序、 驗證資料，並設定開始會議的線上會議的排程。

![上架其中初始化階段](./media/ft-initiate-phase.png)

## <a name="assess-phase"></a>評估階段

一旦上架程序開始時，FastTrack Center 適用於您評估您的來源環境和需求。 若要評估您的環境，位於執行工具與 FastTrack 專家將引導您完成評估您的內部部署 Active Directory、 網際網路瀏覽器、 用戶端裝置的作業系統、 網域名稱系統 (DNS)、 網路、 基礎結構及身分識別系統決定是否需要上架的任何變更。

FastTrack Center 也讓您連線如何驅動成功採用合格服務的相關指引。

根據您目前的設定，我們提供 EMS 或其個別雲端服務會帶您最多成功登入的最小需求的來源環境的修復計劃。 我們也設定適當的檢查點通話修復階段。

![上架評估階段](./media/ft-assess-phase.png)

## <a name="remediate-phase"></a>修復階段
您執行的工作的修復計劃在來源環境，使得您能夠符合上架和採用 （視需要） 的每個服務的需求。

![上架修復階段](./media/ft-remediate-phase.png)

開始 「 啟用 」 階段之前，我們會一起驗證來確定您已準備就緒可繼續進行修復活動的成果。

## <a name="enable-phase"></a>啟用階段
當所有修復活動都都完成時，專案會進入設定服務取用的核心基礎結構，以及佈建每個合格的 EMS 雲端服務。

**啟用階段-核心功能**

核心上架包括服務佈建和租用戶與身分識別整合。 它還包括提供基礎以上架線上服務，例如 Azure AD Premium、 Intune，與 Azure 資訊保護的步驟。

![上架啟用階段-核心功能](./media/ft-enable-phase-core-01.png)

![上架啟用階段-核心功能](./media/ft-enable-phase-core-02.png)
> [!NOTE]
> WAP 代表 Web 應用程式 Proxy。SSL 代表安全通訊端層。SDS 代表學校資料同步處理。有關 SDS 的詳細資訊，請參閱[歡迎使用 Microsoft 學校資料同步處理](https://go.microsoft.com/fwlink/?linkid=871480)。

> [!NOTE]
> 受管理的驗證方法包括，但不限於密碼雜湊同步處理。 身分識別整合是一份計時活動，並不包含移轉或停用現有的驗證方法，例如受管理或同盟。

### <a name="enable-phase---azure-ad-premium"></a>啟用階段-Azure AD Premium

Azure AD Premium 環境可以設定使用 Active Directory Federation Services (AD FS) 與 Azure Active Directory Connect 工具的目錄同步處理 （視需要）。

對於包含同步處理至雲端的內部部署身分識別的 Azure AD Premium 案例，我們幫助您藉由將 IT 系統管理員和使用者新增至您的訂閱，設定管理先決條件，設定 Azure AD Premium，設定目錄同步處理與受管理的驗證與 AD FS 使用 Azure AD Connect 工具，設定測試使用者，驗證您的核心服務使用情況。

Azure AD Premium 安裝程式包括啟用下列功能：

-   Azure Active Directory 自助密碼重設 (SSPR)。

-   Azure 多重要素驗證 (Azure MFA)。

-   最多三個 (3) 或多個軟體即服務 (SaaS) 應用程式整合搭配單一登入 (SSO) 從[Azure Active Directory 服務商場](https://azure.microsoft.com/marketplace/active-directory/)。

-   自動使用者佈建預先整合的 SaaS 應用程式所列在[應用程式整合教學課程清單](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list)，限制為僅限輸出的佈建。

-   自訂登入畫面，其中包括標誌、 文字和影像。

-   自助服務和動態群組 （群組）。

-   Azure Active Directory 應用程式 Proxy。

-   Azure Active Directory Connect Health。

-   Azure Active Directory 條件式存取。

-   使用 azure Active Directory 規定。

-   Azure Active Directory Identity Protection。

-   Azure Active Directory 特殊權限的身分識別管理。

-   Azure Active Directory 存取評論。

![上架啟用階段-Azure AD Premium](./media/ft-enable-phase_aad-premium_adconnect_adfed.png)

### <a name="enable-phase---intune"></a>啟用階段-Intune

針對 Intune，我們引導您進行準備好要使用 Microsoft Intune 管理裝置。 確切的步驟取決於您的來源環境取決於您的行動裝置和行動應用程式管理需要。 步驟可以包括：

-   授權您的使用者。 我們也提供協助如何大量授權啟動您 Microsoft 雲端服務租用戶 （視需要）。

-   設定是由 Intune 使用運用您的內部部署 Active Directory 或雲端身分識別的身分識別。

-   將使用者新增至您 Intune 訂用帳戶、 定義 IT 系統管理員角色，並建立使用者和裝置群組。

-   設定您的行動裝置管理 (MDM) 授權單位，請根據您管理的需求，包括：

    -   當 Intune 是唯一的 MDM 解決方案，或為搭配 Office 365 的行動裝置管理，請將 Intune 設定為 MDM 授權單位。

-   提供 MDM 指導：

    -   設定要用來驗證 MDM 管理原則的測試群組。

    -   設定 MDM 管理原則和等服務：

        -   每個應用程式部署支援的平台透過 web 連結或深層連結。

        -   條件式存取原則。

        -   部署的電子郵件、 無線網路和虛擬私人網路 (VPN) 設定檔如果貴組織中有現有的憑證授權單位、 Wi-fi 或 VPN 基礎結構。

        -   設定 Microsoft Intune Exchange 連接器 （於適用時）。

        -   連線到 Intune 資料倉儲

        -   整合與 Intune:
            -   遠端協助 」 的小組檢視器 （小組檢視器訂閱是必要的）。

            -   行動裝置威脅防護 （銷售額） 協力廠商解決方案 （行動威脅國防版訂閱是必要的）。

            -   電信費用管理解決方案 （電信費用管理方案訂閱是必要的）。

            -   Windows Defender 進階威脅防護 （Windows 版 E5 或 Microsoft 365 E5 授權所需）。

    -   註冊每個[支援的平台](https://technet.microsoft.com/library/dn600287.aspx)Intune 的裝置。

-   提供應用程式防護指導方針：

    -   設定每個支援的平台的應用程式保護原則。

    -   設定受管理的應用程式的條件式存取原則。

    -   選取目標與上述的 MAM 原則的適當的使用者群組。

    -   使用受管理的應用程式使用狀況報告。

-   上提供的電腦管理下列項目的指引：

    -   安裝 Intune 用戶端軟體 （如果需要）。

    -   使用軟體和硬體 Intune 中可用的報告。

    > [!IMPORTANT]
    > FastTrack 不支援使用 Intune Windows 10 傳統電腦管理。 FastTrack 只支援透過 Intune 行動裝置管理 (MDM) 的 Windows 10 裝置管理。

#### <a name="windows-autopilot"></a>Windows Autopilot

FastTrack 可協助您簡化您的裝置佈建與 Windows Autopilot 和 Intune，讓新的裝置至您的使用者不需要來建立、 維護和自訂作業系統映像套用到您的裝置。

FastTrack 支援下列 Autopilot 案例：

- **Azure AD 自助：** 裝置加入 Azure AD 和到 Intune 註冊。 使用 Windows 10 1703年和最新版本時，被支援此案例。

- **混合 AAD 自助：** 裝置加入同時在內部部署 AD 和 Azure AD 和到 Intune 註冊。 使用 Windows 10 1809年和最新版本時，被支援此案例。

- **自我佈建：** 裝置會自動加入 Azure AD。 使用 Windows 1809 和最新版本時，被支援此案例。

    > [!IMPORTANT]
    > FastTrack 不支援自動駕駛案例起始從 Configuration Manager。

若要安裝 Windows Autopilot 步驟取決於您的來源環境，且可以包含：

- 設定並針對 Windows Autopilot 安裝 Microsoft Intune。

- 設定 Azure AD 動態群組

- 新增公司商標至 Azure AD。

- 建立和指派給 Windows Autopilot 設定檔 （例限制本機系統管理員帳戶建立 Windows Autopilot 設定檔） 的裝置。

- 自訂擴充的-全新體驗 (OOBE)，以符合組織的需求。

- 在 Azure AD 中設定的 MDM 自動註冊和 Intune。

#### <a name="deploy-outlook-for-ios-and-android-securely"></a>安全地部署 Outlook for iOS 和 Android

FastTrack 可協助您藉由貴組織，以確保您的使用者必須安裝的所有必要應用程式中安全地部署 Outlook for iOS 和 Android。

安全地 for iOS 和 Android 使用 Intune 部署 Outlook Mobile 步驟取決於您的來源環境，且可以包含：

- 下載 Outlook for iOS 和 Android、 Microsoft Authenticator 和 Intune 公司入口網站應用程式透過 Apple App Store 或 Google Play 商店。
- 上設定，也提供下列項目的指引：
    - Outlook for iOS 和 Android、 Microsoft Authenticator 和使用 Intune Intune 公司入口網站應用程式部署。
    - 應用程式保護原則
    - 條件式存取原則
    - 應用程式設定原則

    > [!IMPORTANT]
    > FastTrack 團隊不支援使用 Exchange 的行動裝置信箱原則保護 Outlook for iOS 和 Android。

#### <a name="co-management"></a>共同撰寫管理

FastTrack 會引導您準備好要同時管理 Configuration Manager 和 Intune 的 Windows 10 裝置。 確切的步驟，取決於您的來源環境，且可以包含：

- 說明共同管理的優點。

- 授權您的使用者。 FastTrack 也提供如何大量授權啟動您 Microsoft 雲端服務租用戶 （視需要） 的協助。

- 設定可用於由 Intune 利用下列一項來識別您的內部部署 Active Directory 及/或雲端身分識別。

- 將使用者新增至您 Intune 訂用帳戶、 定義 IT 系統管理員角色，並建立使用者和裝置群組。

- 提供如何從 Intune 整合與 System Center Configuration Manager （混合），以 Intune 獨立移動指引。

- 指導您設定的 MDM 自動註冊 microsoft Azure Active Directory。

- 提供指導方針設定混合式 Azure [Active Directory 加入。

- 指導您如何設定雲端管理閘道

- 啟用 Configuration Manager 主控台中的共同管理。

- 設定您想要切換到 Intune 的支援工作負載。

- 安裝 Configuration Manager 用戶端在 Intune 中的註冊裝置。

- 提供如何監視環境中的共同管理活動的指引。

FastTrack 也提供您指引如何驅動成功採用合格服務。

![上架啟用階段-Intune](./media/ft-enable-phase_intune_mam.png)

![上架啟用階段-Intune](./media/ft-enable-phase_intune_mdm-mam_cloudonly.png)

![上架啟用階段-共同撰寫管理](./media/ft-9-enable-phase-comanagement.png)

#### <a name="enable-phase--azure-information-protection"></a>啟用階段 – Azure 資訊保護

Azure 資訊保護提供支援： 

- 自動分類和標籤 Office 應用程式 （如 Word、 PowerPoint、 Excel 和 Outlook） 中的資訊的客戶在 Windows 上執行，並使用 Azure 資訊保護用戶端。 
- 使用 Azure 資訊保護掃描器靜態檔案。
- 使用 Exchange Online 的郵件流程規則的傳輸中的電子郵件。 

要套用保護使用 Microsoft Azure Rights Management Services (Azure RMS)、 Office 365 郵件加密 (OME)，以及資料外洩防護 (DLP) 的客戶也提供支援。 

客戶如何提供下列項目的指引： 

- 啟動並設定其租用戶。
- 建立及設定標籤和原則。
- 將資訊保護套用至文件。 


> [!NOTE]
> **想要了解更多？** 請參閱[Enterprise Mobility + Security](https://www.microsoft.com/en-us/cloud-platform/enterprise-mobility)。

## <a name="next-steps"></a>後續步驟

[適用於 EMS-Microsoft 責任的 FastTrack 權益](EMS-fasttrack-responsibilities.md)
