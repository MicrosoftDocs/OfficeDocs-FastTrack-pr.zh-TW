---
title: FastTrack 責任
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 10/01/2018
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9840bd79-fb09-4f8e-b7c9-e96dfdcd3a33
description: 在上架期間 FastTrack 專家需擔負下列責任。
ms.openlocfilehash: 813fc4c1f4fdb48bdae8184b9afc0528dcb4feb7
ms.sourcegitcommit: a754d02f1dea1a2147f716a2cbebda7b68141777
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/01/2018
ms.locfileid: "25353730"
---
# <a name="fasttrack-responsibilities"></a>FastTrack 責任

在上架期間 FastTrack 專家需擔負下列責任。\*
  
## <a name="general"></a>一般

- 如同詳細的階段說明中所述，會針對成功計劃發展、實作及必要的組態活動，為您提供遠端支援協助。
- 提供可用的文件及軟體工具、管理主控台和指令碼，提供您指引以減少或消除組態工作，並成功地規劃資源。 
    
## <a name="initiate-phase"></a>起始階段

- 與您協同作業以了解您的目的、組織目標，以及服務的使用計劃。
- 搭配使用 Office 365 共同作業服務 (例如 Microsoft Teams) 來登入。   
- 定義您要上架的合格服務。 
    
## <a name="assess-phase"></a>評估階段

- 進行成功計劃會議，提供指引以利您成功地達成使用者採用。  
- 提供管理概觀。
- 提供以下的相關指引： 
  - 網域名稱系統 (DNS)、網路和基礎結構需求。
  - 用戶端需求 (網際網路瀏覽器、用戶端作業系統、行動裝置和服務的需求)。
  - 使用者身分識別與佈建。
  - 啟用所購買且定義為上架一部分的合格服務。 
  - 驅動成功服務採用和價值。  
- 建立修復服務活動的時間表。
- 提供修復檢查清單。 
- 評定現有的 SharePoint Server 2013 或 SharePoint Server 2016 基礎結構，包括：
  - SharePoint Online 混合式 的必要條件。 
  - SharePoint Online 混合式 功能的內部部署基礎結構整備狀態。
  - 存取所需的 SharePoint Online 端點。
  - 商務用 OneDrive 混合式 的對象。 
- 評定現有的 Lync 或 商務用 Skype Online 基礎結構，包括：
  - 支援的 商務用 Skype 用戶端部署策略。
  - 存取端點。
  - 連線品質。
  - 頻寬估計。
  - 支援分割網域伺服器組態的先決條件。
  - 讓已識別的使用者準備移至 商務用 Skype Online。
- 評估訊息基礎結構，包括： 
  - 整體郵件流程和路由準則。
  - 用戶端存取 (包括現有已發佈的用戶端存取端點)。
  - 整合所需的來源訊息環境。
- 若使用 FastTrack Center 資料移轉服務且您符合資格，就會提供資料移轉。
    
## <a name="remediate-phase"></a>修復階段

- 就約定的排程與您進行電話會議，以審視修復活動及成功規劃的進度。 
- 逐步引導您執行評估工具以識別並修正問題，並解譯結果。
    
## <a name="enable-phase"></a>啟用階段

