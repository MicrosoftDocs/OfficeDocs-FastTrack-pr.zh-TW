---
title: 資料移轉
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 11/2/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。 我們可以提供的協助類型取決於您的 Office 365 授權數量。
ms.openlocfilehash: 7b796ea88c884445bd7069c6c7768c8fc3e3d170
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827646"
---
# <a name="data-migration"></a><span data-ttu-id="c4090-104">資料移轉</span><span class="sxs-lookup"><span data-stu-id="c4090-104">Data Migration</span></span>

<span data-ttu-id="c4090-105">FastTrack 可協助您將來源環境中的郵件和檔案資料移轉至 Office 365 (Exchange Online、SharePoint Online 及 [商務用 OneDrive])。</span><span class="sxs-lookup"><span data-stu-id="c4090-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="c4090-106">我們提供的協助類型取決於您的 Office 365 授權數量：</span><span class="sxs-lookup"><span data-stu-id="c4090-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="c4090-107">**針對有 150-499 個授權的 Microsoft Office 365 租用戶** ：FastTrack 僅提供移轉指引；由您負責執行資料移轉。</span><span class="sxs-lookup"><span data-stu-id="c4090-107">**For Office 365 tenants with 150-499 licenses** : FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="c4090-108">我們會透過可協助您規劃及使用免費工具的文件，引導您執行自助移轉。</span><span class="sxs-lookup"><span data-stu-id="c4090-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="c4090-109">**針對具有 500 個或更多授權數量的 Microsoft Office 365 租用戶** ：FastTrack 會提供移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="c4090-109">**For Office 365 tenants with 500 or more licenses** : FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="c4090-110">我們會提供指引以協助規劃您的移轉事件、設定您的來源環境和 Office 365 租用戶，並充分利用我們的資料移轉服務來移轉您的資料。</span><span class="sxs-lookup"><span data-stu-id="c4090-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="c4090-111">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="c4090-111">You create and schedule your migration events.</span></span> <span data-ttu-id="c4090-112">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="c4090-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="c4090-113">如果您在 9/1/2017 之前已購買或續約ㄧ個商業方案，您只需使用 150 個授權，就能獲得資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="c4090-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="c4090-114">針對教育方案，只有您的付費教職員授權符合使用資料移轉服務的資格。</span><span class="sxs-lookup"><span data-stu-id="c4090-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="c4090-115">考量</span><span class="sxs-lookup"><span data-stu-id="c4090-115">Considerations</span></span>

  - <span data-ttu-id="c4090-116">您的來源環境必須符合特定期望條件，才能將資料移轉至 Microsoft Office 365。</span><span class="sxs-lookup"><span data-stu-id="c4090-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="c4090-117">如需其它與 Exchange、SharePoint、和 [商務用 OneDrive] 適用的來源環境期望，請參照 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="c4090-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="c4090-118">為提供資料移轉服務，我們需要您的來源環境及 Office 365 租用戶的適當存取權和權限。</span><span class="sxs-lookup"><span data-stu-id="c4090-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="c4090-119">我們的資料移轉服務既不是以受特殊法律、也不是受監管要求而設計或使用的。</span><span class="sxs-lookup"><span data-stu-id="c4090-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="c4090-120">當我們移轉您的資料時，可以將資料在任何我們進行設施維護的地方進行移轉、儲存及處理的動作（除非您的 FastTrack 移轉專案有提供另外的位置）。</span><span class="sxs-lookup"><span data-stu-id="c4090-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="c4090-121">我們不能保證郵件或檔案移轉的速度。</span><span class="sxs-lookup"><span data-stu-id="c4090-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="c4090-122">無法預料的問題（例如在來源環境中有無法讀取或已損毀的項目）可能會使我們無法移轉您的某些資料項目。</span><span class="sxs-lookup"><span data-stu-id="c4090-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="c4090-123">在我們控制範圍之外的外部因素（像是第三方應用程式開發介面 (APIs) 出現變更）會導致我們的資料移轉服務出現變更、延遲、或暫停的情況。</span><span class="sxs-lookup"><span data-stu-id="c4090-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="c4090-124">移轉服務的狀態</span><span class="sxs-lookup"><span data-stu-id="c4090-124">Migration service availability</span></span>

  - <span data-ttu-id="c4090-125">**針對商業及英國政府客戶：** 我們提供每天 24 小時、每周 7 天（24x7）的全年無休資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="c4090-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="c4090-126">**針對美國政府/DOD 客戶：** 我們提供每天 24 小時、每周 5 個工作天（24x5）的資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="c4090-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="c4090-127">移轉至 Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c4090-127">Migration to Exchange Online</span></span>

