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
ms.openlocfilehash: 437da2c12375bfc2d9614c452b0685f18ad3d188
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592424"
---
# <a name="data-migration"></a><span data-ttu-id="aea01-104">資料移轉</span><span class="sxs-lookup"><span data-stu-id="aea01-104">Data Migration</span></span>

<span data-ttu-id="aea01-105">FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。</span><span class="sxs-lookup"><span data-stu-id="aea01-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="aea01-106">我們提供的協助類型取決於您的 Office 365 授權數量：</span><span class="sxs-lookup"><span data-stu-id="aea01-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="aea01-107">**針對有 150-499 個授權的 Microsoft Office 365 租用戶**：FastTrack 僅提供移轉指引；由您負責執行資料移轉。</span><span class="sxs-lookup"><span data-stu-id="aea01-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="aea01-108">我們會透過可協助您規劃及使用免費工具的文件，引導您執行自助移轉。</span><span class="sxs-lookup"><span data-stu-id="aea01-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="aea01-109">**針對具有 500 個或更多授權數量的 Microsoft Office 365 租用戶**：FastTrack 會提供移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="aea01-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="aea01-110">我們會提供指引以協助規劃您的移轉事件、設定您的來源環境和 Office 365 租用戶，並充分利用我們的資料移轉服務來移轉您的資料。</span><span class="sxs-lookup"><span data-stu-id="aea01-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="aea01-111">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="aea01-111">You create and schedule your migration events.</span></span> <span data-ttu-id="aea01-112">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="aea01-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="aea01-113">如果您在 9/1/2017 之前已購買或續約ㄧ個商業方案，您只需使用 150 個授權，就能獲得資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="aea01-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="aea01-114">針對教育方案，只有您的付費教職員授權符合使用資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="aea01-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="aea01-115">考量</span><span class="sxs-lookup"><span data-stu-id="aea01-115">Considerations</span></span>

  - <span data-ttu-id="aea01-116">您的來源環境必須符合特定期望條件，才能將資料移轉至 Microsoft Office 365。</span><span class="sxs-lookup"><span data-stu-id="aea01-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="aea01-117">如需其它與 Exchange、SharePoint、和 [商務用 OneDrive] 適用的來源環境期望，請參照 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="aea01-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="aea01-118">為提供資料移轉服務，我們需要您的來源環境及 Office 365 租用戶的適當存取權和權限。</span><span class="sxs-lookup"><span data-stu-id="aea01-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="aea01-119">我們的資料移轉服務既不是以受特殊法律、也不是受監管要求而設計或使用的。</span><span class="sxs-lookup"><span data-stu-id="aea01-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="aea01-120">當我們移轉您的資料時，可以將資料在任何我們進行設施維護的地方進行移轉、儲存及處理的動作（除非您的 FastTrack 移轉專案有提供另外的位置）。</span><span class="sxs-lookup"><span data-stu-id="aea01-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="aea01-121">我們不能保證郵件或檔案移轉的速度。</span><span class="sxs-lookup"><span data-stu-id="aea01-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="aea01-122">無法預料的問題（例如在來源環境中有無法讀取或已損毀的項目）可能會使我們無法移轉您的某些資料項目。</span><span class="sxs-lookup"><span data-stu-id="aea01-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="aea01-123">在我們控制範圍之外的外部因素（像是第三方應用程式開發介面 (APIs) 出現變更）會導致我們的資料移轉服務出現變更、延遲、或暫停的情況。</span><span class="sxs-lookup"><span data-stu-id="aea01-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="aea01-124">移轉服務的狀態</span><span class="sxs-lookup"><span data-stu-id="aea01-124">Migration service availability</span></span>

  - <span data-ttu-id="aea01-125">**針對商業及英國政府客戶：** 我們提供每天 24 小時、每周 7 天（24x7）的全年無休資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="aea01-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="aea01-126">**針對美國政府/DOD 客戶：** 我們提供每天 24 小時、每周 5 個工作天（24x5）的資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="aea01-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="aea01-127">移轉至 Exchange Online</span><span class="sxs-lookup"><span data-stu-id="aea01-127">Migration to Exchange Online</span></span>

