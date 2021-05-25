---
title: 資料移轉
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。 我們可以提供的協助類型取決於您的 Office 365 授權數量。
ms.openlocfilehash: 4fc2f5c1bf74de40109e7022ba7c333065f74d24
ms.sourcegitcommit: 736a256276ead91385e1ec37b8a120b22259c4ea
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/24/2021
ms.locfileid: "52626670"
---
# <a name="data-migration"></a>資料移轉

FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。

我們提供的協助類型取決於您的 Office 365 授權數量：

  - **針對有 150-499 個授權的 Microsoft Office 365 租用戶**：FastTrack 僅提供移轉指引；由您負責執行資料移轉。 我們會透過可協助您規劃及使用免費工具的文件，引導您執行自助移轉。
  - **針對具有 500 個或更多授權數量的 Microsoft Office 365 租用戶**：FastTrack 會提供移轉指引和資料移轉服務。 我們會提供指引以協助規劃您的移轉事件、設定您的來源環境和 Office 365 租用戶，並充分利用我們的資料移轉服務來移轉您的資料。 您可以建立您的移轉事件並設定排程。 我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。

> [!NOTE]
> 如果您在 9/1/2017 之前已購買或續約ㄧ個商業方案，您只需使用 150 個授權，就能獲得資料移轉服務的資格。 針對教育方案，只有您的付費教職員授權符合使用資料移轉服務的資格。

### <a name="considerations"></a>考量

  - 您的來源環境必須符合特定期望條件，才能將資料移轉至 Microsoft Office 365。 如需其它與 Exchange、SharePoint、和 [商務用 OneDrive] 適用的來源環境期望，請參照 [產品和功能](products-and-capabilities.md)。
  - 為提供資料移轉服務，我們需要您的來源環境及 Office 365 租用戶的適當存取權和權限。
  - 我們的資料移轉服務既不是以受特殊法律、也不是受監管要求而設計或使用的。 當我們移轉您的資料時，可以將資料在任何我們進行設施維護的地方進行移轉、儲存及處理的動作（除非您的 FastTrack 移轉專案有提供另外的位置）。
  - 我們不能保證郵件或檔案移轉的速度。
  - 無法預料的問題（例如在來源環境中有無法讀取或已損毀的項目）可能會使我們無法移轉您的某些資料項目。
  - 在我們控制範圍之外的外部因素（像是第三方應用程式開發介面 (APIs) 出現變更）會導致我們的資料移轉服務出現變更、延遲、或暫停的情況。

### <a name="migration-service-availability"></a>移轉服務的狀態

  - **針對商業及英國政府客戶：** 我們提供每天 24 小時、每周 7 天（24x7）的全年無休資料移轉服務。
  - **針對美國政府/DOD 客戶：** 我們提供每天 24 小時、每周 5 個工作天（24x5）的資料移轉服務。

## <a name="migration-to-exchange-online"></a>移轉至 Exchange Online

當您選擇使用 FastTrack 將您的電子郵件移轉到 Exchange Online 時，我們會提供您移轉指引和資料移轉服務。 我們會提供指引以協助規劃您的移轉、設定您的來源環境和 Exchange Online，並充分利用我們的資料移轉服務來移轉您的信箱。 您可以建立您的移轉事件並設定排程。 我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。 當您的移轉事件完成後，您可以預期在您的來源環境中，郵件經適當排程和從合格來源信箱移轉到 Exchange Online。

### <a name="considerations"></a>考量

  - 在進行移轉之前，您必須完成適用於 Exchange Online 的 FastTrack 核心上線動作；
      - 如果您是自行上線，您必須傳送檢查和先決條件。 如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。
  - FastTrack 只會移轉至使用中的 Office 365 信箱。
  - 如果您想要從內部部署的 Exchange 環境將資料移轉出來，您必須滿足ㄧ些特定需求。 如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。
  - 每個來源環境都必須為其中各自相應的產品使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。
  - 存在於內部部署 Active Directory Domain Services 中的通訊群組清單（*MailEnabledGroup* 物件）和外部連絡人（*MailEnabledContact* 物件）並不屬於信箱資料移轉的一部分。 不過，您可以使用 Microsoft Azure Active Directory (Azure AD) Connect 進行同步處理。 

## <a name="source-environments"></a>來源環境