<span data-ttu-id="c4090-128">當您選擇使用 FastTrack 將您的電子郵件移轉到 Exchange Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="c4090-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c4090-129">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 Exchange Online，並充分利用我們的資料移轉服務來移轉您的信箱。</span><span class="sxs-lookup"><span data-stu-id="c4090-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="c4090-130">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="c4090-130">You create and schedule your migration events.</span></span> <span data-ttu-id="c4090-131">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="c4090-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c4090-132">當您的移轉事件完成後，您可以預期在您的來源環境中，郵件經適當排程和從合格來源信箱移轉到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="c4090-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="c4090-133">考量</span><span class="sxs-lookup"><span data-stu-id="c4090-133">Considerations</span></span>

  - <span data-ttu-id="c4090-134">在進行移轉之前，您必須完成適用於 Exchange Online 的 FastTrack 核心上線動作；</span><span class="sxs-lookup"><span data-stu-id="c4090-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="c4090-135">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="c4090-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="c4090-136">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="c4090-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="c4090-137">FastTrack 只會移轉至使用中的 Office 365 信箱。</span><span class="sxs-lookup"><span data-stu-id="c4090-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="c4090-138">如果您想要從內部部署的 Exchange 環境將資料移轉出來，您必須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="c4090-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="c4090-139">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="c4090-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="c4090-140">每個來源環境都必須為其中各自相應的產品使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="c4090-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="c4090-141">存在於內部部署 Active Directory Domain Services 中的通訊群組清單（ *MailEnabledGroup* 物件）和外部連絡人（ *MailEnabledContact* 物件）並不屬於信箱資料移轉的一部分。</span><span class="sxs-lookup"><span data-stu-id="c4090-141">Distribution lists ( *MailEnabledGroup* objects) and external contacts ( *MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="c4090-142">不過，您可以使用 Microsoft Azure Active Directory (Azure AD) Connect 進行同步處理。</span><span class="sxs-lookup"><span data-stu-id="c4090-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="c4090-143">來源環境</span><span class="sxs-lookup"><span data-stu-id="c4090-143">Source environments</span></span>

