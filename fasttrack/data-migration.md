---
title: 資料移轉
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。 我們可以提供的協助類型取決於您的 Office 365 授權數量。
ms.openlocfilehash: 0ecfdfab7c7f7ae8879ea6374c3560dcaeb2f283
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016469"
---
# <a name="data-migration"></a><span data-ttu-id="3c557-104">資料移轉</span><span class="sxs-lookup"><span data-stu-id="3c557-104">Data Migration</span></span>

<span data-ttu-id="3c557-105">FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。</span><span class="sxs-lookup"><span data-stu-id="3c557-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="3c557-106">我們提供的協助類型取決於您的 Office 365 授權數量：</span><span class="sxs-lookup"><span data-stu-id="3c557-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="3c557-107">**針對有 150-499 個授權的 Microsoft Office 365 租用戶**：FastTrack 僅提供移轉指引；由您負責執行資料移轉。</span><span class="sxs-lookup"><span data-stu-id="3c557-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="3c557-108">我們會透過可協助您規劃及使用免費工具的文件，引導您執行自助移轉。</span><span class="sxs-lookup"><span data-stu-id="3c557-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="3c557-109">**針對具有 500 個或更多授權數量的 Microsoft Office 365 租用戶**：FastTrack 會提供移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="3c557-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="3c557-110">我們會提供指引以協助規劃您的移轉事件、設定您的來源環境和 Office 365 租用戶，並充分利用我們的資料移轉服務來移轉您的資料。</span><span class="sxs-lookup"><span data-stu-id="3c557-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="3c557-111">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="3c557-111">You create and schedule your migration events.</span></span> <span data-ttu-id="3c557-112">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="3c557-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="3c557-113">如果您在 9/1/2017 之前已購買或續約ㄧ個商業方案，您只需使用 150 個授權，就能獲得資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="3c557-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="3c557-114">針對教育方案，只有您的付費教職員授權符合使用資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="3c557-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="3c557-115">考量</span><span class="sxs-lookup"><span data-stu-id="3c557-115">Considerations</span></span>

  - <span data-ttu-id="3c557-116">您的來源環境必須符合特定期望條件，才能將資料移轉至 Microsoft Office 365。</span><span class="sxs-lookup"><span data-stu-id="3c557-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="3c557-117">如需其它與 Exchange、SharePoint、和 [商務用 OneDrive] 適用的來源環境期望，請參照 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="3c557-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="3c557-118">為提供資料移轉服務，我們需要您的來源環境及 Office 365 租用戶的適當存取權和權限。</span><span class="sxs-lookup"><span data-stu-id="3c557-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="3c557-119">我們的資料移轉服務既不是以受特殊法律、也不是受監管要求而設計或使用的。</span><span class="sxs-lookup"><span data-stu-id="3c557-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="3c557-120">當我們移轉您的資料時，可以將資料在任何我們進行設施維護的地方進行移轉、儲存及處理的動作（除非您的 FastTrack 移轉專案有提供另外的位置）。</span><span class="sxs-lookup"><span data-stu-id="3c557-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="3c557-121">我們不能保證郵件或檔案移轉的速度。</span><span class="sxs-lookup"><span data-stu-id="3c557-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="3c557-122">無法預料的問題（例如在來源環境中有無法讀取或已損毀的項目）可能會使我們無法移轉您的某些資料項目。</span><span class="sxs-lookup"><span data-stu-id="3c557-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="3c557-123">在我們控制範圍之外的外部因素（像是第三方應用程式開發介面 (APIs) 出現變更）會導致我們的資料移轉服務出現變更、延遲、或暫停的情況。</span><span class="sxs-lookup"><span data-stu-id="3c557-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="3c557-124">移轉服務的狀態</span><span class="sxs-lookup"><span data-stu-id="3c557-124">Migration service availability</span></span>

  - <span data-ttu-id="3c557-125">**針對商業及英國政府客戶：** 我們提供每天 24 小時、每周 7 天（24x7）的全年無休資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="3c557-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="3c557-126">**針對美國政府/DOD 客戶：** 我們提供每天 24 小時、每周 5 個工作天（24x5）的資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="3c557-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="3c557-127">移轉至 Exchange Online</span><span class="sxs-lookup"><span data-stu-id="3c557-127">Migration to Exchange Online</span></span>

