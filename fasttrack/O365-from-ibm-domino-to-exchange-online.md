---
title: 附錄 A：從 IBM Domino 移轉至 Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 12/03/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 從 IBM Domino 移轉至 Exchange Online 包含幾個重要的層面，包括下列階段期間發生的情況：
ms.openlocfilehash: c3efb9f7d68776e7ca2d846d7e9f7ad1bcfc5398
ms.sourcegitcommit: 39616c06c0617700b1393e055894acb6aa6f7776
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 12/02/2019
ms.locfileid: "39662974"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="f7731-103">附錄 A：從 IBM Domino 移轉至 Exchange Online</span><span class="sxs-lookup"><span data-stu-id="f7731-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="f7731-104">從 IBM Domino 移轉至 Exchange Online 包含幾個重要的層面，包括下列階段期間發生的情況：</span><span class="sxs-lookup"><span data-stu-id="f7731-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="f7731-105">始階段</span><span class="sxs-lookup"><span data-stu-id="f7731-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="f7731-106">評估階段</span><span class="sxs-lookup"><span data-stu-id="f7731-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="f7731-107">修復階段</span><span class="sxs-lookup"><span data-stu-id="f7731-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="f7731-108">啟用階段</span><span class="sxs-lookup"><span data-stu-id="f7731-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="f7731-109">移轉階段</span><span class="sxs-lookup"><span data-stu-id="f7731-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="f7731-110">身分識別</span><span class="sxs-lookup"><span data-stu-id="f7731-110">Identities</span></span>

<span data-ttu-id="f7731-111">您負責建立和管理身分識別 (僅限雲端、同步處理，或與其內部部署 Active Directory 同盟)。</span><span class="sxs-lookup"><span data-stu-id="f7731-111">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory).</span></span> <span data-ttu-id="f7731-112">您必須在上架的早期階段，完成 Domino 與內部部署 Active Directory 或 Azure Active Directory 之間的身份識別對應 (若未存在)。</span><span class="sxs-lookup"><span data-stu-id="f7731-112">You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure Active Directory during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="f7731-113">共存</span><span class="sxs-lookup"><span data-stu-id="f7731-113">Coexistence</span></span>

<span data-ttu-id="f7731-114">「適用於 Office 365 的 FastTrack 中心權益」提供內部部署 Domino 環境與 Exchange Online 之間的雙向郵件流量給所有客戶。</span><span class="sxs-lookup"><span data-stu-id="f7731-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="f7731-115">移轉</span><span class="sxs-lookup"><span data-stu-id="f7731-115">Migration</span></span>

<span data-ttu-id="f7731-p102">從 Domino 移轉到 Exchange Online 的標準 FastTrack Center 程序牽涉到先預先接移資料至 Azure 再移轉至 Exchange Online 信箱。 FastTrack 移轉要求 FastTrack Center 和您在不同的上架階段中執行活動。我們在以下幾節中會說明這些活動。</span><span class="sxs-lookup"><span data-stu-id="f7731-p102">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes. FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="f7731-p103">透過 FastTrack 服務來轉移的資料，得於美國或任何一處 Microsoft 的維護設備間進行傳輸、儲存及處理。FastTrack 服務並非專為受特殊法律或法規規範所約束之資料而設計。</span><span class="sxs-lookup"><span data-stu-id="f7731-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="f7731-121">起始階段</span><span class="sxs-lookup"><span data-stu-id="f7731-121">Initiate phase</span></span>

 <span data-ttu-id="f7731-122">**關鍵動作**</span><span class="sxs-lookup"><span data-stu-id="f7731-122">**Key actions**</span></span>
  