<span data-ttu-id="aea01-128">當您選擇使用 FastTrack 將您的電子郵件移轉到 Exchange Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="aea01-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="aea01-129">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 Exchange Online，並充分利用我們的資料移轉服務來移轉您的信箱。</span><span class="sxs-lookup"><span data-stu-id="aea01-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="aea01-130">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="aea01-130">You create and schedule your migration events.</span></span> <span data-ttu-id="aea01-131">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="aea01-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="aea01-132">當您的移轉事件完成後，您可以預期在您的來源環境中，郵件經適當排程和從合格來源信箱移轉到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="aea01-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="aea01-133">考量</span><span class="sxs-lookup"><span data-stu-id="aea01-133">Considerations</span></span>

  - <span data-ttu-id="aea01-134">在進行移轉之前，您必須完成適用於 Exchange Online 的 FastTrack 核心上線動作；</span><span class="sxs-lookup"><span data-stu-id="aea01-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="aea01-135">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="aea01-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="aea01-136">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="aea01-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="aea01-137">FastTrack 只會移轉至使用中的 Office 365 信箱。</span><span class="sxs-lookup"><span data-stu-id="aea01-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="aea01-138">如果您想要從內部部署的 Exchange 環境將資料移轉出來，您必須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="aea01-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="aea01-139">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="aea01-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="aea01-140">每個來源環境都必須為其中各自相應的產品使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="aea01-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="aea01-141">存在於內部部署 Active Directory Domain Services 中的通訊群組清單（*MailEnabledGroup* 物件）和外部連絡人（*MailEnabledContact* 物件）並不屬於信箱資料移轉的一部分。</span><span class="sxs-lookup"><span data-stu-id="aea01-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="aea01-142">不過，您可以使用 Microsoft Azure Active Directory (Azure AD) Connect 進行同步處理。</span><span class="sxs-lookup"><span data-stu-id="aea01-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="aea01-143">來源環境</span><span class="sxs-lookup"><span data-stu-id="aea01-143">Source environments</span></span>

