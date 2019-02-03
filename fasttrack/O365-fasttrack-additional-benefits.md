---
title: 附錄 B：FastTrack Center 其他權益
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 2/2/2019
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Priority
description: Exchange Online 租用戶購買至少 20,000 個授權的客戶符合 FastTrack Center 附加服務的資格。如需詳細資料，請參閱合格服務與計劃。
ms.openlocfilehash: abdb722bdb69945a1a90d8cae3fe71a5259e9dc9
ms.sourcegitcommit: 0a8250d759e010cff6958016267f29acb0b7e17c
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/01/2019
ms.locfileid: "29696720"
---
# <a name="appendix-b---fasttrack-center-additional-benefit"></a>附錄 B：FastTrack Center 其他權益

Exchange Online 租用戶購買至少 20,000 個授權的客戶符合 FastTrack Center 附加服務的資格。如需詳細資料，請參閱＜[合格服務與計劃](M365-eligible-services-and-plans.md)＞。 
  
## <a name="onboarding-and-migration-phases"></a>上架及移轉階段

## <a name="core"></a>核心

核心上架服務新增內容包含異地備援 Active Directory Federation Services (AD FS) 的設定指引和服務的 AD FS 用戶端存取原則。 
  
## <a name="exchange-online"></a>Exchange Online

針對 Exchange Online，我們提供下列的設定指引︰
- 設定整合通訊 (UM) 與 Exchange Online。
- 設定 Exchange Online 和舊版的內部部署公用資料夾之間的共存。
- 擁有郵件功能的應用程式整合。 
- 信箱移轉規劃及群組。
    
## <a name="skype-for-business-online"></a>商務用 Skype Online

針對 商務用 Skype Online，我們提供內部部署 Lync 與 商務用 Skype 使用者遷移至 商務用 Skype Online 的指南。
  
## <a name="office-365-proplus"></a>Office 365 專業增強版

針對 Office 365 專業增強版，我們提供下列指引︰ 
- 評估與規劃著重於預備您的環境，用於符合 Microsoft 最佳做法的初始部署及管理更新。 
- 使用 Office 365 部署工具開發部署組態和更新設定。 
- 使用 System Center Configuration Manager 部署套件。  
- 部署並設定 Office 遙測，提供指引以利您評估使用關鍵業務 Office 文件，以及應用程式相容性的解決方案。
    
## <a name="fasttrack-responsibilities"></a>FastTrack 責任

在上架期間 FastTrack 專家需擔負下列責任。這些可能是取代＜[FastTrack 責任](O365-fasttrack-responsibilities.md)＞中所定義的活動或活動之外的部分。
  
## <a name="general"></a>一般