- <span data-ttu-id="f7731-123">將 Domino 識別為來源郵件平台。</span><span class="sxs-lookup"><span data-stu-id="f7731-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="f7731-124">決定 FastTrack Center 是否執行移轉。</span><span class="sxs-lookup"><span data-stu-id="f7731-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="f7731-125">**客戶責任**</span><span class="sxs-lookup"><span data-stu-id="f7731-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="f7731-126">提供來源訊息平台的基本資訊，並與 FastTrack Center 確認移轉目的。</span><span class="sxs-lookup"><span data-stu-id="f7731-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="f7731-127">參與 FastTrack Center 權益程序的逐步解說。</span><span class="sxs-lookup"><span data-stu-id="f7731-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="f7731-128">簽署 FastTrack 服務合約。</span><span class="sxs-lookup"><span data-stu-id="f7731-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="f7731-129">評估階段</span><span class="sxs-lookup"><span data-stu-id="f7731-129">Assess phase</span></span>

 <span data-ttu-id="f7731-130">**關鍵動作**</span><span class="sxs-lookup"><span data-stu-id="f7731-130">**Key actions**</span></span>
  
- <span data-ttu-id="f7731-131">FastTrack Center 與客戶召開移轉研討會。</span><span class="sxs-lookup"><span data-stu-id="f7731-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="f7731-132">您完成移轉必要元件，像是移轉問卷和佈建系統管理工作站。</span><span class="sxs-lookup"><span data-stu-id="f7731-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="f7731-133">移轉 Domino 的評估會在您的內部部署環境中執行。</span><span class="sxs-lookup"><span data-stu-id="f7731-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="f7731-134">**客戶責任**</span><span class="sxs-lookup"><span data-stu-id="f7731-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="f7731-135">佈建 FastTrack Center 用來管理上架和移轉工作的系統管理工作站，如評估、建立複本、稽核、在移轉期間設定轉寄等。</span><span class="sxs-lookup"><span data-stu-id="f7731-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="f7731-p104">評估對成功計劃和執行速移轉很重要。它是由需要特定存取 Domino 環境的移轉架構設計人員執行。必要的系統管理工作站元件包括設定來存取所有來源 Domino 郵件伺服器的 Notes 用戶端，和 Azure Domino 複本預備伺服器。</span><span class="sxs-lookup"><span data-stu-id="f7731-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="f7731-p105">提供移轉小組遠端存取系統管理工作站、帳戶及權限來執行評估與移轉活動。這包括在內部部署和在 Exchange Online 中，佈建移轉所需的系統管理權限的多個帳戶。</span><span class="sxs-lookup"><span data-stu-id="f7731-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="f7731-p106">開啟防火牆連接埠。輸出連接埠必須在來源 Domino 郵件伺服器與 Azure 預備伺服器之間開啟。其他通訊用連接埠 (如系統管理工作站、來源 Domino 伺服器和 Exchange 伺服器內部部署 (如果有的話)) 也必須開啟。</span><span class="sxs-lookup"><span data-stu-id="f7731-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the Azure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="f7731-p107">啟用來源 Domino 環境與 Azure Domino 預備伺服器之間的交互憑證以進行複寫。交互憑證工作是在客戶的 Domino 系統管理員與 FastTrack Center 之間協調。</span><span class="sxs-lookup"><span data-stu-id="f7731-p107">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="f7731-146">完成移轉份問卷，會擷取在 Azure 中設定移轉環境所需的資訊 (如工具、指令碼和移轉伺服器)。</span><span class="sxs-lookup"><span data-stu-id="f7731-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="f7731-147">請確定 Office 365 的目標信箱已啟用 Messaging Application Program Interface (MAPI) 通訊協定。</span><span class="sxs-lookup"><span data-stu-id="f7731-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="f7731-p108">某些 Office 365 方案不支援 MAPI 通訊協定。若要移轉資料，這些方案的信箱必須在移轉事件發生之前轉換為支援 MAPI 的方案。移轉完畢之後，可以重新變更這些方案。</span><span class="sxs-lookup"><span data-stu-id="f7731-p108">Some Office 365 plans don't support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="f7731-151">修復階段</span><span class="sxs-lookup"><span data-stu-id="f7731-151">Remediate phase</span></span>

 <span data-ttu-id="f7731-152">**關鍵動作**</span><span class="sxs-lookup"><span data-stu-id="f7731-152">**Key actions**</span></span>
  