我們的資料移轉服務會將資料從這些來源環境中移轉出來：

  - 含有單一個或多個 Exchange 組織的單一或多個 Active Directory 樹系 (每ㄧ個 Exchange 郵件系統都必須使用 Exchange 2010 或更新的版本)。
  - 單一個具 IMAP 功能的電子郵件環境。
  - G Suite 環境 (僅限 Gmail、連絡人和Outlook 行事曆)。

下列表格顯示每個來源環境特定的移轉詳細資料：

<table>
<thead>
<tr class="header">
<th><strong>來源環境</strong></th>
<th><strong>移轉類型</strong></th>
<th><strong>可以移轉那些內容</strong></th>
<th><strong>哪些內容不能移轉</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong><br />
<br />
<strong>附注：</strong>如需內部部署 Exchange 相依性，請參閱<a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">混合部署必要條件</span></a>。</td>
<td>混合部署移轉</td>
<td><ul>
<li>電子郵件</li>
<li>伺服器端信箱規則</li>
<li>委派</li>
<li>信箱連絡人 </li>
<li> 行事曆 </li>
<li> 工作 </li>
<li> 受版權管理的電子郵件 </li>
<li> 加密的電子郵件 </li>
<li> 簽章 </li>
<li> 隨著使用者信箱移轉的個人封存 </li>
<li> 可復原的項目 </li>
</ul></td>
<td><ul>
<li> 公用資料夾 </li>
<li> 任何超過郵件大小限制的電子郵件 </li>
<li> 日誌封存或任何協力廠商封存解決方案 </li>
<li> 遭封鎖或非作用中的使用者 </li>
<li> 從個人存放區資料表 (PST) 檔案封存的資料 </li>
<li> 損毀的項目 </li>
<li> 非使用中的信箱 </li>
<li> 用戶端信箱規則</li>
</ul></td>
</tr>
<tr class="even">
<td><strong>G Suite 環境 (僅限 Gmail、連絡人和行事曆)</strong><br />
<br />
<strong>附注：</strong> 您的 G 套件環境必須符合 <a href="/exchange/mailbox-migration/perform-g-suite-migration">執行 G Suite 遷移</a>中所述的必要條件。</td>
<td>轉換或分段</td>
<td><ul>
<li> 電子郵件 </li>
<li> 信箱連絡人 (每個連絡人最多可移轉 3 個電子郵件地址) </li>
<li> 行事曆 </li>
<li> 標籤 </li>
</ul></td>
<td><ul>
<li> 規則 </li>
<li> 委派 </li>
<li> 簽章 </li>
<li> 工作 </li>
<li> 任何超過郵件大小限制的電子郵件或附件 </li>
<li> 遭封鎖或非作用中的使用者 </li>
<li> 從 PST 檔案或任何協力廠商封存解決方案 (例如 Google Vault) 封存的資料 </li>
<li> 權限管理或加密的電子郵件 </li>
<li> 損毀的項目 </li>
<li> Google Hangouts** </li>
<li> Google Groups </li>
<li> 資源信箱 </li>
<li> 非使用中的信箱 </li>
<li> 假期設定和自動回覆設定 </li>
<li> 共用行事曆、雲端附件、Google Hangout 連結和活動色彩 </li>
</ul>
**可移轉儲存為標籤的 Hangout 交談。 </td>
</tr>
<tr class="odd">
<td><strong>IMAP4 來源 (例如 Domino、GroupWise 和 Zimbra)</strong></td>
<td>使用原生 IMAP4 工具進行的移轉</td>
<td><li>電子郵件 </li></td>
<td><ul>
<li> 規則 </li>
<li> 委派 </li>
<li> 通訊群組清單 </li>
<li> 外部連絡人 </li>
<li> 擁有郵件功能的使用者 </li>
<li> 遭封鎖或非作用中的使用者 </li>
<li> 信箱連絡人 </li>
<li> 行事曆 </li>
<li> 簽章 </li>
<li> 工作 </li>
<li> 任何超過郵件大小限制的電子郵件 </li>
<li> 封存資料 </li>
<li> 加密的電子郵件 </li>
<li> 損毀的項目 </li>
<li> 非使用中的信箱 </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a>Exchange Online 遷移的 FastTrack 責任

我們的 FastTrack 專家在進行移轉專案時執行標準動作。 如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。

我們的 FastTrack 專家也會執行下列 Exchange 移轉動作特定的活動：

  -  可提供指引，以便協助您啟用在來源環境與 Exchange Online 之間並立的 SMTP 郵件路由傳送（如果適用的話）。