<span data-ttu-id="3c557-128">當您選擇使用 FastTrack 將您的電子郵件移轉到 Exchange Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="3c557-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3c557-129">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 Exchange Online，並充分利用我們的資料移轉服務來移轉您的信箱。</span><span class="sxs-lookup"><span data-stu-id="3c557-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="3c557-130">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="3c557-130">You create and schedule your migration events.</span></span> <span data-ttu-id="3c557-131">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="3c557-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3c557-132">當您的移轉事件完成後，您可以預期在您的來源環境中，郵件經適當排程和從合格來源信箱移轉到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="3c557-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="3c557-133">考量</span><span class="sxs-lookup"><span data-stu-id="3c557-133">Considerations</span></span>

  - <span data-ttu-id="3c557-134">在進行移轉之前，您必須完成適用於 Exchange Online 的 FastTrack 核心上線動作；</span><span class="sxs-lookup"><span data-stu-id="3c557-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="3c557-135">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="3c557-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="3c557-136">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="3c557-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="3c557-137">FastTrack 只會移轉至使用中的 Office 365 信箱。</span><span class="sxs-lookup"><span data-stu-id="3c557-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="3c557-138">如果您想要從內部部署的 Exchange 環境將資料移轉出來，您必須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="3c557-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="3c557-139">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="3c557-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="3c557-140">每個來源環境都必須為其中各自相應的產品使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="3c557-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="3c557-141">存在於內部部署 Active Directory Domain Services 中的通訊群組清單（*MailEnabledGroup* 物件）和外部連絡人（*MailEnabledContact* 物件）並不屬於信箱資料移轉的一部分。</span><span class="sxs-lookup"><span data-stu-id="3c557-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="3c557-142">不過，您可以使用 Microsoft Azure Active Directory (Azure AD) Connect 進行同步處理。</span><span class="sxs-lookup"><span data-stu-id="3c557-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="3c557-143">來源環境</span><span class="sxs-lookup"><span data-stu-id="3c557-143">Source environments</span></span>

