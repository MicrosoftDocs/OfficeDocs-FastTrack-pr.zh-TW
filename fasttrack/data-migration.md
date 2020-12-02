---
title: 資料移轉
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 12/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。 我們可以提供的協助類型取決於您的 Office 365 授權數量。
ms.openlocfilehash: 5a64bcbecffa3fd78f54b9a5e0f3f07e76d0b316
ms.sourcegitcommit: d69d3e1e478a817f8279e9da98880499e9302665
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 12/01/2020
ms.locfileid: "49525334"
---
# <a name="data-migration"></a><span data-ttu-id="8bc17-104">資料移轉</span><span class="sxs-lookup"><span data-stu-id="8bc17-104">Data Migration</span></span>

<span data-ttu-id="8bc17-105">FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。</span><span class="sxs-lookup"><span data-stu-id="8bc17-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="8bc17-106">我們提供的協助類型取決於您的 Office 365 授權數量：</span><span class="sxs-lookup"><span data-stu-id="8bc17-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="8bc17-107">**針對有 150-499 個授權的 Microsoft Office 365 租用戶**：FastTrack 僅提供移轉指引；由您負責執行資料移轉。</span><span class="sxs-lookup"><span data-stu-id="8bc17-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="8bc17-108">我們會透過可協助您規劃及使用免費工具的文件，引導您執行自助移轉。</span><span class="sxs-lookup"><span data-stu-id="8bc17-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="8bc17-109">**針對具有 500 個或更多授權數量的 Microsoft Office 365 租用戶**：FastTrack 會提供移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8bc17-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="8bc17-110">我們會提供指引以協助規劃您的移轉事件、設定您的來源環境和 Office 365 租用戶，並充分利用我們的資料移轉服務來移轉您的資料。</span><span class="sxs-lookup"><span data-stu-id="8bc17-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="8bc17-111">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="8bc17-111">You create and schedule your migration events.</span></span> <span data-ttu-id="8bc17-112">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="8bc17-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="8bc17-113">如果您在 9/1/2017 之前已購買或續約ㄧ個商業方案，您只需使用 150 個授權，就能獲得資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="8bc17-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="8bc17-114">針對教育方案，只有您的付費教職員授權符合使用資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="8bc17-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="8bc17-115">考量</span><span class="sxs-lookup"><span data-stu-id="8bc17-115">Considerations</span></span>

  - <span data-ttu-id="8bc17-116">您的來源環境必須符合特定期望條件，才能將資料移轉至 Microsoft Office 365。</span><span class="sxs-lookup"><span data-stu-id="8bc17-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="8bc17-117">如需其它與 Exchange、SharePoint、和 [商務用 OneDrive] 適用的來源環境期望，請參照 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="8bc17-118">為提供資料移轉服務，我們需要您的來源環境及 Office 365 租用戶的適當存取權和權限。</span><span class="sxs-lookup"><span data-stu-id="8bc17-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="8bc17-119">我們的資料移轉服務既不是以受特殊法律、也不是受監管要求而設計或使用的。</span><span class="sxs-lookup"><span data-stu-id="8bc17-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="8bc17-120">當我們移轉您的資料時，可以將資料在任何我們進行設施維護的地方進行移轉、儲存及處理的動作（除非您的 FastTrack 移轉專案有提供另外的位置）。</span><span class="sxs-lookup"><span data-stu-id="8bc17-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="8bc17-121">我們不能保證郵件或檔案移轉的速度。</span><span class="sxs-lookup"><span data-stu-id="8bc17-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="8bc17-122">無法預料的問題（例如在來源環境中有無法讀取或已損毀的項目）可能會使我們無法移轉您的某些資料項目。</span><span class="sxs-lookup"><span data-stu-id="8bc17-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="8bc17-123">在我們控制範圍之外的外部因素（像是第三方應用程式開發介面 (APIs) 出現變更）會導致我們的資料移轉服務出現變更、延遲、或暫停的情況。</span><span class="sxs-lookup"><span data-stu-id="8bc17-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="8bc17-124">移轉服務的狀態</span><span class="sxs-lookup"><span data-stu-id="8bc17-124">Migration service availability</span></span>

  - <span data-ttu-id="8bc17-125">**針對商業及英國政府客戶：** 我們提供每天 24 小時、每周 7 天（24x7）的全年無休資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8bc17-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="8bc17-126">**針對美國政府/DOD 客戶：** 我們提供每天 24 小時、每周 5 個工作天（24x5）的資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8bc17-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="8bc17-127">移轉至 Exchange Online</span><span class="sxs-lookup"><span data-stu-id="8bc17-127">Migration to Exchange Online</span></span>