### <a name="your-responsibilities"></a>您的責任

由您在進行移轉專案時執行標準動作。 如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。

你也要執行下列 Exchange 移轉動作特定的活動：

  - 完成適用於 Exchange Online 的 FastTrack 核心上線動作。 如果您是自行上線，您必須傳送檢查和先決條件。 如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。
  -  依 Office 365 指引安裝適當層級的用戶端軟體。 如需詳細資訊，請參閱 [現代化工作場所](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。
  -  如果您想要從內部部署的 Exchange 環境將資料移轉出來，須滿足ㄧ些特定需求。 如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。
  -  如果適用的話，每個來源環境都必須使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。
  -  若適用的話，在您的來源環境和 Exchange Online 中，設定和驗證 SMTP 郵件路由傳送共存。
  -  請確定您的來源信箱容量大小未超過目標信箱配額。 視來源平台而定，您可能需要對來源資料限制在目標信箱配額的 85%。
  -  視需要移轉用戶端資料。 這包含、但不限於本機通訊錄、本機 PST 檔案中的資料、Outlook 規則和本機 Outlook 設定。
  -  協助使用者修正用戶端的遷移問題。

## <a name="migration-to-sharepoint-online"></a>移轉至 SharePoint Online

當您選擇使用 FastTrack 將您的檔案移轉到 SharePoint Online 時，我們會提供您移轉指引和資料移轉服務。 我們會提供指引以協助規劃您的移轉、設定您的來源環境和 SharePoint Online，並充分利用我們的資料移轉服務來移轉您的檔案。 您可以建立您的移轉事件並設定排程。 我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。 當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 SharePoint Online。

### <a name="considerations"></a>考量

 - 所有的移轉動作都受到 SharePoint Online 的配額限制。 如需詳細資訊，請參閱<a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint 限制</a>。 
  - 我們建議您將移轉的總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。

### <a name="source-environment-details"></a>來源環境詳細資料

我們的資料移轉服務可將資料從這些來源環境移轉出來：

  - 檔案共用 (支援 SMB 2.0+ 裝置的伺服器訊息區 (SMB) 檔案共用)。
  - 單一 G Suite 環境 (僅限 Google 雲端硬碟)。
  - Box (Starter、Business、Enterprise)。
  - Dropbox for Teams (標準版和進階版)。

下列表格顯示每個來源環境特定的移轉詳細資料：

<table>
<thead>
<tr class="header">
<th><strong>來源環境</strong></th>
<th><strong>移轉類型</strong></th>
<th><strong>可以移轉那些內容</strong></th>
 <th><strong>哪些內容不能移轉</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> 文件 </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層級檔案和資料夾權限* </li>
<li> 群組層級檔案和資料夾權限* </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
</ul>
*需要設定目錄同步處理。 只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。 不移轉直接在檔案共用裝置上管理的權限。 若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</td>
<td><ul>
<li> 擁有權歷程記錄與先前的版本 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 舊版 </li>
<li> Windows 檔案和資料夾屬性 (例如唯讀、隱藏) </li>
<li> 非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定： </li>
<li> 明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限) </li>
<li> NTFS 稽核組態 </li>
<li> 檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料 </li>
<li> 無法存取或損毀的文件 </li>
<li> 隱藏的共用 </li>
<li> 共用 (例如共用層級授與的權限) </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式) ，包括超過 10 MB 的檔案。 </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層次資料夾權限 </li>
<li> 群組層級資料夾權限 </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
<li> 共用的磁碟 (資料夾和檔案) </li>
<li> 正在移轉屬於 Google Drive 帳戶的共用內容 </li>
</ul></td>
<td><ul>
<li> 擁有權歷程記錄、先前的版本和註解 </li>
<li> 檔案與資料夾描述、資料夾顏色 </li>
<li> 使用者層次檔案權限 </li>
<li> 群組層級檔案權限 </li>
<li> 進階中繼資料 </li>
<li> 檔案鎖定屬性 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 丟到垃圾筒的項目 </li>
<li> 無法存取或損毀的文件 </li>
<li> 遭封鎖或非作用中的使用者 </li>
<li> Google 相簿、表單、地圖及其他連線的應用程式 </li>
<li> Google 繪圖 </li>
<li> 組織外部的共用內容 </li>
<li> 內容不是由移轉中的 Google 雲端硬碟帳戶所擁有 </li>
<li> 外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。 指示使用者在移轉之後，與外部使用者再次共用內容。） </li>
<li> 共用磁碟機成員權限（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。 指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。) </li>
<li> 標記為受限或未 copyable 的檔案 </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter、Business、Enterprise)</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> 文件 </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層次資料夾權限 </li>
<li> 群組層級資料夾權限 </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
<li> 正在移轉屬於 Box 帳戶的共用內容 </li>
<li> 方框附注 (轉換為 Word 檔案格式)  </li>
</ul></td>
<td><ul>
<li> 擁有權歷程記錄、先前的版本和註解 </li>
<li> 檔案與資料夾描述 </li>
<li> 使用者層次檔案權限 </li>
<li> 群組層級檔案權限 </li>
<li> Box 標記和進階中繼資料 </li>
<li> 檔案鎖定屬性 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 丟到垃圾筒的項目 </li>
<li> 無法存取或損毀的文件 </li>
<li> 遭封鎖或非作用中的使用者 </li>
<li> Box 應用程式、書籤、我的最愛及工作流程 </li>
<li> 不屬於已移轉的 Box 帳戶的內容 </li>
<li> 外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。 指示使用者在移轉之後，與外部使用者再次共用內容。） </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox for Teams (標準版和進階版)</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> 文件 </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層次資料夾權限 </li>
<li> 群組層級資料夾權限 </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
<li> 共用的小組資料夾和內容 </li>
<li> 正在移轉屬於 Dropbox 帳戶的共用內容 </li>
</ul></td>
<td><ul>
<li> 擁有權歷程記錄、先前的版本和註解 </li>
<li> 檔案與資料夾描述 </li>
<li> 使用者層次檔案權限 </li>
<li> 群組層級檔案權限 </li>
<li> 進階中繼資料 </li>
<li> 檔案鎖定屬性 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 丟到垃圾筒的項目 </li>
<li> 無法存取或損毀的文件 </li>
<li> 已卸載的 Dropbox 資料夾 </li>
<li> 已刪除或中斷連線的使用者 </li>
<li> Dropbox Paper、Showcases 和 Spaces </li>
<li> Dropbox 應用程式和我的最愛 (釘選/星號) </li>
<li> 不是由已移轉的 Dropbox 帳戶所擁有的內容 </li>
<li> 外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。 指示使用者在移轉之後，與外部使用者再次共用內容） </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a>SharePoint 線上遷移的 FastTrack 責任

