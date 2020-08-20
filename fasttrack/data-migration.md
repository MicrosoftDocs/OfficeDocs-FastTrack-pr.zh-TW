---
title: 資料移轉
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。 我們可以提供的協助類型取決於您的 Office 365 授權數量。
ms.openlocfilehash: fc7f07aea6104fdc6f06b3d624778919b351b34d
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/17/2020
ms.locfileid: "46776684"
---
# <a name="data-migration"></a><span data-ttu-id="e32ed-104">資料移轉</span><span class="sxs-lookup"><span data-stu-id="e32ed-104">Data Migration</span></span>

<span data-ttu-id="e32ed-105">FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。</span><span class="sxs-lookup"><span data-stu-id="e32ed-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="e32ed-106">我們提供的協助類型取決於您的 Office 365 授權數量：</span><span class="sxs-lookup"><span data-stu-id="e32ed-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="e32ed-107">**針對有 150-499 個授權的 Microsoft Office 365 租用戶**：FastTrack 僅提供移轉指引；由您負責執行資料移轉。</span><span class="sxs-lookup"><span data-stu-id="e32ed-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="e32ed-108">我們會透過可協助您規劃及使用免費工具的文件，引導您執行自助移轉。</span><span class="sxs-lookup"><span data-stu-id="e32ed-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="e32ed-109">**針對具有 500 個或更多授權數量的 Microsoft Office 365 租用戶**：FastTrack 會提供移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="e32ed-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="e32ed-110">我們會提供指引以協助規劃您的移轉事件、設定您的來源環境和 Office 365 租用戶，並充分利用我們的資料移轉服務來移轉您的資料。</span><span class="sxs-lookup"><span data-stu-id="e32ed-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="e32ed-111">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="e32ed-111">You create and schedule your migration events.</span></span> <span data-ttu-id="e32ed-112">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="e32ed-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="e32ed-113">如果您在 9/1/2017 之前已購買或續約ㄧ個商業方案，您只需使用 150 個授權，就能獲得資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="e32ed-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="e32ed-114">針對教育方案，只有您的付費教職員授權符合使用資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="e32ed-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="e32ed-115">考量</span><span class="sxs-lookup"><span data-stu-id="e32ed-115">Considerations</span></span>

  - <span data-ttu-id="e32ed-116">您的來源環境必須符合特定期望條件，才能將資料移轉至 Microsoft Office 365。</span><span class="sxs-lookup"><span data-stu-id="e32ed-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="e32ed-117">如需其它與 Exchange、SharePoint、和 [商務用 OneDrive] 適用的來源環境期望，請參照 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="e32ed-118">為提供資料移轉服務，我們需要您的來源環境及 Office 365 租用戶的適當存取權和權限。</span><span class="sxs-lookup"><span data-stu-id="e32ed-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="e32ed-119">我們的資料移轉服務既不是以受特殊法律、也不是受監管要求而設計或使用的。</span><span class="sxs-lookup"><span data-stu-id="e32ed-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="e32ed-120">當我們移轉您的資料時，可以將資料在任何我們進行設施維護的地方進行移轉、儲存及處理的動作（除非您的 FastTrack 移轉專案有提供另外的位置）。</span><span class="sxs-lookup"><span data-stu-id="e32ed-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="e32ed-121">我們不能保證郵件或檔案移轉的速度。</span><span class="sxs-lookup"><span data-stu-id="e32ed-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="e32ed-122">無法預料的問題（例如在來源環境中有無法讀取或已損毀的項目）可能會使我們無法移轉您的某些資料項目。</span><span class="sxs-lookup"><span data-stu-id="e32ed-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="e32ed-123">在我們控制範圍之外的外部因素（像是第三方應用程式開發介面 (APIs) 出現變更）會導致我們的資料移轉服務出現變更、延遲、或暫停的情況。</span><span class="sxs-lookup"><span data-stu-id="e32ed-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="e32ed-124">移轉服務的狀態</span><span class="sxs-lookup"><span data-stu-id="e32ed-124">Migration service availability</span></span>

  - <span data-ttu-id="e32ed-125">**針對商業及英國政府客戶：** 我們提供每天 24 小時、每周 7 天（24x7）的全年無休資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="e32ed-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="e32ed-126">**針對美國政府/DOD 客戶：** 我們提供每天 24 小時、每周 5 個工作天（24x5）的資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="e32ed-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="e32ed-127">移轉至 Exchange Online</span><span class="sxs-lookup"><span data-stu-id="e32ed-127">Migration to Exchange Online</span></span>