<span data-ttu-id="8bc17-128">當您選擇使用 FastTrack 將您的電子郵件移轉到 Exchange Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8bc17-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8bc17-129">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 Exchange Online，並充分利用我們的資料移轉服務來移轉您的信箱。</span><span class="sxs-lookup"><span data-stu-id="8bc17-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="8bc17-130">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="8bc17-130">You create and schedule your migration events.</span></span> <span data-ttu-id="8bc17-131">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="8bc17-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8bc17-132">當您的移轉事件完成後，您可以預期在您的來源環境中，郵件經適當排程和從合格來源信箱移轉到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="8bc17-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="8bc17-133">考量</span><span class="sxs-lookup"><span data-stu-id="8bc17-133">Considerations</span></span>

  - <span data-ttu-id="8bc17-134">在進行移轉之前，您必須完成適用於 Exchange Online 的 FastTrack 核心上線動作；</span><span class="sxs-lookup"><span data-stu-id="8bc17-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="8bc17-135">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="8bc17-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8bc17-136">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="8bc17-137">FastTrack 只會移轉至使用中的 Office 365 信箱。</span><span class="sxs-lookup"><span data-stu-id="8bc17-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="8bc17-138">如果您想要從內部部署的 Exchange 環境將資料移轉出來，您必須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="8bc17-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8bc17-139">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="8bc17-140">每個來源環境都必須為其中各自相應的產品使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="8bc17-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="8bc17-141">存在於內部部署 Active Directory Domain Services 中的通訊群組清單（*MailEnabledGroup* 物件）和外部連絡人（*MailEnabledContact* 物件）並不屬於信箱資料移轉的一部分。</span><span class="sxs-lookup"><span data-stu-id="8bc17-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="8bc17-142">不過，您可以使用 Microsoft Azure Active Directory (Azure AD) Connect 進行同步處理。</span><span class="sxs-lookup"><span data-stu-id="8bc17-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="8bc17-143">來源環境</span><span class="sxs-lookup"><span data-stu-id="8bc17-143">Source environments</span></span>