我們的 FastTrack 專家在進行移轉專案時執行標準動作。 如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊

### <a name="your-responsibilities"></a>您的責任

由您在進行移轉專案時執行標準動作。 如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊

你也要執行下列 SharePoint Online 移轉動作特定的活動：

  - 使用您的移轉事件針對所有 SharePoint 小組網站進行佈建。

## <a name="migration-to-onedrive-for-business"></a>移轉至商務用 OneDrive

當您選擇使用 FastTrack 將您的檔案移轉到 商務用 OneDrive 時，我們會提供您移轉指引和資料移轉服務。 我們會提供指引以協助規劃您的移轉、設定您的來源環境和 商務用 OneDrive，並充分利用我們的資料移轉服務來移轉您的檔案。 您可以建立您的移轉事件並設定排程。 我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。 當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 商務用 OneDrive。

### <a name="considerations"></a>考量

  - 所有的移轉動作都受到 SharePoint Online 的配額限制。 如需詳細資訊，請參閱<a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint 限制</a>。 
  - 我們建議您將移轉的資料總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。
  - FastTrack 只會移轉到使用中的 [商務用 OneDrive] 磁碟機。

### <a name="source-environment-details"></a>來源環境詳細資料

我們的資料移轉服務可將資料從這些來源環境移轉出來：

  - 檔案共用 (支援 SMB 2.0+ 之裝置的 SMB 檔案共用)。
  - 單一 G Suite 環境 (僅限 Google 雲端硬碟)。
  - Box (Starter、Business、Enterprise)。
  - Dropbox for Teams (標準版和進階版)。

下列表格顯示每個來源環境特定的移轉詳細資料：

<table>
<thead>
<tr class="header">
 <th><strong>來源環境</strong></th>
 <th><strong>移轉類型</strong></th>
 <th><strong>可以移轉那些內容</strong></th>
 <th><strong>不能移轉什麼內容</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> 文件 </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層級檔案和資料夾權限* </li>