<span data-ttu-id="aea01-144">我們的資料移轉服務會將資料從這些來源環境中移轉出來：</span><span class="sxs-lookup"><span data-stu-id="aea01-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="aea01-145">含有單一個或多個 Exchange 組織的單一或多個 Active Directory 樹系 (每ㄧ個 Exchange 郵件系統都必須使用 Exchange 2010 或更新的版本)。</span><span class="sxs-lookup"><span data-stu-id="aea01-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="aea01-146">單一個具 IMAP 功能的電子郵件環境。</span><span class="sxs-lookup"><span data-stu-id="aea01-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="aea01-147">G Suite 環境 (僅限 Gmail、連絡人和Outlook 行事曆)。</span><span class="sxs-lookup"><span data-stu-id="aea01-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="aea01-148">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="aea01-149"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="aea01-150"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="aea01-151"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="aea01-152"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="aea01-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="aea01-154">
<strong>附注：</strong>如需內部部署 Exchange 相依性，請參閱<a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">混合部署必要條件</span></a>。</span><span class="sxs-lookup"><span data-stu-id="aea01-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="aea01-155">混合部署移轉</span><span class="sxs-lookup"><span data-stu-id="aea01-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="aea01-156">電子郵件</span><span class="sxs-lookup"><span data-stu-id="aea01-156">Emails</span></span></li>
<li><span data-ttu-id="aea01-157">伺服器端信箱規則</span><span class="sxs-lookup"><span data-stu-id="aea01-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="aea01-158">委派</span><span class="sxs-lookup"><span data-stu-id="aea01-158">Delegates</span></span></li>
<li><span data-ttu-id="aea01-159">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="aea01-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="aea01-160">行事曆</span><span class="sxs-lookup"><span data-stu-id="aea01-160">Calendar</span></span> </li>
<li> <span data-ttu-id="aea01-161">工作</span><span class="sxs-lookup"><span data-stu-id="aea01-161">Tasks</span></span> </li>
<li> <span data-ttu-id="aea01-162">受版權管理的電子郵件</span><span class="sxs-lookup"><span data-stu-id="aea01-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="aea01-163">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="aea01-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="aea01-164">簽章</span><span class="sxs-lookup"><span data-stu-id="aea01-164">Signatures</span></span> </li>
<li> <span data-ttu-id="aea01-165">隨著使用者信箱移轉的個人封存</span><span class="sxs-lookup"><span data-stu-id="aea01-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="aea01-166">可復原的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="aea01-167">公用資料夾</span><span class="sxs-lookup"><span data-stu-id="aea01-167">Public folders</span></span> </li>
<li> <span data-ttu-id="aea01-168">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="aea01-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="aea01-169">日誌封存或任何協力廠商封存解決方案</span><span class="sxs-lookup"><span data-stu-id="aea01-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="aea01-170">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="aea01-171">從個人存放區資料表 (PST) 檔案封存的資料</span><span class="sxs-lookup"><span data-stu-id="aea01-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="aea01-172">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="aea01-173">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="aea01-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="aea01-174">用戶端信箱規則</span><span class="sxs-lookup"><span data-stu-id="aea01-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="aea01-175"><strong>G Suite 環境 (僅限 Gmail、連絡人和行事曆)</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="aea01-176">
<strong>附注：</strong> 您的 G 套件環境必須符合 [執行 G Suite 遷移](/Exchange/mailbox-migration/perform-g-suite-migration)中所述的必要條件。</span><span class="sxs-lookup"><span data-stu-id="aea01-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in [Perform a G Suite migration](/Exchange/mailbox-migration/perform-g-suite-migration).</span></span></td>
<td><span data-ttu-id="aea01-177">轉換或分段</span><span class="sxs-lookup"><span data-stu-id="aea01-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-178">電子郵件</span><span class="sxs-lookup"><span data-stu-id="aea01-178">Emails</span></span> </li>
<li> <span data-ttu-id="aea01-179">信箱連絡人 (每個連絡人最多可移轉 3 個電子郵件地址)</span><span class="sxs-lookup"><span data-stu-id="aea01-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="aea01-180">行事曆</span><span class="sxs-lookup"><span data-stu-id="aea01-180">Calendar</span></span> </li>
<li> <span data-ttu-id="aea01-181">標籤</span><span class="sxs-lookup"><span data-stu-id="aea01-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="aea01-182">規則</span><span class="sxs-lookup"><span data-stu-id="aea01-182">Rules</span></span> </li>
<li> <span data-ttu-id="aea01-183">委派</span><span class="sxs-lookup"><span data-stu-id="aea01-183">Delegates</span></span> </li>
<li> <span data-ttu-id="aea01-184">簽章</span><span class="sxs-lookup"><span data-stu-id="aea01-184">Signatures</span></span> </li>
<li> <span data-ttu-id="aea01-185">工作</span><span class="sxs-lookup"><span data-stu-id="aea01-185">Tasks</span></span> </li>
<li> <span data-ttu-id="aea01-186">任何超過郵件大小限制的電子郵件或附件</span><span class="sxs-lookup"><span data-stu-id="aea01-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="aea01-187">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="aea01-188">從 PST 檔案或任何協力廠商封存解決方案 (例如 Google Vault) 封存的資料</span><span class="sxs-lookup"><span data-stu-id="aea01-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="aea01-189">權限管理或加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="aea01-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="aea01-190">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="aea01-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="aea01-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="aea01-192">Google Groups</span><span class="sxs-lookup"><span data-stu-id="aea01-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="aea01-193">資源信箱</span><span class="sxs-lookup"><span data-stu-id="aea01-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="aea01-194">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="aea01-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="aea01-195">假期設定和自動回覆設定</span><span class="sxs-lookup"><span data-stu-id="aea01-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="aea01-196">共用行事曆、雲端附件、Google Hangout 連結和活動色彩</span><span class="sxs-lookup"><span data-stu-id="aea01-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="aea01-197">\*\*可移轉儲存為標籤的 Hangout 交談。</span><span class="sxs-lookup"><span data-stu-id="aea01-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="aea01-198"><strong>IMAP4 來源 (例如 Domino、GroupWise 和 Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="aea01-199">使用原生 IMAP4 工具進行的移轉</span><span class="sxs-lookup"><span data-stu-id="aea01-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="aea01-200">電子郵件</span><span class="sxs-lookup"><span data-stu-id="aea01-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="aea01-201">規則</span><span class="sxs-lookup"><span data-stu-id="aea01-201">Rules</span></span> </li>
<li> <span data-ttu-id="aea01-202">委派</span><span class="sxs-lookup"><span data-stu-id="aea01-202">Delegates</span></span> </li>
<li> <span data-ttu-id="aea01-203">通訊群組清單</span><span class="sxs-lookup"><span data-stu-id="aea01-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="aea01-204">外部連絡人</span><span class="sxs-lookup"><span data-stu-id="aea01-204">External contacts</span></span> </li>
<li> <span data-ttu-id="aea01-205">擁有郵件功能的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="aea01-206">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="aea01-207">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="aea01-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="aea01-208">行事曆</span><span class="sxs-lookup"><span data-stu-id="aea01-208">Calendar</span></span> </li>
<li> <span data-ttu-id="aea01-209">簽章</span><span class="sxs-lookup"><span data-stu-id="aea01-209">Signatures</span></span> </li>
<li> <span data-ttu-id="aea01-210">工作</span><span class="sxs-lookup"><span data-stu-id="aea01-210">Tasks</span></span> </li>
<li> <span data-ttu-id="aea01-211">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="aea01-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="aea01-212">封存資料</span><span class="sxs-lookup"><span data-stu-id="aea01-212">Archive data</span></span> </li>
<li> <span data-ttu-id="aea01-213">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="aea01-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="aea01-214">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="aea01-215">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="aea01-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="aea01-216">Exchange Online 遷移的 FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="aea01-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="aea01-217">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="aea01-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="aea01-218">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="aea01-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="aea01-219">我們的 FastTrack 專家也會執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="aea01-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="aea01-220">可提供指引，以便協助您啟用在來源環境與 Exchange Online 之間並立的 SMTP 郵件路由傳送（如果適用的話）。</span><span class="sxs-lookup"><span data-stu-id="aea01-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="aea01-221">您的責任</span><span class="sxs-lookup"><span data-stu-id="aea01-221">Your responsibilities</span></span>