<span data-ttu-id="c4090-144">我們的資料移轉服務會將資料從這些來源環境中移轉出來：</span><span class="sxs-lookup"><span data-stu-id="c4090-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="c4090-145">含有單一個或多個 Exchange 組織的單一或多個 Active Directory 樹系 (每ㄧ個 Exchange 郵件系統都必須使用 Exchange 2010 或更新的版本)。</span><span class="sxs-lookup"><span data-stu-id="c4090-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="c4090-146">單一個具 IMAP 功能的電子郵件環境。</span><span class="sxs-lookup"><span data-stu-id="c4090-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="c4090-147">G Suite 環境 (僅限 Gmail、連絡人和Outlook 行事曆)。</span><span class="sxs-lookup"><span data-stu-id="c4090-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="c4090-148">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="c4090-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c4090-149"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="c4090-150"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="c4090-151"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="c4090-152"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c4090-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="c4090-154">
<strong>附注：</strong> 如需內部部署 Exchange 相依性，請參閱 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">混合部署必要條件</span></a>。</span><span class="sxs-lookup"><span data-stu-id="c4090-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="c4090-155">混合部署移轉</span><span class="sxs-lookup"><span data-stu-id="c4090-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="c4090-156">電子郵件</span><span class="sxs-lookup"><span data-stu-id="c4090-156">Emails</span></span></li>
<li><span data-ttu-id="c4090-157">信箱規則</span><span class="sxs-lookup"><span data-stu-id="c4090-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="c4090-158">委派</span><span class="sxs-lookup"><span data-stu-id="c4090-158">Delegates</span></span></li>
<li><span data-ttu-id="c4090-159">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="c4090-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="c4090-160">行事曆</span><span class="sxs-lookup"><span data-stu-id="c4090-160">Calendar</span></span> </li>
<li> <span data-ttu-id="c4090-161">工作</span><span class="sxs-lookup"><span data-stu-id="c4090-161">Tasks</span></span> </li>
<li> <span data-ttu-id="c4090-162">受版權管理的電子郵件</span><span class="sxs-lookup"><span data-stu-id="c4090-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="c4090-163">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="c4090-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="c4090-164">簽章</span><span class="sxs-lookup"><span data-stu-id="c4090-164">Signatures</span></span> </li>
<li> <span data-ttu-id="c4090-165">隨著使用者信箱移轉的個人封存</span><span class="sxs-lookup"><span data-stu-id="c4090-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="c4090-166">可復原的項目</span><span class="sxs-lookup"><span data-stu-id="c4090-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4090-167">公用資料夾</span><span class="sxs-lookup"><span data-stu-id="c4090-167">Public folders</span></span> </li>
<li> <span data-ttu-id="c4090-168">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="c4090-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c4090-169">日誌封存或任何協力廠商封存解決方案</span><span class="sxs-lookup"><span data-stu-id="c4090-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="c4090-170">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="c4090-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4090-171">從個人存放區資料表 (PST) 檔案封存的資料</span><span class="sxs-lookup"><span data-stu-id="c4090-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="c4090-172">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="c4090-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c4090-173">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="c4090-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c4090-174"><strong>G Suite 環境 (僅限 Gmail、連絡人和行事曆)</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="c4090-175">
<strong>附注：</strong> 您的 G 套件環境必須符合 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">執行 G Suite 遷移</a>中所述的必要條件。</span><span class="sxs-lookup"><span data-stu-id="c4090-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="c4090-176">轉換或分段</span><span class="sxs-lookup"><span data-stu-id="c4090-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4090-177">電子郵件</span><span class="sxs-lookup"><span data-stu-id="c4090-177">Emails</span></span> </li>
<li> <span data-ttu-id="c4090-178">信箱連絡人 (每個連絡人最多可移轉 3 個電子郵件地址)</span><span class="sxs-lookup"><span data-stu-id="c4090-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="c4090-179">行事曆</span><span class="sxs-lookup"><span data-stu-id="c4090-179">Calendar</span></span> </li>
<li> <span data-ttu-id="c4090-180">標籤</span><span class="sxs-lookup"><span data-stu-id="c4090-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4090-181">規則</span><span class="sxs-lookup"><span data-stu-id="c4090-181">Rules</span></span> </li>
<li> <span data-ttu-id="c4090-182">委派</span><span class="sxs-lookup"><span data-stu-id="c4090-182">Delegates</span></span> </li>
<li> <span data-ttu-id="c4090-183">簽章</span><span class="sxs-lookup"><span data-stu-id="c4090-183">Signatures</span></span> </li>
<li> <span data-ttu-id="c4090-184">工作</span><span class="sxs-lookup"><span data-stu-id="c4090-184">Tasks</span></span> </li>
<li> <span data-ttu-id="c4090-185">任何超過郵件大小限制的電子郵件或附件</span><span class="sxs-lookup"><span data-stu-id="c4090-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c4090-186">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="c4090-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4090-187">從 PST 檔案或任何協力廠商封存解決方案 (例如 Google Vault) 封存的資料</span><span class="sxs-lookup"><span data-stu-id="c4090-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="c4090-188">權限管理或加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="c4090-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="c4090-189">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="c4090-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c4090-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="c4090-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="c4090-191">Google Groups</span><span class="sxs-lookup"><span data-stu-id="c4090-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="c4090-192">資源信箱</span><span class="sxs-lookup"><span data-stu-id="c4090-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="c4090-193">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="c4090-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="c4090-194">假期設定和自動回覆設定</span><span class="sxs-lookup"><span data-stu-id="c4090-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="c4090-195">共用行事曆、雲端附件、Google Hangout 連結和活動色彩</span><span class="sxs-lookup"><span data-stu-id="c4090-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="c4090-196">\*\*可移轉儲存為標籤的 Hangout 交談。</span><span class="sxs-lookup"><span data-stu-id="c4090-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c4090-197"><strong>IMAP4 來源 (例如 Domino、GroupWise 和 Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="c4090-198">使用原生 IMAP4 工具進行的移轉</span><span class="sxs-lookup"><span data-stu-id="c4090-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="c4090-199">電子郵件</span><span class="sxs-lookup"><span data-stu-id="c4090-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="c4090-200">規則</span><span class="sxs-lookup"><span data-stu-id="c4090-200">Rules</span></span> </li>
<li> <span data-ttu-id="c4090-201">委派</span><span class="sxs-lookup"><span data-stu-id="c4090-201">Delegates</span></span> </li>
<li> <span data-ttu-id="c4090-202">通訊群組清單</span><span class="sxs-lookup"><span data-stu-id="c4090-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="c4090-203">外部連絡人</span><span class="sxs-lookup"><span data-stu-id="c4090-203">External contacts</span></span> </li>
<li> <span data-ttu-id="c4090-204">擁有郵件功能的使用者</span><span class="sxs-lookup"><span data-stu-id="c4090-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="c4090-205">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="c4090-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4090-206">信箱連絡人</span><span class="sxs-lookup"><span data-stu-id="c4090-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="c4090-207">行事曆</span><span class="sxs-lookup"><span data-stu-id="c4090-207">Calendar</span></span> </li>
<li> <span data-ttu-id="c4090-208">簽章</span><span class="sxs-lookup"><span data-stu-id="c4090-208">Signatures</span></span> </li>
<li> <span data-ttu-id="c4090-209">工作</span><span class="sxs-lookup"><span data-stu-id="c4090-209">Tasks</span></span> </li>
<li> <span data-ttu-id="c4090-210">任何超過郵件大小限制的電子郵件</span><span class="sxs-lookup"><span data-stu-id="c4090-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c4090-211">封存資料</span><span class="sxs-lookup"><span data-stu-id="c4090-211">Archive data</span></span> </li>
<li> <span data-ttu-id="c4090-212">加密的電子郵件</span><span class="sxs-lookup"><span data-stu-id="c4090-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="c4090-213">損毀的項目</span><span class="sxs-lookup"><span data-stu-id="c4090-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c4090-214">非使用中的信箱</span><span class="sxs-lookup"><span data-stu-id="c4090-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c4090-215">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="c4090-215">FastTrack responsibilities</span></span>

<span data-ttu-id="c4090-216">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="c4090-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c4090-217">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="c4090-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c4090-218">我們的 FastTrack 專家也會執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="c4090-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="c4090-219">可提供指引，以便協助您啟用在來源環境與 Exchange Online 之間並立的 SMTP 郵件路由傳送（如果適用的話）。</span><span class="sxs-lookup"><span data-stu-id="c4090-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c4090-220">您的責任</span><span class="sxs-lookup"><span data-stu-id="c4090-220">Your responsibilities</span></span>