<li> 群組層級檔案和資料夾權限* </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
</ul>
<br>
*需要設定目錄同步處理。 只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。 不移轉直接在檔案共用裝置上管理的權限。 若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。 </td>
<td><ul>
<li> 擁有權歷程記錄與先前的版本 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 舊版 </li>
<li> Windows 檔案和資料夾屬性 (例如唯讀、隱藏) </li>
<li> 非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定： </li>
<li> 明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限) </li>
<li> NTFS 稽核組態 </li>
<li> 檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料 </li>
<li> 無法存取或損毀的文件 </li>
<li> 隱藏的共用 </li>
<li> 共用 (例如共用層級授與的權限) </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式 ，包括超過 10 MB 的檔案) </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層次資料夾權限 </li>
<li> 群組層級資料夾權限 </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
<li> 共用的磁碟 (資料夾和檔案) </li>
<li> 正在移轉屬於 Google Drive 帳戶的共用內容 </li>
</ul></td>
<td><ul>
<li> 擁有權歷程記錄、先前的版本和註解 </li>
<li> 檔案與資料夾描述、資料夾顏色 </li>
<li> 使用者層次檔案權限 </li>
<li> 群組層級檔案權限 </li>
<li> 進階中繼資料 </li>
<li> 檔案鎖定屬性 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 丟到垃圾筒的項目 </li>
<li> 無法存取或損毀的文件 </li>
<li> 遭封鎖或非作用中的使用者 </li>
<li> Google 相簿表單、地圖及其他連線的應用程式 </li>
<li> Google 繪圖 </li>
<li> 組織外部的共用內容 </li>
<li> 內容不是由移轉中的 Google 雲端硬碟帳戶所擁有 </li>
<li> 外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。 指示使用者在移轉之後，與外部使用者再次共用內容。） </li>
<li> 共用磁碟機成員資格權限 (<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。 指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。) </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter、Business、Enterprise)</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> 文件 </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層次資料夾權限 </li>
<li> 群組層級資料夾權限 </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
<li> 正在移轉屬於 Box 帳戶的共用內容 </li>
</ul></td>
<td><ul>
<li> 擁有權歷程記錄、先前的版本和註解 </li>
<li> 檔案與資料夾描述 </li>
<li> 使用者層次檔案權限 </li>
<li> 群組層級檔案權限 </li>
<li> Box 標記和進階中繼資料 </li>
<li> 檔案鎖定屬性 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 丟到垃圾筒的項目 </li>
<li> 無法存取或損毀的文件 </li>
<li> 遭封鎖或非作用中的使用者 </li>
<li> Box 應用程式、書籤、我的最愛及工作流程 </li>
<li> 不屬於已移轉的 Box 帳戶的內容 </li>
<li> 外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。 指示使用者在移轉之後，與外部使用者再次共用內容。） </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox for Teams (標準版和進階版)</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> 文件 </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層次資料夾權限 </li>
<li> 群組層級資料夾權限 </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
<li> 共用的小組資料夾和內容 </li>
<li> 正在移轉屬於 Dropbox 帳戶的共用內容 </li>
</ul></td>
<td><ul>
<li> 擁有權歷程記錄、先前的版本和註解 </li>
<li> 檔案與資料夾描述 </li>
<li> 使用者層次檔案權限 </li>
<li> 群組層級檔案權限 </li>
<li> 進階中繼資料 </li>
<li> 檔案鎖定屬性 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 丟到垃圾筒的項目 </li>
<li> 無法存取或損毀的文件 </li>
<li> 已卸載的 Dropbox 資料夾 </li>
<li> 已刪除或中斷連線的使用者 </li>
<li> Dropbox Paper、Showcases 和 Spaces </li>
<li> Dropbox 應用程式和我的最愛 (釘選/星號) </li>
<li> 不是由已移轉的 Dropbox 帳戶所擁有的內容 </li>
<li> 外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。 指示使用者在移轉之後，與外部使用者再次共用內容。） </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a>商務用 OneDrive 遷移的 FastTrack 責任

我們的 FastTrack 專家在進行移轉專案時執行標準動作。 如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。

### <a name="your-responsibilities"></a>您的責任

由您在進行移轉專案時執行標準動作。 如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。

你也要執行下列 [商務用 OneDrive] 移轉動作特定的活動：

  - 使用您的移轉事件針對所有 [商務用 OneDrive] 網站進行佈建。

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a>遷移至 Microsoft Teams 和 Microsoft 365 群組