<span data-ttu-id="e32ed-128">當您選擇使用 FastTrack 將您的電子郵件移轉到 Exchange Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="e32ed-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="e32ed-129">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 Exchange Online，並充分利用我們的資料移轉服務來移轉您的信箱。</span><span class="sxs-lookup"><span data-stu-id="e32ed-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="e32ed-130">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="e32ed-130">You create and schedule your migration events.</span></span> <span data-ttu-id="e32ed-131">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="e32ed-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="e32ed-132">當您的移轉事件完成後，您可以預期在您的來源環境中，郵件經適當排程和從合格來源信箱移轉到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="e32ed-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="e32ed-133">考量</span><span class="sxs-lookup"><span data-stu-id="e32ed-133">Considerations</span></span>

  - <span data-ttu-id="e32ed-134">在進行移轉之前，您必須完成適用於 Exchange Online 的 FastTrack 核心上線動作；</span><span class="sxs-lookup"><span data-stu-id="e32ed-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="e32ed-135">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="e32ed-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="e32ed-136">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="e32ed-137">FastTrack 只會移轉至使用中的 Office 365 信箱。</span><span class="sxs-lookup"><span data-stu-id="e32ed-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="e32ed-138">如果您想要從內部部署的 Exchange 環境將資料移轉出來，您必須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="e32ed-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="e32ed-139">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="e32ed-140">每個來源環境都必須為其中各自相應的產品使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="e32ed-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="e32ed-141">存在於內部部署 Active Directory Domain Services 中的通訊群組清單（*MailEnabledGroup* 物件）和外部連絡人（*MailEnabledContact* 物件）並不屬於信箱資料移轉的一部分。</span><span class="sxs-lookup"><span data-stu-id="e32ed-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="e32ed-142">不過，您可以使用 Microsoft Azure Active Directory (Azure AD) Connect 進行同步處理。</span><span class="sxs-lookup"><span data-stu-id="e32ed-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="e32ed-143">來源環境</span><span class="sxs-lookup"><span data-stu-id="e32ed-143">Source environments</span></span>