<span data-ttu-id="c4090-221">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="c4090-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c4090-222">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="c4090-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c4090-223">你也要執行下列 Exchange 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="c4090-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="c4090-224">完成適用於 Exchange Online 的 FastTrack 核心上線動作。</span><span class="sxs-lookup"><span data-stu-id="c4090-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="c4090-225">如果您是自行上線，您必須傳送檢查和先決條件。</span><span class="sxs-lookup"><span data-stu-id="c4090-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="c4090-226">如需詳細資訊，請參閱 [產品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="c4090-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="c4090-227">依 Office 365 指引安裝適當層級的用戶端軟體。</span><span class="sxs-lookup"><span data-stu-id="c4090-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="c4090-228">如需詳細資訊，請參閱 [現代化工作場所](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。</span><span class="sxs-lookup"><span data-stu-id="c4090-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="c4090-229">如果您想要從內部部署的 Exchange 環境將資料移轉出來，須滿足ㄧ些特定需求。</span><span class="sxs-lookup"><span data-stu-id="c4090-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="c4090-230">如需詳細資訊，請參閱 [混合式部署的先決條件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="c4090-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="c4090-231">如果適用的話，每個來源環境都必須使用最新的 Service Pack (SP) 和 彙總套件 (RU)/累積更新 (CU) 層級。</span><span class="sxs-lookup"><span data-stu-id="c4090-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="c4090-232">若適用的話，在您的來源環境和 Exchange Online 中，設定和驗證 SMTP 郵件路由傳送共存。</span><span class="sxs-lookup"><span data-stu-id="c4090-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="c4090-233">請確定您的來源信箱容量大小未超過目標信箱配額。</span><span class="sxs-lookup"><span data-stu-id="c4090-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="c4090-234">視來源平台而定，您可能需要對來源資料限制在目標信箱配額的 85%。</span><span class="sxs-lookup"><span data-stu-id="c4090-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="c4090-235">視需要移轉用戶端資料。</span><span class="sxs-lookup"><span data-stu-id="c4090-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="c4090-236">這包含、但不限於本機通訊錄、本機 PST 檔案中的資料、Outlook 規則和本機 Outlook 設定。</span><span class="sxs-lookup"><span data-stu-id="c4090-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="c4090-237">協助使用者修正用戶端的遷移問題。</span><span class="sxs-lookup"><span data-stu-id="c4090-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="c4090-238">移轉至 SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="c4090-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="c4090-239">當您選擇使用 FastTrack 將您的檔案移轉到 SharePoint Online 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="c4090-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c4090-240">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 SharePoint Online，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="c4090-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="c4090-241">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="c4090-241">You create and schedule your migration events.</span></span> <span data-ttu-id="c4090-242">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="c4090-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c4090-243">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 SharePoint Online。</span><span class="sxs-lookup"><span data-stu-id="c4090-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="c4090-244">考量</span><span class="sxs-lookup"><span data-stu-id="c4090-244">Considerations</span></span>

  - <span data-ttu-id="c4090-245">所有的移轉動作都受到 SharePoint Online 的配額限制。</span><span class="sxs-lookup"><span data-stu-id="c4090-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="c4090-246">如需詳細資訊，可參照 [<span class="underline">SharePoint Online 和 [商務用 OneDrive]：軟體使用範圍及限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="c4090-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="c4090-247">我們建議您將移轉的總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="c4090-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="c4090-248">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="c4090-248">Source environment details</span></span>