<span data-ttu-id="aea01-222">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="aea01-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="aea01-223">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="aea01-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="aea01-224">你也要執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="aea01-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="aea01-225">完成適用於 Exchange Online 的 FastTrack 核心上線動作。</span><span class="sxs-lookup"><span data-stu-id="aea01-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="aea01-226">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="aea01-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="aea01-227">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="aea01-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="aea01-228">依 Office 365 指引安裝適當層級的用戶端軟體。</span><span class="sxs-lookup"><span data-stu-id="aea01-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="aea01-229">如需詳細資訊，請參閱 [現代化工作場所](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。</span><span class="sxs-lookup"><span data-stu-id="aea01-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="aea01-230">如果您想要從內部部署的 Exchange 環境將資料移轉出來，須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="aea01-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="aea01-231">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="aea01-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="aea01-232">如果適用的話，每個來源環境都必須使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="aea01-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="aea01-233">若適用的話，在您的來源環境和 Exchange Online 中，設定和驗證 SMTP 郵件路由傳送共存。</span><span class="sxs-lookup"><span data-stu-id="aea01-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="aea01-234">請確定您的來源信箱容量大小未超過目標信箱配額。</span><span class="sxs-lookup"><span data-stu-id="aea01-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="aea01-235">視來源平台而定，您可能需要對來源資料限制在目標信箱配額的 85%。</span><span class="sxs-lookup"><span data-stu-id="aea01-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="aea01-236">視需要移轉用戶端資料。</span><span class="sxs-lookup"><span data-stu-id="aea01-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="aea01-237">這包含、但不限於本機通訊錄、本機 PST 檔案中的資料、Outlook 規則和本機 Outlook 設定。</span><span class="sxs-lookup"><span data-stu-id="aea01-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="aea01-238">協助使用者修正用戶端的遷移問題。</span><span class="sxs-lookup"><span data-stu-id="aea01-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="aea01-239">移轉至 SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="aea01-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="aea01-240">當您選擇使用 FastTrack 將您的檔案移轉到 SharePoint Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="aea01-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="aea01-241">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 SharePoint Online，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="aea01-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="aea01-242">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="aea01-242">You create and schedule your migration events.</span></span> <span data-ttu-id="aea01-243">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="aea01-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="aea01-244">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 SharePoint Online。</span><span class="sxs-lookup"><span data-stu-id="aea01-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="aea01-245">考量</span><span class="sxs-lookup"><span data-stu-id="aea01-245">Considerations</span></span>

 - <span data-ttu-id="aea01-246">所有的移轉動作都受到 SharePoint Online 的配額限制。</span><span class="sxs-lookup"><span data-stu-id="aea01-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="aea01-247">如需詳細資訊，請參閱<a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint 限制</a>。</span><span class="sxs-lookup"><span data-stu-id="aea01-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="aea01-248">我們建議您將移轉的總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="aea01-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="aea01-249">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="aea01-249">Source environment details</span></span>