- <span data-ttu-id="f7731-153">FastTrack Center 會檢閱移轉評估報告，並測試您使用問卷所提供的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="f7731-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="f7731-154">必須為您完成 FastTrack Center 所建議的修復項目。</span><span class="sxs-lookup"><span data-stu-id="f7731-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="f7731-155">**客戶責任**</span><span class="sxs-lookup"><span data-stu-id="f7731-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="f7731-156">依據 FastTrack Cente 提供的指導方針修復 Domino 環境 (例如，在郵件檔案中，設定識別為遺失的任何必要權限)。</span><span class="sxs-lookup"><span data-stu-id="f7731-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="f7731-157">確定 Domino 信箱低於移轉所允許的最大大小。</span><span class="sxs-lookup"><span data-stu-id="f7731-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="f7731-158">雖然 FastTrack 會移轉多達允許的總目標大小的 85% 信箱，但嘗試移轉大於 2 GB 的信箱會帶來額外的風險，如：</span><span class="sxs-lookup"><span data-stu-id="f7731-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="f7731-p109">延長移轉持續時間。    </span><span class="sxs-lookup"><span data-stu-id="f7731-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="f7731-p110">佔用移轉其他信箱時所用的資源。    </span><span class="sxs-lookup"><span data-stu-id="f7731-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="f7731-161">大幅增加錯誤率。</span><span class="sxs-lookup"><span data-stu-id="f7731-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="f7731-p111">準備要移轉的郵件資料庫及其存取控制清單 (ACL)。您必須執行一些修復步驟，才能將郵件資料庫及其權限成功移轉至 Exchange Online 的共用信箱。其中部分步驟如下：</span><span class="sxs-lookup"><span data-stu-id="f7731-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online. A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="f7731-165">移除 Domino 目錄中的現有郵件資料庫項目並建立新的個人記錄。</span><span class="sxs-lookup"><span data-stu-id="f7731-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="f7731-166">在內部部署 Active Directory 中建立擁有郵件功能的萬用安全性群組，其同步至 Office 365 Azure Active Directory，並且用來在 Exchange Online 中設定共用信箱上的權限。</span><span class="sxs-lookup"><span data-stu-id="f7731-166">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure Active Directory and used to configure permissions on the shared mailbox in Exchange Online.</span></span> <span data-ttu-id="f7731-167">這會將郵件資料庫的權限集轉移至 Exchange Online 的共用信箱。</span><span class="sxs-lookup"><span data-stu-id="f7731-167">This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="f7731-168">當一般使用者準備就緒，並且經過新的郵件系統與用戶端訓練後，即可立即啟動。</span><span class="sxs-lookup"><span data-stu-id="f7731-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="f7731-169">啟用階段</span><span class="sxs-lookup"><span data-stu-id="f7731-169">Enable phase</span></span>

 <span data-ttu-id="f7731-170">**關鍵動作**</span><span class="sxs-lookup"><span data-stu-id="f7731-170">**Key actions**</span></span>
  
