---
title: 資料移轉
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。 我們可以提供的協助類型取決於您的 Office 365 授權數量。
ms.openlocfilehash: 8d74a288291907db22213f317ce8e89923590907
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996252"
---
# <a name="data-migration"></a><span data-ttu-id="8d3da-104">資料移轉</span><span class="sxs-lookup"><span data-stu-id="8d3da-104">Data Migration</span></span>

<span data-ttu-id="8d3da-105">FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。</span><span class="sxs-lookup"><span data-stu-id="8d3da-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="8d3da-106">我們提供的協助類型取決於您的 Office 365 授權數量：</span><span class="sxs-lookup"><span data-stu-id="8d3da-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="8d3da-107">**針對有 150-499 個授權的 Microsoft Office 365 租用戶**：FastTrack 僅提供移轉指引；由您負責執行資料移轉。</span><span class="sxs-lookup"><span data-stu-id="8d3da-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="8d3da-108">我們會透過可協助您規劃及使用免費工具的文件，引導您執行自助移轉。</span><span class="sxs-lookup"><span data-stu-id="8d3da-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="8d3da-109">**針對具有 500 個或更多授權數量的 Microsoft Office 365 租用戶**：FastTrack 會提供移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8d3da-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="8d3da-110">我們會提供指引以協助規劃您的移轉事件、設定您的來源環境和 Office 365 租用戶，並充分利用我們的資料移轉服務來移轉您的資料。</span><span class="sxs-lookup"><span data-stu-id="8d3da-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="8d3da-111">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="8d3da-111">You create and schedule your migration events.</span></span> <span data-ttu-id="8d3da-112">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="8d3da-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="8d3da-113">如果您在 9/1/2017 之前已購買或續約ㄧ個商業方案，您只需使用 150 個授權，就能獲得資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="8d3da-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="8d3da-114">針對教育方案，只有您的付費教職員授權符合使用資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="8d3da-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="8d3da-115">考量</span><span class="sxs-lookup"><span data-stu-id="8d3da-115">Considerations</span></span>

  - <span data-ttu-id="8d3da-116">您的來源環境必須符合特定期望條件，才能將資料移轉至 Microsoft Office 365。</span><span class="sxs-lookup"><span data-stu-id="8d3da-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="8d3da-117">如需其它與 Exchange、SharePoint、和 [商務用 OneDrive] 適用的來源環境期望，請參照 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="8d3da-118">為提供資料移轉服務，我們需要您的來源環境及 Office 365 租用戶的適當存取權和權限。</span><span class="sxs-lookup"><span data-stu-id="8d3da-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="8d3da-119">我們的資料移轉服務既不是以受特殊法律、也不是受監管要求而設計或使用的。</span><span class="sxs-lookup"><span data-stu-id="8d3da-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="8d3da-120">當我們移轉您的資料時，可以將資料在任何我們進行設施維護的地方進行移轉、儲存及處理的動作（除非您的 FastTrack 移轉專案有提供另外的位置）。</span><span class="sxs-lookup"><span data-stu-id="8d3da-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="8d3da-121">我們不能保證郵件或檔案移轉的速度。</span><span class="sxs-lookup"><span data-stu-id="8d3da-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="8d3da-122">無法預料的問題（例如在來源環境中有無法讀取或已損毀的項目）可能會使我們無法移轉您的某些資料項目。</span><span class="sxs-lookup"><span data-stu-id="8d3da-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="8d3da-123">在我們控制範圍之外的外部因素（像是第三方應用程式開發介面 (APIs) 出現變更）會導致我們的資料移轉服務出現變更、延遲、或暫停的情況。</span><span class="sxs-lookup"><span data-stu-id="8d3da-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="8d3da-124">移轉服務的狀態</span><span class="sxs-lookup"><span data-stu-id="8d3da-124">Migration service availability</span></span>

  - <span data-ttu-id="8d3da-125">**針對商業及英國政府客戶：** 我們提供每天 24 小時、每周 7 天（24x7）的全年無休資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8d3da-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="8d3da-126">**針對美國政府/DOD 客戶：** 我們提供每天 24 小時、每周 5 個工作天（24x5）的資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8d3da-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="8d3da-127">移轉至 Exchange Online</span><span class="sxs-lookup"><span data-stu-id="8d3da-127">Migration to Exchange Online</span></span>