<span data-ttu-id="aea01-250">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="aea01-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="aea01-251">檔案共用 (支援 SMB 2.0+ 裝置的伺服器訊息區 (SMB) 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="aea01-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="aea01-252">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="aea01-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="aea01-253">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="aea01-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="aea01-254">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="aea01-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="aea01-255">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="aea01-256"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="aea01-257"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="aea01-258"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="aea01-259"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="aea01-260"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="aea01-261">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-262">文件</span><span class="sxs-lookup"><span data-stu-id="aea01-262">Documents</span></span> </li>
<li> <span data-ttu-id="aea01-263">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-264">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="aea01-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-265">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="aea01-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-266">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-267">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-268">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-268">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-269">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-269">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-270">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-270">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-271">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="aea01-272">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="aea01-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="aea01-273">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="aea01-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="aea01-274">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="aea01-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="aea01-275">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="aea01-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-276">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="aea01-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="aea01-277">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-278">舊版</span><span class="sxs-lookup"><span data-stu-id="aea01-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="aea01-279">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="aea01-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="aea01-280">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="aea01-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="aea01-281">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="aea01-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="aea01-282">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="aea01-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="aea01-283">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="aea01-284">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-285">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="aea01-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="aea01-286">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="aea01-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="aea01-287">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="aea01-288"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="aea01-289">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-290">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式) ，包括超過 10 MB 的檔案。</span><span class="sxs-lookup"><span data-stu-id="aea01-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="aea01-291">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-292">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-293">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-294">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-295">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-296">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-296">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-297">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-297">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-298">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-298">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-299">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="aea01-300">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="aea01-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="aea01-301">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="aea01-302">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="aea01-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="aea01-303">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="aea01-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="aea01-304">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-305">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-306">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="aea01-307">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="aea01-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="aea01-308">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-309">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="aea01-310">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-311">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="aea01-312">Google 相簿、表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="aea01-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="aea01-313">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="aea01-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="aea01-314">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="aea01-315">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="aea01-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="aea01-316">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="aea01-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="aea01-317">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="aea01-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="aea01-318">共用磁碟機成員權限（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="aea01-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="aea01-319">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="aea01-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="aea01-320">標記為受限或未 copyable 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="aea01-321">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="aea01-322"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="aea01-323">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-324">文件</span><span class="sxs-lookup"><span data-stu-id="aea01-324">Documents</span></span> </li>
<li> <span data-ttu-id="aea01-325">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-326">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-327">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-328">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-329">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-330">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-330">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-331">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-331">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-332">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-332">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-333">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="aea01-334">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="aea01-335">方框附注 (轉換為 Word 檔案格式) </span><span class="sxs-lookup"><span data-stu-id="aea01-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="aea01-336">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="aea01-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="aea01-337">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="aea01-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="aea01-338">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-339">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-340">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="aea01-341">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="aea01-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="aea01-342">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-343">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="aea01-344">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-345">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="aea01-346">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="aea01-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="aea01-347">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="aea01-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="aea01-348">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="aea01-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="aea01-349">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="aea01-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="aea01-350">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="aea01-351"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="aea01-352">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-353">文件</span><span class="sxs-lookup"><span data-stu-id="aea01-353">Documents</span></span> </li>
<li> <span data-ttu-id="aea01-354">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-355">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-356">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-357">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-358">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-359">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-359">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-360">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-360">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-361">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-361">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-362">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="aea01-363">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="aea01-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="aea01-364">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="aea01-365">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="aea01-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="aea01-366">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="aea01-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="aea01-367">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-368">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-369">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="aea01-370">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="aea01-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="aea01-371">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-372">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="aea01-373">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-374">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="aea01-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="aea01-375">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="aea01-376">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="aea01-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="aea01-377">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="aea01-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="aea01-378">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="aea01-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="aea01-379">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="aea01-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="aea01-380">指示使用者在移轉之後，與外部使用者再次共用內容）</span><span class="sxs-lookup"><span data-stu-id="aea01-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="aea01-381">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="aea01-382">SharePoint 線上遷移的 FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="aea01-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="aea01-383">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="aea01-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="aea01-384">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="aea01-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="aea01-385">您的責任</span><span class="sxs-lookup"><span data-stu-id="aea01-385">Your responsibilities</span></span>

<span data-ttu-id="aea01-386">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="aea01-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="aea01-387">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="aea01-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="aea01-388">你也要執行下列 SharePoint Online 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="aea01-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="aea01-389">使用您的移轉事件針對所有 SharePoint 小組網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="aea01-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="aea01-390">移轉至商務用 OneDrive</span><span class="sxs-lookup"><span data-stu-id="aea01-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="aea01-391">當您選擇使用 FastTrack 將您的檔案移轉到 商務用 OneDrive 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="aea01-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="aea01-392">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 商務用 OneDrive，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="aea01-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="aea01-393">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="aea01-393">You create and schedule your migration events.</span></span> <span data-ttu-id="aea01-394">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="aea01-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="aea01-395">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 商務用 OneDrive。</span><span class="sxs-lookup"><span data-stu-id="aea01-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

### <a name="considerations"></a><span data-ttu-id="aea01-396">考量</span><span class="sxs-lookup"><span data-stu-id="aea01-396">Considerations</span></span>

  - <span data-ttu-id="aea01-397">所有的移轉動作都受到 SharePoint Online 的配額限制。</span><span class="sxs-lookup"><span data-stu-id="aea01-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="aea01-398">如需詳細資訊，請參閱<a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint 限制</a>。</span><span class="sxs-lookup"><span data-stu-id="aea01-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="aea01-399">我們建議您將移轉的資料總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="aea01-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="aea01-400">FastTrack 只會移轉到使用中的 [商務用 OneDrive] 磁碟機。</span><span class="sxs-lookup"><span data-stu-id="aea01-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="aea01-401">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="aea01-401">Source environment details</span></span>

