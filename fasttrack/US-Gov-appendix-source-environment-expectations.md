---
title: 來源環境預期 for Office 365 US Government
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 04/02/2019
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: FastTrack Center 權益可提供指引，以利您設定與來源環境的整合層級 (例如，如果您有服務在來源環境中，且想要移至 Office 365 時)。
ms.openlocfilehash: 7556568b4f9a3ab9291f00aff528d3fc37b0063d
ms.sourcegitcommit: 8d1fbbfc6b05522ea1259149349548f072fefcac
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/01/2019
ms.locfileid: "31016945"
---
# <a name="source-environment-expectations-for-office-365-us-government"></a>來源環境預期 for Office 365 US Government

FastTrack Center 權益可提供指引，以利您設定與來源環境的整合層級 (例如，如果您有服務在來源環境中，且想要移至 Office 365 時)。
  
> [!NOTE]
> 如果需要整合，您的來源環境必須符合該應用程式所需的最低層級。 
  
下表顯示您現有來源環境中預期會用於上架的內容。

|**活動**|**來源環境預期**|
|:-----|:-----|
|核心上架 | Active Directory 樹系，功能樹系層級設定為 Windows Server 2003 以上版本，並使用下列樹系組態：  <br/>      單一 Active Directory 樹系。  <br/>    單一 Active Directory 帳戶樹系和資源樹系 (Exchange 和/或 Lync 2010、Lync 2013 或 商務用 Skype) 拓樸。  <br/>  多個 Active Directory 帳戶樹系和資源樹系 (Exchange 和/或 Lync 2010、Lync 2013 或 商務用 Skype) 拓樸。  <br/>  多重 Active Directory 帳戶樹系，其中一個樹系為包含 Exchange 和/或 Lync 2010、Lync 2013 或商務用 Skype 的集中式 Active Directory 帳戶樹系。  <br/>  多個 Active Directory 帳戶樹系，每個都有自己的 Exchange 組織。 <br/> <br/> **附註**  在多重樹系 Active Directory 案例中，如果部署了 Lync 2010、Lync 2013 或商務用 Skype，則必須是部署在和 Exchange 相同的 Active Directory 樹系中。**   <br/>  <br/>      **附註**  在 Exchange 多重混合設定中，搭配多個 Exchange 組織實作多重 Active Directory 樹系時，不支援來源樹系之間共用的使用者主要名稱 (UPN) 命名空間。同時也應該分隔 Exchange 組織之間的主要 SMTP 命名空間。如需詳細資訊，請參閱＜[具有多個 Active Directory 樹系的混合部署](https://go.microsoft.com/fwlink/?linkid=845444)＞。**     <br/>   <br/>   **附註**  對於所有多重樹系組態，AD FS 部署是在 FastTrack Center 權益的範圍外。**           |
|Exchange Online 上架 | 您的環境必須具備下列最低層級的其中一項：  <br/>  含有 Exchange Server 2003 以上版本的單一或多個 Exchange 組織。  <br/>  單一 IBM Domino 7.0.3+ 環境 ([附錄 A：從 IBM Domino 移轉至 Exchange Online](O365-from-ibm-domino-to-exchange-online.md))。  <br/>  具備單一網際網路訊息存取通訊協定 (IMAP) 功能的電子郵件環境。  <br/>  單一 G Suite 環境 (僅限 Gmail、連絡人和行事曆)。  <br/>  單一 Novell GroupWise 7.0.4+ 環境。            |
|SharePoint Online 和商務用 OneDrive 上架  | **SharePoint 混合式**  <br/>  SharePoint 混合式組態包括設定混合式搜尋、網站、分類、內容類型、商務用 OneDrive、擴充的應用程式啟動器、外部網路網站，以及從內部部署連線到單一目標 SharePoint Online 環境的自助網站架設。若要啟用 SharePoint 混合式，您必須具有下列其中一項 SharePoint Server 內部部署環境︰  <br/> <br/> ***SharePoint Server 2013***  <br/>  混合式內容類型的 2017 年 6 月公開更新 (PU)。如需詳細資訊，請參閱＜[設定混合式 SharePoint 分類和混合式的內容類型](https://go.microsoft.com/fwlink/?linkid=853547)＞。<br/>  自助網站建立組態的 2017 年三月 PU。只有 SharePoint Server 2013 才支援混合式自助網站建立。如需詳細資訊，請參閱[混合式自助網站建立](https://go.microsoft.com/fwlink/?linkid=846015)。<br/>  從 2016 年 11 月公開更新開始，且須具備混合式分類。如需詳細資訊，請參閱＜[規劃混合式 SharePoint 分類和混合式的內容類型](https://go.microsoft.com/fwlink/?linkid=844867)＞。<br/>  從 2016 年 7 月公開更新開始，所有其他的混合式組態案例。  <br/><br/> **附註**  SharePoint Server 2013 混合案例只支援搭配 SharePoint Server 2013。SharePoint Foundation 2013 中不支援這些案例。**  <br/>   <br/>    ***SharePoint Server 2016***  <br/>  混合式內容類型的 2017 年 6 月公開更新。如需詳細資訊，請參閱＜[設定混合式 SharePoint 分類和混合式的內容類型](https://go.microsoft.com/fwlink/?linkid=853547)＞。<br/>  從 2016 年 11 月公開更新 (Feature Pack 1) 與混合式分類。如需詳細資訊，請參閱＜[規劃混合式 SharePoint 分類和混合式的內容類型](https://go.microsoft.com/fwlink/?linkid=844867)＞。<br/>  從 2016 年 7 月公開更新開始，所有其他的混合式組態案例。  <br/><br/> **附註**  FastTrack Center 提供的權益不包含將內部部署 SharePoint 環境升級為 SharePoint Server 2013 或 SharePoint Server 2016。如需詳細資訊，請參閱＜[SharePoint 混合式功能的最小的公用更新層級](https://go.microsoft.com/fwlink/?linkid=853548)＞。**             |
|商務用 Skype Online 上架  | **網路評估**  <br/>  連接埠和端點檢查。  <br/>  連線品質檢查。  <br/>  頻寬估計。  <br/><br/>  **Lync 混合式**  <br/>  單一內部部署 Active Directory 樹系。  <br/>  Lync 2010 Server 環境與 Lync 2013 系統管理工具或 商務用 Skype 2015 系統管理工具和 Lync 2010 Edge server role。  <br/>  Lync 2013 Server 環境和 Lync 2013 Edge 伺服器角色。  <br/><br/>  **商務用 Skype Online 混合式**  <br/>  單一內部部署 Active Directory 樹系。  <br/>  單一 Active Directory 帳戶樹系 + 和資源樹系 (Exchange 及/或商務用 Skype) 拓撲。  <br/>  多個 Active Directory 帳戶樹系，其中一個樹系是具有 Exchange 和/或商務用 Skype 的集中式 Active Directory 帳戶樹系。  <br/>  商務用 Skype Server 2015 環境包括商務用 Skype Edge server role。  <br/><br/> **附註**  此額外的服務適用於設定及驗證分割網域 (混合) 工作，不包含引進內部部署元件 (例如，Lync 2013 系統管理工具或 Lync 2013/商務用 Skype Online 伺服器，或 Lync 2010、Lync 2013 或 商務用 Skype Edge Server)。**    <br/><br/>        **會議室裝置**  <br/>  建立 [商務用 Skype 解決方案目錄](https://go.microsoft.com/fwlink/?LinkId=615775)中 [會議室系統] 索引標籤上所列的已支援會議室裝置所需的線上帳戶。  <br/><br/>  **啟用音訊會議**  <br/>  會議橋接預設設定的組織設定。  <br/>  對授權使用者會議橋接的指派。  <br/><br/>  **啟用電話系統和通話方案指引 （僅限美國 – GCC 高] 或 [DoD 計劃中無法使用）**  <br/>  雲端語音預設設定的組織設定。  <br/>  授權使用者號碼的指派。  <br/>  透過使用者介面 (UI) 的本機號碼移轉指引最多至 999。  <br/>  本機號碼移轉服務要求 (SR) 支援超過 999。  <br/><br/>  **啟用 Skype 商務會議廣播指引上架 （不適用於 GCC 高] 或 [DoD 計劃）**  <br/>  針對會議廣播服務同盟的組織設定。   |
|Microsoft Teams 上架 （不適用於 GCC High 或 DoD 計劃） | 已在適用於 Office 365 的 Azure Active Directory 中啟用識別。  <br/>  已啟用 SharePoint Online 的使用者。  <br/>  已存在 Exchange 信箱 (位在 Exchange 混合式組態中，線上和/或內部部署形式)。  <br/>  啟用 Office 365 群組。  <br/><br/> **附註**  若未以 SharePoint Online 授權指派並啟用使用者，他們在 Office 365 中就不會有商務用 OneDrive 儲存空間。在通道中仍可繼續使用檔案共用，但若沒有 Office 365 中的商務用 OneDrive 儲存空間，使用者便無法在 [聊天] 中分享檔案。Microsoft Teams 不支援 SharePoint 的內部部署。**   <br/> <br/>       **附註**  理想的狀態是所有使用者的信箱，都位於 Exchange Online 上。其信箱位在內部部署上的使用者，必須透過 Azure Active Directory Connect，將其身分識別與 Office 365 目錄同步。對於這些 Exchange 混合客戶，如果使用者的信箱位在內部部署上，則使用者無法新增或設定連接器。**          |
| 服務上架，包含：  <br/>  *Exchange Online <br/> SharePoint Online<br/>商務用 OneDrive <br/> Skype for Business Online <br/> Microsoft Teams <br/> Power BI <br/> Project Online <br/> Yammer <br/> Office 365 專業增強版<br/>*   |線上用戶端軟體 (如 Project for Office 365、Outlook 用戶端、商務用 OneDrive 同步用戶端、Power BI Desktop 和 商務用 Skype) 必須採用 [Office 的系統需求](https://go.microsoft.com/fwlink/?LinkID=723597)中所定義的最低層級。  <br/> Microsoft Teams Windows 安裝程式和 Mac 桌面用戶端可以從這裡下載：[https://go.microsoft.com/fwlink/?linkid=839411](https://go.microsoft.com/fwlink/?linkid=839411)。   |
   

  