<span data-ttu-id="e32ed-144">我們的資料移轉服務會將資料從這些來源環境中移轉出來：</span><span class="sxs-lookup"><span data-stu-id="e32ed-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="e32ed-145">含有單一個或多個 Exchange 組織的單一或多個 Active Directory 樹系 (每ㄧ個 Exchange 郵件系統都必須使用 Exchange 2010 或更新的版本)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="e32ed-146">單一個具 IMAP 功能的電子郵件環境。</span><span class="sxs-lookup"><span data-stu-id="e32ed-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="e32ed-147">G Suite 環境 (僅限 Gmail、連絡人和Outlook 行事曆)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="e32ed-148">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="e32ed-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e32ed-149"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="e32ed-150"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="e32ed-151"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="e32ed-152"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e32ed-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="e32ed-154">
<strong>注意事項：</strong> 若需內部部署 Exchange 相依性資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">混合式部署必要條件</span></a>。</span><span class="sxs-lookup"><span data-stu-id="e32ed-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="e32ed-155">混合部署移轉</span><span class="sxs-lookup"><span data-stu-id="e32ed-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="e32ed-156">電子郵件</span><span class="sxs-lookup"><span data-stu-id="e32ed-156">Emails</span></span></li>
<li><span data-ttu-id="e32ed-157">信箱規則</span><span class="sxs-lookup"><span data-stu-id="e32ed-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="e32ed-158">委派</span><span class="sxs-lookup"><span data-stu-id="e32ed-158">Delegates</span></span></li>
<li><span data-ttu-id="e32ed-159">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="e32ed-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="e32ed-160">行事曆</span><span class="sxs-lookup"><span data-stu-id="e32ed-160">Calendar</span></span> </li>
<li> <span data-ttu-id="e32ed-161">工作</span><span class="sxs-lookup"><span data-stu-id="e32ed-161">Tasks</span></span> </li>
<li> <span data-ttu-id="e32ed-162">受版權管理的電子郵件</span><span class="sxs-lookup"><span data-stu-id="e32ed-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="e32ed-163">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="e32ed-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="e32ed-164">簽章</span><span class="sxs-lookup"><span data-stu-id="e32ed-164">Signatures</span></span> </li>
<li> <span data-ttu-id="e32ed-165">隨著使用者信箱移轉的個人封存</span><span class="sxs-lookup"><span data-stu-id="e32ed-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="e32ed-166">可復原的項目</span><span class="sxs-lookup"><span data-stu-id="e32ed-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e32ed-167">公用資料夾</span><span class="sxs-lookup"><span data-stu-id="e32ed-167">Public folders</span></span> </li>
<li> <span data-ttu-id="e32ed-168">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="e32ed-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="e32ed-169">日誌封存或任何協力廠商封存解決方案</span><span class="sxs-lookup"><span data-stu-id="e32ed-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="e32ed-170">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="e32ed-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e32ed-171">從個人存放區資料表 (PST) 檔案封存的資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="e32ed-172">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="e32ed-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="e32ed-173">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="e32ed-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e32ed-174"><strong>G Suite 環境 (僅限 Gmail、連絡人和行事曆)</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="e32ed-175">
<strong>注意事項：</strong> 您的 G Suite 環境必須符合在下列章節中所述的先決條件<a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">執行 G Suite 移轉</a>。</span><span class="sxs-lookup"><span data-stu-id="e32ed-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="e32ed-176">轉換或分段</span><span class="sxs-lookup"><span data-stu-id="e32ed-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="e32ed-177">電子郵件</span><span class="sxs-lookup"><span data-stu-id="e32ed-177">Emails</span></span> </li>
<li> <span data-ttu-id="e32ed-178">信箱連絡人 (每個連絡人最多可移轉 3 個電子郵件地址)</span><span class="sxs-lookup"><span data-stu-id="e32ed-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="e32ed-179">行事曆</span><span class="sxs-lookup"><span data-stu-id="e32ed-179">Calendar</span></span> </li>
<li> <span data-ttu-id="e32ed-180">標籤</span><span class="sxs-lookup"><span data-stu-id="e32ed-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e32ed-181">規則</span><span class="sxs-lookup"><span data-stu-id="e32ed-181">Rules</span></span> </li>
<li> <span data-ttu-id="e32ed-182">委派</span><span class="sxs-lookup"><span data-stu-id="e32ed-182">Delegates</span></span> </li>
<li> <span data-ttu-id="e32ed-183">簽章</span><span class="sxs-lookup"><span data-stu-id="e32ed-183">Signatures</span></span> </li>
<li> <span data-ttu-id="e32ed-184">工作</span><span class="sxs-lookup"><span data-stu-id="e32ed-184">Tasks</span></span> </li>
<li> <span data-ttu-id="e32ed-185">任何超過郵件大小限制的電子郵件或附件</span><span class="sxs-lookup"><span data-stu-id="e32ed-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="e32ed-186">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="e32ed-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e32ed-187">從 PST 檔案或任何協力廠商封存解決方案 (例如 Google Vault) 封存的資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="e32ed-188">權限管理或加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="e32ed-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="e32ed-189">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="e32ed-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="e32ed-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="e32ed-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="e32ed-191">Google Groups</span><span class="sxs-lookup"><span data-stu-id="e32ed-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="e32ed-192">資源信箱</span><span class="sxs-lookup"><span data-stu-id="e32ed-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="e32ed-193">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="e32ed-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="e32ed-194">假期設定和自動回覆設定</span><span class="sxs-lookup"><span data-stu-id="e32ed-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="e32ed-195">共用行事曆、雲端附件、Google Hangout 連結和活動色彩</span><span class="sxs-lookup"><span data-stu-id="e32ed-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="e32ed-196">\*\*可移轉儲存為標籤的 Hangout 交談。</span><span class="sxs-lookup"><span data-stu-id="e32ed-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e32ed-197"><strong>IMAP4 來源 (例如 Domino、GroupWise 和 Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="e32ed-198">使用原生 IMAP4 工具進行的移轉</span><span class="sxs-lookup"><span data-stu-id="e32ed-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="e32ed-199">電子郵件</span><span class="sxs-lookup"><span data-stu-id="e32ed-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="e32ed-200">規則</span><span class="sxs-lookup"><span data-stu-id="e32ed-200">Rules</span></span> </li>
<li> <span data-ttu-id="e32ed-201">委派</span><span class="sxs-lookup"><span data-stu-id="e32ed-201">Delegates</span></span> </li>
<li> <span data-ttu-id="e32ed-202">通訊群組清單</span><span class="sxs-lookup"><span data-stu-id="e32ed-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="e32ed-203">外部連絡人</span><span class="sxs-lookup"><span data-stu-id="e32ed-203">External contacts</span></span> </li>
<li> <span data-ttu-id="e32ed-204">擁有郵件功能的使用者</span><span class="sxs-lookup"><span data-stu-id="e32ed-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="e32ed-205">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="e32ed-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e32ed-206">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="e32ed-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="e32ed-207">行事曆</span><span class="sxs-lookup"><span data-stu-id="e32ed-207">Calendar</span></span> </li>
<li> <span data-ttu-id="e32ed-208">簽章</span><span class="sxs-lookup"><span data-stu-id="e32ed-208">Signatures</span></span> </li>
<li> <span data-ttu-id="e32ed-209">工作</span><span class="sxs-lookup"><span data-stu-id="e32ed-209">Tasks</span></span> </li>
<li> <span data-ttu-id="e32ed-210">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="e32ed-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="e32ed-211">封存資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-211">Archive data</span></span> </li>
<li> <span data-ttu-id="e32ed-212">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="e32ed-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="e32ed-213">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="e32ed-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="e32ed-214">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="e32ed-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="e32ed-215">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="e32ed-215">FastTrack responsibilities</span></span>

<span data-ttu-id="e32ed-216">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="e32ed-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="e32ed-217">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="e32ed-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="e32ed-218">我們的 FastTrack 專家也會執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="e32ed-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="e32ed-219">可提供指引，以便協助您啟用在來源環境與 Exchange Online 之間並立的 SMTP 郵件路由傳送（如果適用的話）。</span><span class="sxs-lookup"><span data-stu-id="e32ed-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="e32ed-220">您的責任</span><span class="sxs-lookup"><span data-stu-id="e32ed-220">Your responsibilities</span></span>

<span data-ttu-id="e32ed-221">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="e32ed-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="e32ed-222">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="e32ed-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="e32ed-223">你也要執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="e32ed-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="e32ed-224">完成適用於 Exchange Online 的 FastTrack 核心上線動作。</span><span class="sxs-lookup"><span data-stu-id="e32ed-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="e32ed-225">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="e32ed-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="e32ed-226">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="e32ed-227">依 Office 365 指引安裝適當層級的用戶端軟體。</span><span class="sxs-lookup"><span data-stu-id="e32ed-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="e32ed-228">如需詳細資訊，請參閱 [現代化工作場所](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="e32ed-229">如果您想要從內部部署的 Exchange 環境將資料移轉出來，須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="e32ed-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="e32ed-230">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="e32ed-231">如果適用的話，每個來源環境都必須使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="e32ed-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="e32ed-232">若適用的話，在您的來源環境和 Exchange Online 中，設定和驗證 SMTP 郵件路由傳送共存。</span><span class="sxs-lookup"><span data-stu-id="e32ed-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="e32ed-233">請確定您的來源信箱容量大小未超過目標信箱配額。</span><span class="sxs-lookup"><span data-stu-id="e32ed-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="e32ed-234">視來源平台而定，您可能需要對來源資料限制在目標信箱配額的 85%。</span><span class="sxs-lookup"><span data-stu-id="e32ed-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="e32ed-235">視需要移轉用戶端資料。</span><span class="sxs-lookup"><span data-stu-id="e32ed-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="e32ed-236">這包含、但不限於本機通訊錄、本機 PST 檔案中的資料、Outlook 規則和本機 Outlook 設定。</span><span class="sxs-lookup"><span data-stu-id="e32ed-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="e32ed-237">協助使用者修正用戶端的遷移問題。</span><span class="sxs-lookup"><span data-stu-id="e32ed-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="e32ed-238">移轉至 SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="e32ed-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="e32ed-239">當您選擇使用 FastTrack 將您的檔案移轉到 SharePoint Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="e32ed-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="e32ed-240">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 SharePoint Online，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="e32ed-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="e32ed-241">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="e32ed-241">You create and schedule your migration events.</span></span> <span data-ttu-id="e32ed-242">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="e32ed-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="e32ed-243">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 SharePoint Online。</span><span class="sxs-lookup"><span data-stu-id="e32ed-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="e32ed-244">考量</span><span class="sxs-lookup"><span data-stu-id="e32ed-244">Considerations</span></span>

  - <span data-ttu-id="e32ed-245">所有的移轉動作都受到 SharePoint Online 的配額限制。</span><span class="sxs-lookup"><span data-stu-id="e32ed-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="e32ed-246">如需詳細資訊，可參照 [<span class="underline">SharePoint Online 和 [商務用 OneDrive]：軟體使用範圍及限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="e32ed-247">我們建議您將移轉的總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="e32ed-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="e32ed-248">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-248">Source environment details</span></span>

<span data-ttu-id="e32ed-249">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="e32ed-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="e32ed-250">檔案共用 (支援 SMB 2.0+ 裝置的伺服器訊息區 (SMB) 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="e32ed-251">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="e32ed-252">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="e32ed-253">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="e32ed-254">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="e32ed-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e32ed-255"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="e32ed-256"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="e32ed-257"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="e32ed-258"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e32ed-259"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="e32ed-260">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="e32ed-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e32ed-261">文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-261">Documents</span></span> </li>
<li> <span data-ttu-id="e32ed-262">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="e32ed-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e32ed-263">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="e32ed-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="e32ed-264">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="e32ed-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="e32ed-265">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="e32ed-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e32ed-266">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="e32ed-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e32ed-267">建立日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-267">Created date</span></span> </li>
<li> <span data-ttu-id="e32ed-268">修改日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-268">Modified date</span></span> </li>
<li> <span data-ttu-id="e32ed-269">建立者</span><span class="sxs-lookup"><span data-stu-id="e32ed-269">Created by</span></span> </li>
<li> <span data-ttu-id="e32ed-270">上次修改者</span><span class="sxs-lookup"><span data-stu-id="e32ed-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="e32ed-271">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="e32ed-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="e32ed-272">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="e32ed-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="e32ed-273">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="e32ed-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="e32ed-274">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="e32ed-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="e32ed-275">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="e32ed-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="e32ed-276">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="e32ed-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e32ed-277">舊版</span><span class="sxs-lookup"><span data-stu-id="e32ed-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="e32ed-278">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="e32ed-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="e32ed-279">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="e32ed-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="e32ed-280">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="e32ed-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="e32ed-281">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="e32ed-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="e32ed-282">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="e32ed-283">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e32ed-284">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="e32ed-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="e32ed-285">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="e32ed-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="e32ed-286">檔案或資料夾超過目前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 的規定和限制 </span></a> </span><span class="sxs-lookup"><span data-stu-id="e32ed-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e32ed-287"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="e32ed-288">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="e32ed-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e32ed-289">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式) ，包括超過 10 MB 的檔案。</span><span class="sxs-lookup"><span data-stu-id="e32ed-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="e32ed-290">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="e32ed-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e32ed-291">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-292">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-293">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="e32ed-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e32ed-294">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="e32ed-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e32ed-295">建立日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-295">Created date</span></span> </li>
<li> <span data-ttu-id="e32ed-296">修改日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-296">Modified date</span></span> </li>
<li> <span data-ttu-id="e32ed-297">建立者</span><span class="sxs-lookup"><span data-stu-id="e32ed-297">Created by</span></span> </li>
<li> <span data-ttu-id="e32ed-298">上次修改者</span><span class="sxs-lookup"><span data-stu-id="e32ed-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e32ed-299">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="e32ed-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="e32ed-300">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e32ed-301">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="e32ed-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e32ed-302">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="e32ed-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="e32ed-303">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-304">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-305">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="e32ed-306">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="e32ed-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e32ed-307">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="e32ed-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e32ed-308">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="e32ed-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="e32ed-309">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e32ed-310">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="e32ed-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e32ed-311">Google 相簿、表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="e32ed-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="e32ed-312">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="e32ed-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="e32ed-313">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="e32ed-314">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="e32ed-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="e32ed-315">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="e32ed-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="e32ed-316">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="e32ed-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="e32ed-317">共用磁碟機成員權限（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="e32ed-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="e32ed-318">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="e32ed-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="e32ed-319">檔案或資料夾超過目前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 的規定和限制 </span></a> </span><span class="sxs-lookup"><span data-stu-id="e32ed-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e32ed-320"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="e32ed-321">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="e32ed-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e32ed-322">文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-322">Documents</span></span> </li>
<li> <span data-ttu-id="e32ed-323">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="e32ed-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e32ed-324">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-325">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-326">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="e32ed-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e32ed-327">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="e32ed-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e32ed-328">建立日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-328">Created date</span></span> </li>
<li> <span data-ttu-id="e32ed-329">修改日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-329">Modified date</span></span> </li>
<li> <span data-ttu-id="e32ed-330">建立者</span><span class="sxs-lookup"><span data-stu-id="e32ed-330">Created by</span></span> </li>
<li> <span data-ttu-id="e32ed-331">上次修改者</span><span class="sxs-lookup"><span data-stu-id="e32ed-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e32ed-332">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e32ed-333">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="e32ed-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e32ed-334">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="e32ed-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="e32ed-335">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-336">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-337">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="e32ed-338">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="e32ed-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e32ed-339">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="e32ed-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e32ed-340">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="e32ed-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="e32ed-341">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e32ed-342">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="e32ed-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e32ed-343">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="e32ed-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="e32ed-344">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="e32ed-345">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="e32ed-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="e32ed-346">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="e32ed-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="e32ed-347">檔案或資料夾超過目前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 的規定和限制 </span></a> </span><span class="sxs-lookup"><span data-stu-id="e32ed-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e32ed-348"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="e32ed-349">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="e32ed-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e32ed-350">文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-350">Documents</span></span> </li>
<li> <span data-ttu-id="e32ed-351">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="e32ed-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e32ed-352">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-353">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-354">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="e32ed-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e32ed-355">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="e32ed-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e32ed-356">建立日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-356">Created date</span></span> </li>
<li> <span data-ttu-id="e32ed-357">修改日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-357">Modified date</span></span> </li>
<li> <span data-ttu-id="e32ed-358">建立者</span><span class="sxs-lookup"><span data-stu-id="e32ed-358">Created by</span></span> </li>
<li> <span data-ttu-id="e32ed-359">上次修改者</span><span class="sxs-lookup"><span data-stu-id="e32ed-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e32ed-360">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="e32ed-361">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e32ed-362">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="e32ed-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e32ed-363">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="e32ed-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="e32ed-364">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-365">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-366">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="e32ed-367">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="e32ed-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e32ed-368">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="e32ed-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e32ed-369">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="e32ed-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="e32ed-370">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e32ed-371">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="e32ed-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="e32ed-372">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="e32ed-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="e32ed-373">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="e32ed-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="e32ed-374">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="e32ed-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="e32ed-375">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="e32ed-376">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="e32ed-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="e32ed-377">指示使用者在移轉之後，與外部使用者再次共用內容）</span><span class="sxs-lookup"><span data-stu-id="e32ed-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="e32ed-378">檔案或資料夾超過目前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 的規定和限制 </span></a> </span><span class="sxs-lookup"><span data-stu-id="e32ed-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="e32ed-379">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="e32ed-379">FastTrack responsibilities</span></span>

<span data-ttu-id="e32ed-380">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="e32ed-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="e32ed-381">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="e32ed-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="e32ed-382">您的責任</span><span class="sxs-lookup"><span data-stu-id="e32ed-382">Your responsibilities</span></span>

<span data-ttu-id="e32ed-383">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="e32ed-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="e32ed-384">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="e32ed-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="e32ed-385">你也要執行下列 SharePoint Online 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="e32ed-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="e32ed-386">使用您的移轉事件針對所有 SharePoint 小組網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="e32ed-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="e32ed-387">移轉至商務用 OneDrive</span><span class="sxs-lookup"><span data-stu-id="e32ed-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="e32ed-388">當您選擇使用 FastTrack 將您的檔案移轉到 商務用 OneDrive 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="e32ed-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="e32ed-389">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 商務用 OneDrive，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="e32ed-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="e32ed-390">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="e32ed-390">You create and schedule your migration events.</span></span> <span data-ttu-id="e32ed-391">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="e32ed-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="e32ed-392">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 商務用 OneDrive。</span><span class="sxs-lookup"><span data-stu-id="e32ed-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="e32ed-393">考量</span><span class="sxs-lookup"><span data-stu-id="e32ed-393">Considerations</span></span>

  - <span data-ttu-id="e32ed-394">所有的移轉事件都受 [商務用 OneDrive] 配額的限制。</span><span class="sxs-lookup"><span data-stu-id="e32ed-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="e32ed-395">如需詳細資訊，請參照 [<span class="underline">SharePoint Online 和 [商務用 OneDrive]：軟體使用範圍及限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="e32ed-396">我們建議您將移轉的資料總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="e32ed-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="e32ed-397">FastTrack 只會移轉到使用中的 [商務用 OneDrive] 磁碟機。</span><span class="sxs-lookup"><span data-stu-id="e32ed-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="e32ed-398">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-398">Source environment details</span></span>

<span data-ttu-id="e32ed-399">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="e32ed-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="e32ed-400">檔案共用 (支援 SMB 2.0+ 之裝置的 SMB 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="e32ed-401">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="e32ed-402">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="e32ed-403">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="e32ed-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="e32ed-404">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="e32ed-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="e32ed-405"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="e32ed-406"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="e32ed-407"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="e32ed-408"><strong>不能移轉什麼內容</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e32ed-409"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="e32ed-410">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="e32ed-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e32ed-411">文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-411">Documents</span></span> </li>
<li> <span data-ttu-id="e32ed-412">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="e32ed-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e32ed-413">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="e32ed-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="e32ed-414">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="e32ed-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="e32ed-415">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="e32ed-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e32ed-416">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="e32ed-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e32ed-417">建立日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-417">Created date</span></span> </li>
<li> <span data-ttu-id="e32ed-418">修改日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-418">Modified date</span></span> </li>
<li> <span data-ttu-id="e32ed-419">建立者</span><span class="sxs-lookup"><span data-stu-id="e32ed-419">Created by</span></span> </li>
<li> <span data-ttu-id="e32ed-420">上次修改者</span><span class="sxs-lookup"><span data-stu-id="e32ed-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="e32ed-421">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="e32ed-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="e32ed-422">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="e32ed-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="e32ed-423">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="e32ed-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="e32ed-424">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="e32ed-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="e32ed-425">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="e32ed-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="e32ed-426">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="e32ed-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e32ed-427">舊版</span><span class="sxs-lookup"><span data-stu-id="e32ed-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="e32ed-428">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="e32ed-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="e32ed-429">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="e32ed-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="e32ed-430">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="e32ed-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="e32ed-431">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="e32ed-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="e32ed-432">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="e32ed-433">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e32ed-434">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="e32ed-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="e32ed-435">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="e32ed-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="e32ed-436">檔案或資料夾超過目前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 的規定和限制 </span></a> </span><span class="sxs-lookup"><span data-stu-id="e32ed-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e32ed-437"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="e32ed-438">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="e32ed-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e32ed-439">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式 ，包括超過 10 MB 的檔案)</span><span class="sxs-lookup"><span data-stu-id="e32ed-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="e32ed-440">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="e32ed-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e32ed-441">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-442">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-443">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="e32ed-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e32ed-444">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="e32ed-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e32ed-445">建立日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-445">Created date</span></span> </li>
<li> <span data-ttu-id="e32ed-446">修改日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-446">Modified date</span></span> </li>
<li> <span data-ttu-id="e32ed-447">建立者</span><span class="sxs-lookup"><span data-stu-id="e32ed-447">Created by</span></span> </li>
<li> <span data-ttu-id="e32ed-448">上次修改者</span><span class="sxs-lookup"><span data-stu-id="e32ed-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e32ed-449">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="e32ed-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="e32ed-450">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e32ed-451">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="e32ed-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e32ed-452">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="e32ed-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="e32ed-453">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-454">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-455">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="e32ed-456">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="e32ed-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e32ed-457">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="e32ed-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e32ed-458">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="e32ed-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="e32ed-459">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e32ed-460">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="e32ed-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e32ed-461">Google 相簿表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="e32ed-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="e32ed-462">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="e32ed-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="e32ed-463">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="e32ed-464">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="e32ed-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="e32ed-465">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="e32ed-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="e32ed-466">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="e32ed-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="e32ed-467">共用磁碟機成員資格權限 (<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="e32ed-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="e32ed-468">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="e32ed-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="e32ed-469">檔案或資料夾超過目前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 的規定和限制 </span></a> </span><span class="sxs-lookup"><span data-stu-id="e32ed-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e32ed-470"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="e32ed-471">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="e32ed-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e32ed-472">文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-472">Documents</span></span> </li>
<li> <span data-ttu-id="e32ed-473">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="e32ed-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e32ed-474">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-475">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-476">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="e32ed-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e32ed-477">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="e32ed-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e32ed-478">建立日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-478">Created date</span></span> </li>
<li> <span data-ttu-id="e32ed-479">修改日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-479">Modified date</span></span> </li>
<li> <span data-ttu-id="e32ed-480">建立者</span><span class="sxs-lookup"><span data-stu-id="e32ed-480">Created by</span></span> </li>
<li> <span data-ttu-id="e32ed-481">上次修改者</span><span class="sxs-lookup"><span data-stu-id="e32ed-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e32ed-482">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e32ed-483">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="e32ed-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e32ed-484">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="e32ed-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="e32ed-485">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-486">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-487">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="e32ed-488">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="e32ed-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e32ed-489">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="e32ed-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e32ed-490">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="e32ed-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="e32ed-491">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e32ed-492">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="e32ed-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e32ed-493">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="e32ed-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="e32ed-494">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="e32ed-495">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="e32ed-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="e32ed-496">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="e32ed-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="e32ed-497">檔案或資料夾超過目前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 的規定和限制 </span></a> </span><span class="sxs-lookup"><span data-stu-id="e32ed-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e32ed-498"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="e32ed-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="e32ed-499">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="e32ed-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e32ed-500">文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-500">Documents</span></span> </li>
<li> <span data-ttu-id="e32ed-501">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="e32ed-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e32ed-502">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-503">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-504">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="e32ed-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e32ed-505">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="e32ed-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e32ed-506">建立日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-506">Created date</span></span> </li>
<li> <span data-ttu-id="e32ed-507">修改日期</span><span class="sxs-lookup"><span data-stu-id="e32ed-507">Modified date</span></span> </li>
<li> <span data-ttu-id="e32ed-508">建立者</span><span class="sxs-lookup"><span data-stu-id="e32ed-508">Created by</span></span> </li>
<li> <span data-ttu-id="e32ed-509">上次修改者</span><span class="sxs-lookup"><span data-stu-id="e32ed-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e32ed-510">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="e32ed-511">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e32ed-512">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="e32ed-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e32ed-513">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="e32ed-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="e32ed-514">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-515">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="e32ed-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e32ed-516">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="e32ed-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="e32ed-517">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="e32ed-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e32ed-518">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="e32ed-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e32ed-519">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="e32ed-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="e32ed-520">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="e32ed-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e32ed-521">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="e32ed-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="e32ed-522">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="e32ed-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="e32ed-523">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="e32ed-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="e32ed-524">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="e32ed-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="e32ed-525">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="e32ed-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="e32ed-526">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="e32ed-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="e32ed-527">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="e32ed-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="e32ed-528">檔案或資料夾超過目前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 的規定和限制 </span></a> </span><span class="sxs-lookup"><span data-stu-id="e32ed-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="e32ed-529">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="e32ed-529">FastTrack responsibilities</span></span>

<span data-ttu-id="e32ed-530">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="e32ed-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="e32ed-531">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="e32ed-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="e32ed-532">您的責任</span><span class="sxs-lookup"><span data-stu-id="e32ed-532">Your responsibilities</span></span>

<span data-ttu-id="e32ed-533">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="e32ed-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="e32ed-534">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="e32ed-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="e32ed-535">你也要執行下列 [商務用 OneDrive] 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="e32ed-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="e32ed-536">使用您的移轉事件針對所有 [商務用 OneDrive] 網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="e32ed-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