<span data-ttu-id="c4090-249">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="c4090-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="c4090-250">檔案共用 (支援 SMB 2.0+ 裝置的伺服器訊息區 (SMB) 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="c4090-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="c4090-251">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="c4090-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="c4090-252">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="c4090-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="c4090-253">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="c4090-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="c4090-254">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="c4090-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c4090-255"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="c4090-256"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="c4090-257"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="c4090-258"><strong>哪些內容不能移轉</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c4090-259"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="c4090-260">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="c4090-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4090-261">文件</span><span class="sxs-lookup"><span data-stu-id="c4090-261">Documents</span></span> </li>
<li> <span data-ttu-id="c4090-262">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="c4090-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4090-263">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="c4090-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c4090-264">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="c4090-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c4090-265">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="c4090-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4090-266">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="c4090-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4090-267">建立日期</span><span class="sxs-lookup"><span data-stu-id="c4090-267">Created date</span></span> </li>
<li> <span data-ttu-id="c4090-268">修改日期</span><span class="sxs-lookup"><span data-stu-id="c4090-268">Modified date</span></span> </li>
<li> <span data-ttu-id="c4090-269">建立者</span><span class="sxs-lookup"><span data-stu-id="c4090-269">Created by</span></span> </li>
<li> <span data-ttu-id="c4090-270">上次修改者</span><span class="sxs-lookup"><span data-stu-id="c4090-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="c4090-271">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="c4090-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="c4090-272">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="c4090-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="c4090-273">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="c4090-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="c4090-274">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="c4090-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4090-275">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="c4090-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="c4090-276">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="c4090-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4090-277">舊版</span><span class="sxs-lookup"><span data-stu-id="c4090-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="c4090-278">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="c4090-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="c4090-279">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="c4090-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="c4090-280">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="c4090-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="c4090-281">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="c4090-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="c4090-282">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="c4090-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="c4090-283">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="c4090-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4090-284">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="c4090-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="c4090-285">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="c4090-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="c4090-286">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4090-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c4090-287"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="c4090-288">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="c4090-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4090-289">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式) ，包括超過 10 MB 的檔案。</span><span class="sxs-lookup"><span data-stu-id="c4090-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="c4090-290">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="c4090-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4090-291">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-292">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-293">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="c4090-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4090-294">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="c4090-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4090-295">建立日期</span><span class="sxs-lookup"><span data-stu-id="c4090-295">Created date</span></span> </li>
<li> <span data-ttu-id="c4090-296">修改日期</span><span class="sxs-lookup"><span data-stu-id="c4090-296">Modified date</span></span> </li>
<li> <span data-ttu-id="c4090-297">建立者</span><span class="sxs-lookup"><span data-stu-id="c4090-297">Created by</span></span> </li>
<li> <span data-ttu-id="c4090-298">上次修改者</span><span class="sxs-lookup"><span data-stu-id="c4090-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4090-299">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="c4090-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="c4090-300">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="c4090-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4090-301">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="c4090-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4090-302">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="c4090-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="c4090-303">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-304">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-305">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="c4090-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4090-306">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="c4090-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4090-307">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="c4090-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4090-308">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="c4090-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4090-309">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="c4090-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4090-310">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="c4090-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4090-311">Google 相簿、表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="c4090-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="c4090-312">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="c4090-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="c4090-313">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="c4090-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="c4090-314">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="c4090-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="c4090-315">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="c4090-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="c4090-316">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="c4090-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c4090-317">共用磁碟機成員權限（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="c4090-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="c4090-318">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="c4090-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="c4090-319">標記為受限或未 copyable 的檔案</span><span class="sxs-lookup"><span data-stu-id="c4090-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="c4090-320">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4090-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c4090-321"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="c4090-322">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="c4090-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4090-323">文件</span><span class="sxs-lookup"><span data-stu-id="c4090-323">Documents</span></span> </li>
<li> <span data-ttu-id="c4090-324">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="c4090-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4090-325">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-326">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-327">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="c4090-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4090-328">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="c4090-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4090-329">建立日期</span><span class="sxs-lookup"><span data-stu-id="c4090-329">Created date</span></span> </li>
<li> <span data-ttu-id="c4090-330">修改日期</span><span class="sxs-lookup"><span data-stu-id="c4090-330">Modified date</span></span> </li>
<li> <span data-ttu-id="c4090-331">建立者</span><span class="sxs-lookup"><span data-stu-id="c4090-331">Created by</span></span> </li>
<li> <span data-ttu-id="c4090-332">上次修改者</span><span class="sxs-lookup"><span data-stu-id="c4090-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4090-333">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="c4090-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4090-334">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="c4090-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4090-335">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="c4090-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c4090-336">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-337">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-338">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="c4090-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4090-339">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="c4090-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4090-340">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="c4090-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4090-341">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="c4090-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4090-342">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="c4090-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4090-343">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="c4090-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4090-344">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="c4090-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="c4090-345">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="c4090-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="c4090-346">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="c4090-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="c4090-347">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="c4090-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c4090-348">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4090-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c4090-349"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="c4090-350">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="c4090-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4090-351">文件</span><span class="sxs-lookup"><span data-stu-id="c4090-351">Documents</span></span> </li>
<li> <span data-ttu-id="c4090-352">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="c4090-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4090-353">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-354">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-355">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="c4090-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4090-356">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="c4090-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4090-357">建立日期</span><span class="sxs-lookup"><span data-stu-id="c4090-357">Created date</span></span> </li>
<li> <span data-ttu-id="c4090-358">修改日期</span><span class="sxs-lookup"><span data-stu-id="c4090-358">Modified date</span></span> </li>
<li> <span data-ttu-id="c4090-359">建立者</span><span class="sxs-lookup"><span data-stu-id="c4090-359">Created by</span></span> </li>
<li> <span data-ttu-id="c4090-360">上次修改者</span><span class="sxs-lookup"><span data-stu-id="c4090-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4090-361">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="c4090-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="c4090-362">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="c4090-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4090-363">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="c4090-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4090-364">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="c4090-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c4090-365">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-366">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-367">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="c4090-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4090-368">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="c4090-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4090-369">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="c4090-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4090-370">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="c4090-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4090-371">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="c4090-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4090-372">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="c4090-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="c4090-373">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="c4090-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="c4090-374">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="c4090-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="c4090-375">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="c4090-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="c4090-376">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="c4090-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="c4090-377">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="c4090-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="c4090-378">指示使用者在移轉之後，與外部使用者再次共用內容）</span><span class="sxs-lookup"><span data-stu-id="c4090-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="c4090-379">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4090-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c4090-380">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="c4090-380">FastTrack responsibilities</span></span>

<span data-ttu-id="c4090-381">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="c4090-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c4090-382">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="c4090-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c4090-383">您的責任</span><span class="sxs-lookup"><span data-stu-id="c4090-383">Your responsibilities</span></span>