當您選擇使用 FastTrack 將檔案遷移至 Microsoft Teams 和 Microsoft 365 群組時，我們會提供遷移指南和資料移轉服務。 我們提供指引，協助您規劃遷移、設定來源環境及 Teams 和 Microsoft 365 群組，以及利用我們的資料移轉服務來遷移您的檔案。 您可以建立您的移轉事件並設定排程。 我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。 當您的遷移事件完成時，您可以期望來源環境中適當排程與合格來源環境的檔案已遷移至 Teams 和 Microsoft 365 群組。 Teams 通道和 Microsoft 365 群組必須先由客戶預先布建，使用者才能將資料移轉至這些目的地類型。 Teams 和 Microsoft 365 群組會影響您對檔案目的地位置的許可權。 Teams 和 Microsoft 365 群組是為允許共同作業而建立的。 在遷移至那些目的地時，Teams 通道或 Microsoft 365 群組決定誰可以存取這些檔案。 FastTrack 在遷移期間，不會將使用者或群組新增至任何 Teams 通道或 Microsoft 365 群組的許可權。

### <a name="considerations"></a>考量

- 所有的移轉動作都受到 SharePoint Online 的配額限制。 如需詳細資訊，請參閱<a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint 限制</a>。 
- 我們建議您將移轉的總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。 


### <a name="source-environment-details"></a>來源環境詳細資料

我們的資料移轉服務可將資料從這些來源環境移轉出來： 

- 檔案共用 (支援 SMB 2.0+ 裝置的伺服器訊息區 (SMB) 檔案共用)。
-  單一 G Suite 環境 (僅限 Google 雲端硬碟)。 
- Box (Starter、Business、Enterprise)。 
- Dropbox for Teams (標準版和進階版)。 

下列表格顯示每個來源環境特定的移轉詳細資料：

<table>
<thead>
<tr class="header">
 <th><strong>來源環境</strong></th>
 <th><strong>移轉類型</strong></th>
 <th><strong>可以移轉那些內容</strong></th>
 <th><strong>不能移轉什麼內容</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> 文件 </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層級檔案和資料夾權限* </li>