<span data-ttu-id="3c557-144">我們的資料移轉服務會將資料從這些來源環境中移轉出來：</span><span class="sxs-lookup"><span data-stu-id="3c557-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="3c557-145">含有單一個或多個 Exchange 組織的單一或多個 Active Directory 樹系 (每ㄧ個 Exchange 郵件系統都必須使用 Exchange 2010 或更新的版本)。</span><span class="sxs-lookup"><span data-stu-id="3c557-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="3c557-146">單一個具 IMAP 功能的電子郵件環境。</span><span class="sxs-lookup"><span data-stu-id="3c557-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="3c557-147">G Suite 環境 (僅限 Gmail、連絡人和Outlook 行事曆)。</span><span class="sxs-lookup"><span data-stu-id="3c557-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="3c557-148">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="3c557-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="3c557-149"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="3c557-150"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="3c557-151"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="3c557-152"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3c557-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="3c557-154">
<strong>附注：</strong> 如需內部部署 Exchange 相依性，請參閱 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">混合部署必要條件</span></a>。</span><span class="sxs-lookup"><span data-stu-id="3c557-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="3c557-155">混合部署移轉</span><span class="sxs-lookup"><span data-stu-id="3c557-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="3c557-156">電子郵件</span><span class="sxs-lookup"><span data-stu-id="3c557-156">Emails</span></span></li>
<li><span data-ttu-id="3c557-157">伺服器端信箱規則</span><span class="sxs-lookup"><span data-stu-id="3c557-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="3c557-158">委派</span><span class="sxs-lookup"><span data-stu-id="3c557-158">Delegates</span></span></li>
<li><span data-ttu-id="3c557-159">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="3c557-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="3c557-160">行事曆</span><span class="sxs-lookup"><span data-stu-id="3c557-160">Calendar</span></span> </li>
<li> <span data-ttu-id="3c557-161">工作</span><span class="sxs-lookup"><span data-stu-id="3c557-161">Tasks</span></span> </li>
<li> <span data-ttu-id="3c557-162">受版權管理的電子郵件</span><span class="sxs-lookup"><span data-stu-id="3c557-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="3c557-163">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="3c557-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="3c557-164">簽章</span><span class="sxs-lookup"><span data-stu-id="3c557-164">Signatures</span></span> </li>
<li> <span data-ttu-id="3c557-165">隨著使用者信箱移轉的個人封存</span><span class="sxs-lookup"><span data-stu-id="3c557-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="3c557-166">可復原的項目</span><span class="sxs-lookup"><span data-stu-id="3c557-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c557-167">公用資料夾</span><span class="sxs-lookup"><span data-stu-id="3c557-167">Public folders</span></span> </li>
<li> <span data-ttu-id="3c557-168">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="3c557-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3c557-169">日誌封存或任何協力廠商封存解決方案</span><span class="sxs-lookup"><span data-stu-id="3c557-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="3c557-170">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="3c557-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c557-171">從個人存放區資料表 (PST) 檔案封存的資料</span><span class="sxs-lookup"><span data-stu-id="3c557-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="3c557-172">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="3c557-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3c557-173">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="3c557-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="3c557-174">用戶端信箱規則</span><span class="sxs-lookup"><span data-stu-id="3c557-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3c557-175"><strong>G Suite 環境 (僅限 Gmail、連絡人和行事曆)</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="3c557-176">
<strong>附注：</strong> 您的 G 套件環境必須符合 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">執行 G Suite 遷移</a>中所述的必要條件。</span><span class="sxs-lookup"><span data-stu-id="3c557-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="3c557-177">轉換或分段</span><span class="sxs-lookup"><span data-stu-id="3c557-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c557-178">電子郵件</span><span class="sxs-lookup"><span data-stu-id="3c557-178">Emails</span></span> </li>
<li> <span data-ttu-id="3c557-179">信箱連絡人 (每個連絡人最多可移轉 3 個電子郵件地址)</span><span class="sxs-lookup"><span data-stu-id="3c557-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="3c557-180">行事曆</span><span class="sxs-lookup"><span data-stu-id="3c557-180">Calendar</span></span> </li>
<li> <span data-ttu-id="3c557-181">標籤</span><span class="sxs-lookup"><span data-stu-id="3c557-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c557-182">規則</span><span class="sxs-lookup"><span data-stu-id="3c557-182">Rules</span></span> </li>
<li> <span data-ttu-id="3c557-183">委派</span><span class="sxs-lookup"><span data-stu-id="3c557-183">Delegates</span></span> </li>
<li> <span data-ttu-id="3c557-184">簽章</span><span class="sxs-lookup"><span data-stu-id="3c557-184">Signatures</span></span> </li>
<li> <span data-ttu-id="3c557-185">工作</span><span class="sxs-lookup"><span data-stu-id="3c557-185">Tasks</span></span> </li>
<li> <span data-ttu-id="3c557-186">任何超過郵件大小限制的電子郵件或附件</span><span class="sxs-lookup"><span data-stu-id="3c557-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3c557-187">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="3c557-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c557-188">從 PST 檔案或任何協力廠商封存解決方案 (例如 Google Vault) 封存的資料</span><span class="sxs-lookup"><span data-stu-id="3c557-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="3c557-189">權限管理或加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="3c557-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="3c557-190">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="3c557-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3c557-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="3c557-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="3c557-192">Google Groups</span><span class="sxs-lookup"><span data-stu-id="3c557-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="3c557-193">資源信箱</span><span class="sxs-lookup"><span data-stu-id="3c557-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="3c557-194">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="3c557-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="3c557-195">假期設定和自動回覆設定</span><span class="sxs-lookup"><span data-stu-id="3c557-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="3c557-196">共用行事曆、雲端附件、Google Hangout 連結和活動色彩</span><span class="sxs-lookup"><span data-stu-id="3c557-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="3c557-197">\*\*可移轉儲存為標籤的 Hangout 交談。</span><span class="sxs-lookup"><span data-stu-id="3c557-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3c557-198"><strong>IMAP4 來源 (例如 Domino、GroupWise 和 Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="3c557-199">使用原生 IMAP4 工具進行的移轉</span><span class="sxs-lookup"><span data-stu-id="3c557-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="3c557-200">電子郵件</span><span class="sxs-lookup"><span data-stu-id="3c557-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="3c557-201">規則</span><span class="sxs-lookup"><span data-stu-id="3c557-201">Rules</span></span> </li>
<li> <span data-ttu-id="3c557-202">委派</span><span class="sxs-lookup"><span data-stu-id="3c557-202">Delegates</span></span> </li>
<li> <span data-ttu-id="3c557-203">通訊群組清單</span><span class="sxs-lookup"><span data-stu-id="3c557-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="3c557-204">外部連絡人</span><span class="sxs-lookup"><span data-stu-id="3c557-204">External contacts</span></span> </li>
<li> <span data-ttu-id="3c557-205">擁有郵件功能的使用者</span><span class="sxs-lookup"><span data-stu-id="3c557-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="3c557-206">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="3c557-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c557-207">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="3c557-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="3c557-208">行事曆</span><span class="sxs-lookup"><span data-stu-id="3c557-208">Calendar</span></span> </li>
<li> <span data-ttu-id="3c557-209">簽章</span><span class="sxs-lookup"><span data-stu-id="3c557-209">Signatures</span></span> </li>
<li> <span data-ttu-id="3c557-210">工作</span><span class="sxs-lookup"><span data-stu-id="3c557-210">Tasks</span></span> </li>
<li> <span data-ttu-id="3c557-211">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="3c557-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3c557-212">封存資料</span><span class="sxs-lookup"><span data-stu-id="3c557-212">Archive data</span></span> </li>
<li> <span data-ttu-id="3c557-213">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="3c557-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="3c557-214">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="3c557-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3c557-215">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="3c557-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3c557-216">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="3c557-216">FastTrack responsibilities</span></span>