<span data-ttu-id="aea01-402">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="aea01-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="aea01-403">檔案共用 (支援 SMB 2.0+ 之裝置的 SMB 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="aea01-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="aea01-404">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="aea01-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="aea01-405">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="aea01-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="aea01-406">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="aea01-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="aea01-407">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="aea01-408"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="aea01-409"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="aea01-410"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="aea01-411"><strong>不能移轉什麼內容</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="aea01-412"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="aea01-413">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-414">文件</span><span class="sxs-lookup"><span data-stu-id="aea01-414">Documents</span></span> </li>
<li> <span data-ttu-id="aea01-415">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-416">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="aea01-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-417">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="aea01-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-418">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-419">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-420">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-420">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-421">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-421">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-422">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-422">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-423">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="aea01-424">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="aea01-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="aea01-425">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="aea01-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="aea01-426">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="aea01-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="aea01-427">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="aea01-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="aea01-428">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="aea01-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="aea01-429">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-430">舊版</span><span class="sxs-lookup"><span data-stu-id="aea01-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="aea01-431">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="aea01-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="aea01-432">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="aea01-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="aea01-433">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="aea01-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="aea01-434">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="aea01-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="aea01-435">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="aea01-436">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-437">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="aea01-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="aea01-438">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="aea01-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="aea01-439">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="aea01-440"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="aea01-441">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-442">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式 ，包括超過 10 MB 的檔案)</span><span class="sxs-lookup"><span data-stu-id="aea01-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="aea01-443">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-444">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-445">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-446">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-447">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-448">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-448">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-449">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-449">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-450">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-450">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-451">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="aea01-452">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="aea01-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="aea01-453">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="aea01-454">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="aea01-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="aea01-455">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="aea01-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="aea01-456">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-457">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-458">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="aea01-459">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="aea01-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="aea01-460">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-461">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="aea01-462">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-463">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="aea01-464">Google 相簿表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="aea01-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="aea01-465">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="aea01-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="aea01-466">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="aea01-467">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="aea01-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="aea01-468">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="aea01-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="aea01-469">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="aea01-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="aea01-470">共用磁碟機成員資格權限 (<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="aea01-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="aea01-471">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="aea01-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="aea01-472">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="aea01-473"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="aea01-474">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-475">文件</span><span class="sxs-lookup"><span data-stu-id="aea01-475">Documents</span></span> </li>
<li> <span data-ttu-id="aea01-476">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-477">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-478">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-479">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-480">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-481">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-481">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-482">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-482">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-483">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-483">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-484">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="aea01-485">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="aea01-486">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="aea01-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="aea01-487">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="aea01-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="aea01-488">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-489">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-490">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="aea01-491">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="aea01-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="aea01-492">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-493">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="aea01-494">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-495">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="aea01-496">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="aea01-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="aea01-497">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="aea01-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="aea01-498">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="aea01-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="aea01-499">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="aea01-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="aea01-500">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="aea01-501"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="aea01-502">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-503">文件</span><span class="sxs-lookup"><span data-stu-id="aea01-503">Documents</span></span> </li>
<li> <span data-ttu-id="aea01-504">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-505">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-506">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="aea01-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="aea01-507">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-508">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-509">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-509">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-510">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-510">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-511">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-511">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-512">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="aea01-513">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="aea01-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="aea01-514">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="aea01-515">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="aea01-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="aea01-516">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="aea01-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="aea01-517">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-518">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-519">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="aea01-520">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="aea01-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="aea01-521">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-522">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="aea01-523">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-524">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="aea01-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="aea01-525">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="aea01-526">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="aea01-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="aea01-527">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="aea01-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="aea01-528">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="aea01-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="aea01-529">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="aea01-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="aea01-530">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="aea01-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="aea01-531">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="aea01-532">商務用 OneDrive 遷移的 FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="aea01-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="aea01-533">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="aea01-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="aea01-534">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="aea01-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="aea01-535">您的責任</span><span class="sxs-lookup"><span data-stu-id="aea01-535">Your responsibilities</span></span>

<span data-ttu-id="aea01-536">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="aea01-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="aea01-537">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="aea01-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="aea01-538">你也要執行下列 [商務用 OneDrive] 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="aea01-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="aea01-539">使用您的移轉事件針對所有 [商務用 OneDrive] 網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="aea01-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="aea01-540">遷移至 Microsoft Teams 和 Microsoft 365 群組</span><span class="sxs-lookup"><span data-stu-id="aea01-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="aea01-541">當您選擇使用 FastTrack 將檔案遷移至 Microsoft Teams 和 Microsoft 365 群組時，我們會提供遷移指南和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="aea01-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="aea01-542">我們提供指引，協助您規劃遷移、設定來源環境及 Teams 和 Microsoft 365 群組，以及利用我們的資料移轉服務來遷移您的檔案。</span><span class="sxs-lookup"><span data-stu-id="aea01-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="aea01-543">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="aea01-543">You create and schedule your migration events.</span></span> <span data-ttu-id="aea01-544">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="aea01-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="aea01-545">當您的遷移事件完成時，您可以期望來源環境中適當排程與合格來源環境的檔案已遷移至 Teams 和 Microsoft 365 群組。</span><span class="sxs-lookup"><span data-stu-id="aea01-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="aea01-546">Teams 通道和 Microsoft 365 群組必須先由客戶預先布建，使用者才能將資料移轉至這些目的地類型。</span><span class="sxs-lookup"><span data-stu-id="aea01-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="aea01-547">Teams 和 Microsoft 365 群組會影響您對檔案目的地位置的許可權。</span><span class="sxs-lookup"><span data-stu-id="aea01-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="aea01-548">Teams 和 Microsoft 365 群組是為允許共同作業而建立的。</span><span class="sxs-lookup"><span data-stu-id="aea01-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="aea01-549">在遷移至那些目的地時，Teams 通道或 Microsoft 365 群組決定誰可以存取這些檔案。</span><span class="sxs-lookup"><span data-stu-id="aea01-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="aea01-550">FastTrack 在遷移期間，不會將使用者或群組新增至任何 Teams 通道或 Microsoft 365 群組的許可權。</span><span class="sxs-lookup"><span data-stu-id="aea01-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