<li> 群組層級檔案和資料夾權限* </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
</ul>
<br>
*需要設定目錄同步處理。 只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。 不移轉直接在檔案共用裝置上管理的權限。 若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。 Microsoft 365 群組和/或 Microsoft Teams 通道會影響許可權。 若目的地為 Microsoft 365 群組或 Microsoft Teams 通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。 建議您不要在遷移至 Microsoft 365 群組或 Microsoft Teams 通道的檔案上遷移許可權。</td>
<td><ul>
<li> 擁有權歷程記錄與先前的版本 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 舊版 </li>
<li> Windows 檔案和資料夾屬性 (例如唯讀、隱藏) </li>
<li> 非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定： </li>
<li> 明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限) </li>
<li> NTFS 稽核組態 </li>
<li> 檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料 </li>
<li> 無法存取或損毀的文件 </li>
<li> 隱藏的共用 </li>
<li> 共用 (例如共用層級授與的權限) </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式 ，包括超過 10 MB 的檔案) </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層級資料夾許可權 * </li>
<li> 群組層級資料夾許可權 * </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
<li> 共用的磁碟 (資料夾和檔案) </li>
<li> 正在移轉屬於 Google Drive 帳戶的共用內容 </li>
</ul>
<br>
* 許可權受到 Microsoft 365 群組和/或 Microsoft Teams 通道影響。 若目的地為 Microsoft 365 群組或 Microsoft Teams 通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。 建議您不要在遷移至 Microsoft 365 群組或 Microsoft Teams 通道的檔案上遷移許可權。 
</td>
<td><ul>
<li> 擁有權歷程記錄、先前的版本和註解 </li>
<li> 檔案與資料夾描述、資料夾顏色 </li>
<li> 使用者層次檔案權限 </li>
<li> 群組層級檔案權限 </li>
<li> 進階中繼資料 </li>
<li> 檔案鎖定屬性 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 丟到垃圾筒的項目 </li>
<li> 無法存取或損毀的文件 </li>
<li> 遭封鎖或非作用中的使用者 </li>
<li> Google 相簿表單、地圖及其他連線的應用程式 </li>
<li> Google 繪圖 </li>
<li> 組織外部的共用內容 </li>
<li> 內容不是由移轉中的 Google 雲端硬碟帳戶所擁有 </li>
<li> 外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。 指示使用者在移轉之後，與外部使用者再次共用內容。） </li>
<li> 共用磁碟機成員資格權限 (<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。 指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。) </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter、Business、Enterprise)</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> 文件 </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層級資料夾許可權 * </li>
<li> 群組層級資料夾許可權 * </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
<li> 正在移轉屬於 Box 帳戶的共用內容 </li>
<li> 方框附注 (轉換為 Word 檔案格式)  </li>
</ul>
<br>
* 許可權受到 Microsoft 365 群組和/或 Microsoft Teams 通道影響。 若目的地為 Microsoft 365 群組或 Microsoft Teams 通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。 建議您不要在遷移至 Microsoft 365 群組或 Microsoft Teams 通道的檔案上遷移許可權。 </td>
<td><ul>
<li> 擁有權歷程記錄、先前的版本和註解 </li>
<li> 檔案與資料夾描述 </li>
<li> 使用者層次檔案權限 </li>
<li> 群組層級檔案權限 </li>
<li> Box 標記和進階中繼資料 </li>
<li> 檔案鎖定屬性 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 丟到垃圾筒的項目 </li>
<li> 無法存取或損毀的文件 </li>
<li> 遭封鎖或非作用中的使用者 </li>
<li> Box 應用程式、書籤、我的最愛及工作流程 </li>
<li> 不屬於已移轉的 Box 帳戶的內容 </li>
<li> 外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。 指示使用者在移轉之後，與外部使用者再次共用內容。） </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox for Teams (標準版和進階版)</strong></td>
<td>單一或多個階段</td>
<td><ul>
<li> 文件 </li>
<li> 檔案與資料夾結構 </li>
<li> 使用者層級資料夾許可權 * </li>
<li> 群組層級資料夾許可權 * </li>
<li> 小於 15 GB 的檔案 </li>
<li> 基本文件與資料夾的中繼資料：
<ul>
<li> 建立日期 </li>
<li> 修改日期 </li>
<li> 建立者 </li>
<li> 上次修改者 </li>
</ul></li>
<li> 共用的小組資料夾和內容 </li>
<li> 正在移轉屬於 Dropbox 帳戶的共用內容 </li>
</ul>
<br>
* 許可權受到 Microsoft 365 群組和/或 Microsoft Teams 通道影響。 若目的地為 Microsoft 365 群組或 Microsoft Teams 通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。 建議您不要在遷移至 Microsoft 365 群組或 Microsoft Teams 通道的檔案上遷移許可權。
</td>
<td><ul>
<li> 擁有權歷程記錄、先前的版本和註解 </li>
<li> 檔案與資料夾描述 </li>
<li> 使用者層次檔案權限 </li>
<li> 群組層級檔案權限 </li>
<li> 進階中繼資料 </li>
<li> 檔案鎖定屬性 </li>
<li> 內容中的內嵌 URL 轉換 </li>
<li> 丟到垃圾筒的項目 </li>
<li> 無法存取或損毀的文件 </li>
<li> 已卸載的 Dropbox 資料夾 </li>
<li> 已刪除或中斷連線的使用者 </li>
<li> Dropbox Paper、Showcases 和 Spaces </li>
<li> Dropbox 應用程式和我的最愛 (釘選/星號) </li>
<li> 不是由已移轉的 Dropbox 帳戶所擁有的內容 </li>
<li> 外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。 指示使用者在移轉之後，與外部使用者再次共用內容。） </li>
<li> 檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a>FastTrack Microsoft Teams 和 Microsoft 365 群組遷移的責任

我們的 FastTrack 專家在進行移轉專案時執行標準動作。 如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。

### <a name="your-responsibilities"></a>您的責任 

由您在進行移轉專案時執行標準動作。 如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。
您也可以針對 Microsoft Teams 和 Microsoft 365 群組遷移執行下列活動： 

- 將所有 Microsoft Teams 通道和 Microsoft 365 群組布建為遷移事件的目標。

> [!NOTE]
>FastTrack 未預先布建 Microsoft Teams 通道或 Microsoft 365 群組。 FastTrack 不會將使用者或群組新增至 Microsoft Teams 通道或 Microsoft 365 群組。 您必須先將使用者或群組新增至所有 Microsoft Teams 通道和 Microsoft 365 群組，再將資料移轉至這些目的地，這樣使用者才能存取這些新遷移的檔。