<span data-ttu-id="3c557-217">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="3c557-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3c557-218">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="3c557-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3c557-219">我們的 FastTrack 專家也會執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="3c557-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="3c557-220">可提供指引，以便協助您啟用在來源環境與 Exchange Online 之間並立的 SMTP 郵件路由傳送（如果適用的話）。</span><span class="sxs-lookup"><span data-stu-id="3c557-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3c557-221">您的責任</span><span class="sxs-lookup"><span data-stu-id="3c557-221">Your responsibilities</span></span>

<span data-ttu-id="3c557-222">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="3c557-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3c557-223">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="3c557-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3c557-224">你也要執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="3c557-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="3c557-225">完成適用於 Exchange Online 的 FastTrack 核心上線動作。</span><span class="sxs-lookup"><span data-stu-id="3c557-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="3c557-226">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="3c557-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="3c557-227">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="3c557-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="3c557-228">依 Office 365 指引安裝適當層級的用戶端軟體。</span><span class="sxs-lookup"><span data-stu-id="3c557-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="3c557-229">如需詳細資訊，請參閱 [現代化工作場所](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。</span><span class="sxs-lookup"><span data-stu-id="3c557-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="3c557-230">如果您想要從內部部署的 Exchange 環境將資料移轉出來，須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="3c557-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="3c557-231">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="3c557-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="3c557-232">如果適用的話，每個來源環境都必須使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="3c557-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="3c557-233">若適用的話，在您的來源環境和 Exchange Online 中，設定和驗證 SMTP 郵件路由傳送共存。</span><span class="sxs-lookup"><span data-stu-id="3c557-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="3c557-234">請確定您的來源信箱容量大小未超過目標信箱配額。</span><span class="sxs-lookup"><span data-stu-id="3c557-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="3c557-235">視來源平台而定，您可能需要對來源資料限制在目標信箱配額的 85%。</span><span class="sxs-lookup"><span data-stu-id="3c557-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="3c557-236">視需要移轉用戶端資料。</span><span class="sxs-lookup"><span data-stu-id="3c557-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="3c557-237">這包含、但不限於本機通訊錄、本機 PST 檔案中的資料、Outlook 規則和本機 Outlook 設定。</span><span class="sxs-lookup"><span data-stu-id="3c557-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="3c557-238">協助使用者修正用戶端的遷移問題。</span><span class="sxs-lookup"><span data-stu-id="3c557-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="3c557-239">移轉至 SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="3c557-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="3c557-240">當您選擇使用 FastTrack 將您的檔案移轉到 SharePoint Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="3c557-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3c557-241">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 SharePoint Online，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="3c557-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3c557-242">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="3c557-242">You create and schedule your migration events.</span></span> <span data-ttu-id="3c557-243">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="3c557-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3c557-244">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 SharePoint Online。</span><span class="sxs-lookup"><span data-stu-id="3c557-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="3c557-245">考量</span><span class="sxs-lookup"><span data-stu-id="3c557-245">Considerations</span></span>

  - <span data-ttu-id="3c557-246">所有的移轉動作都受到 SharePoint Online 的配額限制。</span><span class="sxs-lookup"><span data-stu-id="3c557-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="3c557-247">如需詳細資訊，可參照 [<span class="underline">SharePoint Online 和 [商務用 OneDrive]：軟體使用範圍及限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="3c557-247">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="3c557-248">我們建議您將移轉的總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="3c557-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="3c557-249">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="3c557-249">Source environment details</span></span>