### <a name="considerations"></a><span data-ttu-id="aea01-551">考量</span><span class="sxs-lookup"><span data-stu-id="aea01-551">Considerations</span></span>

- <span data-ttu-id="aea01-552">所有的移轉動作都受到 SharePoint Online 的配額限制。</span><span class="sxs-lookup"><span data-stu-id="aea01-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="aea01-553">如需詳細資訊，請參閱<a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint 限制</a>。</span><span class="sxs-lookup"><span data-stu-id="aea01-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="aea01-554">我們建議您將移轉的總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="aea01-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


### <a name="source-environment-details"></a><span data-ttu-id="aea01-555">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="aea01-555">Source environment details</span></span>

<span data-ttu-id="aea01-556">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="aea01-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="aea01-557">檔案共用 (支援 SMB 2.0+ 裝置的伺服器訊息區 (SMB) 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="aea01-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="aea01-558">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="aea01-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="aea01-559">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="aea01-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="aea01-560">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="aea01-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="aea01-561">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="aea01-562"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="aea01-563"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="aea01-564"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="aea01-565"><strong>不能移轉什麼內容</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="aea01-566"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="aea01-567">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-568">文件</span><span class="sxs-lookup"><span data-stu-id="aea01-568">Documents</span></span> </li>
<li> <span data-ttu-id="aea01-569">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-570">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="aea01-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-571">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="aea01-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-572">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-573">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-574">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-574">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-575">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-575">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-576">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-576">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-577">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="aea01-578">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="aea01-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="aea01-579">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="aea01-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="aea01-580">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="aea01-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="aea01-581">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="aea01-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="aea01-582">Microsoft 365 群組和/或 Microsoft Teams 通道會影響許可權。</span><span class="sxs-lookup"><span data-stu-id="aea01-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="aea01-583">若目的地為 Microsoft 365 群組或 Microsoft Teams 通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。</span><span class="sxs-lookup"><span data-stu-id="aea01-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="aea01-584">建議您不要在遷移至 Microsoft 365 群組或 Microsoft Teams 通道的檔案上遷移許可權。</span><span class="sxs-lookup"><span data-stu-id="aea01-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-585">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="aea01-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="aea01-586">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-587">舊版</span><span class="sxs-lookup"><span data-stu-id="aea01-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="aea01-588">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="aea01-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="aea01-589">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="aea01-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="aea01-590">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="aea01-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="aea01-591">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="aea01-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="aea01-592">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="aea01-593">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-594">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="aea01-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="aea01-595">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="aea01-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="aea01-596">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="aea01-597"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="aea01-598">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-599">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式 ，包括超過 10 MB 的檔案)</span><span class="sxs-lookup"><span data-stu-id="aea01-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="aea01-600">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-601">使用者層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="aea01-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-602">群組層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="aea01-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-603">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-604">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-605">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-605">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-606">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-606">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-607">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-607">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-608">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="aea01-609">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="aea01-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="aea01-610">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="aea01-611">\* 許可權受到 Microsoft 365 群組和/或 Microsoft Teams 通道影響。</span><span class="sxs-lookup"><span data-stu-id="aea01-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="aea01-612">若目的地為 Microsoft 365 群組或 Microsoft Teams 通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。</span><span class="sxs-lookup"><span data-stu-id="aea01-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="aea01-613">建議您不要在遷移至 Microsoft 365 群組或 Microsoft Teams 通道的檔案上遷移許可權。</span><span class="sxs-lookup"><span data-stu-id="aea01-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="aea01-614">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="aea01-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="aea01-615">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="aea01-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="aea01-616">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-617">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-618">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="aea01-619">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="aea01-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="aea01-620">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-621">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="aea01-622">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-623">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="aea01-624">Google 相簿表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="aea01-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="aea01-625">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="aea01-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="aea01-626">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="aea01-627">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="aea01-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="aea01-628">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="aea01-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="aea01-629">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="aea01-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="aea01-630">共用磁碟機成員資格權限 (<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="aea01-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="aea01-631">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="aea01-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="aea01-632">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="aea01-633"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="aea01-634">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-635">文件</span><span class="sxs-lookup"><span data-stu-id="aea01-635">Documents</span></span> </li>
<li> <span data-ttu-id="aea01-636">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-637">使用者層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="aea01-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-638">群組層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="aea01-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-639">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-640">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-641">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-641">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-642">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-642">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-643">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-643">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-644">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="aea01-645">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="aea01-646">方框附注 (轉換為 Word 檔案格式) </span><span class="sxs-lookup"><span data-stu-id="aea01-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="aea01-647">\* 許可權受到 Microsoft 365 群組和/或 Microsoft Teams 通道影響。</span><span class="sxs-lookup"><span data-stu-id="aea01-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="aea01-648">若目的地為 Microsoft 365 群組或 Microsoft Teams 通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。</span><span class="sxs-lookup"><span data-stu-id="aea01-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="aea01-649">建議您不要在遷移至 Microsoft 365 群組或 Microsoft Teams 通道的檔案上遷移許可權。</span><span class="sxs-lookup"><span data-stu-id="aea01-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="aea01-650">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="aea01-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="aea01-651">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="aea01-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="aea01-652">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-653">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-654">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="aea01-655">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="aea01-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="aea01-656">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-657">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="aea01-658">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-659">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="aea01-660">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="aea01-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="aea01-661">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="aea01-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="aea01-662">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="aea01-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="aea01-663">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="aea01-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="aea01-664">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="aea01-665"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="aea01-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="aea01-666">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="aea01-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="aea01-667">文件</span><span class="sxs-lookup"><span data-stu-id="aea01-667">Documents</span></span> </li>
<li> <span data-ttu-id="aea01-668">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="aea01-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="aea01-669">使用者層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="aea01-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-670">群組層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="aea01-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="aea01-671">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="aea01-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="aea01-672">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="aea01-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="aea01-673">建立日期</span><span class="sxs-lookup"><span data-stu-id="aea01-673">Created date</span></span> </li>
<li> <span data-ttu-id="aea01-674">修改日期</span><span class="sxs-lookup"><span data-stu-id="aea01-674">Modified date</span></span> </li>
<li> <span data-ttu-id="aea01-675">建立者</span><span class="sxs-lookup"><span data-stu-id="aea01-675">Created by</span></span> </li>
<li> <span data-ttu-id="aea01-676">上次修改者</span><span class="sxs-lookup"><span data-stu-id="aea01-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="aea01-677">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="aea01-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="aea01-678">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="aea01-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="aea01-679">\* 許可權受到 Microsoft 365 群組和/或 Microsoft Teams 通道影響。</span><span class="sxs-lookup"><span data-stu-id="aea01-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="aea01-680">若目的地為 Microsoft 365 群組或 Microsoft Teams 通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。</span><span class="sxs-lookup"><span data-stu-id="aea01-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="aea01-681">建議您不要在遷移至 Microsoft 365 群組或 Microsoft Teams 通道的檔案上遷移許可權。</span><span class="sxs-lookup"><span data-stu-id="aea01-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="aea01-682">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="aea01-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="aea01-683">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="aea01-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="aea01-684">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-685">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="aea01-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="aea01-686">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="aea01-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="aea01-687">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="aea01-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="aea01-688">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="aea01-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="aea01-689">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="aea01-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="aea01-690">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="aea01-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="aea01-691">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="aea01-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="aea01-692">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="aea01-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="aea01-693">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="aea01-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="aea01-694">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="aea01-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="aea01-695">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="aea01-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="aea01-696">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="aea01-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="aea01-697">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="aea01-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="aea01-698">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="aea01-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="aea01-699">FastTrack Microsoft Teams 和 Microsoft 365 群組遷移的責任</span><span class="sxs-lookup"><span data-stu-id="aea01-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="aea01-700">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="aea01-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="aea01-701">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="aea01-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="aea01-702">您的責任</span><span class="sxs-lookup"><span data-stu-id="aea01-702">Your responsibilities</span></span> 

<span data-ttu-id="aea01-703">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="aea01-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="aea01-704">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="aea01-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="aea01-705">您也可以針對 Microsoft Teams 和 Microsoft 365 群組遷移執行下列活動：</span><span class="sxs-lookup"><span data-stu-id="aea01-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="aea01-706">將所有 Microsoft Teams 通道和 Microsoft 365 群組布建為遷移事件的目標。</span><span class="sxs-lookup"><span data-stu-id="aea01-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="aea01-707">FastTrack 未預先布建 Microsoft Teams 通道或 Microsoft 365 群組。</span><span class="sxs-lookup"><span data-stu-id="aea01-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="aea01-708">FastTrack 不會將使用者或群組新增至 Microsoft Teams 通道或 Microsoft 365 群組。</span><span class="sxs-lookup"><span data-stu-id="aea01-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="aea01-709">您必須先將使用者或群組新增至所有 Microsoft Teams 通道和 Microsoft 365 群組，再將資料移轉至這些目的地，這樣使用者才能存取這些新遷移的檔。</span><span class="sxs-lookup"><span data-stu-id="aea01-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>