<span data-ttu-id="8d3da-128">當您選擇使用 FastTrack 將您的電子郵件移轉到 Exchange Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8d3da-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8d3da-129">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 Exchange Online，並充分利用我們的資料移轉服務來移轉您的信箱。</span><span class="sxs-lookup"><span data-stu-id="8d3da-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="8d3da-130">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="8d3da-130">You create and schedule your migration events.</span></span> <span data-ttu-id="8d3da-131">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="8d3da-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8d3da-132">當您的移轉事件完成後，您可以預期在您的來源環境中，郵件經適當排程和從合格來源信箱移轉到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="8d3da-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="8d3da-133">考量</span><span class="sxs-lookup"><span data-stu-id="8d3da-133">Considerations</span></span>

  - <span data-ttu-id="8d3da-134">在進行移轉之前，您必須完成適用於 Exchange Online 的 FastTrack 核心上線動作；</span><span class="sxs-lookup"><span data-stu-id="8d3da-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="8d3da-135">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="8d3da-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8d3da-136">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="8d3da-137">FastTrack 只會移轉至使用中的 Office 365 信箱。</span><span class="sxs-lookup"><span data-stu-id="8d3da-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="8d3da-138">如果您想要從內部部署的 Exchange 環境將資料移轉出來，您必須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="8d3da-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8d3da-139">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="8d3da-140">每個來源環境都必須為其中各自相應的產品使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="8d3da-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="8d3da-141">存在於內部部署 Active Directory Domain Services 中的通訊群組清單（*MailEnabledGroup* 物件）和外部連絡人（*MailEnabledContact* 物件）並不屬於信箱資料移轉的一部分。</span><span class="sxs-lookup"><span data-stu-id="8d3da-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="8d3da-142">不過，您可以使用 Microsoft Azure Active Directory (Azure AD) Connect 進行同步處理。</span><span class="sxs-lookup"><span data-stu-id="8d3da-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="8d3da-143">來源環境</span><span class="sxs-lookup"><span data-stu-id="8d3da-143">Source environments</span></span>