<span data-ttu-id="8bc17-144">我們的資料移轉服務會將資料從這些來源環境中移轉出來：</span><span class="sxs-lookup"><span data-stu-id="8bc17-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="8bc17-145">含有單一個或多個 Exchange 組織的單一或多個 Active Directory 樹系 (每ㄧ個 Exchange 郵件系統都必須使用 Exchange 2010 或更新的版本)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="8bc17-146">單一個具 IMAP 功能的電子郵件環境。</span><span class="sxs-lookup"><span data-stu-id="8bc17-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="8bc17-147">G Suite 環境 (僅限 Gmail、連絡人和Outlook 行事曆)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="8bc17-148">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="8bc17-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8bc17-149"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8bc17-150"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8bc17-151"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="8bc17-152"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8bc17-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="8bc17-154">
<strong>附注：</strong> 如需內部部署 Exchange 相依性，請參閱 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">混合部署必要條件</span></a>。</span><span class="sxs-lookup"><span data-stu-id="8bc17-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="8bc17-155">混合部署移轉</span><span class="sxs-lookup"><span data-stu-id="8bc17-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="8bc17-156">電子郵件</span><span class="sxs-lookup"><span data-stu-id="8bc17-156">Emails</span></span></li>
<li><span data-ttu-id="8bc17-157">信箱規則</span><span class="sxs-lookup"><span data-stu-id="8bc17-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="8bc17-158">委派</span><span class="sxs-lookup"><span data-stu-id="8bc17-158">Delegates</span></span></li>
<li><span data-ttu-id="8bc17-159">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="8bc17-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8bc17-160">行事曆</span><span class="sxs-lookup"><span data-stu-id="8bc17-160">Calendar</span></span> </li>
<li> <span data-ttu-id="8bc17-161">工作</span><span class="sxs-lookup"><span data-stu-id="8bc17-161">Tasks</span></span> </li>
<li> <span data-ttu-id="8bc17-162">受版權管理的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8bc17-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="8bc17-163">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8bc17-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="8bc17-164">簽章</span><span class="sxs-lookup"><span data-stu-id="8bc17-164">Signatures</span></span> </li>
<li> <span data-ttu-id="8bc17-165">隨著使用者信箱移轉的個人封存</span><span class="sxs-lookup"><span data-stu-id="8bc17-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="8bc17-166">可復原的項目</span><span class="sxs-lookup"><span data-stu-id="8bc17-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8bc17-167">公用資料夾</span><span class="sxs-lookup"><span data-stu-id="8bc17-167">Public folders</span></span> </li>
<li> <span data-ttu-id="8bc17-168">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8bc17-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8bc17-169">日誌封存或任何協力廠商封存解決方案</span><span class="sxs-lookup"><span data-stu-id="8bc17-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="8bc17-170">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8bc17-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8bc17-171">從個人存放區資料表 (PST) 檔案封存的資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="8bc17-172">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="8bc17-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8bc17-173">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="8bc17-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bc17-174"><strong>G Suite 環境 (僅限 Gmail、連絡人和行事曆)</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="8bc17-175">
<strong>附注：</strong> 您的 G 套件環境必須符合 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">執行 G Suite 遷移</a>中所述的必要條件。</span><span class="sxs-lookup"><span data-stu-id="8bc17-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="8bc17-176">轉換或分段</span><span class="sxs-lookup"><span data-stu-id="8bc17-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="8bc17-177">電子郵件</span><span class="sxs-lookup"><span data-stu-id="8bc17-177">Emails</span></span> </li>
<li> <span data-ttu-id="8bc17-178">信箱連絡人 (每個連絡人最多可移轉 3 個電子郵件地址)</span><span class="sxs-lookup"><span data-stu-id="8bc17-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="8bc17-179">行事曆</span><span class="sxs-lookup"><span data-stu-id="8bc17-179">Calendar</span></span> </li>
<li> <span data-ttu-id="8bc17-180">標籤</span><span class="sxs-lookup"><span data-stu-id="8bc17-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8bc17-181">規則</span><span class="sxs-lookup"><span data-stu-id="8bc17-181">Rules</span></span> </li>
<li> <span data-ttu-id="8bc17-182">委派</span><span class="sxs-lookup"><span data-stu-id="8bc17-182">Delegates</span></span> </li>
<li> <span data-ttu-id="8bc17-183">簽章</span><span class="sxs-lookup"><span data-stu-id="8bc17-183">Signatures</span></span> </li>
<li> <span data-ttu-id="8bc17-184">工作</span><span class="sxs-lookup"><span data-stu-id="8bc17-184">Tasks</span></span> </li>
<li> <span data-ttu-id="8bc17-185">任何超過郵件大小限制的電子郵件或附件</span><span class="sxs-lookup"><span data-stu-id="8bc17-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8bc17-186">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8bc17-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8bc17-187">從 PST 檔案或任何協力廠商封存解決方案 (例如 Google Vault) 封存的資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="8bc17-188">權限管理或加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8bc17-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="8bc17-189">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="8bc17-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8bc17-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="8bc17-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="8bc17-191">Google Groups</span><span class="sxs-lookup"><span data-stu-id="8bc17-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="8bc17-192">資源信箱</span><span class="sxs-lookup"><span data-stu-id="8bc17-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="8bc17-193">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="8bc17-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="8bc17-194">假期設定和自動回覆設定</span><span class="sxs-lookup"><span data-stu-id="8bc17-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="8bc17-195">共用行事曆、雲端附件、Google Hangout 連結和活動色彩</span><span class="sxs-lookup"><span data-stu-id="8bc17-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="8bc17-196">\*\*可移轉儲存為標籤的 Hangout 交談。</span><span class="sxs-lookup"><span data-stu-id="8bc17-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bc17-197"><strong>IMAP4 來源 (例如 Domino、GroupWise 和 Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="8bc17-198">使用原生 IMAP4 工具進行的移轉</span><span class="sxs-lookup"><span data-stu-id="8bc17-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="8bc17-199">電子郵件</span><span class="sxs-lookup"><span data-stu-id="8bc17-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="8bc17-200">規則</span><span class="sxs-lookup"><span data-stu-id="8bc17-200">Rules</span></span> </li>
<li> <span data-ttu-id="8bc17-201">委派</span><span class="sxs-lookup"><span data-stu-id="8bc17-201">Delegates</span></span> </li>
<li> <span data-ttu-id="8bc17-202">通訊群組清單</span><span class="sxs-lookup"><span data-stu-id="8bc17-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="8bc17-203">外部連絡人</span><span class="sxs-lookup"><span data-stu-id="8bc17-203">External contacts</span></span> </li>
<li> <span data-ttu-id="8bc17-204">擁有郵件功能的使用者</span><span class="sxs-lookup"><span data-stu-id="8bc17-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="8bc17-205">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8bc17-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8bc17-206">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="8bc17-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8bc17-207">行事曆</span><span class="sxs-lookup"><span data-stu-id="8bc17-207">Calendar</span></span> </li>
<li> <span data-ttu-id="8bc17-208">簽章</span><span class="sxs-lookup"><span data-stu-id="8bc17-208">Signatures</span></span> </li>
<li> <span data-ttu-id="8bc17-209">工作</span><span class="sxs-lookup"><span data-stu-id="8bc17-209">Tasks</span></span> </li>
<li> <span data-ttu-id="8bc17-210">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8bc17-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8bc17-211">封存資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-211">Archive data</span></span> </li>
<li> <span data-ttu-id="8bc17-212">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8bc17-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="8bc17-213">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="8bc17-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8bc17-214">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="8bc17-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8bc17-215">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="8bc17-215">FastTrack responsibilities</span></span>

<span data-ttu-id="8bc17-216">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8bc17-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8bc17-217">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="8bc17-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8bc17-218">我們的 FastTrack 專家也會執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="8bc17-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="8bc17-219">可提供指引，以便協助您啟用在來源環境與 Exchange Online 之間並立的 SMTP 郵件路由傳送（如果適用的話）。</span><span class="sxs-lookup"><span data-stu-id="8bc17-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8bc17-220">您的責任</span><span class="sxs-lookup"><span data-stu-id="8bc17-220">Your responsibilities</span></span>

<span data-ttu-id="8bc17-221">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8bc17-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8bc17-222">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="8bc17-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8bc17-223">你也要執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="8bc17-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="8bc17-224">完成適用於 Exchange Online 的 FastTrack 核心上線動作。</span><span class="sxs-lookup"><span data-stu-id="8bc17-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="8bc17-225">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="8bc17-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8bc17-226">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="8bc17-227">依 Office 365 指引安裝適當層級的用戶端軟體。</span><span class="sxs-lookup"><span data-stu-id="8bc17-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="8bc17-228">如需詳細資訊，請參閱 [現代化工作場所](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="8bc17-229">如果您想要從內部部署的 Exchange 環境將資料移轉出來，須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="8bc17-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8bc17-230">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="8bc17-231">如果適用的話，每個來源環境都必須使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="8bc17-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="8bc17-232">若適用的話，在您的來源環境和 Exchange Online 中，設定和驗證 SMTP 郵件路由傳送共存。</span><span class="sxs-lookup"><span data-stu-id="8bc17-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="8bc17-233">請確定您的來源信箱容量大小未超過目標信箱配額。</span><span class="sxs-lookup"><span data-stu-id="8bc17-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="8bc17-234">視來源平台而定，您可能需要對來源資料限制在目標信箱配額的 85%。</span><span class="sxs-lookup"><span data-stu-id="8bc17-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="8bc17-235">視需要移轉用戶端資料。</span><span class="sxs-lookup"><span data-stu-id="8bc17-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="8bc17-236">這包含、但不限於本機通訊錄、本機 PST 檔案中的資料、Outlook 規則和本機 Outlook 設定。</span><span class="sxs-lookup"><span data-stu-id="8bc17-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="8bc17-237">協助使用者修正用戶端的遷移問題。</span><span class="sxs-lookup"><span data-stu-id="8bc17-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="8bc17-238">移轉至 SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="8bc17-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="8bc17-239">當您選擇使用 FastTrack 將您的檔案移轉到 SharePoint Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8bc17-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8bc17-240">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 SharePoint Online，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="8bc17-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8bc17-241">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="8bc17-241">You create and schedule your migration events.</span></span> <span data-ttu-id="8bc17-242">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="8bc17-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8bc17-243">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 SharePoint Online。</span><span class="sxs-lookup"><span data-stu-id="8bc17-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="8bc17-244">考量</span><span class="sxs-lookup"><span data-stu-id="8bc17-244">Considerations</span></span>

  - <span data-ttu-id="8bc17-245">所有的移轉動作都受到 SharePoint Online 的配額限制。</span><span class="sxs-lookup"><span data-stu-id="8bc17-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="8bc17-246">如需詳細資訊，可參照 [<span class="underline">SharePoint Online 和 [商務用 OneDrive]：軟體使用範圍及限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="8bc17-247">我們建議您將移轉的總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="8bc17-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8bc17-248">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-248">Source environment details</span></span>

<span data-ttu-id="8bc17-249">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="8bc17-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8bc17-250">檔案共用 (支援 SMB 2.0+ 裝置的伺服器訊息區 (SMB) 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8bc17-251">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8bc17-252">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8bc17-253">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8bc17-254">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="8bc17-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8bc17-255"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8bc17-256"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8bc17-257"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8bc17-258"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8bc17-259"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8bc17-260">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8bc17-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8bc17-261">文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-261">Documents</span></span> </li>
<li> <span data-ttu-id="8bc17-262">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8bc17-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8bc17-263">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="8bc17-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8bc17-264">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="8bc17-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8bc17-265">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8bc17-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8bc17-266">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8bc17-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8bc17-267">建立日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-267">Created date</span></span> </li>
<li> <span data-ttu-id="8bc17-268">修改日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-268">Modified date</span></span> </li>
<li> <span data-ttu-id="8bc17-269">建立者</span><span class="sxs-lookup"><span data-stu-id="8bc17-269">Created by</span></span> </li>
<li> <span data-ttu-id="8bc17-270">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8bc17-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="8bc17-271">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="8bc17-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8bc17-272">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="8bc17-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8bc17-273">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="8bc17-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8bc17-274">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="8bc17-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="8bc17-275">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="8bc17-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8bc17-276">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8bc17-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8bc17-277">舊版</span><span class="sxs-lookup"><span data-stu-id="8bc17-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="8bc17-278">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="8bc17-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8bc17-279">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="8bc17-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8bc17-280">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="8bc17-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8bc17-281">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="8bc17-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8bc17-282">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8bc17-283">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8bc17-284">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="8bc17-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8bc17-285">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="8bc17-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8bc17-286">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8bc17-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bc17-287"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8bc17-288">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8bc17-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8bc17-289">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式) ，包括超過 10 MB 的檔案。</span><span class="sxs-lookup"><span data-stu-id="8bc17-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="8bc17-290">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8bc17-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8bc17-291">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-292">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-293">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8bc17-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8bc17-294">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8bc17-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8bc17-295">建立日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-295">Created date</span></span> </li>
<li> <span data-ttu-id="8bc17-296">修改日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-296">Modified date</span></span> </li>
<li> <span data-ttu-id="8bc17-297">建立者</span><span class="sxs-lookup"><span data-stu-id="8bc17-297">Created by</span></span> </li>
<li> <span data-ttu-id="8bc17-298">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8bc17-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8bc17-299">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="8bc17-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8bc17-300">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8bc17-301">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8bc17-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8bc17-302">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="8bc17-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8bc17-303">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-304">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-305">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8bc17-306">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8bc17-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8bc17-307">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8bc17-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8bc17-308">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8bc17-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="8bc17-309">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8bc17-310">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8bc17-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8bc17-311">Google 相簿、表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="8bc17-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8bc17-312">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="8bc17-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8bc17-313">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8bc17-314">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="8bc17-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8bc17-315">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8bc17-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8bc17-316">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8bc17-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8bc17-317">共用磁碟機成員權限（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="8bc17-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8bc17-318">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="8bc17-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8bc17-319">標記為受限或未 copyable 的檔案</span><span class="sxs-lookup"><span data-stu-id="8bc17-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="8bc17-320">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8bc17-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bc17-321"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8bc17-322">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8bc17-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8bc17-323">文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-323">Documents</span></span> </li>
<li> <span data-ttu-id="8bc17-324">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8bc17-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8bc17-325">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-326">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-327">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8bc17-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8bc17-328">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8bc17-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8bc17-329">建立日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-329">Created date</span></span> </li>
<li> <span data-ttu-id="8bc17-330">修改日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-330">Modified date</span></span> </li>
<li> <span data-ttu-id="8bc17-331">建立者</span><span class="sxs-lookup"><span data-stu-id="8bc17-331">Created by</span></span> </li>
<li> <span data-ttu-id="8bc17-332">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8bc17-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8bc17-333">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="8bc17-334">方框附注 (轉換為 Word 檔案格式) </span><span class="sxs-lookup"><span data-stu-id="8bc17-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8bc17-335">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8bc17-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8bc17-336">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="8bc17-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8bc17-337">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-338">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-339">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8bc17-340">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8bc17-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8bc17-341">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8bc17-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8bc17-342">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8bc17-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="8bc17-343">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8bc17-344">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8bc17-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8bc17-345">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="8bc17-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8bc17-346">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8bc17-347">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8bc17-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8bc17-348">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8bc17-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8bc17-349">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8bc17-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bc17-350"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8bc17-351">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8bc17-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8bc17-352">文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-352">Documents</span></span> </li>
<li> <span data-ttu-id="8bc17-353">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8bc17-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8bc17-354">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-355">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-356">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8bc17-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8bc17-357">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8bc17-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8bc17-358">建立日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-358">Created date</span></span> </li>
<li> <span data-ttu-id="8bc17-359">修改日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-359">Modified date</span></span> </li>
<li> <span data-ttu-id="8bc17-360">建立者</span><span class="sxs-lookup"><span data-stu-id="8bc17-360">Created by</span></span> </li>
<li> <span data-ttu-id="8bc17-361">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8bc17-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8bc17-362">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8bc17-363">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8bc17-364">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8bc17-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8bc17-365">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="8bc17-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8bc17-366">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-367">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-368">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8bc17-369">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8bc17-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8bc17-370">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8bc17-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8bc17-371">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8bc17-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="8bc17-372">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8bc17-373">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="8bc17-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8bc17-374">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="8bc17-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8bc17-375">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="8bc17-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8bc17-376">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="8bc17-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8bc17-377">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8bc17-378">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8bc17-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8bc17-379">指示使用者在移轉之後，與外部使用者再次共用內容）</span><span class="sxs-lookup"><span data-stu-id="8bc17-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="8bc17-380">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8bc17-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8bc17-381">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="8bc17-381">FastTrack responsibilities</span></span>

<span data-ttu-id="8bc17-382">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8bc17-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8bc17-383">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="8bc17-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8bc17-384">您的責任</span><span class="sxs-lookup"><span data-stu-id="8bc17-384">Your responsibilities</span></span>

<span data-ttu-id="8bc17-385">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8bc17-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8bc17-386">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="8bc17-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="8bc17-387">你也要執行下列 SharePoint Online 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="8bc17-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="8bc17-388">使用您的移轉事件針對所有 SharePoint 小組網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="8bc17-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="8bc17-389">移轉至商務用 OneDrive</span><span class="sxs-lookup"><span data-stu-id="8bc17-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="8bc17-390">當您選擇使用 FastTrack 將您的檔案移轉到 商務用 OneDrive 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8bc17-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8bc17-391">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 商務用 OneDrive，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="8bc17-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8bc17-392">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="8bc17-392">You create and schedule your migration events.</span></span> <span data-ttu-id="8bc17-393">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="8bc17-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8bc17-394">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 商務用 OneDrive。</span><span class="sxs-lookup"><span data-stu-id="8bc17-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="8bc17-395">考量</span><span class="sxs-lookup"><span data-stu-id="8bc17-395">Considerations</span></span>

  - <span data-ttu-id="8bc17-396">所有的移轉事件都受 [商務用 OneDrive] 配額的限制。</span><span class="sxs-lookup"><span data-stu-id="8bc17-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="8bc17-397">如需詳細資訊，請參照 [<span class="underline">SharePoint Online 和 [商務用 OneDrive]：軟體使用範圍及限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="8bc17-398">我們建議您將移轉的資料總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="8bc17-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="8bc17-399">FastTrack 只會移轉到使用中的 [商務用 OneDrive] 磁碟機。</span><span class="sxs-lookup"><span data-stu-id="8bc17-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8bc17-400">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-400">Source environment details</span></span>

<span data-ttu-id="8bc17-401">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="8bc17-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8bc17-402">檔案共用 (支援 SMB 2.0+ 之裝置的 SMB 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8bc17-403">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8bc17-404">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8bc17-405">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="8bc17-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8bc17-406">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="8bc17-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="8bc17-407"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="8bc17-408"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="8bc17-409"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8bc17-410"><strong>不能移轉什麼內容</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8bc17-411"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8bc17-412">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8bc17-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8bc17-413">文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-413">Documents</span></span> </li>
<li> <span data-ttu-id="8bc17-414">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8bc17-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8bc17-415">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="8bc17-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8bc17-416">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="8bc17-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8bc17-417">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8bc17-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8bc17-418">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8bc17-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8bc17-419">建立日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-419">Created date</span></span> </li>
<li> <span data-ttu-id="8bc17-420">修改日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-420">Modified date</span></span> </li>
<li> <span data-ttu-id="8bc17-421">建立者</span><span class="sxs-lookup"><span data-stu-id="8bc17-421">Created by</span></span> </li>
<li> <span data-ttu-id="8bc17-422">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8bc17-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="8bc17-423">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="8bc17-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8bc17-424">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="8bc17-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8bc17-425">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="8bc17-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8bc17-426">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="8bc17-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="8bc17-427">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="8bc17-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8bc17-428">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8bc17-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8bc17-429">舊版</span><span class="sxs-lookup"><span data-stu-id="8bc17-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="8bc17-430">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="8bc17-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8bc17-431">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="8bc17-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8bc17-432">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="8bc17-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8bc17-433">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="8bc17-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8bc17-434">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8bc17-435">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8bc17-436">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="8bc17-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8bc17-437">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="8bc17-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8bc17-438">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8bc17-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bc17-439"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8bc17-440">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8bc17-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8bc17-441">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式 ，包括超過 10 MB 的檔案)</span><span class="sxs-lookup"><span data-stu-id="8bc17-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="8bc17-442">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8bc17-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8bc17-443">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-444">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-445">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8bc17-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8bc17-446">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8bc17-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8bc17-447">建立日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-447">Created date</span></span> </li>
<li> <span data-ttu-id="8bc17-448">修改日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-448">Modified date</span></span> </li>
<li> <span data-ttu-id="8bc17-449">建立者</span><span class="sxs-lookup"><span data-stu-id="8bc17-449">Created by</span></span> </li>
<li> <span data-ttu-id="8bc17-450">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8bc17-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8bc17-451">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="8bc17-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8bc17-452">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8bc17-453">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8bc17-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8bc17-454">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="8bc17-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8bc17-455">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-456">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-457">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8bc17-458">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8bc17-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8bc17-459">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8bc17-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8bc17-460">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8bc17-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="8bc17-461">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8bc17-462">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8bc17-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8bc17-463">Google 相簿表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="8bc17-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8bc17-464">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="8bc17-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8bc17-465">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8bc17-466">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="8bc17-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8bc17-467">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8bc17-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8bc17-468">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8bc17-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8bc17-469">共用磁碟機成員資格權限 (<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="8bc17-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8bc17-470">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="8bc17-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8bc17-471">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8bc17-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8bc17-472"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8bc17-473">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8bc17-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8bc17-474">文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-474">Documents</span></span> </li>
<li> <span data-ttu-id="8bc17-475">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8bc17-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8bc17-476">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-477">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-478">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8bc17-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8bc17-479">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8bc17-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8bc17-480">建立日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-480">Created date</span></span> </li>
<li> <span data-ttu-id="8bc17-481">修改日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-481">Modified date</span></span> </li>
<li> <span data-ttu-id="8bc17-482">建立者</span><span class="sxs-lookup"><span data-stu-id="8bc17-482">Created by</span></span> </li>
<li> <span data-ttu-id="8bc17-483">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8bc17-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8bc17-484">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8bc17-485">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8bc17-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8bc17-486">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="8bc17-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8bc17-487">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-488">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-489">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8bc17-490">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8bc17-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8bc17-491">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8bc17-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8bc17-492">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8bc17-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="8bc17-493">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8bc17-494">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8bc17-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8bc17-495">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="8bc17-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8bc17-496">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8bc17-497">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8bc17-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8bc17-498">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8bc17-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8bc17-499">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8bc17-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8bc17-500"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="8bc17-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8bc17-501">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8bc17-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8bc17-502">文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-502">Documents</span></span> </li>
<li> <span data-ttu-id="8bc17-503">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8bc17-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8bc17-504">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-505">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-506">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8bc17-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8bc17-507">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8bc17-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8bc17-508">建立日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-508">Created date</span></span> </li>
<li> <span data-ttu-id="8bc17-509">修改日期</span><span class="sxs-lookup"><span data-stu-id="8bc17-509">Modified date</span></span> </li>
<li> <span data-ttu-id="8bc17-510">建立者</span><span class="sxs-lookup"><span data-stu-id="8bc17-510">Created by</span></span> </li>
<li> <span data-ttu-id="8bc17-511">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8bc17-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8bc17-512">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8bc17-513">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8bc17-514">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8bc17-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8bc17-515">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="8bc17-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8bc17-516">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-517">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8bc17-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8bc17-518">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8bc17-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8bc17-519">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8bc17-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8bc17-520">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8bc17-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8bc17-521">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8bc17-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="8bc17-522">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8bc17-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8bc17-523">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="8bc17-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8bc17-524">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="8bc17-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8bc17-525">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="8bc17-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8bc17-526">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="8bc17-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8bc17-527">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="8bc17-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8bc17-528">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8bc17-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8bc17-529">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8bc17-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8bc17-530">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8bc17-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8bc17-531">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="8bc17-531">FastTrack responsibilities</span></span>

<span data-ttu-id="8bc17-532">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8bc17-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8bc17-533">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="8bc17-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8bc17-534">您的責任</span><span class="sxs-lookup"><span data-stu-id="8bc17-534">Your responsibilities</span></span>

<span data-ttu-id="8bc17-535">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8bc17-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8bc17-536">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="8bc17-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8bc17-537">你也要執行下列 [商務用 OneDrive] 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="8bc17-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="8bc17-538">使用您的移轉事件針對所有 [商務用 OneDrive] 網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="8bc17-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