<span data-ttu-id="3c557-250">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="3c557-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="3c557-251">檔案共用 (支援 SMB 2.0+ 裝置的伺服器訊息區 (SMB) 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="3c557-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="3c557-252">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="3c557-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="3c557-253">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="3c557-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="3c557-254">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="3c557-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="3c557-255">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="3c557-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="3c557-256"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="3c557-257"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="3c557-258"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3c557-259"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3c557-260"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3c557-261">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="3c557-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c557-262">文件</span><span class="sxs-lookup"><span data-stu-id="3c557-262">Documents</span></span> </li>
<li> <span data-ttu-id="3c557-263">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="3c557-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c557-264">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="3c557-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3c557-265">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="3c557-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3c557-266">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="3c557-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c557-267">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="3c557-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c557-268">建立日期</span><span class="sxs-lookup"><span data-stu-id="3c557-268">Created date</span></span> </li>
<li> <span data-ttu-id="3c557-269">修改日期</span><span class="sxs-lookup"><span data-stu-id="3c557-269">Modified date</span></span> </li>
<li> <span data-ttu-id="3c557-270">建立者</span><span class="sxs-lookup"><span data-stu-id="3c557-270">Created by</span></span> </li>
<li> <span data-ttu-id="3c557-271">上次修改者</span><span class="sxs-lookup"><span data-stu-id="3c557-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="3c557-272">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="3c557-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3c557-273">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="3c557-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3c557-274">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="3c557-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3c557-275">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="3c557-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c557-276">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="3c557-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3c557-277">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="3c557-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c557-278">舊版</span><span class="sxs-lookup"><span data-stu-id="3c557-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="3c557-279">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="3c557-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3c557-280">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="3c557-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3c557-281">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="3c557-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3c557-282">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="3c557-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3c557-283">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="3c557-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3c557-284">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="3c557-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c557-285">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="3c557-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3c557-286">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="3c557-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3c557-287">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="3c557-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3c557-288"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3c557-289">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="3c557-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c557-290">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式) ，包括超過 10 MB 的檔案。</span><span class="sxs-lookup"><span data-stu-id="3c557-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="3c557-291">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="3c557-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c557-292">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-293">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-294">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="3c557-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c557-295">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="3c557-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c557-296">建立日期</span><span class="sxs-lookup"><span data-stu-id="3c557-296">Created date</span></span> </li>
<li> <span data-ttu-id="3c557-297">修改日期</span><span class="sxs-lookup"><span data-stu-id="3c557-297">Modified date</span></span> </li>
<li> <span data-ttu-id="3c557-298">建立者</span><span class="sxs-lookup"><span data-stu-id="3c557-298">Created by</span></span> </li>
<li> <span data-ttu-id="3c557-299">上次修改者</span><span class="sxs-lookup"><span data-stu-id="3c557-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c557-300">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="3c557-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3c557-301">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="3c557-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c557-302">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="3c557-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c557-303">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="3c557-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3c557-304">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-305">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-306">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="3c557-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c557-307">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="3c557-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c557-308">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="3c557-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c557-309">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="3c557-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c557-310">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="3c557-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c557-311">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="3c557-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c557-312">Google 相簿、表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="3c557-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3c557-313">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="3c557-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3c557-314">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="3c557-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3c557-315">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="3c557-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3c557-316">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="3c557-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3c557-317">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="3c557-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3c557-318">共用磁碟機成員權限（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="3c557-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3c557-319">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="3c557-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3c557-320">標記為受限或未 copyable 的檔案</span><span class="sxs-lookup"><span data-stu-id="3c557-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="3c557-321">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="3c557-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3c557-322"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3c557-323">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="3c557-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c557-324">文件</span><span class="sxs-lookup"><span data-stu-id="3c557-324">Documents</span></span> </li>
<li> <span data-ttu-id="3c557-325">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="3c557-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c557-326">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-327">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-328">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="3c557-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c557-329">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="3c557-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c557-330">建立日期</span><span class="sxs-lookup"><span data-stu-id="3c557-330">Created date</span></span> </li>
<li> <span data-ttu-id="3c557-331">修改日期</span><span class="sxs-lookup"><span data-stu-id="3c557-331">Modified date</span></span> </li>
<li> <span data-ttu-id="3c557-332">建立者</span><span class="sxs-lookup"><span data-stu-id="3c557-332">Created by</span></span> </li>
<li> <span data-ttu-id="3c557-333">上次修改者</span><span class="sxs-lookup"><span data-stu-id="3c557-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c557-334">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="3c557-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="3c557-335">方框附注 (轉換為 Word 檔案格式) </span><span class="sxs-lookup"><span data-stu-id="3c557-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c557-336">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="3c557-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c557-337">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="3c557-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3c557-338">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-339">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-340">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="3c557-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c557-341">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="3c557-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c557-342">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="3c557-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c557-343">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="3c557-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c557-344">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="3c557-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c557-345">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="3c557-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c557-346">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="3c557-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3c557-347">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="3c557-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3c557-348">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="3c557-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3c557-349">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="3c557-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3c557-350">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="3c557-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3c557-351"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3c557-352">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="3c557-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c557-353">文件</span><span class="sxs-lookup"><span data-stu-id="3c557-353">Documents</span></span> </li>
<li> <span data-ttu-id="3c557-354">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="3c557-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c557-355">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-356">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-357">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="3c557-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c557-358">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="3c557-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c557-359">建立日期</span><span class="sxs-lookup"><span data-stu-id="3c557-359">Created date</span></span> </li>
<li> <span data-ttu-id="3c557-360">修改日期</span><span class="sxs-lookup"><span data-stu-id="3c557-360">Modified date</span></span> </li>
<li> <span data-ttu-id="3c557-361">建立者</span><span class="sxs-lookup"><span data-stu-id="3c557-361">Created by</span></span> </li>
<li> <span data-ttu-id="3c557-362">上次修改者</span><span class="sxs-lookup"><span data-stu-id="3c557-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c557-363">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="3c557-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3c557-364">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="3c557-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c557-365">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="3c557-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c557-366">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="3c557-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3c557-367">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-368">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-369">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="3c557-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c557-370">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="3c557-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c557-371">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="3c557-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c557-372">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="3c557-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c557-373">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="3c557-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c557-374">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="3c557-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3c557-375">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="3c557-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3c557-376">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="3c557-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3c557-377">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="3c557-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3c557-378">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="3c557-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3c557-379">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="3c557-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3c557-380">指示使用者在移轉之後，與外部使用者再次共用內容）</span><span class="sxs-lookup"><span data-stu-id="3c557-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="3c557-381">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="3c557-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3c557-382">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="3c557-382">FastTrack responsibilities</span></span>