<span data-ttu-id="8d3da-144">我們的資料移轉服務會將資料從這些來源環境中移轉出來：</span><span class="sxs-lookup"><span data-stu-id="8d3da-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="8d3da-145">含有單一個或多個 Exchange 組織的單一或多個 Active Directory 樹系 (每ㄧ個 Exchange 郵件系統都必須使用 Exchange 2010 或更新的版本)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="8d3da-146">單一個具 IMAP 功能的電子郵件環境。</span><span class="sxs-lookup"><span data-stu-id="8d3da-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="8d3da-147">G Suite 環境 (僅限 Gmail、連絡人和Outlook 行事曆)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="8d3da-148">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8d3da-149"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8d3da-150"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8d3da-151"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="8d3da-152"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8d3da-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="8d3da-154">
<strong>附注：</strong> 如需內部部署 Exchange 相依性，請參閱 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">混合部署必要條件</span></a>。</span><span class="sxs-lookup"><span data-stu-id="8d3da-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="8d3da-155">混合部署移轉</span><span class="sxs-lookup"><span data-stu-id="8d3da-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="8d3da-156">電子郵件</span><span class="sxs-lookup"><span data-stu-id="8d3da-156">Emails</span></span></li>
<li><span data-ttu-id="8d3da-157">伺服器端信箱規則</span><span class="sxs-lookup"><span data-stu-id="8d3da-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="8d3da-158">委派</span><span class="sxs-lookup"><span data-stu-id="8d3da-158">Delegates</span></span></li>
<li><span data-ttu-id="8d3da-159">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="8d3da-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8d3da-160">行事曆</span><span class="sxs-lookup"><span data-stu-id="8d3da-160">Calendar</span></span> </li>
<li> <span data-ttu-id="8d3da-161">工作</span><span class="sxs-lookup"><span data-stu-id="8d3da-161">Tasks</span></span> </li>
<li> <span data-ttu-id="8d3da-162">受版權管理的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8d3da-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="8d3da-163">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8d3da-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="8d3da-164">簽章</span><span class="sxs-lookup"><span data-stu-id="8d3da-164">Signatures</span></span> </li>
<li> <span data-ttu-id="8d3da-165">隨著使用者信箱移轉的個人封存</span><span class="sxs-lookup"><span data-stu-id="8d3da-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="8d3da-166">可復原的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8d3da-167">公用資料夾</span><span class="sxs-lookup"><span data-stu-id="8d3da-167">Public folders</span></span> </li>
<li> <span data-ttu-id="8d3da-168">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8d3da-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8d3da-169">日誌封存或任何協力廠商封存解決方案</span><span class="sxs-lookup"><span data-stu-id="8d3da-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="8d3da-170">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8d3da-171">從個人存放區資料表 (PST) 檔案封存的資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="8d3da-172">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8d3da-173">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="8d3da-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="8d3da-174">用戶端信箱規則</span><span class="sxs-lookup"><span data-stu-id="8d3da-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8d3da-175"><strong>G Suite 環境 (僅限 Gmail、連絡人和行事曆)</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="8d3da-176">
<strong>附注：</strong> 您的 G 套件環境必須符合 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">執行 G Suite 遷移</a>中所述的必要條件。</span><span class="sxs-lookup"><span data-stu-id="8d3da-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="8d3da-177">轉換或分段</span><span class="sxs-lookup"><span data-stu-id="8d3da-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-178">電子郵件</span><span class="sxs-lookup"><span data-stu-id="8d3da-178">Emails</span></span> </li>
<li> <span data-ttu-id="8d3da-179">信箱連絡人 (每個連絡人最多可移轉 3 個電子郵件地址)</span><span class="sxs-lookup"><span data-stu-id="8d3da-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="8d3da-180">行事曆</span><span class="sxs-lookup"><span data-stu-id="8d3da-180">Calendar</span></span> </li>
<li> <span data-ttu-id="8d3da-181">標籤</span><span class="sxs-lookup"><span data-stu-id="8d3da-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8d3da-182">規則</span><span class="sxs-lookup"><span data-stu-id="8d3da-182">Rules</span></span> </li>
<li> <span data-ttu-id="8d3da-183">委派</span><span class="sxs-lookup"><span data-stu-id="8d3da-183">Delegates</span></span> </li>
<li> <span data-ttu-id="8d3da-184">簽章</span><span class="sxs-lookup"><span data-stu-id="8d3da-184">Signatures</span></span> </li>
<li> <span data-ttu-id="8d3da-185">工作</span><span class="sxs-lookup"><span data-stu-id="8d3da-185">Tasks</span></span> </li>
<li> <span data-ttu-id="8d3da-186">任何超過郵件大小限制的電子郵件或附件</span><span class="sxs-lookup"><span data-stu-id="8d3da-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8d3da-187">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8d3da-188">從 PST 檔案或任何協力廠商封存解決方案 (例如 Google Vault) 封存的資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="8d3da-189">權限管理或加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8d3da-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="8d3da-190">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8d3da-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="8d3da-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="8d3da-192">Google Groups</span><span class="sxs-lookup"><span data-stu-id="8d3da-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="8d3da-193">資源信箱</span><span class="sxs-lookup"><span data-stu-id="8d3da-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="8d3da-194">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="8d3da-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="8d3da-195">假期設定和自動回覆設定</span><span class="sxs-lookup"><span data-stu-id="8d3da-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="8d3da-196">共用行事曆、雲端附件、Google Hangout 連結和活動色彩</span><span class="sxs-lookup"><span data-stu-id="8d3da-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="8d3da-197">\*\*可移轉儲存為標籤的 Hangout 交談。</span><span class="sxs-lookup"><span data-stu-id="8d3da-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8d3da-198"><strong>IMAP4 來源 (例如 Domino、GroupWise 和 Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="8d3da-199">使用原生 IMAP4 工具進行的移轉</span><span class="sxs-lookup"><span data-stu-id="8d3da-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="8d3da-200">電子郵件</span><span class="sxs-lookup"><span data-stu-id="8d3da-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="8d3da-201">規則</span><span class="sxs-lookup"><span data-stu-id="8d3da-201">Rules</span></span> </li>
<li> <span data-ttu-id="8d3da-202">委派</span><span class="sxs-lookup"><span data-stu-id="8d3da-202">Delegates</span></span> </li>
<li> <span data-ttu-id="8d3da-203">通訊群組清單</span><span class="sxs-lookup"><span data-stu-id="8d3da-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="8d3da-204">外部連絡人</span><span class="sxs-lookup"><span data-stu-id="8d3da-204">External contacts</span></span> </li>
<li> <span data-ttu-id="8d3da-205">擁有郵件功能的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="8d3da-206">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8d3da-207">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="8d3da-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8d3da-208">行事曆</span><span class="sxs-lookup"><span data-stu-id="8d3da-208">Calendar</span></span> </li>
<li> <span data-ttu-id="8d3da-209">簽章</span><span class="sxs-lookup"><span data-stu-id="8d3da-209">Signatures</span></span> </li>
<li> <span data-ttu-id="8d3da-210">工作</span><span class="sxs-lookup"><span data-stu-id="8d3da-210">Tasks</span></span> </li>
<li> <span data-ttu-id="8d3da-211">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8d3da-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8d3da-212">封存資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-212">Archive data</span></span> </li>
<li> <span data-ttu-id="8d3da-213">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="8d3da-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="8d3da-214">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8d3da-215">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="8d3da-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="8d3da-216">Exchange Online 遷移的 FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="8d3da-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="8d3da-217">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8d3da-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8d3da-218">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="8d3da-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8d3da-219">我們的 FastTrack 專家也會執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="8d3da-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="8d3da-220">可提供指引，以便協助您啟用在來源環境與 Exchange Online 之間並立的 SMTP 郵件路由傳送（如果適用的話）。</span><span class="sxs-lookup"><span data-stu-id="8d3da-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8d3da-221">您的責任</span><span class="sxs-lookup"><span data-stu-id="8d3da-221">Your responsibilities</span></span>