- 如同詳細的[上架及移轉階段](#onboarding-and-migration-phases)中所述，會針對成功計劃發展、實作及必要的組態活動，為您提供遠端支援協助。
    
## <a name="assess-phase"></a>評估階段

- 進行成功計劃會議，提供指引以利您成功地達成使用者採用。 
- 評估您的環境以支援異地備援 AD FS 的組態。  
- 執行評估來識別您的 AD FS 用戶端存取需求。
    
## <a name="enable-phase"></a>啟用階段

### <a name="geo-redundant-ad-fs-guidance"></a>異地備援 AD FS 指引

- 提供專為跨兩個 (2) 資料中心的異地備援 AD FS 拓撲所設計的標準參考架構。標準架構提供：
  - FastTrack Center 效益範圍內的服務同盟驗證。 
  - 單一站台恢復。  
  - [高可用性] 和 [容錯移轉]。  
  - 調整大小指引。 
- 提供使用 Windows 內部資料庫和 SQL Server 的指引做為 AD FS 伺服陣列的資料庫執行個體。   
- 驗證每個樹系範圍中的同盟驗證建立。  
- 確認最多 10 個使用者的同盟驗證功能。
    
> [!NOTE]
> AD FS 部署在具有多重 Active Directory 樹系組態的其他權益合格客戶的範圍內。 
  
### <a name="ad-fs-client-access-policy-guidance"></a>AD FS 用戶端存取原則指引

- 檢閱保護 Office 365 資源所需的原則及組態。  
- 針對支援案例界限內的識別用戶端存取案例，提供設定 AD FS 用戶端存取原則的指引與協助。如需詳細資訊，請參閱[根據用戶端的位置限制存取 Office 365 服務](https://go.microsoft.com/fwlink/?LinkID=525689)。 
- 針對具有最多 10 個使用者的識別用戶端存取案例驗證具有修改的用戶端存取原則的同盟驗證功能。
    
## <a name="exchange-online"></a>Exchange Online

### <a name="exchange-unified-messaging-guidance"></a>Exchange 整合通訊指引

- 提供在 Exchange Online 上啟用最多 10 個的必要組態的指引︰ 
  - UM 撥號對應表。   
  - UM 信箱原則。 
  - 自動語音應答。  
- 提供內部部署 Lync 或 商務用 Skype 環境設定以啟用 UM 的指引，並特別指定：  
  - Exchange Online 託管原則。  
  - Exchange Online 託管語音信箱原則。 
  - UM 自動語音應答連絡人和 Outlook 語音信箱將使用者重新導向至 Exchange Online。 
  - 協助建立聯盟所要求的服務位置 (SRV) 記錄。
> [!NOTE]
> 可使用支援的 UM IP 通訊閘和工作階段邊界控制器 (SBCs) 來設定 UM。如需詳細資訊，請參閱＜[UM 電話系統整合](https://go.microsoft.com/fwlink/?LinkID=809293)＞(機器翻譯)。 
  
### <a name="public-folder-coexistence-guidance"></a>公用資料夾共存指引

- 提供單一公用資料夾樹狀目錄共存的指引，包括：  
  - Exchange 2007、Exchange 2010 和 Exchange 2013 中的公用資料夾準備。 
  - 同步處理 Exchange 2007、Exchange 2010 和 Exchange 2013 公用資料夾階層與 Exchange Online所需的 Windows PowerShell cmdlets。  
  - 將公用資料夾存取重新導向至內部部署公用資料夾的 Exchange Online 組態。  
  - 從 Exchange Online 存取公用資料夾至單一 Exchange 2007、Exchange 2010或 Exchange 2013 內部部署環境的設定。  
  - 在 Exchange Online 中協助對最多 10 個使用者存取驗證公用資料夾環境。
    
### <a name="mail-enabled-application-integration-guidance"></a>擁有郵件功能的應用程式整合指引

- 提供以下的指引範本︰  
  - 大量散發郵件應用程式。  
  - 透過 Exchange 路由傳送電子郵件的應用程式。  
  - 使用 Exchange 信箱的應用程式。  
  - 需要在 Exchange 伺服器上安裝的協力廠商或自訂元件的應用程式。
    
### <a name="mailbox-migration-planning-and-grouping"></a>信箱移轉規劃及群組

- 提供建立移轉計劃的指引，包括︰  
  - 批次群組使用者和資源。
  - 協調移轉批次所需的軟體套件部署。   
  - 建立使用者通訊計畫的指引。 
  - 協調移轉批次大小、錯誤率及預期服務台協助。 
- 根據客戶所提供的相關資訊，依類型、商業功能和委派存取提供批次群組使用者及資源信箱的指引。
    
## <a name="skype-for-business-online"></a>商務用 Skype Online

- 提供在 商務用 Skype 混合部署 (保留使用者的連絡人清單) 中批次移轉使用者的指引。
    
## <a name="office-365-proplus"></a>Office 365 專業增強版

- 提供指導與協助︰  
  - 評估與規劃符合 Microsoft 最佳做法的初始部署及管理更新。
  - 部署和設定 Office 遙測。 
  - 對 Office 2013+ 版本使用「群組原則」的用戶端啟用遙測記錄。 
  - 部署前一個 Office 用戶端 (Office 2003、Office 2007 和 Office 2010) 的 Office 遙測代理程式。 
  - 部署遙測處理器。 
    > [!NOTE]
    > 這需要可儲存遙測資料的檔案共用位置，以及執行 SQL Server 2005+ 版本的伺服器，用以將已處理的資料提交至此。 
  
## <a name="your-responsibilities"></a>您的責任

在上架期間您需擔負下列責任。這些是＜[您的責任](O365-your-responsibilities.md)＞一節中所定義的責任以外的部分。 
  
- 根據專案計劃指派及管理資源。  
- 採取即時動作來減輕風險，並解決由客戶、合作夥伴專案經理和 FastTrack 專案經理所提出的問題。   
- 檢閱狀態報表，並採取適當動作。   
- 為作業發起人或經理指派決策授權以執行決策委員會。  
- 指派執行發起人與 Microsoft 執行發起人共同合作。  
- 建立每月決策委員會會議。
    

  