<span data-ttu-id="c4090-384">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="c4090-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c4090-385">如需詳細資訊，請參照在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊</span><span class="sxs-lookup"><span data-stu-id="c4090-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="c4090-386">你也要執行下列 SharePoint Online 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="c4090-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="c4090-387">使用您的移轉事件針對所有 SharePoint 小組網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="c4090-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="c4090-388">移轉至商務用 OneDrive</span><span class="sxs-lookup"><span data-stu-id="c4090-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="c4090-389">當您選擇使用 FastTrack 將您的檔案移轉到 商務用 OneDrive 時，我們會提供您移轉指引和資料移轉服務。</span><span class="sxs-lookup"><span data-stu-id="c4090-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c4090-390">我們會提供指引以協助規劃您的移轉、設定您的來源環境和 商務用 OneDrive，並充分利用我們的資料移轉服務來移轉您的檔案。</span><span class="sxs-lookup"><span data-stu-id="c4090-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="c4090-391">您可以建立您的移轉事件並設定排程。</span><span class="sxs-lookup"><span data-stu-id="c4090-391">You create and schedule your migration events.</span></span> <span data-ttu-id="c4090-392">我們會依照您的排程啟動移轉事件、監控進度，並提供狀態報表。</span><span class="sxs-lookup"><span data-stu-id="c4090-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c4090-393">當您的移轉事件完成後，您可以預期從您的來源環境中，檔案經適當排程及合格來源移轉到 商務用 OneDrive。</span><span class="sxs-lookup"><span data-stu-id="c4090-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="c4090-394">考量</span><span class="sxs-lookup"><span data-stu-id="c4090-394">Considerations</span></span>

  - <span data-ttu-id="c4090-395">所有的移轉事件都受 [商務用 OneDrive] 配額的限制。</span><span class="sxs-lookup"><span data-stu-id="c4090-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="c4090-396">如需詳細資訊，請參照 [<span class="underline">SharePoint Online 和 [商務用 OneDrive]：軟體使用範圍及限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="c4090-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="c4090-397">我們建議您將移轉的資料總量限制在你有權使用的 SharePoint Online 儲存額度 (包含您可能另外購買的額外儲存空間) 的 75%。</span><span class="sxs-lookup"><span data-stu-id="c4090-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="c4090-398">FastTrack 只會移轉到使用中的 [商務用 OneDrive] 磁碟機。</span><span class="sxs-lookup"><span data-stu-id="c4090-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="c4090-399">來源環境詳細資料</span><span class="sxs-lookup"><span data-stu-id="c4090-399">Source environment details</span></span>