- <span data-ttu-id="f7731-171">FastTrack Center：</span><span class="sxs-lookup"><span data-stu-id="f7731-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="f7731-172">在 Azure 中設立移轉環境。</span><span class="sxs-lookup"><span data-stu-id="f7731-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="f7731-173">在內部部署系統管理工作站上設定移轉工具。</span><span class="sxs-lookup"><span data-stu-id="f7731-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="f7731-174">設定並示範如何使用自動匯入工具。</span><span class="sxs-lookup"><span data-stu-id="f7731-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="f7731-175">進行所有移轉元件驗證，並執行測試移轉。</span><span class="sxs-lookup"><span data-stu-id="f7731-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="f7731-176">**客戶責任**</span><span class="sxs-lookup"><span data-stu-id="f7731-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="f7731-p113">負責排程信箱移轉的人員，必須瞭解如何使用自動匯入工具。您可以使用這個工具將移轉排程匯入排程資料庫中，讓 FastTrack Center 用來執行預先移轉活動。</span><span class="sxs-lookup"><span data-stu-id="f7731-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="f7731-179">執行預先移轉活動，如匯入使用者排程、分析稽核報告、修復任何問題，以及重新匯入有問題的使用者帳戶。</span><span class="sxs-lookup"><span data-stu-id="f7731-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="f7731-p114">預先移轉活動是在您與 FastTrack Center 之間協調。匯入使用者移轉排程後複寫至 Azure。</span><span class="sxs-lookup"><span data-stu-id="f7731-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="f7731-p115">複寫所需的時間視資料量而定。FastTrack Center 接著會執行稽核來判斷移轉整備度。會將稽核結果提供給您，通常需要進行後續修復。由於它們必須在使用者的排程移轉之前開始，因此將這些步驟統稱為「T-minus」。</span><span class="sxs-lookup"><span data-stu-id="f7731-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="f7731-186">移轉階段</span><span class="sxs-lookup"><span data-stu-id="f7731-186">Migrate phase</span></span>

 <span data-ttu-id="f7731-187">**關鍵動作**</span><span class="sxs-lookup"><span data-stu-id="f7731-187">**Key actions**</span></span>
  
- <span data-ttu-id="f7731-188">FastTrack Center：</span><span class="sxs-lookup"><span data-stu-id="f7731-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="f7731-189">執行試驗與快速移轉。</span><span class="sxs-lookup"><span data-stu-id="f7731-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="f7731-190">執行移轉事件和 T-minus 活動。</span><span class="sxs-lookup"><span data-stu-id="f7731-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="f7731-191">提供移轉後協助。</span><span class="sxs-lookup"><span data-stu-id="f7731-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="f7731-192">**客戶責任**</span><span class="sxs-lookup"><span data-stu-id="f7731-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="f7731-193">在移轉 21 天前識別並匯入移轉排程。</span><span class="sxs-lookup"><span data-stu-id="f7731-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="f7731-p116">這項工作很重要，因為預先移轉活動牽涉到修復，並可能在實際移轉日 (T-0) 之前重試在不同階段建立複本。移轉一些信箱時，正在其他信箱上執行 T-minus 活動。這必須適當規劃和協調。</span><span class="sxs-lookup"><span data-stu-id="f7731-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="f7731-197">修正在 T-minus 活動過程中識別的問題。</span><span class="sxs-lookup"><span data-stu-id="f7731-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="f7731-198">解決並修正會影響移轉活動的任何 Domino 伺服器問題。</span><span class="sxs-lookup"><span data-stu-id="f7731-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="f7731-199">與一般使用者溝通即將來臨的移轉日期。</span><span class="sxs-lookup"><span data-stu-id="f7731-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="f7731-200">為新的郵件系統與用戶端執行一般使用者整備活動和訓練。</span><span class="sxs-lookup"><span data-stu-id="f7731-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="f7731-p117">識別並報告移轉後問題。FastTrack Center 會提供移轉後協助直到移轉後 T+5 日，之後您必須自行負責。您可以記錄移轉後票證問題，像是遺漏電子郵件、行事曆項目和連絡人，或信箱中有重複的項目。</span><span class="sxs-lookup"><span data-stu-id="f7731-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="f7731-204">FastTrack Center 不涵蓋部署、授權費用，或支援目錄準備 (包括 Domino 至 Active Directory 目錄同步處理)、Notes 應用程式交互操作性的軟體附加元件、自我服務移轉，或封存檔移轉等相關事宜。</span><span class="sxs-lookup"><span data-stu-id="f7731-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  