提供以下的相關指引： 
- 在成功計畫中評估進度並判斷您需要怎樣的進一步協助。
- 啟動您的 Office 365 租用戶。  
- 設定 TCP/IP 通訊協定和防火牆連接埠。
- 設定合格服務 DNS。 
- 驗證對 Office 365 的連線。
- 使用 Azure Active Directory 連接您的內部部署 Active Directory：
  - 在您的 Active Directory 網域服務 (AD DS) 和 Office 365 之間安裝目錄同步作業伺服器 (如有必要)。 
  - 使用 Azure Active Directory Connect 工具設定密碼同步處理 (密碼雜湊) 至 Office 365 (Azure Active Directory) (如有需要)。
  - 單一與多重樹系環境：
      - 設定 Azure Active Directory 通過驗證 (如有必要)。\*\*
      - 設定 Azure Active Directory 無縫單一登入 (SSO)，(如有必要)。\*\*\*
    > [!NOTE]
    > 如果在您的 Active Directory 之間有樹系信任且正確配置了名稱尾碼路由，則會支援多重樹系環境的Azure Active Directory 通過驗證。其他代理程式可安裝在多個內部部署伺服器，以提供高可用性的登入要求。如需詳細資訊，請參閱 [：快速入門](https://go.microsoft.com/fwlink/?linkid=860094)與 [Azure Active Directory 無縫單一登入：快速入門](https://go.microsoft.com/fwlink/?linkid=860095)。 
- 對於當同盟身分識別為目標時的單一樹系： 
  - 若需要，在單一站台、容錯組態中，針對向 Office 365 的本機網域驗證安裝和設定 AD FS。
  - 安裝和設定 WAP 以在必要時將您的 AD FS 基礎結構發佈至網路中。
    > [!NOTE]
    > 對於所有多重樹系組態，AD FS 部署是在範圍外。 
- 測試 SSO 功能 (若已部署)。
- 驅動成功服務採用和價值。
    
\*\*如需通過驗證的詳細資訊，請參閱＜[Azure Active Directory 傳遞驗證：目前的限制](https://go.microsoft.com/fwlink/?linkid=860356)＞。 

\*\*\*如需無縫 SSO 問題的詳細資訊，請參閱＜[針對 Azure Active Directory 無縫單一登入進行疑難排解](https://go.microsoft.com/fwlink/?linkid=841926)＞。

## <a name="exchange-online"></a>Exchange Online

提供以下的相關指引：
- 建立或更新 DNS 記錄。 
- 啟用來源訊息系統與 Office 365 環境間的電子郵件路由。 
- 設定 Exchange Online Protection 功能 (包括 Exchange Online 進階威脅防護 功能，如果在您的訂閱中可用)，並確認您的 MX 記錄針對所有已驗證已啟用郵件的網域指向 Office 365。
- 在單一內部部署 Exchange 組織與 Office 365 之間，「或者」** 在多重內部部署 Exchange 組織與 Office 365 之間進行混合設定。 
    
如需資料移轉責任的詳細資訊，請參閱＜[資料移轉](O365-data-migration.md)＞。
  
## <a name="sharepoint-online"></a>SharePoint Online

提供以下的相關指引：
- 設定包括授權在內的使用者佈建。
- 啟用 SharePoint Online 管理員的網站架設。    
- 規劃網站集合。 
- 保護內容與管理權限。
- 啟用個人網站和社交功能。
- 設定 SharePoint Online 功能。 
- 若使用 FastTrack Center 資料移轉服務且您符合資格，就會提供資料移轉。
- 評估 SharePoint Online 混合式 所需的內部部署 SharePoint 伺服器陣基礎結構組態。 
- 使用工具及自動化以︰
  - 設定內部部署雲端 Search Service 應用程式。 
  - 設定 SharePoint 內部部署與雲端環境之間的信任。
- 設定內部部署 SharePoint 網站以使用 SharePoint Online 混合式 功能。
    
## <a name="onedrive-for-business"></a>商務用 OneDrive

提供以下的相關指引：
- 識別內部部署 SharePoint 版本和整合選項。 
- 識別同步處理和身分識別選項。
- 選取首度發行選項：   
  - Just-In-Time 首度發行。
  - 階段式首度發行 (循序與分階段)。
- 準備用於 商務用 OneDrive 部署的內部部署環境：
  - 識別正確的 商務用 OneDrive 同步用戶端。
  - 設定 DNS、網路連接埠和防火牆。 
- 指派使用者授權。 
- 設定 SharePoint Online 對象，以控制和控制取得 商務用 OneDrive 的對象。 
- 將商務用 OneDrive 同步處理用戶端部署至桌上型電腦。   
- 如何設定 SharePoint Online 混合式商務用 OneDrive 重新導向 (僅限 SharePoint 2013 和 SharePoint 2016)。
- 若使用 FastTrack Center 資料移轉服務且您符合資格，就會進行資料移轉。
    
## <a name="skype-for-business-online"></a>商務用 Skype Online

提供以下的相關指引：
- 針對 Office 365 佈建商務用 Skype 身分識別。 
- 啟用 Office 365 的線上會議、立即訊息 (IM) 及顯示狀態功能。 
- 建立要與支援的會議室系統裝置產生關聯的帳戶 (最多 10 個帳戶)。 
- 設定分割網域伺服器環境以支援 Lync 混合式或 商務用 Skype Online 混合案例 (如果適用)。
- 啟用音訊會議：
  - 會議橋接預設設定的組織設定。
  - 對授權使用者會議橋接的指派。
- 啟用電話系統：
  - 啟用電話系統和通話方案上架 (在可用的市場)。
  - 授權使用者號碼的指派。
  - 透過 UI 的本機號碼移轉指引最多至 999。
  - 本機號碼移轉 SR 支援超過 999。
- 啟用商務用 Skype 會議廣播：
  - 啟用商務用 Skype 會議廣播上架指引。
  - 針對會議廣播服務同盟的組織設定。
    
## <a name="microsoft-teams"></a>Microsoft Teams

提供以下的相關指引：
- 確認最低需求。
- 設定防火牆連接埠。
- 設立 DNS。  
- 確認您的 Office 365 租用戶上已啟用 Microsoft Teams。
- 啟用或停用使用者授權。
- Microsoft Teams 用戶端發佈。
- IT 專業人員和系統管理功能。
- 核心產品功能。
- 客戶成功的範本。
    
## <a name="power-bi"></a>Power BI

提供以下的相關指引：
- 檢閱 Power BI 訂閱計劃。 
- 新增 Power BI 服務。 
- 下載 Power BI Desktop 應用程式。
    
## <a name="project-online"></a>Microsoft Project Online

提供以下的相關指引：
- 檢閱訂用計劃。
- 驗證基本 SharePoint 功能。
- 新增 Microsoft Project Online 服務。
- 將使用者新增至 Microsoft Project Online，包括 ERP Sync。
- 建立專案以驗證基本 Microsoft Project Online 功能。
    
## <a name="project-online-professional-and-project-online-premium"></a>Microsoft Project Online 專業版和 Microsoft Project Online 進階版

提供以下的相關指引：
- 解決部署問題。
- 使用 Office 365 系統管理中心 和 Windows PowerShell 指派使用者授權。
- 從入口網站下載並安裝 Microsoft Project Online 桌面用戶端。   
- 使用 Office 部署工具或群組原則範本來設定更新設定。
- 設定 Microsoft Project Online 桌面用戶端 的單一內部網站發佈伺服器，包含建立 Office 2016 部署工具之 configuration.xml 檔案的相關指引。 
- 正在將 Microsoft Project Online 桌面用戶端連接至 Microsoft Project Online。
    
## <a name="yammer-enterprise"></a>Yammer Enterprise

提供將您的單一 Yammer Basic 網路轉換成單一 Yammer Enterprise 網路的指導。
  
## <a name="office-365-proplus"></a>Office 365 專業增強版

提供以下的相關指引：
- 解決部署問題。
- 使用 Office 365 系統管理中心 和 Windows PowerShell 指派使用者授權。
- 使用隨選即用從 Office 365 入口網站安裝 Office 365 專業增強版。
- 在您的 iOS、Android 或 Windows Mobile 裝置上安裝 Office Mobile 應用程式 (如 Outlook Mobile、Word Mobile、Excel Mobile 和 PowerPoint Mobile)。 
- 使用 Office 2016 部署工具或群組原則範本來設定更新設定。
- 設定 Office 365 專業增強版 的單一內部網站發佈伺服器，包含建立搭配 Office 部署工具使用之 configuration.xml 檔案的相關協助。
- 使用 System Center Configuration Manager 部署，包含建立 System Center Configuration Manager 封裝的協助。
    
## <a name="microsoft-staffhub"></a>Microsoft StaffHub

提供以下的相關指引：
- 確認您的 Office 365 租用戶上已啟用 Microsoft StaffHub。
- 啟用或停用使用者授權。
- 核心產品功能。
- 下載 Microsoft StaffHub 的位置。
    
\*如需 Office 365 US Government 的 FastTrack 責任詳細資訊，請參閱 [Office 365 US Government 的 FastTrack 責任](US-Gov-appendix-fasttrack-responsibilities.md)。

