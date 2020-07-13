---
title: 資料移轉
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack Specialists provide guidance on steps for data migration to Office 365. This is available for all eligible customers with Office 365 services for Exchange Online, OneDrive for Business, and SharePoint Online.
ms.openlocfilehash: 7780af3d5edcdbdf21acba1d421bf379967305fa
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011307"
---
# <a name="data-migration"></a>資料移轉

您可能具有必須移轉到 Office 365 的來源環境中資料。

**如果您使用的是含150-499 授權的 Office 365 租用戶：** 我們會使用工具和文件組合來提供指導方針，讓您順利進行移轉。 

**針對擁有500 或更多授權的 Office 365 租用戶\*：** 的資料移轉服務可供 Exchange Online、SharePoint Online 和商務用 OneDrive 使用。 您的 FastTrack 權益包括為您提供來源環境整合與移轉資料的指導方針。
  
\*If you purchased or renewed a commercial plan prior to 9/1/2017, 150 seats is the minimum seat requirement throughout your current subscription period in order to receive the migration benefit. For education plans, only paid faculty and staff licenses are eligible for migration services. 
  
> [!NOTE]
> Data migrated through the FastTrack services may be transferred to, stored, and processed anywhere that Microsoft maintains facilities (except as otherwise provided for your particular FastTrack engagement). The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements. 
  
> [!NOTE]
> 未預期的問題 (包含但不限於來源環境中無法讀取或毀損的項目) 可能會使某些項目無法進行移轉。 
  
> [!NOTE]
> 移轉協助提供的語言有：繁體中文和簡體中文 (僅限說中文的資源)、英文、法文、德文、義大利文、日文、葡萄牙文 (巴西)、西班牙文。 
  
> [!NOTE]
> 如果需要整合，您的來源環境必須符合該應用程式所需的最低層級。 
  