<span data-ttu-id="c4090-400">我們的資料移轉服務可將資料從這些來源環境移轉出來：</span><span class="sxs-lookup"><span data-stu-id="c4090-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="c4090-401">檔案共用 (支援 SMB 2.0+ 之裝置的 SMB 檔案共用)。</span><span class="sxs-lookup"><span data-stu-id="c4090-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="c4090-402">單一 G Suite 環境 (僅限 Google 雲端硬碟)。</span><span class="sxs-lookup"><span data-stu-id="c4090-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="c4090-403">Box (Starter、Business、Enterprise)。</span><span class="sxs-lookup"><span data-stu-id="c4090-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="c4090-404">Dropbox for Teams (標準版和進階版)。</span><span class="sxs-lookup"><span data-stu-id="c4090-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="c4090-405">下列表格顯示每個來源環境特定的移轉詳細資料：</span><span class="sxs-lookup"><span data-stu-id="c4090-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="c4090-406"><strong>來源環境</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="c4090-407"><strong>移轉類型</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="c4090-408"><strong>可以移轉那些內容</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="c4090-409"><strong>不能移轉什麼內容</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c4090-410"><strong>任何支援 SMB 2.0+ 的檔案共用裝置</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="c4090-411">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="c4090-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4090-412">文件</span><span class="sxs-lookup"><span data-stu-id="c4090-412">Documents</span></span> </li>
<li> <span data-ttu-id="c4090-413">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="c4090-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4090-414">使用者層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="c4090-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c4090-415">群組層級檔案和資料夾權限\*</span><span class="sxs-lookup"><span data-stu-id="c4090-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c4090-416">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="c4090-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4090-417">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="c4090-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4090-418">建立日期</span><span class="sxs-lookup"><span data-stu-id="c4090-418">Created date</span></span> </li>
<li> <span data-ttu-id="c4090-419">修改日期</span><span class="sxs-lookup"><span data-stu-id="c4090-419">Modified date</span></span> </li>
<li> <span data-ttu-id="c4090-420">建立者</span><span class="sxs-lookup"><span data-stu-id="c4090-420">Created by</span></span> </li>
<li> <span data-ttu-id="c4090-421">上次修改者</span><span class="sxs-lookup"><span data-stu-id="c4090-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="c4090-422">\*需要設定目錄同步處理。</span><span class="sxs-lookup"><span data-stu-id="c4090-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="c4090-423">只移轉公開給 [Windows 檔案總管] 的 NTFS 權限。</span><span class="sxs-lookup"><span data-stu-id="c4090-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="c4090-424">不移轉直接在檔案共用裝置上管理的權限。</span><span class="sxs-lookup"><span data-stu-id="c4090-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="c4090-425">若資料儲存在 SMB 2.0 裝置上，將會移轉 SMB 通訊協定公開的 NTFS 等同權限。</span><span class="sxs-lookup"><span data-stu-id="c4090-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="c4090-426">擁有權歷程記錄與先前的版本</span><span class="sxs-lookup"><span data-stu-id="c4090-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="c4090-427">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="c4090-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4090-428">舊版</span><span class="sxs-lookup"><span data-stu-id="c4090-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="c4090-429">Windows 檔案和資料夾屬性 (例如唯讀、隱藏)</span><span class="sxs-lookup"><span data-stu-id="c4090-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="c4090-430">非 Windows New Technology File System (NTFS) 和 NTFS 的進階權限和特殊設定：</span><span class="sxs-lookup"><span data-stu-id="c4090-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="c4090-431">明確拒絕權限 (在移轉之後移除，內容受限於平行權限或上層資料夾權限)</span><span class="sxs-lookup"><span data-stu-id="c4090-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="c4090-432">NTFS 稽核組態</span><span class="sxs-lookup"><span data-stu-id="c4090-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="c4090-433">檔案分類基礎結構 (FCI) 提供的其他檔案中繼資料</span><span class="sxs-lookup"><span data-stu-id="c4090-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="c4090-434">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="c4090-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4090-435">隱藏的共用</span><span class="sxs-lookup"><span data-stu-id="c4090-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="c4090-436">共用 (例如共用層級授與的權限)</span><span class="sxs-lookup"><span data-stu-id="c4090-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="c4090-437">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4090-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c4090-438"><strong>單一 G Suite 環境 (僅限 Google 雲端硬碟)</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="c4090-439">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="c4090-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4090-440">Google 文件、試算表及投影片 (檔案轉換為 Office 等同格式 ，包括超過 10 MB 的檔案)</span><span class="sxs-lookup"><span data-stu-id="c4090-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="c4090-441">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="c4090-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4090-442">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-443">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-444">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="c4090-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4090-445">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="c4090-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4090-446">建立日期</span><span class="sxs-lookup"><span data-stu-id="c4090-446">Created date</span></span> </li>
<li> <span data-ttu-id="c4090-447">修改日期</span><span class="sxs-lookup"><span data-stu-id="c4090-447">Modified date</span></span> </li>
<li> <span data-ttu-id="c4090-448">建立者</span><span class="sxs-lookup"><span data-stu-id="c4090-448">Created by</span></span> </li>
<li> <span data-ttu-id="c4090-449">上次修改者</span><span class="sxs-lookup"><span data-stu-id="c4090-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4090-450">共用的磁碟 (資料夾和檔案)</span><span class="sxs-lookup"><span data-stu-id="c4090-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="c4090-451">正在移轉屬於 Google Drive 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="c4090-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4090-452">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="c4090-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4090-453">檔案與資料夾描述、資料夾顏色</span><span class="sxs-lookup"><span data-stu-id="c4090-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="c4090-454">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-455">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-456">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="c4090-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4090-457">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="c4090-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4090-458">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="c4090-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4090-459">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="c4090-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4090-460">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="c4090-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4090-461">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="c4090-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4090-462">Google 相簿表單、地圖及其他連線的應用程式</span><span class="sxs-lookup"><span data-stu-id="c4090-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="c4090-463">Google 繪圖</span><span class="sxs-lookup"><span data-stu-id="c4090-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="c4090-464">組織外部的共用內容</span><span class="sxs-lookup"><span data-stu-id="c4090-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="c4090-465">內容不是由移轉中的 Google 雲端硬碟帳戶所擁有</span><span class="sxs-lookup"><span data-stu-id="c4090-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="c4090-466">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="c4090-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="c4090-467">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="c4090-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c4090-468">共用磁碟機成員資格權限 (<strong>注意事項</strong>：使用 Google 雲端硬碟系統管理員報告來識別共用磁碟機的成員資格。</span><span class="sxs-lookup"><span data-stu-id="c4090-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="c4090-469">指導使用者在進行移轉之前，在目標上設定這些成員資格的設定值。)</span><span class="sxs-lookup"><span data-stu-id="c4090-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="c4090-470">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4090-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c4090-471"><strong>Box (Starter、Business、Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="c4090-472">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="c4090-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4090-473">文件</span><span class="sxs-lookup"><span data-stu-id="c4090-473">Documents</span></span> </li>
<li> <span data-ttu-id="c4090-474">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="c4090-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4090-475">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-476">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-477">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="c4090-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4090-478">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="c4090-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4090-479">建立日期</span><span class="sxs-lookup"><span data-stu-id="c4090-479">Created date</span></span> </li>
<li> <span data-ttu-id="c4090-480">修改日期</span><span class="sxs-lookup"><span data-stu-id="c4090-480">Modified date</span></span> </li>
<li> <span data-ttu-id="c4090-481">建立者</span><span class="sxs-lookup"><span data-stu-id="c4090-481">Created by</span></span> </li>
<li> <span data-ttu-id="c4090-482">上次修改者</span><span class="sxs-lookup"><span data-stu-id="c4090-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4090-483">正在移轉屬於 Box 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="c4090-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4090-484">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="c4090-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4090-485">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="c4090-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c4090-486">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-487">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-488">Box 標記和進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="c4090-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4090-489">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="c4090-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4090-490">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="c4090-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4090-491">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="c4090-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4090-492">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="c4090-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4090-493">遭封鎖或非作用中的使用者</span><span class="sxs-lookup"><span data-stu-id="c4090-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c4090-494">Box 應用程式、書籤、我的最愛及工作流程</span><span class="sxs-lookup"><span data-stu-id="c4090-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="c4090-495">不屬於已移轉的 Box 帳戶的內容</span><span class="sxs-lookup"><span data-stu-id="c4090-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="c4090-496">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Box 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="c4090-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="c4090-497">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="c4090-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c4090-498">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4090-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c4090-499"><strong>Dropbox for Teams (標準版和進階版)</strong></span><span class="sxs-lookup"><span data-stu-id="c4090-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="c4090-500">單一或多個階段</span><span class="sxs-lookup"><span data-stu-id="c4090-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c4090-501">文件</span><span class="sxs-lookup"><span data-stu-id="c4090-501">Documents</span></span> </li>
<li> <span data-ttu-id="c4090-502">檔案與資料夾結構</span><span class="sxs-lookup"><span data-stu-id="c4090-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c4090-503">使用者層次資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-504">群組層級資料夾權限</span><span class="sxs-lookup"><span data-stu-id="c4090-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c4090-505">小於 15 GB 的檔案</span><span class="sxs-lookup"><span data-stu-id="c4090-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c4090-506">基本文件與資料夾的中繼資料：</span><span class="sxs-lookup"><span data-stu-id="c4090-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c4090-507">建立日期</span><span class="sxs-lookup"><span data-stu-id="c4090-507">Created date</span></span> </li>
<li> <span data-ttu-id="c4090-508">修改日期</span><span class="sxs-lookup"><span data-stu-id="c4090-508">Modified date</span></span> </li>
<li> <span data-ttu-id="c4090-509">建立者</span><span class="sxs-lookup"><span data-stu-id="c4090-509">Created by</span></span> </li>
<li> <span data-ttu-id="c4090-510">上次修改者</span><span class="sxs-lookup"><span data-stu-id="c4090-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c4090-511">共用的小組資料夾和內容</span><span class="sxs-lookup"><span data-stu-id="c4090-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="c4090-512">正在移轉屬於 Dropbox 帳戶的共用內容</span><span class="sxs-lookup"><span data-stu-id="c4090-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c4090-513">擁有權歷程記錄、先前的版本和註解</span><span class="sxs-lookup"><span data-stu-id="c4090-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c4090-514">檔案與資料夾描述</span><span class="sxs-lookup"><span data-stu-id="c4090-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c4090-515">使用者層次檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-516">群組層級檔案權限</span><span class="sxs-lookup"><span data-stu-id="c4090-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c4090-517">進階中繼資料</span><span class="sxs-lookup"><span data-stu-id="c4090-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c4090-518">檔案鎖定屬性</span><span class="sxs-lookup"><span data-stu-id="c4090-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c4090-519">內容中的內嵌 URL 轉換</span><span class="sxs-lookup"><span data-stu-id="c4090-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c4090-520">丟到垃圾筒的項目</span><span class="sxs-lookup"><span data-stu-id="c4090-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="c4090-521">無法存取或損毀的文件</span><span class="sxs-lookup"><span data-stu-id="c4090-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c4090-522">已卸載的 Dropbox 資料夾</span><span class="sxs-lookup"><span data-stu-id="c4090-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="c4090-523">已刪除或中斷連線的使用者</span><span class="sxs-lookup"><span data-stu-id="c4090-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="c4090-524">Dropbox Paper、Showcases 和 Spaces</span><span class="sxs-lookup"><span data-stu-id="c4090-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="c4090-525">Dropbox 應用程式和我的最愛 (釘選/星號)</span><span class="sxs-lookup"><span data-stu-id="c4090-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="c4090-526">不是由已移轉的 Dropbox 帳戶所擁有的內容</span><span class="sxs-lookup"><span data-stu-id="c4090-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="c4090-527">外部使用者的權限和中繼資料（<strong>注意事項</strong>：使用 Dropbox 報告來識別與外部使用者共用的內容。</span><span class="sxs-lookup"><span data-stu-id="c4090-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="c4090-528">指示使用者在移轉之後，與外部使用者再次共用內容。）</span><span class="sxs-lookup"><span data-stu-id="c4090-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c4090-529">檔案或資料夾超過目前的<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint 線上限制和限制</span></a> </span><span class="sxs-lookup"><span data-stu-id="c4090-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c4090-530">FastTrack 責任</span><span class="sxs-lookup"><span data-stu-id="c4090-530">FastTrack responsibilities</span></span>

<span data-ttu-id="c4090-531">我們的 FastTrack 專家在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="c4090-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c4090-532">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="c4090-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c4090-533">您的責任</span><span class="sxs-lookup"><span data-stu-id="c4090-533">Your responsibilities</span></span>

<span data-ttu-id="c4090-534">由您在進行移轉專案時執行標準動作。</span><span class="sxs-lookup"><span data-stu-id="c4090-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c4090-535">如需詳細資訊，請參閱在 [流程和預期](process-and-expectations.md) 中的資料移轉責任資訊。</span><span class="sxs-lookup"><span data-stu-id="c4090-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c4090-536">你也要執行下列 [商務用 OneDrive] 移轉動作特定的活動：</span><span class="sxs-lookup"><span data-stu-id="c4090-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="c4090-537">使用您的移轉事件針對所有 [商務用 OneDrive] 網站進行佈建。</span><span class="sxs-lookup"><span data-stu-id="c4090-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