<span data-ttu-id="8d3da-222">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8d3da-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8d3da-223">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="8d3da-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8d3da-224">你也要執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="8d3da-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="8d3da-225">完成適用於 Exchange Online 的 FastTrack 核心上線動作。</span><span class="sxs-lookup"><span data-stu-id="8d3da-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="8d3da-226">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="8d3da-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8d3da-227">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="8d3da-228">依 Office 365 指引安裝適當層級的用戶端軟體。</span><span class="sxs-lookup"><span data-stu-id="8d3da-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="8d3da-229">如需詳細資訊，請參閱 [現代化工作場所](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="8d3da-230">如果您想要從內部部署的 Exchange 環境將資料移轉出來，須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="8d3da-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8d3da-231">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="8d3da-232">如果適用的話，每個來源環境都必須使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="8d3da-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="8d3da-233">若適用的話，在您的來源環境和 Exchange Online 中，設定和驗證 SMTP 郵件路由傳送共存。</span><span class="sxs-lookup"><span data-stu-id="8d3da-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="8d3da-234">請確定您的來源信箱容量大小未超過目標信箱配額。</span><span class="sxs-lookup"><span data-stu-id="8d3da-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="8d3da-235">視來源平台而定，您可能需要對來源資料限制在目標信箱配額的 85%。</span><span class="sxs-lookup"><span data-stu-id="8d3da-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="8d3da-236">視需要移轉用戶端資料。</span><span class="sxs-lookup"><span data-stu-id="8d3da-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="8d3da-237">這包含、但不限於本機通訊錄、本機 PST 檔案中的資料、Outlook 規則和本機 Outlook 設定。</span><span class="sxs-lookup"><span data-stu-id="8d3da-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="8d3da-238">協助使用者修正用戶端的遷移問題。</span><span class="sxs-lookup"><span data-stu-id="8d3da-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="8d3da-239">移轉至 SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="8d3da-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="8d3da-240">當您選擇使用 FastTrack 將您的檔案移轉到 SharePoint Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8d3da-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8d3da-241">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 SharePoint Online，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="8d3da-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8d3da-242">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="8d3da-242">You create and schedule your migration events.</span></span> <span data-ttu-id="8d3da-243">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="8d3da-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8d3da-244">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 SharePoint Online。</span><span class="sxs-lookup"><span data-stu-id="8d3da-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="8d3da-245">考量</span><span class="sxs-lookup"><span data-stu-id="8d3da-245">Considerations</span></span>

 - <span data-ttu-id="8d3da-246">所有的移轉動作都受到 SharePoint Online 的配額限制。</span><span class="sxs-lookup"><span data-stu-id="8d3da-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="8d3da-247">如需詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint 限制</a> 。</span><span class="sxs-lookup"><span data-stu-id="8d3da-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="8d3da-248">我們建議您將移轉的總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="8d3da-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8d3da-249">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-249">Source environment details</span></span>

<span data-ttu-id="8d3da-250">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="8d3da-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8d3da-251">檔案共用 (支援 SMB 2.0+ 裝置的伺服器訊息區 (SMB) 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8d3da-252">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8d3da-253">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8d3da-254">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8d3da-255">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8d3da-256"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8d3da-257"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8d3da-258"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8d3da-259"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8d3da-260"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8d3da-261">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-262">文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-262">Documents</span></span> </li>
<li> <span data-ttu-id="8d3da-263">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-264">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="8d3da-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-265">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="8d3da-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-266">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-267">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-268">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-268">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-269">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-269">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-270">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-270">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-271">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="8d3da-272">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="8d3da-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8d3da-273">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="8d3da-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8d3da-274">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="8d3da-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8d3da-275">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="8d3da-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-276">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="8d3da-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8d3da-277">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-278">舊版</span><span class="sxs-lookup"><span data-stu-id="8d3da-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="8d3da-279">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="8d3da-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8d3da-280">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="8d3da-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8d3da-281">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="8d3da-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8d3da-282">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="8d3da-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8d3da-283">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8d3da-284">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-285">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="8d3da-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8d3da-286">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="8d3da-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8d3da-287">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8d3da-288"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8d3da-289">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-290">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式) ，包括超過 10 MB 的檔案。</span><span class="sxs-lookup"><span data-stu-id="8d3da-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="8d3da-291">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-292">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-293">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-294">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-295">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-296">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-296">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-297">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-297">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-298">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-298">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-299">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8d3da-300">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="8d3da-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8d3da-301">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8d3da-302">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8d3da-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8d3da-303">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="8d3da-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8d3da-304">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-305">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-306">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8d3da-307">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8d3da-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8d3da-308">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-309">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="8d3da-310">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-311">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8d3da-312">Google 相簿、表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="8d3da-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8d3da-313">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="8d3da-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8d3da-314">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8d3da-315">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="8d3da-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8d3da-316">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8d3da-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8d3da-317">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8d3da-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8d3da-318">共用磁碟機成員權限（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="8d3da-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8d3da-319">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="8d3da-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8d3da-320">標記為受限或未 copyable 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="8d3da-321">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8d3da-322"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8d3da-323">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-324">文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-324">Documents</span></span> </li>
<li> <span data-ttu-id="8d3da-325">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-326">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-327">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-328">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-329">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-330">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-330">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-331">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-331">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-332">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-332">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-333">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8d3da-334">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="8d3da-335">方框附注 (轉換為 Word 檔案格式) </span><span class="sxs-lookup"><span data-stu-id="8d3da-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8d3da-336">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8d3da-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8d3da-337">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="8d3da-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8d3da-338">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-339">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-340">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8d3da-341">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8d3da-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8d3da-342">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-343">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="8d3da-344">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-345">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8d3da-346">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="8d3da-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8d3da-347">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8d3da-348">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8d3da-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8d3da-349">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8d3da-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8d3da-350">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8d3da-351"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8d3da-352">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-353">文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-353">Documents</span></span> </li>
<li> <span data-ttu-id="8d3da-354">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-355">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-356">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-357">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-358">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-359">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-359">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-360">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-360">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-361">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-361">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-362">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8d3da-363">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8d3da-364">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8d3da-365">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8d3da-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8d3da-366">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="8d3da-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8d3da-367">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-368">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-369">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8d3da-370">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8d3da-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8d3da-371">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-372">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="8d3da-373">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-374">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="8d3da-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8d3da-375">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8d3da-376">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="8d3da-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8d3da-377">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="8d3da-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8d3da-378">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8d3da-379">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8d3da-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8d3da-380">指示使用者在移轉之後，與外部使用者再次共用內容）</span><span class="sxs-lookup"><span data-stu-id="8d3da-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="8d3da-381">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="8d3da-382">SharePoint 線上遷移的 FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="8d3da-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="8d3da-383">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8d3da-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8d3da-384">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="8d3da-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8d3da-385">您的責任</span><span class="sxs-lookup"><span data-stu-id="8d3da-385">Your responsibilities</span></span>

<span data-ttu-id="8d3da-386">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8d3da-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8d3da-387">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="8d3da-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="8d3da-388">你也要執行下列 SharePoint Online 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="8d3da-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="8d3da-389">使用您的移轉事件針對所有 SharePoint 小組網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="8d3da-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="8d3da-390">移轉至商務用 OneDrive</span><span class="sxs-lookup"><span data-stu-id="8d3da-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="8d3da-391">當您選擇使用 FastTrack 將您的檔案移轉到 商務用 OneDrive 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8d3da-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8d3da-392">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 商務用 OneDrive，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="8d3da-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8d3da-393">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="8d3da-393">You create and schedule your migration events.</span></span> <span data-ttu-id="8d3da-394">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="8d3da-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8d3da-395">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 商務用 OneDrive。</span><span class="sxs-lookup"><span data-stu-id="8d3da-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="8d3da-396">考量</span><span class="sxs-lookup"><span data-stu-id="8d3da-396">Considerations</span></span>

  - <span data-ttu-id="8d3da-397">所有的移轉動作都受到 SharePoint Online 的配額限制。</span><span class="sxs-lookup"><span data-stu-id="8d3da-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="8d3da-398">如需詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint 限制</a> 。</span><span class="sxs-lookup"><span data-stu-id="8d3da-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="8d3da-399">我們建議您將移轉的資料總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="8d3da-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="8d3da-400">FastTrack 只會移轉到使用中的 [商務用 OneDrive] 磁碟機。</span><span class="sxs-lookup"><span data-stu-id="8d3da-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8d3da-401">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-401">Source environment details</span></span>

<span data-ttu-id="8d3da-402">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="8d3da-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8d3da-403">檔案共用 (支援 SMB 2.0+ 之裝置的 SMB 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8d3da-404">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8d3da-405">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8d3da-406">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8d3da-407">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="8d3da-408"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="8d3da-409"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="8d3da-410"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8d3da-411"><strong>不能移轉什麼內容</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8d3da-412"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8d3da-413">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-414">文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-414">Documents</span></span> </li>
<li> <span data-ttu-id="8d3da-415">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-416">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="8d3da-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-417">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="8d3da-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-418">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-419">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-420">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-420">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-421">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-421">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-422">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-422">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-423">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="8d3da-424">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="8d3da-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8d3da-425">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="8d3da-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8d3da-426">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="8d3da-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8d3da-427">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="8d3da-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="8d3da-428">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="8d3da-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8d3da-429">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-430">舊版</span><span class="sxs-lookup"><span data-stu-id="8d3da-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="8d3da-431">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="8d3da-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8d3da-432">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="8d3da-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8d3da-433">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="8d3da-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8d3da-434">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="8d3da-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8d3da-435">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8d3da-436">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-437">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="8d3da-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8d3da-438">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="8d3da-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8d3da-439">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8d3da-440"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8d3da-441">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-442">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式 ，包括超過 10 MB 的檔案)</span><span class="sxs-lookup"><span data-stu-id="8d3da-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="8d3da-443">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-444">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-445">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-446">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-447">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-448">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-448">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-449">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-449">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-450">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-450">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-451">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8d3da-452">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="8d3da-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8d3da-453">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8d3da-454">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8d3da-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8d3da-455">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="8d3da-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8d3da-456">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-457">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-458">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8d3da-459">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8d3da-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8d3da-460">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-461">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="8d3da-462">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-463">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8d3da-464">Google 相簿表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="8d3da-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8d3da-465">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="8d3da-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8d3da-466">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8d3da-467">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="8d3da-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8d3da-468">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8d3da-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8d3da-469">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8d3da-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8d3da-470">共用磁碟機成員資格權限 (<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="8d3da-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8d3da-471">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="8d3da-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8d3da-472">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8d3da-473"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8d3da-474">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-475">文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-475">Documents</span></span> </li>
<li> <span data-ttu-id="8d3da-476">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-477">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-478">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-479">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-480">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-481">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-481">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-482">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-482">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-483">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-483">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-484">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8d3da-485">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8d3da-486">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8d3da-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8d3da-487">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="8d3da-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8d3da-488">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-489">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-490">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8d3da-491">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8d3da-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8d3da-492">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-493">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="8d3da-494">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-495">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8d3da-496">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="8d3da-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8d3da-497">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8d3da-498">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8d3da-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8d3da-499">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8d3da-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8d3da-500">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8d3da-501"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8d3da-502">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-503">文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-503">Documents</span></span> </li>
<li> <span data-ttu-id="8d3da-504">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-505">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-506">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-507">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-508">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-509">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-509">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-510">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-510">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-511">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-511">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-512">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8d3da-513">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8d3da-514">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8d3da-515">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8d3da-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8d3da-516">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="8d3da-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8d3da-517">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-518">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-519">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8d3da-520">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8d3da-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8d3da-521">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-522">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="8d3da-523">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-524">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="8d3da-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8d3da-525">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8d3da-526">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="8d3da-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8d3da-527">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="8d3da-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8d3da-528">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8d3da-529">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8d3da-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8d3da-530">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8d3da-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8d3da-531">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="8d3da-532">OneDrive 商務遷移的 FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="8d3da-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="8d3da-533">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8d3da-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8d3da-534">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="8d3da-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8d3da-535">您的責任</span><span class="sxs-lookup"><span data-stu-id="8d3da-535">Your responsibilities</span></span>

<span data-ttu-id="8d3da-536">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8d3da-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8d3da-537">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="8d3da-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8d3da-538">你也要執行下列 [商務用 OneDrive] 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="8d3da-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="8d3da-539">使用您的移轉事件針對所有 [商務用 OneDrive] 網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="8d3da-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="8d3da-540">遷移至 Microsoft 團隊和 Microsoft 365 群組</span><span class="sxs-lookup"><span data-stu-id="8d3da-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="8d3da-541">當您選擇使用 FastTrack 將檔案遷移至 Microsoft 團隊和 Microsoft 365 群組時，我們會提供遷移指南和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="8d3da-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8d3da-542">我們提供的指導可協助您規劃遷移、設定來源環境和團隊和 Microsoft 365 群組，並利用我們的資料移轉服務來遷移您的檔案。</span><span class="sxs-lookup"><span data-stu-id="8d3da-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8d3da-543">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="8d3da-543">You create and schedule your migration events.</span></span> <span data-ttu-id="8d3da-544">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="8d3da-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8d3da-545">當您的遷移事件完成時，您可以指望適當排程的檔案和來源環境的合格來源，已遷移到小組和 Microsoft 365 群組。</span><span class="sxs-lookup"><span data-stu-id="8d3da-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="8d3da-546">小組通道和 Microsoft 365 群組必須先由客戶預先布建，使用者才能將資料移轉至這些目的地類型。</span><span class="sxs-lookup"><span data-stu-id="8d3da-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="8d3da-547">小組和 Microsoft 365 群組會影響您對檔案目的地位置的許可權。</span><span class="sxs-lookup"><span data-stu-id="8d3da-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="8d3da-548">小組和 Microsoft 365 群組是為允許共同作業而建立的。</span><span class="sxs-lookup"><span data-stu-id="8d3da-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="8d3da-549">「小組頻道」或「Microsoft 365 群組」會決定在遷移至這些目的地時，誰可以存取這些檔案。</span><span class="sxs-lookup"><span data-stu-id="8d3da-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="8d3da-550">FastTrack 在遷移期間，不會將使用者或群組新增至任何小組通道或 Microsoft 365 群組的許可權。</span><span class="sxs-lookup"><span data-stu-id="8d3da-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="8d3da-551">考量</span><span class="sxs-lookup"><span data-stu-id="8d3da-551">Considerations</span></span>

- <span data-ttu-id="8d3da-552">所有的移轉動作都受到 SharePoint Online 的配額限制。</span><span class="sxs-lookup"><span data-stu-id="8d3da-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="8d3da-553">如需詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint 限制</a> 。</span><span class="sxs-lookup"><span data-stu-id="8d3da-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="8d3da-554">我們建議您將移轉的總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="8d3da-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="8d3da-555">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-555">Source environment details</span></span>

<span data-ttu-id="8d3da-556">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="8d3da-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="8d3da-557">檔案共用 (支援 SMB 2.0+ 裝置的伺服器訊息區 (SMB) 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="8d3da-558">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="8d3da-559">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="8d3da-560">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="8d3da-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="8d3da-561">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="8d3da-562"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="8d3da-563"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="8d3da-564"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8d3da-565"><strong>不能移轉什麼內容</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8d3da-566"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8d3da-567">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-568">文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-568">Documents</span></span> </li>
<li> <span data-ttu-id="8d3da-569">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-570">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="8d3da-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-571">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="8d3da-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-572">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-573">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-574">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-574">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-575">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-575">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-576">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-576">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-577">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="8d3da-578">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="8d3da-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8d3da-579">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="8d3da-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8d3da-580">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="8d3da-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8d3da-581">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="8d3da-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="8d3da-582">Microsoft 365 群組和/或 Microsoft 小組通道會影響許可權。</span><span class="sxs-lookup"><span data-stu-id="8d3da-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="8d3da-583">若目的地是 Microsoft 365 群組或 Microsoft 團隊通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。</span><span class="sxs-lookup"><span data-stu-id="8d3da-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="8d3da-584">建議您不要在遷移至 Microsoft 365 群組或 Microsoft 團隊管道的檔案上遷移許可權。</span><span class="sxs-lookup"><span data-stu-id="8d3da-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-585">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="8d3da-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8d3da-586">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-587">舊版</span><span class="sxs-lookup"><span data-stu-id="8d3da-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="8d3da-588">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="8d3da-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8d3da-589">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="8d3da-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8d3da-590">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="8d3da-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8d3da-591">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="8d3da-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8d3da-592">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8d3da-593">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-594">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="8d3da-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8d3da-595">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="8d3da-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8d3da-596">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8d3da-597"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8d3da-598">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-599">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式 ，包括超過 10 MB 的檔案)</span><span class="sxs-lookup"><span data-stu-id="8d3da-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="8d3da-600">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-601">使用者層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="8d3da-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-602">群組層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="8d3da-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-603">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-604">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-605">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-605">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-606">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-606">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-607">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-607">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-608">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8d3da-609">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="8d3da-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8d3da-610">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="8d3da-611">\* 「Microsoft 365 群組」和/或 Microsoft 小組通道會影響許可權。</span><span class="sxs-lookup"><span data-stu-id="8d3da-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="8d3da-612">若目的地是 Microsoft 365 群組或 Microsoft 團隊通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。</span><span class="sxs-lookup"><span data-stu-id="8d3da-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="8d3da-613">建議您不要在遷移至 Microsoft 365 群組或 Microsoft 團隊管道的檔案上遷移許可權。</span><span class="sxs-lookup"><span data-stu-id="8d3da-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="8d3da-614">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8d3da-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8d3da-615">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="8d3da-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8d3da-616">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-617">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-618">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8d3da-619">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8d3da-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8d3da-620">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-621">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="8d3da-622">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-623">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8d3da-624">Google 相簿表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="8d3da-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8d3da-625">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="8d3da-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8d3da-626">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8d3da-627">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="8d3da-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8d3da-628">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8d3da-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8d3da-629">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8d3da-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8d3da-630">共用磁碟機成員資格權限 (<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="8d3da-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8d3da-631">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="8d3da-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8d3da-632">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8d3da-633"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8d3da-634">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-635">文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-635">Documents</span></span> </li>
<li> <span data-ttu-id="8d3da-636">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-637">使用者層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="8d3da-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-638">群組層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="8d3da-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-639">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-640">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-641">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-641">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-642">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-642">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-643">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-643">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-644">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8d3da-645">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="8d3da-646">方框附注 (轉換為 Word 檔案格式) </span><span class="sxs-lookup"><span data-stu-id="8d3da-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="8d3da-647">\* 「Microsoft 365 群組」和/或 Microsoft 小組通道會影響許可權。</span><span class="sxs-lookup"><span data-stu-id="8d3da-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="8d3da-648">若目的地是 Microsoft 365 群組或 Microsoft 團隊通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。</span><span class="sxs-lookup"><span data-stu-id="8d3da-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="8d3da-649">建議您不要在遷移至 Microsoft 365 群組或 Microsoft 團隊管道的檔案上遷移許可權。</span><span class="sxs-lookup"><span data-stu-id="8d3da-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="8d3da-650">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8d3da-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8d3da-651">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="8d3da-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8d3da-652">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-653">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-654">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8d3da-655">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8d3da-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8d3da-656">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-657">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="8d3da-658">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-659">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8d3da-660">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="8d3da-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8d3da-661">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8d3da-662">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8d3da-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8d3da-663">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8d3da-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8d3da-664">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8d3da-665"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="8d3da-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8d3da-666">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="8d3da-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8d3da-667">文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-667">Documents</span></span> </li>
<li> <span data-ttu-id="8d3da-668">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="8d3da-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8d3da-669">使用者層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="8d3da-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-670">群組層級資料夾許可權 \*</span><span class="sxs-lookup"><span data-stu-id="8d3da-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8d3da-671">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="8d3da-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8d3da-672">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="8d3da-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8d3da-673">建立日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-673">Created date</span></span> </li>
<li> <span data-ttu-id="8d3da-674">修改日期</span><span class="sxs-lookup"><span data-stu-id="8d3da-674">Modified date</span></span> </li>
<li> <span data-ttu-id="8d3da-675">建立者</span><span class="sxs-lookup"><span data-stu-id="8d3da-675">Created by</span></span> </li>
<li> <span data-ttu-id="8d3da-676">上次修改者</span><span class="sxs-lookup"><span data-stu-id="8d3da-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8d3da-677">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8d3da-678">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="8d3da-679">\* 「Microsoft 365 群組」和/或 Microsoft 小組通道會影響許可權。</span><span class="sxs-lookup"><span data-stu-id="8d3da-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="8d3da-680">若目的地是 Microsoft 365 群組或 Microsoft 團隊通道，群組或通道會決定遷移後的檔案的最後許可權設定檔。</span><span class="sxs-lookup"><span data-stu-id="8d3da-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="8d3da-681">建議您不要在遷移至 Microsoft 365 群組或 Microsoft 團隊管道的檔案上遷移許可權。</span><span class="sxs-lookup"><span data-stu-id="8d3da-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="8d3da-682">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="8d3da-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8d3da-683">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="8d3da-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8d3da-684">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-685">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="8d3da-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8d3da-686">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="8d3da-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8d3da-687">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="8d3da-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8d3da-688">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="8d3da-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8d3da-689">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="8d3da-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="8d3da-690">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="8d3da-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8d3da-691">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="8d3da-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8d3da-692">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="8d3da-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8d3da-693">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="8d3da-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8d3da-694">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="8d3da-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8d3da-695">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="8d3da-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8d3da-696">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="8d3da-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8d3da-697">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="8d3da-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8d3da-698">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="8d3da-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="8d3da-699">Microsoft 團隊和 Microsoft 365 群組遷移的 FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="8d3da-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="8d3da-700">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8d3da-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8d3da-701">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="8d3da-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8d3da-702">您的責任</span><span class="sxs-lookup"><span data-stu-id="8d3da-702">Your responsibilities</span></span> 

<span data-ttu-id="8d3da-703">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="8d3da-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8d3da-704">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="8d3da-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="8d3da-705">您也可以執行下列針對 Microsoft 團隊和 Microsoft 365 群組遷移的活動：</span><span class="sxs-lookup"><span data-stu-id="8d3da-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="8d3da-706">將所有 Microsoft 團隊通道和 Microsoft 365 群組布建為遷移事件的目標。</span><span class="sxs-lookup"><span data-stu-id="8d3da-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="8d3da-707">FastTrack 未預先提供 Microsoft 團隊通道或 Microsoft 365 群組。</span><span class="sxs-lookup"><span data-stu-id="8d3da-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="8d3da-708">FastTrack 不會將使用者或群組新增至 Microsoft 小組通道或 Microsoft 365 群組。</span><span class="sxs-lookup"><span data-stu-id="8d3da-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="8d3da-709">您必須先將使用者或群組新增至所有的 Microsoft 團隊通道和 Microsoft 365 群組，再將資料移轉至這些目的地，這樣使用者才能存取這些新遷移的檔。</span><span class="sxs-lookup"><span data-stu-id="8d3da-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>