> [!NOTE]
> Microsoft 於 2020 年 3 月推出新功能，提供六個月的 [Office 365 E1](https://docs.microsoft.com/microsoftteams/e1-trial-license) 和 [Office 365 G1](https://docs.microsoft.com/microsoftteams/g1-trial-license) 試用版授權，以因應客戶在 COVID-19 疫情爆發時的遠端工作和學習需求。 其中一項例外，FastTrack 將從 2020 年 3 月至 2020 年 8 月為擁有 500 個以上試用授權的租用戶提供資料移轉服務，並為學生提供 [Office 365 A1](https://www.microsoft.com/microsoft-365/academic/compare-office-365-education-plans?activetab=tab:primaryr1) 的資料移轉服務。 Microsoft 保留不經通知即可取消、變更或暫停此優惠的權利。

下表顯示您現有來源環境中預期會移轉的內容。
  

|**活動**|**來源環境預期**|
|:-----|:-----|
|**Exchange Online 移轉**  <br/> | Microsoft migrates any combination of the source environments listed below, each one at a time. We can migrate the onboarded messaging system using the FastTrack Center or if it's passed the FastTrack Center checks. This includes:  <br/>  若以 Exchange 2010+ 為基礎的混合式已實作於個別組織且 Exchange 郵件系統是 2003+，則為擁有單一或多個 Exchange 組織的單一或多個 Active Directory 樹系。  <br/>  具備單一 IMAP 功能的電子郵件環境。  <br/>  G Suite 環境 (僅限 Gmail、連絡人和行事曆)。 <br/> <br/> **附註** *移轉之前，必須先完成 Exchange Online 上架。* <br/> <br/> **附註** *FastTrack 只會移轉至作用中的 Office 365 信箱。* <br/> <br/> **附註** *如需內部部署 Exchange 相依性的詳細資訊，請參閱＜[混合部署必要條件](https://go.microsoft.com/fwlink/?LinkId=787528)＞。* <br/><br/> **附註** *移轉多個來源郵件環境 (如多個 Exchange 組織或多個 Domino 組織 ) 時，這些移轉會依序進行。*| 
|**SharePoint Online 移轉**  <br/> | 檔案共用 (支援 SMB 2.0+ 之裝置的伺服器訊息區 (SMB) 檔案共用)。 <br/> 單一 G Suite 環境 (僅限 Google 雲端硬碟)。<br/>  Box (Starter、Business、Enterprise)。  <br/> Dropbox for Teams (標準版和進階版)。<br/> |
|**商務用 OneDrive 移轉**  <br/> | 檔案共用 (支援 SMB 2.0+ 之裝置的 SMB 檔案共用)。  <br/>  單一 G Suite 環境 (僅限 Google 雲端硬碟)。  <br/>  Box (Starter、Business、Enterprise)。 <br/> Dropbox for Teams (標準版和進階版)。<br/><br/> **附註** *FastTrack 只會移轉至作用中的 Office 365 磁碟機。 *|
   
## <a name="migration-to-exchange-online"></a>遷移至 Exchange Online
''
### <a name="enable-to-migrate"></a>啟用即可移轉
  
如果您使用 Microsoft 來移轉您的電子郵件，我們將提供相關指引讓 Exchange Online 與來源環境均可進行移轉。 根據來源環境而定，我們可能會執行各種啟用步驟。 我們將使用工具和文件的組合，並在適用且可行的情況下執行設定工作，為您提供指引。 遵循適用的參數，我們接著移轉信箱、監控作業，並提供狀態報告。
'' Microsoft 可能需要您郵件系統的適當存取權和權限，才能執行移轉活動。
  
### <a name="migration-policy-and-steps"></a>移轉原則和步驟
  
> [!NOTE]
> 移轉時段亦稱為移轉批次。

#### <a name="commercial-and-uk-government"></a>商業版及英國政府機構

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>美國政府/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
 ### <a name="end-state"></a>結束狀態
  
移轉批次後的預期結束狀態包括：
- 來源環境中適當排程與合格來源信箱中的資料會移轉至 Office 365。 
- Microsoft 會提供移轉批次的移轉後報告。
    
預期在完成所有移轉之後的結束狀態包括：
- 合格來源信箱移轉至 Office 365 的資料定義於下表。
- 如下表所述，要移轉的資料類型視來源環境而定。
    
> [!NOTE]
> All source environments need to be on the latest service packs (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment at the end of the Enable phase. Data migration services are subject to external factors beyond Microsoft's control, like changes to third-party application programming interfaces (APIs), which could result in changes to, delays in, or suspension of these services. For the duration of the FastTrack services, data you make available to Microsoft is accessible from and stored anywhere that Microsoft and its suppliers maintain facilities. 
  
|||||
|:-----|:-----|:-----|:-----|
|**來源環境**|**移轉類型**|**會從來源信箱移轉的內容**|**不會移轉哪些內容**|
|**Exchange 2003+**|系統轉換| 電子郵件 <br/> 信箱規則 <br/> 委派 <br/> 信箱連絡人 <br/> 行事曆 <br/> 工作 <br/> 受版權管理的電子郵件 <br/> 加密的電子郵件| 公用資料夾 <br/> 個人連絡人 <br/> 擁有郵件功能的使用者 <br/> 遭封鎖或非作用中的使用者 <br/> 簽章 <br/> 信箱暫放 <br/>  任何超過郵件大小限制的電子郵件 <br/> 封存資料 <br/> 損毀的項目 <br/>  非使用中的信箱 |
|**Exchange 2003 和 Exchange 2007**|接移| 電子郵件 <br/> 信箱規則 <br/> 委派 <br/> 信箱連絡人 <br/> 行事曆 <br/> 工作 <br/> 受版權管理的電子郵件 <br/> 加密的電子郵件| 公用資料夾 <br/> 個人連絡人 <br/> 擁有郵件功能的使用者 <br/> 遭封鎖或非作用中的使用者 <br/> 簽章 <br/> 信箱暫放 <br/> 任何超過郵件大小限制的電子郵件 <br/> 封存資料 <br/> 損毀的項目 <br/> 非使用中的信箱 |
|**Exchange 2010、Exchange 2013、Exchange 2016 和 Exchange 2019** <br/><br/> **附註** *如需內部部署 Exchange 相依性的詳細資訊，請參閱＜[混合部署必要條件](https://go.microsoft.com/fwlink/?LinkId=787528)＞。*           |混合部署移轉| 電子郵件 <br/> 信箱規則 <br/> 委派 <br/> 信箱連絡人 <br/> 行事曆 <br/> Tasks <br/> 簽章 <br/> 隨著使用者信箱移轉的個人封存 <br/> 可復原的項目 <br/> 受版權管理的電子郵件 <br/> 加密的電子郵件| 公用資料夾 <br/> 任何超過郵件大小限制的電子郵件 <br/> 日誌封存或任何協力廠商封存解決方案 <br/> 遭封鎖或非作用中的使用者 <br/> 從個人存放區資料表 (PST) 檔案封存的資料 <br/> 損毀的項目 <br/> 非使用中的信箱 |
|**G Suite 環境 (僅限 Gmail、連絡人和行事曆)** <br/> <br/> **附註** *您的 G Suite 環境必須啟用 Google API 和 Google Admin SDK 才能擴充功能。* <br/>          |轉換或分段| 電子郵件 <br/> 信箱連絡人\*  <br/> 行事曆 <br/> 標籤 <br/> \*每個連絡人最多會移轉三個電子郵件地址| 規則 <br/> 委派 <br/> 簽章 <br/> 工作 <br/> 任何超過郵件大小限制的電子郵件或附件 <br/> 遭封鎖或非作用中的使用者 <br/> 從 PST 檔案或任何協力廠商封存解決方案 (例如 Google Vault) 封存的資料 <br/> 權限管理或加密的電子郵件 <br/> 損毀的項目 <br/> Google Hangouts\*\* <br/> Google Groups <br/> 資源信箱 <br/> 非使用中的信箱 <br/> 假期設定和自動回覆設定 <br/> 共用行事曆、雲端附件、Google Hangout 連結和活動色彩 <br/>\*\*會移轉儲存為標籤的 Hangout 交談 |
|**IMAP4 來源 (例如 Domino、GroupWise 和 Zimbra)** |使用原生 IMAP4 工具進行的移轉| 電子郵件 | 規則 <br/> 委派 <br/> 通訊群組清單 <br/> 外部連絡人 <br/> 擁有郵件功能的使用者 <br/> 遭封鎖或非作用中的使用者 <br/> 信箱連絡人 <br/> 行事曆 <br/> 簽章 <br/> 工作 <br/> 任何超過郵件大小限制的電子郵件 <br/> 封存資料 <br/> 加密的電子郵件 <br/> 損毀的項目 <br/> 非使用中的信箱 |
   
> [!NOTE]
> If distribution lists (MailEnabledGroup objects) and external contacts (MailEnabledContact objects) are in the on-premises Active Directory, they can be synchronized using Azure AD Connect. However, they aren't a part of mailbox data migration. For more information, see the **Identity integration** example in [Core](O365-onboarding-and-migration.md#core). 
  
FastTrack 專家會在移轉期間執行下列工作：
- 提供標準範本以便排程信箱移轉。
- 提供 FastTrack 專家所需權限的資訊。 
- 以預定的格式收集預定的信箱移轉排程。
- 先嘗試在移轉批次內執行單一信箱的移轉最多 2 次，才將該信箱報告為移轉失敗。
- 在 Exchange 和 IMAP4 來源環境中，信箱內容最多只能移轉使用者信箱儲存空間限制的 85% (例如，如果信箱儲存空間限制為 50 GB，則 Microsoft 最多會移轉 50 GB 儲存空間限制的 85%)。 
- 啟用來源訊息環境與 Office 365 Exchange Online 之間的 SMTP 郵件路由共存 (使用轉換移轉時除外)。
- 提供移轉後報告。
- Provide post-migration assistance for critical issues. The following issues are considered critical:
  - 在移轉期間遺失資料。
  - 在移轉期間無法使用來源環境。
  - 移轉活動導致來源環境發生問題。
    
您會在移轉期間執行下列工作：
- 完成 Exchange Online 上架或使用 FastTrack Center 通過必要的檢查。
- 處理所有與使用者的通訊。  
- 依 Office 365 指導方針安裝適當層級的用戶端軟體。 如需詳細資訊，請參閱[現代化工作場所](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。 
- 驗證來源郵件環境與 Office 365 Exchange Online 之間的 SMTP 郵件路由共存 (若適用)。
- 以定義的方法針對每個移轉事件提供排程和要移轉的特定信箱清單。
- 進行移轉批次前，從排程卸除 24 小時前的信箱。 
- 如下表所列，在 24 小時期間內排程目標平均信箱數目。
    
|||
|:-----|:-----|
|**適合移轉的信箱數目** <br/> |**24 小時期間內的平均最小信箱數目** <br/> |
|150-1000  <br/> |總數的 25%  <br/> |
|1001-5000  <br/> |總數的 20%  <br/> |
|5001-10000  <br/> |總數的 15%  <br/> |
|\>10000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > These numbers are based on best practice. However, the number of mailboxes that migrate per day will vary based on environment, readiness, and business constraints. Microsoft can't guarantee the speed of mailbox migration. 
  
- 在移轉批次中最少排程 35 個信箱。 
- 如果適用的話，修正移轉前失敗。  
- 將來源環境的存取權和權限提供給 FastTrack 專家以執行移轉活動。 
- 在 Office 365 中取得及/或提供已授權的管理帳戶以執行移轉活動 (視需要而定)。 
- 協助用戶端遷移問題，必要時執行移轉後作業。 
- Migrate client-side data if desired. This includes, but is not limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.   
- 如果適用的話，將信箱大小縮小為低於目標 Office 365 信箱限制的 85%。   
- 處理移轉後報告中的動作，包括未移動的信箱。  
- 如果適用的話，修正移轉後失敗並重新排程信箱。   
- Engage in post-migration assistance for critical issues. The following issues are considered critical:
  - 在移轉期間遺失資料。
  - 在移轉期間無法使用來源環境。
  - 移轉活動導致來源環境發生問題。
    
You need to follow the standard migration process and engage with Microsoft appropriately. This includes providing access and permissions to source and Office 365 environments, providing migration schedules, correcting any causes for migration errors, and so on. You also need to engage with end users for communications, mailbox migration schedule, and handling end user migration-related issues.
  
> [!NOTE]
> Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
  
## <a name="migration-to-sharepoint-online"></a>移轉至 SharePoint Online

### <a name="enable-to-migrate"></a>啟用即可移轉
  
If you use Microsoft to migrate your data, we provide guidance to enable both SharePoint Online and the source environment for migration. Depending on the source, we may perform various Enable steps. We provide guidance for you by using a combination of tools and documentation and by performing configuration tasks where applicable and feasible.
  
您需要提供適當的存取權和權限給 Microsoft，以執行某些活動。
  
### <a name="migration-policy-and-steps"></a>移轉原則和步驟
  
> [!NOTE]
> 移轉時段亦稱為移轉批次。

#### <a name="commercial-and-uk-government"></a>商業版及英國政府機構

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>美國政府/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.

- 所有移轉都受限於 [SharePoint Online 和商務用 OneDrive 軟體的界限及限制](https://go.microsoft.com/fwlink/?LinkID=616612)中所述的 SharePoint Online 配額。   
- 移轉的整體資料數量將受限於您有權使用的整體 SharePoint Online 儲存空間配額的 75% (包括您可能需要另外購買的額外儲存空間)。
    
 ### <a name="end-state"></a>結束狀態
  
移轉批次後的預期結束狀態包括： 
- 來源環境中適當排程與合格來源中的資料會移轉至 SharePoint Online。   
- Microsoft 會提供移轉批次的移轉後報告。
    
預期在完成所有移轉之後的結束狀態包括： 
- 合格來源的資料會移轉至 Office 365，如下表定義。  
- 如下表所述，要移轉的資料類型視來源環境而定：
    
|||||
|:-----|:-----|:-----|:-----|
|**來源環境** <br/> |**移轉類型** <br/> |**什麼會移轉** <br/> |**不會移轉哪些內容** <br/> |
|**任何支援 SMB 2.0+ 的檔案共用裝置**  <br/> |單一或多個階段  <br/> | 文件  <br/>  檔案與資料夾結構  <br/>  使用者層級檔案和資料夾權限\*  <br/>  群組層級檔案和資料夾權限\*  <br/>  小於 15 GB 的檔案  <br/>  基本文件與資料夾的中繼資料：  <br/>  建立日期  <br/>  修改日期  <br/>  建立者  <br/>  上次修改者  <br/><br/> \**需要設定目錄同步處理。只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。不移轉直接在檔案共用裝置上管理的權限。若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。* <br/> | 擁有權歷程記錄與先前的版本  <br/>  內容中的內嵌 URL 轉換  <br/>  舊版  <br/>  Windows 檔案和資料夾屬性 (例如唯讀、隱藏)  <br/>  非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：  <br/>  明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)  <br/>  NTFS 稽核組態  <br/>  檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料  <br/>  無法存取或損毀的文件  <br/>  隱藏的共用  <br/>  共用 (例如共用層級授與的權限)  <br/>  檔案或資料夾超過目前 [Sharepoint 的規定和限制](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**單一 G Suite 環境 (僅限 Google 雲端硬碟)**  <br/> |單一或多個階段  <br/> | <br/>  Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式) ，包括超過 10 MB 的檔案。 <br/>  檔案與資料夾結構  <br/>  使用者層次資料夾權限  <br/>  群組層級資料夾權限 <br/>  小於 15 GB 的檔案  <br/> 基本文件與資料夾的中繼資料： <br/> 建立日期  <br/>  修改日期  <br/>  建立者  <br/>  上次修改者  <br/> 共用的磁碟 (資料夾和檔案) <br/>  正在移轉之 Google 雲端硬碟所擁有的共用內容 (如果明確與使用者或群組共用)\*  <br/><br/> \**使用 Google 雲端硬碟系統管理員來識別外部帳戶。指示使用者在移轉之後重新共用其內容。* <br/> | 擁有權歷程記錄、先前的版本和註解 <br/>  檔案與資料夾描述、資料夾顏色  <br/>  使用者層次檔案權限  <br/>  群組層級檔案權限  <br/>  進階中繼資料  <br/>  檔案鎖定屬性  <br/>  內容中的內嵌 URL 轉換  <br/>  丟到垃圾筒的項目  <br/>  無法存取或損毀的文件  <br/>  遭封鎖或非作用中的使用者  <br/>  Google 相簿、表單、地圖及其他連線的應用程式  <br/>  Google 繪圖  <br/>  組織外部的共用內容  <br/> 內容不是由移轉中的 Google 雲端硬碟帳戶所擁有 <br/>外部使用者的權限和中繼資料  <br/> 共用的磁碟機成員權限\* <br/> 檔案或資料夾超過目前 [Sharepoint 的規定和限制](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**使用 Google 雲端硬碟系統管理員來識別外部帳戶。指示使用者在移轉之後重新共用其內容。* <br/>|
|**Box (Starter、Business、Enterprise)**  <br/> |單一或多個階段  <br/> | 文件  <br/>  檔案與資料夾結構  <br/>  使用者層級資料夾權限  <br/>  群組層級資料夾權限  <br/>  小於 15 GB 的檔案  <br/>  基本文件與資料夾的中繼資料：  <br/>  建立日期  <br/>  修改日期  <br/>  建立者  <br/>  上次修改者  <br/>  正在移轉之 Box 帳戶所擁有的共用內容 (如果明確與使用者或群組共用)\*  <br/><br/> \**使用 Box 報告來識別外部帳戶。指示使用者在移轉之後再度分享其內容。* <br/> | 擁有權歷程記錄、先前的版本和註解 <br/>  使用者層級檔案權限  <br/>  群組層級檔案權限  <br/>  檔案與資料夾描述  <br/>  Box 標記和進階中繼資料  <br/>  檔案鎖定屬性  <br/>  內容中的內嵌 URL 轉換  <br/>  丟到垃圾筒的項目  <br/>  無法存取或損毀的文件  <br/>  遭封鎖或非作用中的使用者  <br/>  Box 附註 (因移轉時未轉換而無功能)  <br/>  Box 應用程式、書籤、我的最愛及工作流程  <br/>  內容不屬於移轉之 Box 帳戶 (共用資料夾)  <br/>  外部使用者的權限和中繼資料\*  <br/>  檔案或資料夾超過目前 [Sharepoint 的規定和限制](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/>\**使用 Google 雲端硬碟系統管理員來識別共用磁碟機成員資格。指示使用者在移轉前先組態目標的成員資格設定。* |
|**Dropbox for Teams (標準版和進階版)**  <br/> |單一或多個階段  <br/> | 文件  <br/>  檔案與資料夾結構  <br/>  使用者層次資料夾權限  <br/>  群組層級資料夾權限  <br/>  小於 15 GB 的檔案  <br/>  基本文件與資料夾的中繼資料：  <br/>  建立日期  <br/>  修改日期  <br/>  建立者  <br/>  上次修改者  <br/> 共用的小組資料夾和內容 <br/>  正在移轉之 Dropbox 帳戶所擁有的共用內容 (如果明確與使用者或群組共用)\*  <br/> <br/> \**使用 Dropbox 報告來識別外部帳戶。指示使用者在移轉之後再度分享其內容。* <br/> | 擁有權歷程記錄、先前的版本和註解 <br/>  檔案與資料夾描述 <br/>  使用者層次檔案權限  <br/>  群組層級檔案權限    <br/> 進階中繼資料  <br/>  檔案鎖定屬性  <br/>  內容中的內嵌 URL 轉換  <br/>  丟到垃圾筒的項目  <br/>  無法存取或損毀的文件  <br/>  已卸載的 Dropbox 資料夾 <br/>  已刪除或中斷連線的使用者 <br/>  Dropbox Paper、Showcases 和 Spaces  <br/> Dropbox 應用程式和我的最愛 (釘選/星號) <br/> 不是由已移轉的 Dropbox 帳戶所擁有的內容  <br/>  外部使用者的權限和中繼資料\*  <br/>  檔案或資料夾超過目前 [Sharepoint 的規定和限制](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**使用 Dropbox 報告來識別外部帳戶。指示使用者在移轉之後再度分享其內容。* <br/> |
   
FastTrack 專家會在移轉期間執行下列工作： 
- 舉行一場移轉逐步研習會，並涵蓋所選取移轉案例的程序與方法。
- 針對案例適用的情況，提供評估與移轉工具的必要條件。   
- 針對評估與移轉目的，對來源和目標環境的移轉小組存取權提供先決條件。 
- 提供評估工具以進行目標來源環境的評估，或是提供如何使用原生來源平台功能來建立評估報告的指示。   
- 在部署時協助，並執行評估與移轉工具 (若適用)。   
- 為內容移轉 (於適用時) 在準備中設定移轉基礎結構。    
- 進行有限的測試移轉作業以驗證移轉基礎結構，以及所需的必要條件。   
- 佈建現成可用的目標 SharePoint Online 站台作為移轉的一部分。    
- 在快速移轉前先進行一次試驗移轉。   
- 針對所選案例提供移轉排程的相關指導。 
- 依據由客戶提供且經 FastTrack 資源驗證的移轉排程來進行加速移轉多批內容。   
- 在各個移轉視窗完成後提供移轉結果。   
- 參與加速移轉問題分類並提供可能的補救選項指引。   
- 針對每個加速移轉視窗提供最終移轉報告。   
- 在移轉完成後至多五天，於使用者接受度測試中提供移轉後協助。
    
您會在移轉期間執行下列工作： 
- Provide project resources recommended for assessment and migration activities. These include: 
  - 專案管理。 
  - 使用者接受度測試 (UAT)。  
  - 系統管理員負責來源和目標內容平台。  
- 針對評估和移轉活動提供基礎結構必要條件 (如有必要)。  
- 將來源及目標環境的存取權和權限提供給 FastTrack 專家以執行移轉活動 (如有必要)。
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
- 提供必要條件並執行支援評定和移轉所需的活動。   
- 安裝由 FastTrack 所提供的評估工具，並完成評估資料收集活動 (如果適用)。   
- 在內部部署安裝由 FastTrack 所提供的移轉軟體 (如果適用)。   
- 完成 FastTrack 所提供的補救報告中所述的補救動作　(如果適用)。  
- 使用 FastTrack 範本和指引來提供移轉排程。   
- 執行移轉品質保證和使用者接受度測試。   
- 執行移轉後的移轉補救措施 (如果適用)。
- 規劃及實作變更管理與使用者通訊 (若適用)。   
- 管理和設定來源系統和裝置 (成功完成評估及移轉活動所需) 的任何變更。
- 至少提前三 (3) 天提供已定義方法的排程和要在每個移轉事件移轉的特定使用者資料清單。
- 進行移轉批次前，從排程卸除 24 小時前的使用者資料。 這應該會對應到最後的移轉批次。
> [!NOTE]
> Microsoft 不保證檔案移轉的速度。
    
## <a name="migration-to-onedrive-for-business"></a>移轉至商務用 OneDrive

 ### <a name="enable-to-migrate"></a>啟用即可移轉
  
If you use Microsoft to migrate your data, we provide guidance to enable both OneDrive for Business and the source environment for migration. Depending on the source, we may perform various Enable steps. We help you with some activities by using a combination of tools, documentation, and guidance, and by performing configuration tasks where applicable and feasible.
  
You may need to provide appropriate access and permissions to Microsoft to perform some activities. If you don't provide access and/or permissions, you need to perform certain defined tasks yourself with guidance from Microsoft. 
  
### <a name="migration-policy-and-steps"></a>移轉原則和步驟
  
> [!NOTE]
> 移轉時段亦稱為移轉批次。

#### <a name="commercial-and-uk-government"></a>商業版及英國政府機構

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>美國政府/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
- 所有移轉都需要來源環境的適當存取權和權限。   
- 所有移轉都受限於 [SharePoint Online 和商務用 OneDrive：軟體界限及限制](https://go.microsoft.com/fwlink/?LinkId=698855)中所述的商務用 OneDrive 配額。
    
 ### <a name="end-state"></a>結束狀態
  
移轉批次後的預期結束狀態包括：  
- 來源環境中適當排程與合格來源中的資料會移轉至商務用 OneDrive。  
- Microsoft 會提供移轉批次的移轉後報告。
    
預期在完成所有移轉之後的結束狀態包括：
- 合格來源移轉至 Office 365 的資料定義於下表。  
- 如下表所述，要移轉的資料類型視來源環境而定。
    
|||||
|:-----|:-----|:-----|:-----|
|**來源環境**|**移轉類型**|**什麼會移轉**|**不會移轉哪些內容**|
|**任何支援 SMB 2.0+ 的檔案共用裝置**  <br/> |單一或多個階段  <br/> | 文件  <br/>  檔案與資料夾結構  <br/>  使用者層級檔案和資料夾權限\*  <br/>  群組層級檔案和資料夾權限\*  <br/>  小於 15 GB 的檔案  <br/>  基本文件與資料夾的中繼資料：  <br/>  建立日期  <br/>  修改日期  <br/>  建立者  <br/>  上次修改者  <br/> <br/>\**需要設定目錄同步處理。只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。不移轉直接在檔案共用裝置上管理的權限。若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。* <br/> | 擁有權歷程記錄與先前的版本  <br/>  內容中的內嵌 URL 轉換  <br/>  舊版  <br/>  Windows 檔案和資料夾屬性 (例如唯讀、隱藏)  <br/>  非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：  <br/>  明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)  <br/>  NTFS 稽核組態  <br/>  FCI 提供的其他檔案中繼資料  <br/>  無法存取或損毀的文件  <br/>  隱藏的共用  <br/>  共用 (例如共用層級授與的權限)  <br/>  檔案或資料夾超過目前 [Sharepoint 的規定和限制](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**單一 G Suite 環境 (僅限 Google 雲端硬碟)**  <br/> |單一或多個階段  <br/> | Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式 ，包括超過 10 MB 的檔案)  <br/>  檔案與資料夾結構  <br/>  使用者層次資料夾權限  <br/>  群組層級資料夾權限  <br/>  小於 15 GB 的檔案  <br/>  基本文件與資料夾的中繼資料：  <br/>  建立日期  <br/>  修改日期  <br/>  建立者  <br/>  上次修改者  <br/> 共用的磁碟 (資料夾和檔案) <br/> 正在移轉之 Google 雲端硬碟所擁有的共用內容 (如果明確與使用者或群組共用)\* <br/> <br/>\**使用 Google 雲端硬碟系統管理員來識別外部帳戶。指示使用者在移轉之後重新共用其內容。* <br/> | 擁有權歷程記錄、先前的版本和註解  <br/>  檔案與資料夾描述、資料夾顏色  <br/>   使用者層次檔案權限  <br/>  群組層級檔案權限  <br/> 進階中繼資料 <br/>  檔案鎖定屬性 <br/> 內容中的內嵌 URL 轉換  <br/> 丟到垃圾筒的項目 <br/> 無法存取或損毀的文件 <br/> 遭封鎖或非作用中的使用者 <br/> Google 相簿 <br/> 表單、地圖及其他連線的應用程式 <br/> Google 繪圖 <br/> 組織外部的共用內容 <br/> 內容不是由移轉中的 Google 雲端硬碟帳戶所擁有 <br/> 外部使用者的權限和中繼資料<br/> 共用的磁碟機成員權限\*<br/> 檔案或資料夾超過目前 [Sharepoint 的規定和限制](https://go.microsoft.com/fwlink/?linkid=846724) <br/><br/> \**使用 Google 雲端硬碟系統管理員來識別共用磁碟機成員資格。指示使用者在移轉前先組態目標的成員資格設定。* <br/> |
|**Box (Starter、Business、Enterprise)**  <br/> |單一或多個階段  <br/> | 文件  <br/>  檔案與資料夾結構  <br/>  使用者層級資料夾權限  <br/>  群組層級資料夾權限  <br/>  小於 15 GB 的檔案  <br/>  基本文件與資料夾的中繼資料：  <br/>  建立日期  <br/>  修改日期  <br/>  建立者  <br/>  上次修改者  <br/>  正在移轉之 Box 帳戶所擁有的共用內容 (如果明確與使用者或群組共用)\*  <br/><br/> \**使用 Box 報告來識別外部帳戶。指示使用者在移轉之後再度分享其內容。* <br/> | 擁有權歷程記錄、先前的版本和註解  <br/>  檔案與資料夾描述  <br/>  使用者層級檔案權限  <br/>  群組層級檔案權限  <br/>  Box 標記和進階中繼資料  <br/>  檔案鎖定屬性  <br/>  內容中的內嵌 URL 轉換  <br/>  丟到垃圾筒的項目  <br/>  無法存取或損毀的文件  <br/>  遭封鎖或非作用中的使用者  <br/>  Box 附註 (因移轉時未轉換而無功能)  <br/>  Box 應用程式、書籤、我的最愛及工作流程  <br/>  內容不屬於移轉之 Box 帳戶 (共用資料夾)  <br/>  外部使用者的權限和中繼資料\*  <br/>  檔案或資料夾超過目前 [Sharepoint 的規定和限制](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Dropbox for Teams (標準版和進階版)**  <br/> |單一或多個階段  <br/> | 文件  <br/>  檔案與資料夾結構  <br/>  使用者層次資料夾權限  <br/>  群組層級資料夾權限  <br/>  小於 15 GB 的檔案  <br/>  基本文件與資料夾的中繼資料：  <br/>  建立日期  <br/>  修改日期  <br/>  建立者  <br/>  上次修改者  <br/> 共用的小組資料夾和內容 <br/> 正在移轉之 Dropbox 帳戶所擁有的共用內容 (如果明確與使用者或群組共用)\*  <br/> <br/> \**使用 Dropbox 報告來識別外部帳戶。指示使用者在移轉之後再度分享其內容。* <br/> | 擁有權歷程記錄、先前的版本和註解 <br/>  檔案與資料夾描述 <br/>  使用者層次檔案權限  <br/>  群組層級檔案權限    <br/> 進階中繼資料  <br/>  檔案鎖定屬性  <br/>  內容中的內嵌 URL 轉換  <br/>  丟到垃圾筒的項目  <br/>  無法存取或損毀的文件  <br/>  已卸載的 Dropbox 資料夾 <br/>  已刪除或中斷連線的使用者 <br/>  Dropbox Paper、Showcases 和 Spaces  <br/> Dropbox 應用程式和我的最愛 (釘選/星號) <br/> 不是由已移轉的 Dropbox 帳戶所擁有的內容  <br/>  外部使用者的權限和中繼資料\*  <br/>  檔案或資料夾超過目前 [Sharepoint 的規定和限制](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**使用 Dropbox 報告來識別外部帳戶。指示使用者在移轉之後再度分享其內容。* <br/> |
   
FastTrack 專家會在移轉期間執行下列工作：  
- 舉行一場移轉逐步研習會，並涵蓋所選取移轉案例的程序與方法。   
- 針對案例適用的情況，提供評估與移轉工具的必要條件。  
- 針對評估與移轉目的，對來源和目標環境的移轉小組存取權提供先決條件。   
- 提供評估工具以進行目標來源環境的評估，或是提供如何使用原生來源平台功能來建立評估報告的指示。    
- 在部署時協助，並執行評估與移轉工具 (若適用)。   
- 為內容移轉 (於適用時) 在準備中設定移轉基礎結構。    
- 進行有限的測試移轉作業以驗證移轉基礎結構，以及所需的必要條件。    
- 佈建現成可用的目標 商務用 OneDrive 站台作為移轉的一部分。    
- 在快速移轉前先進行一次試驗移轉。
- 針對所選案例提供移轉排程的相關指導。   
- 依據由客戶提供且經 FastTrack 資源驗證的移轉排程來進行加速移轉多批內容。   
- 在各個移轉視窗完成後提供移轉結果。   
- 參與加速移轉問題分類並提供可能的補救選項指引。 
- 針對每個加速移轉視窗提供最終移轉報告。   
- 在移轉完成後至多五天，於使用者接受度測試中提供移轉後協助。
   
您會在移轉期間執行下列工作：
- Provide project resources recommended for assessment and migration activities. These include:
  - 專案管理。
  - UAT。
  - 系統管理員負責來源和目標內容平台。
- 針對評估和移轉活動提供基礎結構必要條件 (如有必要)。   
- 將來源及目標環境的存取權和權限提供給 FastTrack 專家以執行移轉活動 (如有必要)。  
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
- 安裝由 FastTrack 所提供的評估工具，並完成評估資料收集活動 (如果適用)。
- 在內部部署安裝由 FastTrack 所提供的移轉軟體 (如果適用)。  
- 完成 FastTrack 所提供的補救報告中所述的補救動作　(如果適用)。   
- 使用 FastTrack 範本和指引來提供移轉排程。 
- 提供已定義方法的排程和要在每個移轉事件移轉的特定使用者資料清單。
- Drop user data from the schedule until 24 hours in advance of the migration batch. This should correspond to the final migration batch.
- 執行移轉品質保證和使用者接受度測試。   
- 執行移轉後的移轉補救措施 (如果適用)。  
- 規劃及實作變更管理與使用者通訊 (若適用)。  
- 管理和設定來源系統和裝置 (成功完成評估及移轉活動所需) 的任何變更。
    
> [!NOTE]
> Microsoft 不保證檔案移轉的速度。 