<span data-ttu-id="3c557-383">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="3c557-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3c557-384">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="3c557-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3c557-385">您的責任</span><span class="sxs-lookup"><span data-stu-id="3c557-385">Your responsibilities</span></span>

<span data-ttu-id="3c557-386">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="3c557-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3c557-387">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="3c557-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="3c557-388">你也要執行下列 SharePoint Online 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="3c557-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="3c557-389">使用您的移轉事件針對所有 SharePoint 小組網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="3c557-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="3c557-390">移轉至商務用 OneDrive</span><span class="sxs-lookup"><span data-stu-id="3c557-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="3c557-391">當您選擇使用 FastTrack 將您的檔案移轉到 商務用 OneDrive 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="3c557-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3c557-392">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 商務用 OneDrive，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="3c557-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3c557-393">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="3c557-393">You create and schedule your migration events.</span></span> <span data-ttu-id="3c557-394">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="3c557-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3c557-395">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 商務用 OneDrive。</span><span class="sxs-lookup"><span data-stu-id="3c557-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="3c557-396">考量</span><span class="sxs-lookup"><span data-stu-id="3c557-396">Considerations</span></span>

  - <span data-ttu-id="3c557-397">所有的移轉事件都受 [商務用 OneDrive] 配額的限制。</span><span class="sxs-lookup"><span data-stu-id="3c557-397">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="3c557-398">如需詳細資訊，請參照 [<span class="underline">SharePoint Online 和 [商務用 OneDrive]：軟體使用範圍及限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="3c557-398">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="3c557-399">我們建議您將移轉的資料總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="3c557-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="3c557-400">FastTrack 只會移轉到使用中的 [商務用 OneDrive] 磁碟機。</span><span class="sxs-lookup"><span data-stu-id="3c557-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="3c557-401">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="3c557-401">Source environment details</span></span>

<span data-ttu-id="3c557-402">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="3c557-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="3c557-403">檔案共用 (支援 SMB 2.0+ 之裝置的 SMB 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="3c557-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="3c557-404">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="3c557-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="3c557-405">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="3c557-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="3c557-406">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="3c557-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="3c557-407">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="3c557-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="3c557-408"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="3c557-409"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="3c557-410"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3c557-411"><strong>不能移轉什麼內容</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3c557-412"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3c557-413">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="3c557-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c557-414">文件</span><span class="sxs-lookup"><span data-stu-id="3c557-414">Documents</span></span> </li>
<li> <span data-ttu-id="3c557-415">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="3c557-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c557-416">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="3c557-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3c557-417">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="3c557-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3c557-418">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="3c557-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c557-419">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="3c557-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c557-420">建立日期</span><span class="sxs-lookup"><span data-stu-id="3c557-420">Created date</span></span> </li>
<li> <span data-ttu-id="3c557-421">修改日期</span><span class="sxs-lookup"><span data-stu-id="3c557-421">Modified date</span></span> </li>
<li> <span data-ttu-id="3c557-422">建立者</span><span class="sxs-lookup"><span data-stu-id="3c557-422">Created by</span></span> </li>
<li> <span data-ttu-id="3c557-423">上次修改者</span><span class="sxs-lookup"><span data-stu-id="3c557-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="3c557-424">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="3c557-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3c557-425">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="3c557-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3c557-426">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="3c557-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3c557-427">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="3c557-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="3c557-428">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="3c557-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3c557-429">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="3c557-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c557-430">舊版</span><span class="sxs-lookup"><span data-stu-id="3c557-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="3c557-431">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="3c557-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3c557-432">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="3c557-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3c557-433">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="3c557-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3c557-434">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="3c557-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3c557-435">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="3c557-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3c557-436">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="3c557-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c557-437">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="3c557-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3c557-438">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="3c557-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3c557-439">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="3c557-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3c557-440"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3c557-441">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="3c557-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c557-442">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式 ，包括超過 10 MB 的檔案)</span><span class="sxs-lookup"><span data-stu-id="3c557-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="3c557-443">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="3c557-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c557-444">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-445">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-446">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="3c557-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c557-447">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="3c557-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c557-448">建立日期</span><span class="sxs-lookup"><span data-stu-id="3c557-448">Created date</span></span> </li>
<li> <span data-ttu-id="3c557-449">修改日期</span><span class="sxs-lookup"><span data-stu-id="3c557-449">Modified date</span></span> </li>
<li> <span data-ttu-id="3c557-450">建立者</span><span class="sxs-lookup"><span data-stu-id="3c557-450">Created by</span></span> </li>
<li> <span data-ttu-id="3c557-451">上次修改者</span><span class="sxs-lookup"><span data-stu-id="3c557-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c557-452">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="3c557-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3c557-453">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="3c557-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c557-454">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="3c557-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c557-455">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="3c557-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3c557-456">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-457">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-458">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="3c557-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c557-459">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="3c557-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c557-460">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="3c557-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c557-461">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="3c557-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c557-462">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="3c557-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c557-463">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="3c557-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c557-464">Google 相簿表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="3c557-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3c557-465">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="3c557-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3c557-466">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="3c557-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3c557-467">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="3c557-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3c557-468">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="3c557-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3c557-469">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="3c557-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3c557-470">共用磁碟機成員資格權限 (<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="3c557-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3c557-471">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="3c557-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3c557-472">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="3c557-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3c557-473"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3c557-474">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="3c557-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c557-475">文件</span><span class="sxs-lookup"><span data-stu-id="3c557-475">Documents</span></span> </li>
<li> <span data-ttu-id="3c557-476">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="3c557-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c557-477">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-478">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-479">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="3c557-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c557-480">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="3c557-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c557-481">建立日期</span><span class="sxs-lookup"><span data-stu-id="3c557-481">Created date</span></span> </li>
<li> <span data-ttu-id="3c557-482">修改日期</span><span class="sxs-lookup"><span data-stu-id="3c557-482">Modified date</span></span> </li>
<li> <span data-ttu-id="3c557-483">建立者</span><span class="sxs-lookup"><span data-stu-id="3c557-483">Created by</span></span> </li>
<li> <span data-ttu-id="3c557-484">上次修改者</span><span class="sxs-lookup"><span data-stu-id="3c557-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c557-485">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="3c557-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c557-486">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="3c557-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c557-487">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="3c557-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3c557-488">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-489">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-490">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="3c557-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c557-491">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="3c557-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c557-492">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="3c557-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c557-493">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="3c557-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c557-494">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="3c557-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c557-495">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="3c557-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c557-496">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="3c557-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3c557-497">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="3c557-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3c557-498">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="3c557-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3c557-499">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="3c557-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3c557-500">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="3c557-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3c557-501"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="3c557-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3c557-502">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="3c557-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c557-503">文件</span><span class="sxs-lookup"><span data-stu-id="3c557-503">Documents</span></span> </li>
<li> <span data-ttu-id="3c557-504">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="3c557-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c557-505">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-506">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="3c557-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c557-507">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="3c557-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c557-508">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="3c557-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c557-509">建立日期</span><span class="sxs-lookup"><span data-stu-id="3c557-509">Created date</span></span> </li>
<li> <span data-ttu-id="3c557-510">修改日期</span><span class="sxs-lookup"><span data-stu-id="3c557-510">Modified date</span></span> </li>
<li> <span data-ttu-id="3c557-511">建立者</span><span class="sxs-lookup"><span data-stu-id="3c557-511">Created by</span></span> </li>
<li> <span data-ttu-id="3c557-512">上次修改者</span><span class="sxs-lookup"><span data-stu-id="3c557-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c557-513">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="3c557-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3c557-514">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="3c557-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c557-515">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="3c557-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c557-516">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="3c557-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3c557-517">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-518">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="3c557-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c557-519">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="3c557-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c557-520">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="3c557-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c557-521">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="3c557-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c557-522">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="3c557-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c557-523">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="3c557-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c557-524">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="3c557-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3c557-525">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="3c557-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3c557-526">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="3c557-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3c557-527">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="3c557-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3c557-528">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="3c557-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3c557-529">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="3c557-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3c557-530">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="3c557-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3c557-531">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="3c557-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3c557-532">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="3c557-532">FastTrack responsibilities</span></span>

<span data-ttu-id="3c557-533">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="3c557-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3c557-534">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="3c557-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3c557-535">您的責任</span><span class="sxs-lookup"><span data-stu-id="3c557-535">Your responsibilities</span></span>

<span data-ttu-id="3c557-536">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="3c557-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3c557-537">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="3c557-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3c557-538">你也要執行下列 [商務用 OneDrive] 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="3c557-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="3c557-539">使用您的移轉事件針對所有 [商務用 OneDrive] 網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="3c557-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
