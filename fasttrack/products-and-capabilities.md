---
title: 產品與功能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 本主題包括 FastTrack 所支援之工作負載案例的詳細資料，以及在開始之前所需的來源環境預期。 根據您目前的設定，我們會與您合作，建立修復計畫，以將來源環境帶入成功上架的最低需求。
ms.openlocfilehash: 43c8edc915d45c1af84155d82d995860cd966950
ms.sourcegitcommit: c4f9375811fd23d01edd308108340ace15ec4db7
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/02/2021
ms.locfileid: "53255502"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="fbe81-104">產品與功能</span><span class="sxs-lookup"><span data-stu-id="fbe81-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="fbe81-105">FastTrack 所支援的服務和案例</span><span class="sxs-lookup"><span data-stu-id="fbe81-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="fbe81-106">本主題包括 FastTrack 所支援之工作負載案例的詳細資料，以及在開始之前所需的來源環境預期。</span><span class="sxs-lookup"><span data-stu-id="fbe81-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="fbe81-107">根據您目前的設定，我們會與您合作，建立修復計畫，以將來源環境帶入成功上架的最低需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="fbe81-108">FastTrack 提供指引，協助您先瞭解所有 Microsoft Online) 服務 (通用的核心功能，然後再上架每個合格的服務：</span><span class="sxs-lookup"><span data-stu-id="fbe81-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="fbe81-109">一般</span><span class="sxs-lookup"><span data-stu-id="fbe81-109">General</span></span>](#general)
  - [<span data-ttu-id="fbe81-110">安全性與合規性</span><span class="sxs-lookup"><span data-stu-id="fbe81-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="fbe81-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="fbe81-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="fbe81-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="fbe81-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="fbe81-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="fbe81-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="fbe81-114">Windows 虛擬桌面</span><span class="sxs-lookup"><span data-stu-id="fbe81-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="fbe81-115">應用程式保證</span><span class="sxs-lookup"><span data-stu-id="fbe81-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="fbe81-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="fbe81-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="fbe81-117">如需有關 Office 365 US Government 來源環境預期的資訊，請參閱 [Office 365 US Government 的來源環境預期](/us-gov-appendix-source-environment-expectations)。</span><span class="sxs-lookup"><span data-stu-id="fbe81-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="fbe81-118">一般</span><span class="sxs-lookup"><span data-stu-id="fbe81-118">General</span></span>

<table>
<table style="width: 100%">
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="fbe81-119">服務</span><span class="sxs-lookup"><span data-stu-id="fbe81-119">Service</span></span></th>
<th><span data-ttu-id="fbe81-120">FastTrack 指引詳細資料</span><span class="sxs-lookup"><span data-stu-id="fbe81-120">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="fbe81-121">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="fbe81-121">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="fbe81-122"><strong>核心上架</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-123">我們提供核心上架的遠端指導，包含服務布建、租使用者和身分識別整合。</span><span class="sxs-lookup"><span data-stu-id="fbe81-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="fbe81-124">此外，它還包含為 Exchange Online、SharePoint 線上及 Microsoft Teams 等上架服務奠定基礎的步驟，包括<a href="/office365/enterprise/office-365-network-connectivity-principles">安全性、網路連線能力及規範的討論</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>   

<span data-ttu-id="fbe81-125">將一或多個合格服務上架的動作可以從核心上架完成時開始。</span><span class="sxs-lookup"><span data-stu-id="fbe81-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="fbe81-126"></li>
</ul>  

<strong> 身分識別整合 </strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="fbe81-127">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="fbe81-128">準備內部部署 Active Directory identity 以進行同步處理至 Azure Active Directory (Azure ad) 包括安裝及設定 azure ad 連線 (單一或多樹系) 和授權 (（包含以群組為基礎的授權) ）。</span><span class="sxs-lookup"><span data-stu-id="fbe81-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="fbe81-129">建立雲端身分識別（包括使用以群組為基礎的授權在內的大量匯入和授權）。</span><span class="sxs-lookup"><span data-stu-id="fbe81-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="fbe81-130">為您的雲端旅程選擇和啟用正確的驗證方法、密碼雜湊同步處理、傳遞驗證，或 Active Directory Federation Services (AD FS) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="fbe81-131">使用 passwordless 驗證，為您的使用者選擇及啟用更為便利的驗證經驗 (Fast Identity Online (FIDO) 2 或 Microsoft Authenticator 應用程式) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="fbe81-132">使用單一 Active Directory 樹系和身分識別與 Azure AD 連線工具同步處理的客戶，啟用 AD FS。</span><span class="sxs-lookup"><span data-stu-id="fbe81-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="fbe81-133">這需要 Windows Server 2012 R2 Active Directory Federation Services 2.0 或更新版本。</span><span class="sxs-lookup"><span data-stu-id="fbe81-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="fbe81-134">使用密碼雜湊同步處理或透過驗證，將驗證從 AD FS 遷移至 Azure AD。</span><span class="sxs-lookup"><span data-stu-id="fbe81-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="fbe81-135">遷移預先整合的應用程式 (像 Azure AD 圖庫軟體即服務 (SaaS) 應用程式) 從 AD FS 至 Azure AD for single 登錄 (SSO) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="fbe81-136">從 Azure AD 圖庫啟用 SaaS 應用程式與 SSO 的整合。</span><span class="sxs-lookup"><span data-stu-id="fbe81-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="fbe81-137">針對 <a href="/azure/active-directory/saas-apps/tutorial-list">應用程式整合教學課程清單 </a> 中列出的預先整合的 SaaS 應用程式啟用自動使用者布建， (限制于 Azure AD 圖庫 SaaS 應用程式和輸出布建) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list </a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>

</td>

<td>  <span data-ttu-id="fbe81-138"><strong>網路啟用 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="fbe81-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="fbe81-139">在 FastTrack 的益處中，我們建議您做為連線至雲端服務的最佳作法，以確保最高的效能等級 Microsoft 365。</span><span class="sxs-lookup"><span data-stu-id="fbe81-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="fbe81-140"><strong>Active Directory</strong>樹系這些功能樹系層級已設定為 Windows Server 2003 +，使用下列樹系設定：</span><span class="sxs-lookup"><span data-stu-id="fbe81-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-141">單一 Active Directory 樹系。</span><span class="sxs-lookup"><span data-stu-id="fbe81-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-142">單一 Active Directory 帳戶樹系和資源樹系 (Exchange 和/或 Lync 2010、Lync 2013 或 商務用 Skype) 拓樸。</span><span class="sxs-lookup"><span data-stu-id="fbe81-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-143">多個 Active Directory 帳戶樹系和資源樹系 (Exchange 和/或 Lync 2010、Lync 2013 或 商務用 Skype) 拓樸。</span><span class="sxs-lookup"><span data-stu-id="fbe81-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-144">多重 Active Directory 帳戶樹系，其中一個樹系為包含 Exchange 和/或 Lync 2010、Lync 2013 或商務用 Skype 的集中式 Active Directory 帳戶樹系。</span><span class="sxs-lookup"><span data-stu-id="fbe81-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-145">多個 Active Directory 帳戶樹系，每個都有自己的 Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="fbe81-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-146">承租人設定與 Azure Active Directory 的整合所需的工作（如有需要）。</span><span class="sxs-lookup"><span data-stu-id="fbe81-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="fbe81-147">
  <strong>重要</strong>  </span><span class="sxs-lookup"><span data-stu-id="fbe81-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="fbe81-148">針對多樹系 Active Directory 案例，如果部署 lync 2010、lync 2013 或商務用 Skype，必須將其部署在與 Exchange 相同的 Active Directory 樹系中。</span><span class="sxs-lookup"><span data-stu-id="fbe81-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-149">在 Exchange 多重混合式設定中執行多個 Exchange 組織的多個 Active Directory 樹系時，不支援共用使用者主體名稱 (UPN) 來源樹系之間的命名空間。</span><span class="sxs-lookup"><span data-stu-id="fbe81-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="fbe81-150">同時也應該分隔 Exchange 組織之間的主要 SMTP 命名空間。</span><span class="sxs-lookup"><span data-stu-id="fbe81-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="fbe81-151">如需詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?linkid=845444">使用多個 Active Directory 樹系的混合部署</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-152">對於所有多重樹系設定，Active Directory Federation Services (AD FS) 部署超出範圍。</span><span class="sxs-lookup"><span data-stu-id="fbe81-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="fbe81-153">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。</span><span class="sxs-lookup"><span data-stu-id="fbe81-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="fbe81-154"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-155">我們提供下列專案的遠端部署指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-156">解決部署問題。</span><span class="sxs-lookup"><span data-stu-id="fbe81-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-157">使用 Microsoft 365 系統管理中心和 Windows PowerShell 指派以使用者和以裝置為基礎的授權。</span><span class="sxs-lookup"><span data-stu-id="fbe81-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-158">使用隨選即用從 Office 365 入口網站安裝 Microsoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="fbe81-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-159">在 iOS 或 Android 裝置上安裝 Office Mobile 應用程式 (如 Outlook Mobile、Word Mobile、Excel Mobile 和 PowerPoint Mobile)。</span><span class="sxs-lookup"><span data-stu-id="fbe81-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-160">使用 Office 365 部署工具來設定更新設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-161">本地或雲端安裝的選取項目和設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-162">使用 Office 自訂工具或原生 XML 建立 Office 部署工具，以設定部署套件。</span><span class="sxs-lookup"><span data-stu-id="fbe81-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-163">使用 Microsoft Endpoint Configuration Manager 部署，包含協助建立 Microsoft Endpoint Configuration Manager 套件。</span><span class="sxs-lookup"><span data-stu-id="fbe81-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="fbe81-164">此外，如果您有宏或增益集與舊版 Office 搭配運作，而且您遇到相容性問題，我們會提供指導方針以透過應用程式保證計畫來修正相容性問題，而不需額外收費。</span><span class="sxs-lookup"><span data-stu-id="fbe81-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="fbe81-165">如需詳細資訊，請參閱<strong>App</strong>的部分<a href="#windows-10">Windows 10</a> 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="fbe81-166">線上用戶端軟體必須具備<a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="fbe81-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="fbe81-167"><strong>網路健康情況</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-168">我們提供的遠端指導，可從您的環境取得及解讀重要的網路連線資料，以顯示組織的網站與 Microsoft 的 <a href="/office365/enterprise/office-365-network-connectivity-principles">網路連線原則</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="fbe81-169">這會強調您的網路得分，它會直接影響到遷移速度、使用者經驗、服務效能和可靠性。</span><span class="sxs-lookup"><span data-stu-id="fbe81-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="fbe81-170">我們也會引導您完成此資料所強調的任何修正步驟，以協助您提高網路得分。</span><span class="sxs-lookup"><span data-stu-id="fbe81-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="fbe81-171">Microsoft 365 系統管理中心存取。</span><span class="sxs-lookup"><span data-stu-id="fbe81-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-172">需要 Microsoft 365 應用程式的最新版本。</span><span class="sxs-lookup"><span data-stu-id="fbe81-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-173">已啟用位置服務，因為<a href="/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 系統管理中心的每個網路效能建議 (預覽) </a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-173">Location services enabled as per <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="fbe81-174">安全性及合規性</span><span class="sxs-lookup"><span data-stu-id="fbe81-174">Security and Compliance</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="fbe81-175">服務</span><span class="sxs-lookup"><span data-stu-id="fbe81-175">Service</span></span></th>
<th><span data-ttu-id="fbe81-176">FastTrack 指引詳細資料</span><span class="sxs-lookup"><span data-stu-id="fbe81-176">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="fbe81-177">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="fbe81-177">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="fbe81-178"><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-179">在下列情況下，我們會提供遠端指導來保護您的雲端身分識別。</span><span class="sxs-lookup"><span data-stu-id="fbe81-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="fbe81-180">

<strong>安全基礎結構</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="fbe81-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="fbe81-181">針對您的身分識別設定和啟用強驗證，包括使用 Azure Multi-Factor 驗證 (MFA)  (雲端僅) 、Microsoft Authenticator 應用程式，以及 Azure MFA 和自助密碼重設的組合註冊 (SSPR) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="fbe81-182">部署 FIDO2 或 Microsoft Authenticator 應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="fbe81-183">若為非 Azure AD Premium 客戶，會提供指導方針，以利用安全性預設值來保護您的身分識別。</span><span class="sxs-lookup"><span data-stu-id="fbe81-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-184">針對 Azure AD premium 客戶，提供指導方針以條件式存取來保護您的身分識別。</span><span class="sxs-lookup"><span data-stu-id="fbe81-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-185">使用 Azure AD 密碼保護偵測和封鎖弱密碼的使用。</span><span class="sxs-lookup"><span data-stu-id="fbe81-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-186">使用 Azure AD 應用程式 Proxy，保護內部部署 web 應用程式的遠端存取。</span><span class="sxs-lookup"><span data-stu-id="fbe81-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-187">使用 Azure 身分識別保護來啟用風險型偵測和修正。</span><span class="sxs-lookup"><span data-stu-id="fbe81-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-188">啟用自訂的登入畫面，包括徽標、文字和具有自訂商標的影像。</span><span class="sxs-lookup"><span data-stu-id="fbe81-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-189">使用 Azure AD B2B 與來賓使用者安全地共用應用程式和服務。</span><span class="sxs-lookup"><span data-stu-id="fbe81-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-190">使用以角色為基礎的存取控制 (RBAC) 內建管理角色，以及減少特權管理帳戶數目，來管理 Office 365 系統管理員的存取。</span><span class="sxs-lookup"><span data-stu-id="fbe81-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-191">設定混合式 Azure AD 聯結。</span><span class="sxs-lookup"><span data-stu-id="fbe81-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-192">設定 Azure AD 聯結。</span><span class="sxs-lookup"><span data-stu-id="fbe81-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="fbe81-193">
  
<strong>監視與報告</strong>  
</span><span class="sxs-lookup"><span data-stu-id="fbe81-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="fbe81-194">使用 Azure AD 連線健康情況，啟用針對 AD FS、Azure AD 連線和網域控制站的遠端監控。</span><span class="sxs-lookup"><span data-stu-id="fbe81-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="fbe81-195">
  
<strong>治理</strong>  
</span><span class="sxs-lookup"><span data-stu-id="fbe81-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="fbe81-196">使用 Azure AD 版權管理來管理 Azure AD 身分識別和存取生命週期。</span><span class="sxs-lookup"><span data-stu-id="fbe81-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="fbe81-197">使用 Azure AD access 評論管理 Azure AD 群組成員資格、企業應用程式存取和角色指派。</span><span class="sxs-lookup"><span data-stu-id="fbe81-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-198">檢查 Azure AD 使用條款。</span><span class="sxs-lookup"><span data-stu-id="fbe81-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-199">使用 Azure AD Privileged Identity Management 管理及控制對特權管理員帳戶的存取。</span><span class="sxs-lookup"><span data-stu-id="fbe81-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="fbe81-200">
  
<strong>自動化和效率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="fbe81-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="fbe81-201">啟用 Azure AD SSPR。</span><span class="sxs-lookup"><span data-stu-id="fbe81-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="fbe81-202">讓使用者能夠使用 Azure AD 自助群組管理來建立及管理自己的雲端安全性或 Office 365 群組。</span><span class="sxs-lookup"><span data-stu-id="fbe81-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-203">使用 Azure AD 委派的群組管理來管理企業應用程式的委派存取權。</span><span class="sxs-lookup"><span data-stu-id="fbe81-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-204">啟用 Azure AD 動態群組。</span><span class="sxs-lookup"><span data-stu-id="fbe81-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-205">使用集合在「我的應用程式入口網站」中組織應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="fbe81-206">內部部署的 Active Directory 及其環境已為 Azure AD Premium 做好準備，包括修正已識別的問題，以防止與 Azure AD 和 Azure AD Premium 功能整合。</span><span class="sxs-lookup"><span data-stu-id="fbe81-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="fbe81-207"><strong>Azure 資訊保護 </strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="fbe81-208">如需 Azure 資訊保護的詳細資訊，請參閱下表的<strong>Microsoft 資訊保護</strong>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="fbe81-209"><strong>探索 & 回應</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="fbe81-210"><strong>進階 eDiscovery</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="fbe81-211">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="fbe81-212">建立新的案例。</span><span class="sxs-lookup"><span data-stu-id="fbe81-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="fbe81-213">將保管人置於保留狀態。</span><span class="sxs-lookup"><span data-stu-id="fbe81-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-214">執行搜尋。</span><span class="sxs-lookup"><span data-stu-id="fbe81-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="fbe81-215">將搜尋結果新增至檢閱集。</span><span class="sxs-lookup"><span data-stu-id="fbe81-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="fbe81-216">對複查集執行分析。</span><span class="sxs-lookup"><span data-stu-id="fbe81-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-217">審閱及標記檔。</span><span class="sxs-lookup"><span data-stu-id="fbe81-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-218">從審閱集中匯出資料。</span><span class="sxs-lookup"><span data-stu-id="fbe81-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="fbe81-219">匯入非 Office 365 的資料。</span><span class="sxs-lookup"><span data-stu-id="fbe81-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="fbe81-220">只有 E5 支援的<strong>高級審計</strong> () </span><span class="sxs-lookup"><span data-stu-id="fbe81-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="fbe81-221">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="fbe81-222">啟用高級審核。</span><span class="sxs-lookup"><span data-stu-id="fbe81-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="fbe81-223">執行搜尋審核記錄 UI 和基本審核 PowerShell 命令。</span><span class="sxs-lookup"><span data-stu-id="fbe81-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="fbe81-224">

<strong> 合規性管理員</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="fbe81-225">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="fbe81-226">審閱角色類型。</span><span class="sxs-lookup"><span data-stu-id="fbe81-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="fbe81-227">新增及設定評估。</span><span class="sxs-lookup"><span data-stu-id="fbe81-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="fbe81-228">實施改進動作和決定這會如何影響您的合規性分數，以評估法規遵從性。</span><span class="sxs-lookup"><span data-stu-id="fbe81-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="fbe81-229">審閱內建控制項對應及評估控制項。</span><span class="sxs-lookup"><span data-stu-id="fbe81-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="fbe81-230">在評估中產生報表。</span><span class="sxs-lookup"><span data-stu-id="fbe81-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="fbe81-231">

<strong>下列超出範圍 </strong> 
</span><span class="sxs-lookup"><span data-stu-id="fbe81-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="fbe81-232">自訂腳本或編碼。</span><span class="sxs-lookup"><span data-stu-id="fbe81-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="fbe81-233">電子檔探索 API。</span><span class="sxs-lookup"><span data-stu-id="fbe81-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="fbe81-234">資料連線器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="fbe81-235">規範界限和安全性篩選器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="fbe81-236">資料調查。</span><span class="sxs-lookup"><span data-stu-id="fbe81-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="fbe81-237">資料主體要求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="fbe81-238">設計、設計架構和協力廠商檔審閱。</span><span class="sxs-lookup"><span data-stu-id="fbe81-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="fbe81-239">遵守行業和地區性法規和需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="fbe81-240">在合規性管理員中針對評估建議的改進動作的實際執行。</span><span class="sxs-lookup"><span data-stu-id="fbe81-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="fbe81-241">除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="fbe81-242"><strong>有問必答風險管理</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="fbe81-243">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="fbe81-244">建立原則及檢查設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="fbe81-245">存取報告和警示。</span><span class="sxs-lookup"><span data-stu-id="fbe81-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="fbe81-246">建立案例。</span><span class="sxs-lookup"><span data-stu-id="fbe81-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="fbe81-247">建立通知範本。</span><span class="sxs-lookup"><span data-stu-id="fbe81-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="fbe81-248"> (HR) 連接器建立人力資源的指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="fbe81-249">

<strong> 通訊相容性 </strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="fbe81-250">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="fbe81-251">建立原則及檢查設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="fbe81-252">存取報告和警示。</span><span class="sxs-lookup"><span data-stu-id="fbe81-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="fbe81-253">建立通知範本。</span><span class="sxs-lookup"><span data-stu-id="fbe81-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="fbe81-254">

<strong> 合規性管理員</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="fbe81-255">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="fbe81-256">審閱角色類型。</span><span class="sxs-lookup"><span data-stu-id="fbe81-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="fbe81-257">新增及設定評估。</span><span class="sxs-lookup"><span data-stu-id="fbe81-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="fbe81-258">實施改進動作和決定這會如何影響您的合規性分數，以評估法規遵從性。</span><span class="sxs-lookup"><span data-stu-id="fbe81-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="fbe81-259">審閱內建控制項對應及評估控制項。</span><span class="sxs-lookup"><span data-stu-id="fbe81-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="fbe81-260">在評估中產生報表。</span><span class="sxs-lookup"><span data-stu-id="fbe81-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="fbe81-261">

<strong>下列超出範圍 </strong> 
</span><span class="sxs-lookup"><span data-stu-id="fbe81-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="fbe81-262">建立及管理 Power Automate 流程。</span><span class="sxs-lookup"><span data-stu-id="fbe81-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="fbe81-263">在 HR 連接器) 以外 (的資料連線器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="fbe81-264">自訂正則運算式 (RegEx) 設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="fbe81-265">設計、設計架構和協力廠商檔審閱。</span><span class="sxs-lookup"><span data-stu-id="fbe81-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="fbe81-266">資訊障礙。</span><span class="sxs-lookup"><span data-stu-id="fbe81-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="fbe81-267">特殊許可權存取管理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="fbe81-268">遵守行業和地區性法規和需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="fbe81-269">在合規性管理員中針對評估建議的改進動作的實際執行。</span><span class="sxs-lookup"><span data-stu-id="fbe81-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="fbe81-270">除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="fbe81-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="fbe81-272">Microsoft 365 Defender 是一種整合的後續企業防護套件，其可在端點、身分識別、電子郵件和應用程式上協調偵測、預防、調查和回應，以提供複雜攻擊的整合式防護。</span><span class="sxs-lookup"><span data-stu-id="fbe81-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="fbe81-273">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="fbe81-274">提供 Microsoft 365 安全性中心的概覽。</span><span class="sxs-lookup"><span data-stu-id="fbe81-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-275">檢查跨產品的事件，包括確定完整的攻擊範圍、受影響的資產，以及組合在一起的自動修正動作，以著重于重要專案。</span><span class="sxs-lookup"><span data-stu-id="fbe81-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-276">示範 Microsoft 365 Defender 如何對資產、使用者、裝置和信箱進行調查，以透過自動自我修復的方式來調查可能已遭破壞的資產、使用者、裝置和信箱。</span><span class="sxs-lookup"><span data-stu-id="fbe81-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="fbe81-277">說明及提供客戶如何主動搜尋入侵企圖及破壞您的電子郵件、資料、裝置及帳戶的多個資料組的範例。</span><span class="sxs-lookup"><span data-stu-id="fbe81-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="fbe81-278">向客戶展示如何使用 Microsoft 安全評分來複查和提升其安全性狀況 holistically。</span><span class="sxs-lookup"><span data-stu-id="fbe81-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="fbe81-279"><strong>下列超出範圍</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="fbe81-280">客戶修正活動的專案管理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="fbe81-281">持續管理、威脅回應及修復。</span><span class="sxs-lookup"><span data-stu-id="fbe81-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="fbe81-282">部署指導或教育：</span><span class="sxs-lookup"><span data-stu-id="fbe81-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="fbe81-283">如何修正或轉譯各種警示類型和受監控的活動。</span><span class="sxs-lookup"><span data-stu-id="fbe81-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="fbe81-284">如何調查使用者、電腦、側向移動路徑或實體。</span><span class="sxs-lookup"><span data-stu-id="fbe81-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="fbe81-285">自訂威脅搜尋。</span><span class="sxs-lookup"><span data-stu-id="fbe81-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="fbe81-286">支援<a href=" /fasttrack/us-gov-appendix-overview">GCC-High 或 GCC-DoD Office 365 (美國政府) </a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-286">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="fbe81-287"> (SIEM) 或 API 整合的安全性資訊和事件管理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-287">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="fbe81-288"><strong>Microsoft 雲端 App 安全性</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-288"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-289">Microsoft Cloud App Security 是雲端存取安全性經紀人 (CASB) ，可提供豐富的知名度、控制資料旅行和複雜的分析，以識別和抵禦所有 Microsoft 和協力廠商雲端服務的網路威脅。</span><span class="sxs-lookup"><span data-stu-id="fbe81-289">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="fbe81-290">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-291">設定入口網站，包括：</span><span class="sxs-lookup"><span data-stu-id="fbe81-291">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="fbe81-292">匯入使用者群組。</span><span class="sxs-lookup"><span data-stu-id="fbe81-292">Importing user groups.</span></span></li>
<li> <span data-ttu-id="fbe81-293">管理系統管理存取和設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-293">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="fbe81-294">確定部署的範圍，以選取要監視或排除監控的特定使用者群組。</span><span class="sxs-lookup"><span data-stu-id="fbe81-294">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="fbe81-295">如何設定 IP 範圍及標記。</span><span class="sxs-lookup"><span data-stu-id="fbe81-295">How to set up IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="fbe81-296">使用您的標誌和自訂訊息，將使用者體驗個人化。</span><span class="sxs-lookup"><span data-stu-id="fbe81-296">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="fbe81-297">整合第一方服務，包括：</span><span class="sxs-lookup"><span data-stu-id="fbe81-297">Integrating first-party services including:</span></span>
<ul>
<li> <span data-ttu-id="fbe81-298">適用於端點的 Microsoft Defender。</span><span class="sxs-lookup"><span data-stu-id="fbe81-298">Microsoft Defender for Endpoint.</span></span></li>
<li> <span data-ttu-id="fbe81-299">適用於身分識別的 Microsoft Defender。</span><span class="sxs-lookup"><span data-stu-id="fbe81-299">Microsoft Defender for Identity.</span></span></li>
<li> <span data-ttu-id="fbe81-300">Azure AD Identity Protection。</span><span class="sxs-lookup"><span data-stu-id="fbe81-300">Azure AD Identity Protection.</span></span></li>
<li> <span data-ttu-id="fbe81-301">Azure 資訊保護。</span><span class="sxs-lookup"><span data-stu-id="fbe81-301">Azure Information Protection.</span></span></li>
</ul>
<li> <span data-ttu-id="fbe81-302">使用下列專案設定雲端探索：</span><span class="sxs-lookup"><span data-stu-id="fbe81-302">Setting up cloud discovery using:</span></span></li>
<ul>
<li> <span data-ttu-id="fbe81-303">Microsoft Defender for 端點。</span><span class="sxs-lookup"><span data-stu-id="fbe81-303">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="fbe81-304">Zscaler。</span><span class="sxs-lookup"><span data-stu-id="fbe81-304">Zscaler.</span></span></li>
<li> <span data-ttu-id="fbe81-305">iboss.</span><span class="sxs-lookup"><span data-stu-id="fbe81-305">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="fbe81-306">建立應用程式標記與類別。</span><span class="sxs-lookup"><span data-stu-id="fbe81-306">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="fbe81-307">根據組織的優先順序自訂應用程式風險分數。</span><span class="sxs-lookup"><span data-stu-id="fbe81-307">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="fbe81-308">Sanctioning 與 unsanctioning 應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-308">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="fbe81-309">複查雲端 App 安全性和雲端探索儀表板。</span><span class="sxs-lookup"><span data-stu-id="fbe81-309">Reviewing the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="fbe81-310">使用應用程式連接器連接 <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> 特色應用程式</a> 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-310">Connecting <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="fbe81-311">使用 Azure AD 中的條件式存取和雲端 App 安全性入口網站來保護應用程式與條件式存取應用程式控制。</span><span class="sxs-lookup"><span data-stu-id="fbe81-311">Protecting apps with Conditional Access App Control in the Conditional Access within Azure AD and Cloud App Security portals.</span></span></li>
<li> <span data-ttu-id="fbe81-312">為特色應用程式部署條件式存取應用程式控制。</span><span class="sxs-lookup"><span data-stu-id="fbe81-312">Deploying Conditional Access App Control for featured apps.</span></span></li>
<li> <span data-ttu-id="fbe81-313">使用活動和檔記錄。</span><span class="sxs-lookup"><span data-stu-id="fbe81-313">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="fbe81-314">管理 OAuth 應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-314">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="fbe81-315">審閱及設定原則範本。</span><span class="sxs-lookup"><span data-stu-id="fbe81-315">Reviewing and configuring policy templates.</span></span></li>
<li> <span data-ttu-id="fbe81-316">在 CASBs (的 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">前20個使用案例</a> 中提供設定協助，包括建立或更新最多六個 (6) 原則) ，但不包括：</span><span class="sxs-lookup"><span data-stu-id="fbe81-316">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="fbe81-317">審核網際網路的設定為服務 (IaaS) 環境 (#18) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-317">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="fbe81-318">監控使用者活動，以防範 IaaS 環境中的威脅 (#19) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-318">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
<li> <span data-ttu-id="fbe81-319">瞭解 Microsoft 365 Defender 入口網站中的事件關聯。</span><span class="sxs-lookup"><span data-stu-id="fbe81-319">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="fbe81-320"><strong>下列超出範圍</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-320"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="fbe81-321">客戶修正活動的專案管理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-321">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="fbe81-322">持續管理、威脅回應及修復。</span><span class="sxs-lookup"><span data-stu-id="fbe81-322">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="fbe81-323">將雲端 App 安全性與其他 CASB 方案進行比較。</span><span class="sxs-lookup"><span data-stu-id="fbe81-323">Discussions comparing Cloud App Security to other CASB offerings.</span></span></li>
<li> <span data-ttu-id="fbe81-324">設定雲端 App 安全性以符合特定的規範或法規需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-324">Configuring Cloud App Security to meet specific compliance or regulatory requirements.</span></span></li>
<li> <span data-ttu-id="fbe81-325">將服務部署到非測試實際執行環境。</span><span class="sxs-lookup"><span data-stu-id="fbe81-325">Deploying the service to a non-test production environment.</span></span></li>
<li> <span data-ttu-id="fbe81-326">部署雲端應用程式探索以作為概念證明。</span><span class="sxs-lookup"><span data-stu-id="fbe81-326">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
<li> <span data-ttu-id="fbe81-327">支援<a href=" /fasttrack/us-gov-appendix-overview">GCC-High 或 GCC-DoD Office 365 (美國政府) </a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-327">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="fbe81-328">使用 Docker 或記錄收集器，為連續報告設定基礎結構、安裝或部署自動記錄上載。</span><span class="sxs-lookup"><span data-stu-id="fbe81-328">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> </li>
<li> <span data-ttu-id="fbe81-329">建立雲端探索快照報告。</span><span class="sxs-lookup"><span data-stu-id="fbe81-329">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="fbe81-330">使用封鎖腳本封鎖應用程式使用方式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-330">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="fbe81-331">連接自訂應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-331">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="fbe81-332">在未功能的應用程式上架上和部署條件式存取應用程式控制。</span><span class="sxs-lookup"><span data-stu-id="fbe81-332">Onboarding and deploying Conditional Access App Control for non-featured apps.</span></span></li>
<li> <span data-ttu-id="fbe81-333">與協力廠商身分識別提供者整合 (的 Isp) 和資料遺失防護 (DLP) 提供者。</span><span class="sxs-lookup"><span data-stu-id="fbe81-333">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="fbe81-334">涵蓋進階搜尋功能的訓練或指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-334">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="fbe81-335">自動調查和修正，包括 Microsoft Power Automate 行動手冊。</span><span class="sxs-lookup"><span data-stu-id="fbe81-335">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="fbe81-336">安全性資訊和事件管理 (SIEM) 或 API 整合 (包含 Azure Sentinel) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-336">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>

</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="fbe81-337"><strong>適用於端點的 Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-337"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-338">Microsoft Defender for Endpoint 是專門設計用來協助商業網路避免、偵測、調查和回應高級威脅的平臺。</span><span class="sxs-lookup"><span data-stu-id="fbe81-338">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="fbe81-339">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-339">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-340">部署技術以保護您的端點。</span><span class="sxs-lookup"><span data-stu-id="fbe81-340">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-341">設定 endpoint protection 和裝置限制設定檔。</span><span class="sxs-lookup"><span data-stu-id="fbe81-341">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-342">評估 OS 版本和裝置管理 (包括 Intune、Microsoft Endpoint Configuration Manager、群組原則物件 (gpo) 及協力廠商設定) 以及 Windows Defender AV 服務或其他端點安全性軟體的狀態。</span><span class="sxs-lookup"><span data-stu-id="fbe81-342">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-343">評估 Windows AV 服務或其他端點安全性軟體的狀態。</span><span class="sxs-lookup"><span data-stu-id="fbe81-343">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-344">評估代理及防火牆，以限制網路流量。</span><span class="sxs-lookup"><span data-stu-id="fbe81-344">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-345">說明如何使用板載端點為端點代理程式設定檔部署 Defender，以啟用 Microsoft Defender for Endpoint service。</span><span class="sxs-lookup"><span data-stu-id="fbe81-345">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-346">部署指導方針、設定協助及教育：</span><span class="sxs-lookup"><span data-stu-id="fbe81-346">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="fbe81-347">威脅與弱點管理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-347">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-348">縮小攻擊面。</span><span class="sxs-lookup"><span data-stu-id="fbe81-348">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-349">新一代防護。</span><span class="sxs-lookup"><span data-stu-id="fbe81-349">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-350">端點偵測及回應。</span><span class="sxs-lookup"><span data-stu-id="fbe81-350">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-351">自動化調查與補救措施。</span><span class="sxs-lookup"><span data-stu-id="fbe81-351">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-352">裝置的安全分數。</span><span class="sxs-lookup"><span data-stu-id="fbe81-352">Secure score for devices.</span></span>  
  </li>
<li> <span data-ttu-id="fbe81-353">使用 Microsoft 端點管理員 Microsoft Defender SmartScreen 設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-353">Microsoft Defender SmartScreen configuration using Microsoft Endpoint Manager.</span></span></li>

</ul></li>
<li>  <span data-ttu-id="fbe81-354">查看模擬與示教 (例如練習案例、虛假惡意程式碼和自動調查) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-354">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-355">報表和威脅分析功能的概覽。</span><span class="sxs-lookup"><span data-stu-id="fbe81-355">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-356">整合 microsoft defender for Office 365 與 microsoft defender for Endpoint。</span><span class="sxs-lookup"><span data-stu-id="fbe81-356">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-357">提供 Microsoft Defender 資訊安全中心入口網站的逐步指引。</span><span class="sxs-lookup"><span data-stu-id="fbe81-357">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-358">下列作業系統：</span><span class="sxs-lookup"><span data-stu-id="fbe81-358">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="fbe81-359">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="fbe81-359">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-360">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="fbe81-360">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-361">Windows伺服器2019。</span><span class="sxs-lookup"><span data-stu-id="fbe81-361">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-362">WindowsServer 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="fbe81-362">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-363">Windows伺服器 Semi-Annual 通道 (SAC) 版本1803。</span><span class="sxs-lookup"><span data-stu-id="fbe81-363">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-364">macOS 版本10.13、10.14 及10.15。</span><span class="sxs-lookup"><span data-stu-id="fbe81-364">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="fbe81-365">
<strong>附注：</strong>所有的 Windows 伺服器版本都必須以最新版本的 System Center Configuration Manager 2012 來管理 (1012 R2、1511或 1602) 或 Microsoft Endpoint Configuration Manager (版本2002或更高) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-365">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="fbe81-366"></li>
</ul>

<strong>下列超出範圍 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="fbe81-366"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="fbe81-367">客戶修正活動的專案管理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-367">Project management of the customer's remediation activities.</span></span>  </li>
<li> <span data-ttu-id="fbe81-368">支援<a href=" /fasttrack/us-gov-appendix-overview">GCC-High 或 GCC-DoD Office 365 (美國政府) </a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-368">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li>  <span data-ttu-id="fbe81-369">現場支援。</span><span class="sxs-lookup"><span data-stu-id="fbe81-369">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-370">持續性管理和威脅因應。</span><span class="sxs-lookup"><span data-stu-id="fbe81-370">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-371">上架或設定下列 Microsoft Defender for Endpoint agent：</span><span class="sxs-lookup"><span data-stu-id="fbe81-371">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="fbe81-372">Windows伺服器2008。</span><span class="sxs-lookup"><span data-stu-id="fbe81-372">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-373">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="fbe81-373">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-374">Linux。</span><span class="sxs-lookup"><span data-stu-id="fbe81-374">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-375">移動裝置 (Android 和 iOS) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-375">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="fbe81-376">虛擬桌面基礎結構 (VDI)  (持續或非持續性) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-376">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="fbe81-377">伺服器上架及設定：</span><span class="sxs-lookup"><span data-stu-id="fbe81-377">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="fbe81-378">設定離線通訊的 proxy 伺服器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-378">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-379">設定下層 Configuration Manager 實例和版本的 Configuration Manager 部署套件。</span><span class="sxs-lookup"><span data-stu-id="fbe81-379">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-380">將伺服器上架至 Azure 的安全性中心。</span><span class="sxs-lookup"><span data-stu-id="fbe81-380">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-381">未由 Configuration Manager 管理的伺服器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-381">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="fbe81-382">macOS 上架及設定：</span><span class="sxs-lookup"><span data-stu-id="fbe81-382">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="fbe81-383">手動以 Intune 為基礎的部署。</span><span class="sxs-lookup"><span data-stu-id="fbe81-383">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-384">以 JAMF 為基礎的部署。</span><span class="sxs-lookup"><span data-stu-id="fbe81-384">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="fbe81-385">其他行動裝置管理 (MDM) 以產品為基礎的部署。</span><span class="sxs-lookup"><span data-stu-id="fbe81-385">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-386">手動部署。</span><span class="sxs-lookup"><span data-stu-id="fbe81-386">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="fbe81-387">設定以下能縮小攻擊面的功能：</span><span class="sxs-lookup"><span data-stu-id="fbe81-387">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="fbe81-388">硬體隔離。</span><span class="sxs-lookup"><span data-stu-id="fbe81-388">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-389">應用程式控制。</span><span class="sxs-lookup"><span data-stu-id="fbe81-389">App control.</span></span>  
  </li>
<li> <span data-ttu-id="fbe81-390">裝置控制。</span><span class="sxs-lookup"><span data-stu-id="fbe81-390">Device control.</span></span></li>
<li>  
  <span data-ttu-id="fbe81-391">入侵防護。</span><span class="sxs-lookup"><span data-stu-id="fbe81-391">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-392">網路防火牆。</span><span class="sxs-lookup"><span data-stu-id="fbe81-392">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="fbe81-393">帳戶保護功能的設定或管理，例如：</span><span class="sxs-lookup"><span data-stu-id="fbe81-393">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="fbe81-394">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="fbe81-394">Windows Hello</span></span></li>
<li> <span data-ttu-id="fbe81-395">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="fbe81-395">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="fbe81-396">BitLocker 的設定或管理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-396">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="fbe81-397">註冊或設定 Microsoft 威脅專家。</span><span class="sxs-lookup"><span data-stu-id="fbe81-397">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-398">設定或訓練檢查 API 或安全性資訊和事件管理 (SIEM) 連接。</span><span class="sxs-lookup"><span data-stu-id="fbe81-398">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-399">Microsoft 365 Defender 的註冊或設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-399">Enrollment or configuration of Microsoft 365 Defender.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-400">涵蓋進階搜尋功能的訓練或指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-400">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-401">訓練或指引涵蓋使用或建立 Kusto 查詢。</span><span class="sxs-lookup"><span data-stu-id="fbe81-401">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
<li> <span data-ttu-id="fbe81-402">使用群組原則物件 (gpo) 、Windows 安全性或 Microsoft Edge 涵蓋 Defender SmartScreen 設定的訓練或指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-402">Training or guidance covering Defender SmartScreen configuration using Group Policy Objects (GPOs), Windows Security, or Microsoft Edge.</span></span></li>
</li>
</ul>
<span data-ttu-id="fbe81-403">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。</span><span class="sxs-lookup"><span data-stu-id="fbe81-403">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="fbe81-404"><strong>Microsoft Defender 身分識別 </strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-404"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="fbe81-405">適用於身分識別的 Microsoft Defender 是利用內部部署 Active Directory 訊號的雲端型安全性解決方案，它會識別、偵測及調查貴組織中的進階威脅、遭入侵的身分識別，以及惡意內部攻擊動作。</span><span class="sxs-lookup"><span data-stu-id="fbe81-405">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="fbe81-406">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-406">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-407">執行資源容量規劃的調整大小工具。</span><span class="sxs-lookup"><span data-stu-id="fbe81-407">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>   <span data-ttu-id="fbe81-408">建立身分識別的 Defender 實例。</span><span class="sxs-lookup"><span data-stu-id="fbe81-408">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="fbe81-409">將 Defender 身分識別連接至 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="fbe81-409">Connecting Defender for Identity to Active Directory.</span></span> </li>

<li>  <span data-ttu-id="fbe81-410">部署感應器以直接從您的網域控制站捕捉及分析網路流量和 Windows 事件，包括：</span><span class="sxs-lookup"><span data-stu-id="fbe81-410">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="fbe81-411">下載感應器套件。</span><span class="sxs-lookup"><span data-stu-id="fbe81-411">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="fbe81-412">設定感應器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-412">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="fbe81-413">在您的網域控制站上無訊息地安裝感應器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-413">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="fbe81-414">將感應器部署至多樹系環境。</span><span class="sxs-lookup"><span data-stu-id="fbe81-414">Deploying the sensor to your multi-forest environment.</span></span> </li>
<li> <span data-ttu-id="fbe81-415">設定 Windows 事件收集器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-415">Configuring the Windows Event Collector.</span></span></li>
</ul>
<li>  <span data-ttu-id="fbe81-416">設定入口網站，包括：</span><span class="sxs-lookup"><span data-stu-id="fbe81-416">Configuring the portal, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="fbe81-417">不需要使用 Microsoft Cloud App Security (整合 Defender 以進行身分識別雲端 App 安全性授權，) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-417">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li> <span data-ttu-id="fbe81-418">設定實體標記。</span><span class="sxs-lookup"><span data-stu-id="fbe81-418">Configuring entity tags.</span></span></li>
<li> <span data-ttu-id="fbe81-419">標記機密帳戶。</span><span class="sxs-lookup"><span data-stu-id="fbe81-419">Tagging sensitive accounts.</span></span> </li>
<li> <span data-ttu-id="fbe81-420">接收健康情況問題和安全性警示的電子郵件通知。</span><span class="sxs-lookup"><span data-stu-id="fbe81-420">Receiving email notifications for health issues and security alerts.</span></span> </li>
<li> <span data-ttu-id="fbe81-421">設定警示排除。</span><span class="sxs-lookup"><span data-stu-id="fbe81-421">Configuring alert exclusions.</span></span>  </li>
</ul>
<li> <span data-ttu-id="fbe81-422">提供部署指導、設定協助及教育：</span><span class="sxs-lookup"><span data-stu-id="fbe81-422">Providing deployment guidance, configuration assistance, and education on:</span></span></li>
<ul>
<li> <span data-ttu-id="fbe81-423">瞭解識別安全狀況評估報告。</span><span class="sxs-lookup"><span data-stu-id="fbe81-423">Understanding the Identity Security Posture Assessment report.</span></span></li>
<li> <span data-ttu-id="fbe81-424">瞭解使用者調查優先順序分數和使用者調查排名報告。</span><span class="sxs-lookup"><span data-stu-id="fbe81-424">Understanding the User Investigation Priority Score and User Investigation ranking report.</span></span></li>
<li> <span data-ttu-id="fbe81-425">瞭解非使用中的使用者報告。</span><span class="sxs-lookup"><span data-stu-id="fbe81-425">Understanding the inactive user report.</span></span></li>
<li> <span data-ttu-id="fbe81-426">對已遭破壞之帳戶的修復選項的說明。</span><span class="sxs-lookup"><span data-stu-id="fbe81-426">Explanation of the remediation options on a compromised account.</span></span></li>
</ul>
<li>  <span data-ttu-id="fbe81-427">可促進從高級威脅分析 (ATA) 至 Defender 身分識別的遷移。</span><span class="sxs-lookup"><span data-stu-id="fbe81-427">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="fbe81-428"><strong>下列超出範圍</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-428"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="fbe81-429">客戶修正活動的專案管理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-429">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="fbe81-430">持續管理、威脅回應及修復。</span><span class="sxs-lookup"><span data-stu-id="fbe81-430">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="fbe81-431">將 Defender 身分識別部署為概念證明。</span><span class="sxs-lookup"><span data-stu-id="fbe81-431">Deploying Defender for Identity as a proof of concept.</span></span></li>
<li> <span data-ttu-id="fbe81-432">支援<a href=" /fasttrack/us-gov-appendix-overview">GCC-High 或 GCC-DoD Office 365 (美國政府) </a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-432">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="fbe81-433">針對身分識別感應器活動部署或執行下列 Defender：</span><span class="sxs-lookup"><span data-stu-id="fbe81-433">Deploying or performing the following Defender for Identity sensor activities:</span></span> </li>
<ul>
<li> <span data-ttu-id="fbe81-434">手動容量規劃。</span><span class="sxs-lookup"><span data-stu-id="fbe81-434">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="fbe81-435">執行審核工具。</span><span class="sxs-lookup"><span data-stu-id="fbe81-435">Running the Auditing tool.</span></span> </li>
<li> <span data-ttu-id="fbe81-436">部署獨立感應器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-436">Deploying the standalone sensor.</span></span> </li>
<li> <span data-ttu-id="fbe81-437"> (AD FS) 伺服器部署至 Active Directory Federation Services。</span><span class="sxs-lookup"><span data-stu-id="fbe81-437">Deploying to Active Directory Federation Services (AD FS) servers.</span></span>
<li> <span data-ttu-id="fbe81-438">使用網路介面卡 (NIC) 編組的配接器部署感應器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-438">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="fbe81-439">透過協力廠商工具部署感應器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-439">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="fbe81-440">透過 web proxy 連線來連線至身分識別雲端服務的 Defender。</span><span class="sxs-lookup"><span data-stu-id="fbe81-440">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="fbe81-441">在 Active Directory 中設定 Microsoft 帳戶 (MSA) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-441">Configuring the Microsoft account (MSA) in Active Directory.</span></span>
<li> <span data-ttu-id="fbe81-442">Honeytokens 的建立與管理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-442">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="fbe81-443">啟用網路名稱解析 (NNR) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-443">Enabling Network Name Resolution (NNR).</span></span> </li>
<li> <span data-ttu-id="fbe81-444">設定刪除的物件容器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-444">Configuration of Deleted Objects container.</span></span></li>
<li> <span data-ttu-id="fbe81-445">部署指導或教育：</span><span class="sxs-lookup"><span data-stu-id="fbe81-445">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="fbe81-446">修正或口譯各種警示類型和受監控的活動。</span><span class="sxs-lookup"><span data-stu-id="fbe81-446">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="fbe81-447">調查使用者、電腦、側向移動路徑或實體。</span><span class="sxs-lookup"><span data-stu-id="fbe81-447">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="fbe81-448">威脅或高級搜尋。</span><span class="sxs-lookup"><span data-stu-id="fbe81-448">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="fbe81-449">事件回應。</span><span class="sxs-lookup"><span data-stu-id="fbe81-449">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="fbe81-450">為身分識別提供適用于 Defender 的安全性警示實驗室教學課程。</span><span class="sxs-lookup"><span data-stu-id="fbe81-450">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="fbe81-451">當 Defender 身分識別透過身分識別的感應器傳送安全警示以偵測可疑活動時，提供通知。</span><span class="sxs-lookup"><span data-stu-id="fbe81-451">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="fbe81-452">使用安全帳戶管理員 remote (SAMR) 通訊協定，設定用來執行查詢的 Defender，以識別特定電腦上的本機系統管理員。</span><span class="sxs-lookup"><span data-stu-id="fbe81-452">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="fbe81-453">設定 VPN 解決方案，將 VPN 連線的資訊新增至使用者的設定檔頁面面。</span><span class="sxs-lookup"><span data-stu-id="fbe81-453">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="fbe81-454">安全性資訊和事件管理 (SIEM) 或 API 整合 (包含 Azure Sentinel) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-454">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="fbe81-455">與 <a href="/defender-for-identity/prerequisites"> Microsoft Defender 的身分識別必要條件</a>對齊。</span><span class="sxs-lookup"><span data-stu-id="fbe81-455">Aligned with <a href="/defender-for-identity/prerequisites"> Microsoft Defender for Identity prerequisites</a>.</span></span> </li>
<li>  <span data-ttu-id="fbe81-456">已部署 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="fbe81-456">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-457">您想要為身分識別感應器安裝 Defender 的網域控制站，具有對身分識別雲端服務的 internet 連線能力。</span><span class="sxs-lookup"><span data-stu-id="fbe81-457">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="fbe81-458">您的防火牆和 proxy 必須開啟才能與 ( 的身分識別，以進行身分識別 cloud service 的 Defender。 atp.azure.com 埠443必須) 開啟。</span><span class="sxs-lookup"><span data-stu-id="fbe81-458">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="fbe81-459">執行于下列其中一項的網域控制站：</span><span class="sxs-lookup"><span data-stu-id="fbe81-459">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="fbe81-460">Windows伺服器 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="fbe81-460">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="fbe81-461">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="fbe81-461">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="fbe81-462">Windows Server 2012R 2。</span><span class="sxs-lookup"><span data-stu-id="fbe81-462">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="fbe81-463">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="fbe81-463">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="fbe81-464">Windows伺服器2019與 KB4487044 (OS 組建17763.316 或更新版本) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-464">Windows Server 2019 with KB4487044 (OS Build 17763.316 or later).</span></span></li>
</ul>
<li> <span data-ttu-id="fbe81-465">Microsoft .NET Framework 4.7 或更新版本。</span><span class="sxs-lookup"><span data-stu-id="fbe81-465">Microsoft .NET Framework 4.7 or later.</span></span></li>
<li> <span data-ttu-id="fbe81-466">至少需要有5個 (的磁碟空間) GB 的磁碟空間，而且建議使用 10 GB。</span><span class="sxs-lookup"><span data-stu-id="fbe81-466">A minimum of five (5) GB of disk space is required and 10 GB is recommended.</span></span></li>
<li> <span data-ttu-id="fbe81-467">在網域控制站上安裝兩個 (2) 核心和六個 (6) GB 的 RAM。</span><span class="sxs-lookup"><span data-stu-id="fbe81-467">Two (2) cores and six (6) GB of RAM installed on the domain controller.</span></span></li>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="fbe81-468"><strong>適用於 Office 365 的 Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-468"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-p114">適用於 Office 365 的 Microsoft Defender 可保護貴組織免於來自電子郵件訊息、連結 (URL)，與共同作業工具的惡意威脅。適用於 Office 365 的 Defender 包含:</span><span class="sxs-lookup"><span data-stu-id="fbe81-p114">Microsoft Defender for Office 365 safeguards your organization against malicious threats posed by email messages, links (URLs), and collaboration tools. Defender for Office 365 includes: </span></span><ul>
<li> <span data-ttu-id="fbe81-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> 威脅防護原則</a>：定義威脅防護原則，以設定組織的適當保護層級。</span><span class="sxs-lookup"><span data-stu-id="fbe81-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Threat protection policies</a>: Define threat-protection policies to set the appropriate level of protection for your organization.</span></span></li>
<li> <span data-ttu-id="fbe81-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">報告</a>：查看即時報告，以監視您組織中 Office 365 效能的 Defender。</span><span class="sxs-lookup"><span data-stu-id="fbe81-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Reports</a>: View real-time reports to monitor Defender for Office 365 performance in your organization.</span></span></li>
<li> <span data-ttu-id="fbe81-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">威脅調查與回應功能</a>：使用先進的工具來調查、了解、模擬以及防止潛在威脅。</span><span class="sxs-lookup"><span data-stu-id="fbe81-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Threat investigation and response capabilities</a>: Use leading-edge tools to investigate, understand, simulate, and prevent threats.</span></span></li>
<li> <span data-ttu-id="fbe81-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">自動調查及回應功能</a>：節省調查和減輕威脅的時間和精力。</span><span class="sxs-lookup"><span data-stu-id="fbe81-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Automated investigation and response capabilities</a>: Save time and effort investigating and mitigating threats.</span></span></li>
</ul>

<span data-ttu-id="fbe81-475">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-475">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="fbe81-476">啟用安全連結、安全附件和防網路釣魚。</span><span class="sxs-lookup"><span data-stu-id="fbe81-476">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-477">設定自動化、調查和回應。</span><span class="sxs-lookup"><span data-stu-id="fbe81-477">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-478">使用攻擊模擬器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-478">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-479">報告和威脅分析。</span><span class="sxs-lookup"><span data-stu-id="fbe81-479">Reporting and threat analytics.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-480">瞭解 Microsoft 365 Defender 入口網站中的事件關聯。</span><span class="sxs-lookup"><span data-stu-id="fbe81-480">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="fbe81-481"><strong>下列超出範圍</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-481"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="fbe81-482">客戶修正活動的專案管理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-482">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="fbe81-483">持續管理、威脅回應及修復。</span><span class="sxs-lookup"><span data-stu-id="fbe81-483">Ongoing management, threat response, and remediation.</span></span></li>
<li> <span data-ttu-id="fbe81-484">支援<a href=" /fasttrack/us-gov-appendix-overview">GCC-High 或 GCC-DoD Office 365 (美國政府) </a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-484">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="fbe81-485">將 Office 365 的 Defender 與其他安全性產品進行比較的討論。</span><span class="sxs-lookup"><span data-stu-id="fbe81-485">Discussions comparing Defender for Office 365 to other security offerings.</span></span></li>
<li> <span data-ttu-id="fbe81-486">部署 Office 365 的 Defender 做為概念證明。</span><span class="sxs-lookup"><span data-stu-id="fbe81-486">Deploying Defender for Office 365 as a proof of concept.</span></span></li>
<li> <span data-ttu-id="fbe81-487">連接自訂應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-487">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="fbe81-488">涵蓋進階搜尋功能的訓練或指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-488">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="fbe81-489">自動調查和修正，包括 Microsoft Power Automate 行動手冊。</span><span class="sxs-lookup"><span data-stu-id="fbe81-489">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="fbe81-490">安全性資訊和事件管理 (SIEM) 或 API 整合 (包含 Azure Sentinel) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-490">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
</ul>
</td>
<td><span data-ttu-id="fbe81-491">除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-491">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="fbe81-492"><strong>Microsoft 資訊控管</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-492"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="fbe81-493">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-493">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-494">僅限 E5) 支援建立及發佈保留標籤和原則 (。</span><span class="sxs-lookup"><span data-stu-id="fbe81-494">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="fbe81-495">僅限 E5) 支援記錄管理 (。</span><span class="sxs-lookup"><span data-stu-id="fbe81-495">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="fbe81-496">查看檔計畫建立。</span><span class="sxs-lookup"><span data-stu-id="fbe81-496">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="fbe81-497">建立及記錄管理 (包括事件記錄) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-497">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-498">審閱處置。</span><span class="sxs-lookup"><span data-stu-id="fbe81-498">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="fbe81-499">

<strong> 合規性管理員</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-499">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="fbe81-500">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-500">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="fbe81-501">審閱角色類型。</span><span class="sxs-lookup"><span data-stu-id="fbe81-501">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="fbe81-502">新增及設定評估。</span><span class="sxs-lookup"><span data-stu-id="fbe81-502">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="fbe81-503">實施改進動作和決定這會如何影響您的合規性分數，以評估法規遵從性。</span><span class="sxs-lookup"><span data-stu-id="fbe81-503">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="fbe81-504">審閱內建控制項對應及評估控制項。</span><span class="sxs-lookup"><span data-stu-id="fbe81-504">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="fbe81-505">在評估中產生報表。</span><span class="sxs-lookup"><span data-stu-id="fbe81-505">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="fbe81-506">

  <strong>下列超出範圍 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="fbe81-506">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="fbe81-507">記錄管理檔計畫的開發。</span><span class="sxs-lookup"><span data-stu-id="fbe81-507">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="fbe81-508">資料連線器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-508">Data connectors.</span></span></li>
<li> <span data-ttu-id="fbe81-509">在 SharePoint 中開發資訊架構。</span><span class="sxs-lookup"><span data-stu-id="fbe81-509">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="fbe81-510">自訂腳本和編碼。</span><span class="sxs-lookup"><span data-stu-id="fbe81-510">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="fbe81-511">設計、設計架構和協力廠商檔審閱。</span><span class="sxs-lookup"><span data-stu-id="fbe81-511">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="fbe81-512">E3 的支援。</span><span class="sxs-lookup"><span data-stu-id="fbe81-512">Support for E3.</span></span></li>
<li> <span data-ttu-id="fbe81-513">遵守行業和地區性法規和需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-513">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="fbe81-514">在合規性管理員中針對評估建議的改進動作的實際執行。</span><span class="sxs-lookup"><span data-stu-id="fbe81-514">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="fbe81-515">除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-515">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="fbe81-516"><strong>Microsoft 資訊保護</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-516"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-517">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-517">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-518">在 E3 和 E5) 中支援資料分類 (。</span><span class="sxs-lookup"><span data-stu-id="fbe81-518">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-519">在 E3 和 E5) 中支援的敏感資訊類型 (。</span><span class="sxs-lookup"><span data-stu-id="fbe81-519">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-520">在 E3 和 E5) 中建立 (支援的靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="fbe81-520">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-521">在 E3 和 E5) 中套用敏感度標籤 (支援。</span><span class="sxs-lookup"><span data-stu-id="fbe81-521">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-522">Trainable 中的分類器 (支援的 E5) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-522">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-523">使用 E5) 支援的內容瀏覽器和活動瀏覽器 (，知道您的資料。</span><span class="sxs-lookup"><span data-stu-id="fbe81-523">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-524">使用原則發佈標籤 (手動和自動) E5) 中 (支援。</span><span class="sxs-lookup"><span data-stu-id="fbe81-524">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-525">建立端點資料遺失防護 (為 Windows 10 裝置 (支援的 DLP) 原則 E5) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-525">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-526">為 Microsoft Teams 聊天和頻道建立 DLP 原則。</span><span class="sxs-lookup"><span data-stu-id="fbe81-526">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="fbe81-527">

<strong> 合規性管理員</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-527">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="fbe81-528">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-528">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="fbe81-529">審閱角色類型。</span><span class="sxs-lookup"><span data-stu-id="fbe81-529">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="fbe81-530">新增及設定評估。</span><span class="sxs-lookup"><span data-stu-id="fbe81-530">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="fbe81-531">實施改進動作和決定這會如何影響您的合規性分數，以評估法規遵從性。</span><span class="sxs-lookup"><span data-stu-id="fbe81-531">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="fbe81-532">審閱內建控制項對應及評估控制項。</span><span class="sxs-lookup"><span data-stu-id="fbe81-532">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="fbe81-533">在評估中產生報表。</span><span class="sxs-lookup"><span data-stu-id="fbe81-533">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="fbe81-534">

<strong> Azure 資訊保護</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-534">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="fbe81-535">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-535">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="fbe81-536">啟用並設定您的租使用者。</span><span class="sxs-lookup"><span data-stu-id="fbe81-536">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-537">在 P1 和 P2) 中建立及設定 (支援的標籤和原則。</span><span class="sxs-lookup"><span data-stu-id="fbe81-537">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-538">在 P1 和 P2) 支援的檔中套用資訊保護 (。</span><span class="sxs-lookup"><span data-stu-id="fbe81-538">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-539">在 Office 應用程式中自動分類及標記資訊 (如 Word、PowerPoint、Excel 及 Outlook) 並使用 P2 Windows 中支援的 Azure 資訊保護用戶端 (。</span><span class="sxs-lookup"><span data-stu-id="fbe81-539">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-540">在使用 Azure 資訊保護掃描程式時，在 rest 上探索和標示檔案 (在 P1 和 P2) 中支援。</span><span class="sxs-lookup"><span data-stu-id="fbe81-540">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-541">使用 Exchange Online 郵件流程規則監視傳輸中的電子郵件。</span><span class="sxs-lookup"><span data-stu-id="fbe81-541">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="fbe81-542">如果您想要使用 Microsoft Azure Rights Management Services (Azure RMS) 、Office 365 郵件加密 (OME) 以及資料遺失防護 (DLP) 來套用保護，也會提供指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-542">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="fbe81-543"><strong>下列超出範圍 </strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-543"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="fbe81-544">客戶金鑰。</span><span class="sxs-lookup"><span data-stu-id="fbe81-544">Customer key.</span></span></li>
<li><span data-ttu-id="fbe81-545">自訂正則運算式 (RegEx 機密資訊類型) 開發。</span><span class="sxs-lookup"><span data-stu-id="fbe81-545">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="fbe81-546">建立或修改關鍵字字典。</span><span class="sxs-lookup"><span data-stu-id="fbe81-546">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="fbe81-547">自訂腳本和編碼。</span><span class="sxs-lookup"><span data-stu-id="fbe81-547">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="fbe81-548">Azure Purview。</span><span class="sxs-lookup"><span data-stu-id="fbe81-548">Azure Purview.</span></span></li>
<li> <span data-ttu-id="fbe81-549">設計、設計架構和協力廠商檔審閱。</span><span class="sxs-lookup"><span data-stu-id="fbe81-549">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="fbe81-550">遵守行業和地區性法規和需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-550">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="fbe81-551">在合規性管理員中針對評估建議的改進動作的實際執行。</span><span class="sxs-lookup"><span data-stu-id="fbe81-551">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="fbe81-552">除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，Azure 資訊保護例外情況下沒有最低的系統需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-552">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="fbe81-553"><strong>Azure 資訊保護</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-553"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="fbe81-554">客戶必要的責任包括：</span><span class="sxs-lookup"><span data-stu-id="fbe81-554">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="fbe81-555">要掃描的檔案共用位置清單。</span><span class="sxs-lookup"><span data-stu-id="fbe81-555">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-556">已核准的分類分類。</span><span class="sxs-lookup"><span data-stu-id="fbe81-556">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="fbe81-557">瞭解有關金鑰管理的任何法規限制或需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-557">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-558">為您的內部部署 Active Directory 建立且與 Azure AD 同步處理的服務帳戶。</span><span class="sxs-lookup"><span data-stu-id="fbe81-558">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="fbe81-559">針對分類及保護所設定的標籤。</span><span class="sxs-lookup"><span data-stu-id="fbe81-559">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="fbe81-560">Azure 資訊保護掃描程式的所有必要條件皆已到位。</span><span class="sxs-lookup"><span data-stu-id="fbe81-560">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="fbe81-561">如需詳細資訊，請參閱 <a href="/azure/information-protection/deploy-aip-scanner-prereqs">安裝及部署 Azure 資訊保護統一標記掃描器的必要條件</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-561">For more information, see <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="fbe81-562">請確定使用者裝置執行的是支援的作業系統，且已安裝必要的必要條件。</span><span class="sxs-lookup"><span data-stu-id="fbe81-562">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="fbe81-563">如需詳細資訊，請參閱下列各項。</span><span class="sxs-lookup"><span data-stu-id="fbe81-563">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="fbe81-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">系統管理員指南：安裝 Azure 資訊保護統一標籤用戶端以供使用者</a>   </span><span class="sxs-lookup"><span data-stu-id="fbe81-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="fbe81-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">IOS 或 Android 的 Azure 資訊保護應用程式為何？</a>  </span><span class="sxs-lookup"><span data-stu-id="fbe81-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="fbe81-566">安裝和設定 Azure RMS 連接器和伺服器（包括 Active Directory RMS (AD RMS) 連接器）以進行混合支援。</span><span class="sxs-lookup"><span data-stu-id="fbe81-566">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="fbe81-567">安裝和設定會將您自己的金鑰 (BYOK) 、雙金鑰加密 (DKE)  (整合標籤用戶端) ，或是只保留您自己的金鑰 (HYOK)  (經典用戶端您應該在部署中的其中一個選項。</span><span class="sxs-lookup"><span data-stu-id="fbe81-567">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="fbe81-568"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-568"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-569">我們為您的應用程式和裝置提供準備使用 Intune 做為雲端型行動裝置管理 (MDM) 和行動應用程式管理 (MAM) 提供者的遠端指南。</span><span class="sxs-lookup"><span data-stu-id="fbe81-569">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="fbe81-570">確切的步驟取決於您的來源環境，而且是根據您的行動裝置和行動裝置應用程式管理需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-570">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="fbe81-571">步驟可能包括：</span><span class="sxs-lookup"><span data-stu-id="fbe81-571">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-572">授權使用者。</span><span class="sxs-lookup"><span data-stu-id="fbe81-572">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-573">利用您的內部部署 Active Directory 或雲端身分識別 (Azure AD) 設定供 Intune 使用的身分識別。</span><span class="sxs-lookup"><span data-stu-id="fbe81-573">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-574">將使用者新增到您的 Intune 訂用帳戶、定義 IT 系統管理員角色，以及建立使用者和裝置群組。</span><span class="sxs-lookup"><span data-stu-id="fbe81-574">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-575">根據您的管理需求，設定您的 MDM 授權機構，包括：</span><span class="sxs-lookup"><span data-stu-id="fbe81-575">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-576">當 Intune 為您唯一的 MDM 解決方案時，將 Intune 設定為 MDM 授權單位。</span><span class="sxs-lookup"><span data-stu-id="fbe81-576">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="fbe81-577">為下列提供 MDM 指引：</span><span class="sxs-lookup"><span data-stu-id="fbe81-577">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-578">設定用於驗證 MDM 管理原則的測試群組。</span><span class="sxs-lookup"><span data-stu-id="fbe81-578">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-579">設定 MDM 管理原則和服務，例如：</span><span class="sxs-lookup"><span data-stu-id="fbe81-579">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-580">透過網頁連結或深層連結，為每個支援的平臺部署應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-580">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-581">條件式存取原則。</span><span class="sxs-lookup"><span data-stu-id="fbe81-581">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-582">如果您的組織中有現有的憑證授權單位、無線網路或 VPN 基礎結構，則部署電子郵件、無線網路和 VPN 設定檔。</span><span class="sxs-lookup"><span data-stu-id="fbe81-582">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-583">連接至 Intune 資料倉儲。</span><span class="sxs-lookup"><span data-stu-id="fbe81-583">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-584">整合 Intune 與：</span><span class="sxs-lookup"><span data-stu-id="fbe81-584">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-585">小組檢視器針對遠端協助 (需要) 小組檢視器訂閱。</span><span class="sxs-lookup"><span data-stu-id="fbe81-585">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-586">行動威脅防護 (MTD) 協力廠商解決方案 (必須) 的 MTD 訂閱。</span><span class="sxs-lookup"><span data-stu-id="fbe81-586">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-587">需要)  (電信費用管理解決方案的電訊費用管理解決方案。</span><span class="sxs-lookup"><span data-stu-id="fbe81-587">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="fbe81-588">將每個支援的平台的裝置註冊到 Intune。</span><span class="sxs-lookup"><span data-stu-id="fbe81-588">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="fbe81-589">在下列情況提供應用程式保護指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-589">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-590">針對每個支援的平台設定應用程式保護原則。</span><span class="sxs-lookup"><span data-stu-id="fbe81-590">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-591">為受管理的應用程式設定條件式存取原則。</span><span class="sxs-lookup"><span data-stu-id="fbe81-591">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-592">以先前所述的 MAM 原則針對適當的使用者群組。</span><span class="sxs-lookup"><span data-stu-id="fbe81-592">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-593">使用受管理的應用程式使用方式報告。</span><span class="sxs-lookup"><span data-stu-id="fbe81-593">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="fbe81-594">提供從舊版 PC 管理到 Intune MDM 的遷移指南。</span><span class="sxs-lookup"><span data-stu-id="fbe81-594">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="fbe81-595">
 
</li>
</ul>
  
<strong>雲端附加</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-595">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="fbe81-596">我們將引導您完成 cloud-附上現有 Configuration Manager 環境與 Intune 的準備工作。</span><span class="sxs-lookup"><span data-stu-id="fbe81-596">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="fbe81-597">確切的步驟取決於您的來源環境。</span><span class="sxs-lookup"><span data-stu-id="fbe81-597">The exact steps depend on your source environment.</span></span> <span data-ttu-id="fbe81-598">這些步驟可能包括：</span><span class="sxs-lookup"><span data-stu-id="fbe81-598">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="fbe81-599">授權使用者。</span><span class="sxs-lookup"><span data-stu-id="fbe81-599">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-600">利用內部部署 Active Directory 和雲端身分識別來設定 Intune 將使用的身分識別。</span><span class="sxs-lookup"><span data-stu-id="fbe81-600">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-601">將使用者新增到您的 Intune 訂用帳戶、定義 IT 系統管理員角色，以及建立使用者和裝置群組。</span><span class="sxs-lookup"><span data-stu-id="fbe81-601">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-602">提供指導方針設定混合式 Azure AD 聯結。</span><span class="sxs-lookup"><span data-stu-id="fbe81-602">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-603">提供設定適用于 MDM 自動註冊之 Azure AD 的指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-603">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-604">提供有關如何設定雲端管理閘道的指導方針，用作遠端網際網路型裝置管理的共同管理解決方案。</span><span class="sxs-lookup"><span data-stu-id="fbe81-604">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-605">設定要切換到 Intune 的支援工作負載。</span><span class="sxs-lookup"><span data-stu-id="fbe81-605">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-606">將 Configuration Manager 用戶端安裝在 Intune 中註冊的裝置。</span><span class="sxs-lookup"><span data-stu-id="fbe81-606">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="fbe81-607"><strong>安全地部署 iOS 和 Android 的 Outlook mobile</strong>我們可以提供指導方針，協助您在組織中安全地部署 iOS 和 Android 的 Outlook mobile，以確保您的使用者已安裝所有必要的應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-607"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="fbe81-608">使用 Intune 以安全方式部署 iOS Outlook 行動裝置和 Android 的步驟，視您的來源環境而定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-608">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="fbe81-609">它可以包含：</span><span class="sxs-lookup"><span data-stu-id="fbe81-609">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-610">透過 Apple App store 或 Google Play store，下載 iOS 和 Android、Microsoft Authenticator 及 Intune 公司入口網站應用程式的 Outlook。</span><span class="sxs-lookup"><span data-stu-id="fbe81-610">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-611">提供有關設定的指導方針：</span><span class="sxs-lookup"><span data-stu-id="fbe81-611">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-612">iOS 和 Android、Microsoft Authenticator 及 Intune 公司入口網站應用程式部署使用 Intune 的 Outlook。</span><span class="sxs-lookup"><span data-stu-id="fbe81-612">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-613">應用程式保護原則。</span><span class="sxs-lookup"><span data-stu-id="fbe81-613">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-614">條件式存取原則。</span><span class="sxs-lookup"><span data-stu-id="fbe81-614">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-615">應用程式佈建原則。</span><span class="sxs-lookup"><span data-stu-id="fbe81-615">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="fbe81-616">在規劃使用 Intune 部署無線網路和 VPN 設定檔時，IT 系統管理員必須具備實際執行環境中使用的憑證授權、無線網路和 VPN 基礎結構。</span><span class="sxs-lookup"><span data-stu-id="fbe81-616">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="fbe81-617"><strong>附注</strong>： FastTrack 服務權益不包括設定或設定憑證授權機構、無線網路、VPN 基礎結構或 Apple MDM push 憑證 for Intune 的協助。</span><span class="sxs-lookup"><span data-stu-id="fbe81-617"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="fbe81-618"><strong>附註</strong>: FastTrack 服務權益不包含協助將設定管理員站台伺服器或將設定管理員用戶端設定或升級，以滿足對支援雲端附加所需的最低需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-618"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="fbe81-619">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。</span><span class="sxs-lookup"><span data-stu-id="fbe81-619">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="fbe81-620"><strong>與 Microsoft Defender for Endpoint 整合的 Intune</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-620"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="fbe81-621"><strong>附注</strong>：我們會提供整合 Intune 與 Microsoft Defender for Endpoint 的協助，並根據其 Windows 10 風險等級評估來建立裝置規範原則。</span><span class="sxs-lookup"><span data-stu-id="fbe81-621"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="fbe81-622">我們不會提供有關購買、授權或啟用的協助。</span><span class="sxs-lookup"><span data-stu-id="fbe81-622">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="fbe81-623">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。</span><span class="sxs-lookup"><span data-stu-id="fbe81-623">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="fbe81-624"><strong>Windows Autopilot</strong> </span><span class="sxs-lookup"><span data-stu-id="fbe81-624"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="fbe81-625">IT 系統管理員需負責向組織註冊他們的裝置，方法是讓硬體廠商代表他們上傳或是自行上傳其硬體識別碼到 Windows Autopilot 服務。</span><span class="sxs-lookup"><span data-stu-id="fbe81-625">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="fbe81-626">Office 365</span><span class="sxs-lookup"><span data-stu-id="fbe81-626">Office 365</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="fbe81-627">服務</span><span class="sxs-lookup"><span data-stu-id="fbe81-627">Service</span></span></th>
<th><span data-ttu-id="fbe81-628">FastTrack 指引詳細資料</span><span class="sxs-lookup"><span data-stu-id="fbe81-628">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="fbe81-629">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="fbe81-629">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="fbe81-630"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-630"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-631">對於 Exchange Online，我們將引導您讓組織準備好使用電子郵件的程序。</span><span class="sxs-lookup"><span data-stu-id="fbe81-631">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="fbe81-632">具體步驟取決於來源環境和您的電子郵件遷移計畫。</span><span class="sxs-lookup"><span data-stu-id="fbe81-632">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="fbe81-633">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-633">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-634">針對在 Office 365 中驗證的所有已啟用郵件的網域設定 Exchange Online Protection (EOP) 功能。</span><span class="sxs-lookup"><span data-stu-id="fbe81-634">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-635">指向郵件交換 (MX) 記錄以 Office 365。</span><span class="sxs-lookup"><span data-stu-id="fbe81-635">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-636">設定 Microsoft Defender for Office 365 feature （如果是訂閱服務的一部分）。</span><span class="sxs-lookup"><span data-stu-id="fbe81-636">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="fbe81-637">如需詳細資訊，請參閱<strong>Microsoft Defender for Office 365</strong> table 中的部分。</span><span class="sxs-lookup"><span data-stu-id="fbe81-637">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-p126">為 Office 365 中經驗證之所有已啟用郵件的網域設定資料遺失保護 (DLP) 功能，作為訂閱服務的一部分。將您的 MX 記錄指向 Office 365 之後即完成此項設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="fbe81-p127">為 Office 365 中經驗證之所有已啟用郵件的網域設定 Office 365 訊息加密 (OME) 功能，作為訂閱服務的一部分。將您的 MX 記錄指向 Office 365 之後即完成此項設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="fbe81-642">
  <strong>附注：</strong>信箱複寫服務 (MRS) 會嘗試將您內部部署信箱中所管理 (IRM) 電子郵件的資訊版權，遷移到對應的 Exchange Online 信箱。</span><span class="sxs-lookup"><span data-stu-id="fbe81-642">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="fbe81-643">在移轉之後，客戶必須將 Active Directory Rights Management Services (AD RMS) 範本複製到 Azure 版權管理服務 (Azure RMS)，才能讀取受保護的內容。</span><span class="sxs-lookup"><span data-stu-id="fbe81-643">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="fbe81-644">設定防火牆連接埠。</span><span class="sxs-lookup"><span data-stu-id="fbe81-644">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-645">設定 DNS，包含必要的自動探索、寄件者原則框架 (SPF) 、DomainKeys 識別的郵件 (DKIM) 、以網域為基礎的郵件驗證、報告和一致性 (DMARC) 和 MX 記錄 (如有必要) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-645">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-646">如果需要，則設定您的來源訊息環境與 Exchange Online 間的電子郵件流程。</span><span class="sxs-lookup"><span data-stu-id="fbe81-646">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-647">進行從來源郵件環境到 Office 365 的郵件移轉。</span><span class="sxs-lookup"><span data-stu-id="fbe81-647">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-648">設定信箱用戶端 (Outlook for Windows、Outlook 網頁版，以及 Outlook for iOS 和 Android)。</span><span class="sxs-lookup"><span data-stu-id="fbe81-648">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="fbe81-649">
  <strong>資料移轉</strong>  </span><span class="sxs-lookup"><span data-stu-id="fbe81-649">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="fbe81-650">如需使用 FastTrack Office 365 的資料移轉優點的詳細資訊，請參閱<a href="/fasttrack/data-migration">資料移轉</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-650">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="fbe81-651">您的來源環境必須具有下列其中一個基本層級：</span><span class="sxs-lookup"><span data-stu-id="fbe81-651">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-652">含有 Exchange Server 2003 以上版本的單一或多個 Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="fbe81-652">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-653">具備單一網際網路訊息存取通訊協定 (IMAP) 功能的電子郵件環境。</span><span class="sxs-lookup"><span data-stu-id="fbe81-653">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-654">單一 G Suite 環境 (僅限 Gmail、連絡人和行事曆)。</span><span class="sxs-lookup"><span data-stu-id="fbe81-654">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-655">如需多地理位置功能的詳細資訊，請參閱<a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online 中的多地理位置功能</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-655">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="fbe81-656">線上用戶端軟體（如 Project for Office 365）、Outlook Windows、iOS 和 Android Outlook 商務用 OneDrive 同步處理用戶端、Power BI Desktop 和商務用 Skype，必須是<a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="fbe81-656">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="fbe81-657"><strong>適用於 Office 365 的 Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-657"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-658">如需詳細資訊，請參閱<a href="/fasttrack/products-and-capabilities#security-and-compliance">安全性和合規性</a>中<strong>的 Microsoft Defender Office 365</strong> 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-658">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="fbe81-659"><strong>Microsoft 資訊控管</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-659"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-660">如需詳細資訊，請參閱<a href="/fasttrack/products-and-capabilities#security-and-compliance">安全性和合規性</a>中的<strong>Microsoft 資訊管理</strong>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-660">For more information, see <strong> Microsoft Information Governance</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="fbe81-661"><strong>Microsoft 資訊保護</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-661"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="fbe81-662">如需詳細資訊，請參閱<a href="/fasttrack/products-and-capabilities#security-and-compliance">安全性和合規性</a> <strong>Microsoft 資訊保護</strong>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-662">For more information, see <strong>Microsoft Information Protection </strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="fbe81-663"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-663"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-664">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-665">確認 Exchange Online 中的最低需求、SharePoint 線上、Office 365 群組和 Azure AD 以支援 Teams。</span><span class="sxs-lookup"><span data-stu-id="fbe81-665">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-666">設定防火牆連接埠。</span><span class="sxs-lookup"><span data-stu-id="fbe81-666">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-667">設立 DNS。</span><span class="sxs-lookup"><span data-stu-id="fbe81-667">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-668">確認您的 Office 365 租用戶上已啟用 Teams。</span><span class="sxs-lookup"><span data-stu-id="fbe81-668">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-669">啟用或停用使用者授權。</span><span class="sxs-lookup"><span data-stu-id="fbe81-669">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-670">Teams 的網路評估：</span><span class="sxs-lookup"><span data-stu-id="fbe81-670">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-671">連接埠和端點檢查。</span><span class="sxs-lookup"><span data-stu-id="fbe81-671">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-672">連線品質檢查。</span><span class="sxs-lookup"><span data-stu-id="fbe81-672">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-673">頻寬估計。</span><span class="sxs-lookup"><span data-stu-id="fbe81-673">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="fbe81-674">設定 Teams 和 Android 應用程式 iOS 的 Teams 應用程式原則 (Teams web 應用程式、Teams 桌面應用程式和) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-674">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="fbe81-675">如果適用，我們也會提供下列專案的指引。。</span><span class="sxs-lookup"><span data-stu-id="fbe81-675">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-676">Microsoft Teams會議室裝置：</span><span class="sxs-lookup"><span data-stu-id="fbe81-676">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="fbe81-677">建立 <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams 裝置目錄</a>中列出的受支援電話和會議室裝置所需的線上帳戶。</span><span class="sxs-lookup"><span data-stu-id="fbe81-677">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-678">遠端協助，含已驗證 Microsoft Teams 會議室裝置的服務端設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-678">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-679">啟用音訊會議：</span><span class="sxs-lookup"><span data-stu-id="fbe81-679">Enabling Audio Conferencing:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="fbe81-680">會議橋接預設設定的組織設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-680">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-681">對授權使用者會議橋接的指派。</span><span class="sxs-lookup"><span data-stu-id="fbe81-681">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="fbe81-682">電話系統：</span><span class="sxs-lookup"><span data-stu-id="fbe81-682">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-683">雲端語音預設設定的組織設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-683">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-684">通話方案指引 (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">可用市場</a>) ：</span><span class="sxs-lookup"><span data-stu-id="fbe81-684">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-685">授權使用者號碼的指派。</span><span class="sxs-lookup"><span data-stu-id="fbe81-685">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-686">透過使用者介面 (UI) 的本機號碼移轉指引最多至 999。</span><span class="sxs-lookup"><span data-stu-id="fbe81-686">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-687">本機號碼移轉服務要求 (SR) 支援超過 999。</span><span class="sxs-lookup"><span data-stu-id="fbe81-687">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="fbe81-688">直接路由指引：</span><span class="sxs-lookup"><span data-stu-id="fbe81-688">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-689">組織安裝指導，以供協力廠商託管案例的直接路由設計，或最多10個網站的客戶部署案例。</span><span class="sxs-lookup"><span data-stu-id="fbe81-689">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="fbe81-690">會話邊界控制器 (SBC) 設定複查。</span><span class="sxs-lookup"><span data-stu-id="fbe81-690">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="fbe81-691">使用撥號對應表設定的遠端協助。</span><span class="sxs-lookup"><span data-stu-id="fbe81-691">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="fbe81-692">語音路由設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-692">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="fbe81-693">媒體旁路和本機媒體優化。</span><span class="sxs-lookup"><span data-stu-id="fbe81-693">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="fbe81-694">啟用 Teams 即時活動。</span><span class="sxs-lookup"><span data-stu-id="fbe81-694">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-695">組織設定與 Microsoft Stream 整合。</span><span class="sxs-lookup"><span data-stu-id="fbe81-695">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-696">商務用 Skype Teams 轉換的指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-696">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="fbe81-697">Azure AD 中為 Office 365 啟用的身分識別。</span><span class="sxs-lookup"><span data-stu-id="fbe81-697">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-698">已啟用 SharePoint Online 的使用者。</span><span class="sxs-lookup"><span data-stu-id="fbe81-698">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-699">Exchange 信箱 (線上和內部部署 Exchange 的混合式設定) 中。</span><span class="sxs-lookup"><span data-stu-id="fbe81-699">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-700">啟用 Office 365 群組。</span><span class="sxs-lookup"><span data-stu-id="fbe81-700">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="fbe81-701">
  <strong>附注：</strong>如果未使用 SharePoint 線上授權指派及啟用使用者，則在 Office 365 中不會有商務用 OneDrive 儲存區。</span><span class="sxs-lookup"><span data-stu-id="fbe81-701">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="fbe81-702">檔案共用仍可在通道中運作，但是使用者無法在聊天中共用檔案，也不會在 Office 365 中商務用 OneDrive 儲存區。</span><span class="sxs-lookup"><span data-stu-id="fbe81-702">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="fbe81-703">Teams 不支援 SharePoint 內部部署。</span><span class="sxs-lookup"><span data-stu-id="fbe81-703">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="fbe81-704">
  <strong>附注：</strong>理想的狀態是讓所有使用者的信箱位於 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="fbe81-704">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="fbe81-705">擁有內部部署信箱的使用者，必須透過 Azure AD 連線，將其身分識別與 Office 365 目錄同步。</span><span class="sxs-lookup"><span data-stu-id="fbe81-705">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="fbe81-706">針對這些 Exchange 的混合式客戶，如果使用者的信箱在內部部署中，使用者就無法新增或設定連接器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-706">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="fbe81-707">Microsoft Teams Windows 安裝程式和 Mac 桌面用戶端可以從這裡下載：<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-707">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="fbe81-708"><strong>Outlook for iOS 和 Android</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-708"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-709">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-709">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-710">從 Apple App Store 和 Google Play 下載 Outlook for iOS 和 Android。</span><span class="sxs-lookup"><span data-stu-id="fbe81-710">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-711">設定帳戶並存取 Exchange Online 信箱。</span><span class="sxs-lookup"><span data-stu-id="fbe81-711">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-712">保護 Outlook 行動 (如需詳細資訊，請參閱<a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">在 Exchange Online 中為 iOS 和 Android 提供安全 Outlook</a>) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-712">Securing Outlook mobile (see <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="fbe81-713">Azure AD 中為 Office 365 啟用的身分識別。</span><span class="sxs-lookup"><span data-stu-id="fbe81-713">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-714">已設定 Exchange Online 並指派授權。</span><span class="sxs-lookup"><span data-stu-id="fbe81-714">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="fbe81-715"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-715"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-716">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-716">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-717">指派 Power BI 的授權。</span><span class="sxs-lookup"><span data-stu-id="fbe81-717">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-718">部署 Power BI Desktop 應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-718">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="fbe81-719">線上用戶端軟體（如 Power BI Desktop）必須是<a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="fbe81-719">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="fbe81-720"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-720"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-721">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-721">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-722">確認 Microsoft Project Online 依賴的基本 SharePoint 功能。</span><span class="sxs-lookup"><span data-stu-id="fbe81-722">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-723">將 Microsoft Project Online 服務新增到您的租用戶中 (包括新增使用者的訂閱)。</span><span class="sxs-lookup"><span data-stu-id="fbe81-723">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-724">設定企業資源資料庫​​ (ERP)。</span><span class="sxs-lookup"><span data-stu-id="fbe81-724">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-725">建立您的第一個專案。</span><span class="sxs-lookup"><span data-stu-id="fbe81-725">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="fbe81-726">線上用戶端軟體（如 Project for Office 365）必須是<a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="fbe81-726">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="fbe81-727"><strong>Project Online 專業版和進階版</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-727"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-728">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-728">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-729">解決部署問題。</span><span class="sxs-lookup"><span data-stu-id="fbe81-729">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-730">使用 Microsoft 365 系統管理中心和 Windows PowerShell 指派使用者授權。</span><span class="sxs-lookup"><span data-stu-id="fbe81-730">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-731">使用隨選即用從 Office 365 入口網站安裝 Project Online 桌面用戶端。</span><span class="sxs-lookup"><span data-stu-id="fbe81-731">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-732">使用 Office 365 部署工具來設定更新設定。</span><span class="sxs-lookup"><span data-stu-id="fbe81-732">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-733">設定 Project Online 桌面用戶端的單一內部網站發佈伺服器，包含建立搭配 Office 365 部署工具使用之 configuration.xml 檔案的相關協助。</span><span class="sxs-lookup"><span data-stu-id="fbe81-733">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-734">正在將 Project Online 桌面用戶端連線至 Project Online 專業版或 Project Online 進階版。</span><span class="sxs-lookup"><span data-stu-id="fbe81-734">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="fbe81-735">線上用戶端軟體（如 Project for Office 365）必須是<a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="fbe81-735">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="fbe81-736"><strong>SharePoint Online 和商務用 OneDrive</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-736"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-737">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-737">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-738">設立 DNS。</span><span class="sxs-lookup"><span data-stu-id="fbe81-738">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-739">設定防火牆連接埠。</span><span class="sxs-lookup"><span data-stu-id="fbe81-739">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-740">佈建使用者和授權。</span><span class="sxs-lookup"><span data-stu-id="fbe81-740">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="fbe81-741">啟用 SharePoint Online 管理員的網站架設。</span><span class="sxs-lookup"><span data-stu-id="fbe81-741">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="fbe81-742">規劃網站集合。</span><span class="sxs-lookup"><span data-stu-id="fbe81-742">Planning site collections.</span></span></li>
<li><span data-ttu-id="fbe81-743">保護內容與管理權限。</span><span class="sxs-lookup"><span data-stu-id="fbe81-743">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="fbe81-744">設定 SharePoint Online 功能。</span><span class="sxs-lookup"><span data-stu-id="fbe81-744">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="fbe81-745">設定 SharePoint 混合式功能，如混合式搜尋、混合式網站、混合式分類、內容類型、混合式自助網站架設 (僅限 SharePoint Server 2013)、擴充的應用程式啟動器、混合式商務用 OneDrive，以及外部網路網站。</span><span class="sxs-lookup"><span data-stu-id="fbe81-745">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-746">您的遷移方法。</span><span class="sxs-lookup"><span data-stu-id="fbe81-746">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="fbe81-747">根據您的 SharePoint 版本，商務用 OneDrive 提供額外的指導方針，如下所示：</span><span class="sxs-lookup"><span data-stu-id="fbe81-747">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-748">識別整合選項，並複查內部部署和線上網路基礎結構和頻寬。</span><span class="sxs-lookup"><span data-stu-id="fbe81-748">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-749">安裝 SharePoint Online 2013 SP1 (（如果適用）) 、規劃及實施同步處理及身分識別需求，以及識別您的商務用 OneDrive 同步處理用戶端。</span><span class="sxs-lookup"><span data-stu-id="fbe81-749">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-750">為所有使用者規劃及實施單一推廣 (或分階段的展示) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-750">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-751">指派授權、將「我的網站」和個人文件庫重新導向至 Office 365 (適用于 SharePoint 線上 2013) ，設定物件，以控制 OneDrive (線上 2013 SharePoint 的存取權。</span><span class="sxs-lookup"><span data-stu-id="fbe81-751">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="fbe81-752">在 OneDrive 中重新導向或移動已知的資料夾。</span><span class="sxs-lookup"><span data-stu-id="fbe81-752">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="fbe81-753">部署商務用 OneDrive 用戶端同步處理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-753">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="fbe81-754">
  <strong>資料移轉</strong>  </span><span class="sxs-lookup"><span data-stu-id="fbe81-754">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="fbe81-755">如需使用 FastTrack Office 365 的資料移轉優點的詳細資訊，請參閱<a href="/fasttrack/data-migration">資料移轉</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-755">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="fbe81-756"><strong>SharePoint 混合：</strong>  
</span><span class="sxs-lookup"><span data-stu-id="fbe81-756"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="fbe81-757">SharePoint 混合式設定包括設定混合式搜尋、網站、分類法、內容類型、商務用 OneDrive、擴充的應用程式啟動器、外部網路網站，以及從內部部署至單一目標 SharePoint 線上環境的自助網站架設。</span><span class="sxs-lookup"><span data-stu-id="fbe81-757">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="fbe81-758">
  <strong>附注：</strong>自助網站架設不在執行 SharePoint 2013 的內部部署伺服器範圍內。</span><span class="sxs-lookup"><span data-stu-id="fbe81-758">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="fbe81-759">若要啟用 SharePoint 混合式，您必須具有下列其中一個內部部署 SharePoint 伺服器環境：2013、2016或2019。</span><span class="sxs-lookup"><span data-stu-id="fbe81-759">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="fbe81-760">
  <strong>附注：</strong>SharePoint 伺服器的內部部署 SharePoint 環境升級為不在範圍內。</span><span class="sxs-lookup"><span data-stu-id="fbe81-760">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="fbe81-761">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。</span><span class="sxs-lookup"><span data-stu-id="fbe81-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="fbe81-762">如需詳細資訊，請參閱<a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint 混合式功能的最小公用更新層級</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="fbe81-762">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="fbe81-763">
  <strong>附注：</strong>如需多地理位置功能的詳細資訊，請參閱<a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365 中 OneDrive 和 SharePoint Online 中的多地理位置功能</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="fbe81-763">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="fbe81-764"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-764"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="fbe81-765">我們提供啟用 Yammer Enterprise 服務的遠端指南。</span><span class="sxs-lookup"><span data-stu-id="fbe81-765">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="fbe81-766">線上用戶端軟體必須具備<a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="fbe81-766">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="fbe81-767">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="fbe81-767">Enterprise Mobility + Security</span></span> 

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="fbe81-768">服務</span><span class="sxs-lookup"><span data-stu-id="fbe81-768">Service</span></span></th>
<th><span data-ttu-id="fbe81-769">FastTrack 指引詳細資料</span><span class="sxs-lookup"><span data-stu-id="fbe81-769">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="fbe81-770">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="fbe81-770">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="fbe81-771"><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-771"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-772">如需詳細資訊，請參閱<strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong>的<a href="/fasttrack/products-and-capabilities#security-and-compliance">安全性和符合性</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-772">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="fbe81-773"><strong>Azure 資訊保護 </strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-773"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="fbe81-774">如需 Azure 資訊保護的詳細資訊，請參閱<a href="/fasttrack/products-and-capabilities#security-and-compliance">安全性和合規性</a>中的<strong>Microsoft 資訊保護</strong>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-774">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="fbe81-775"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-775"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-776">如需詳細資訊，請參閱<a href="/fasttrack/products-and-capabilities#security-and-compliance">安全性和合規性</a> <strong>Microsoft Intune</strong> 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-776">For more information, see <strong> Microsoft Intune</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="fbe81-777">Windows 10</span><span class="sxs-lookup"><span data-stu-id="fbe81-777">Windows 10</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="fbe81-778">服務</span><span class="sxs-lookup"><span data-stu-id="fbe81-778">Service</span></span></th>
<th><span data-ttu-id="fbe81-779">FastTrack 指引詳細資料</span><span class="sxs-lookup"><span data-stu-id="fbe81-779">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="fbe81-780">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="fbe81-780">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="fbe81-781"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-781"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-782">我們提供從 Windows 7 專業版升級，並 Windows 8.1 Professional 到 Windows 10 企業版的指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-782">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="fbe81-783">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-783">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-784">瞭解您的 Windows 10 意圖。</span><span class="sxs-lookup"><span data-stu-id="fbe81-784">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-785">評估來源環境和需求 (確定 Microsoft Endpoint Configuration Manager 升級為所需的層級，以支援 Windows 10 部署) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-785">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-786">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 部署 Windows 10 企業版和 Microsoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="fbe81-786">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-787">建議您用來評估您的 Windows 10 應用程式的選項。</span><span class="sxs-lookup"><span data-stu-id="fbe81-787">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-788">啟用桌面 analytics 的使用，以及建立桌面分析部署計畫的指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-788">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-789">使用 Configuration Manager 中的 Office 365 準備儀表板或獨立的準備人工具組來 Microsoft 365 Apps 相容性評估，以 Office 以及部署 Microsoft 365 Apps 的協助。</span><span class="sxs-lookup"><span data-stu-id="fbe81-789">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-790">針對成功部署的最低需求，建立修復檢查清單，以達到您需要執行的動作。</span><span class="sxs-lookup"><span data-stu-id="fbe81-790">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-791">提供現有裝置的升級指導，以 Windows 10 企業版是否符合必要的裝置硬體需求。</span><span class="sxs-lookup"><span data-stu-id="fbe81-791">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-792">提供升級指導以支援現有的部署動作。</span><span class="sxs-lookup"><span data-stu-id="fbe81-792">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="fbe81-793">FastTrack 會建議並提供 Windows 10 就地升級的指引。</span><span class="sxs-lookup"><span data-stu-id="fbe81-793">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="fbe81-794">也提供 Windows 全新映像安裝和 Windows Autopilot 部署案例的指引。</span><span class="sxs-lookup"><span data-stu-id="fbe81-794">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-795">使用 Configuration Manager 部署 Microsoft 365 Apps Windows 10 部署的一部分。</span><span class="sxs-lookup"><span data-stu-id="fbe81-795">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="fbe81-796">提供指導方針，以協助您的組織使用現有的 Configuration Manager 環境或 Microsoft 365 保持最新的 Windows 10 企業版和 Microsoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="fbe81-796">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li> 
</ul><span data-ttu-id="fbe81-797">
  
<strong>下列超出範圍 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="fbe81-797">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="fbe81-798">將 Configuration Manager 升級至最新分支。</span><span class="sxs-lookup"><span data-stu-id="fbe81-798">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-799">建立適用於 Windows 10 部署的自訂映像。</span><span class="sxs-lookup"><span data-stu-id="fbe81-799">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-800">建立及支援 Windows 10 部署的部署指令碼。</span><span class="sxs-lookup"><span data-stu-id="fbe81-800">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-801">將 Windows 10 系統從 BIOS 轉換為整合可延伸韌體介面 (UEFI)。</span><span class="sxs-lookup"><span data-stu-id="fbe81-801">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-802">啟用 Windows 10 的安全性功能。</span><span class="sxs-lookup"><span data-stu-id="fbe81-802">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-803">將 Windows 部署服務 (WDS) 設定為開機前執行環境 (PXE) 啟動。</span><span class="sxs-lookup"><span data-stu-id="fbe81-803">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-804">使用 Microsoft Deployment Toolkit (MDT) 來擷取及部署 Windows 10 映像。</span><span class="sxs-lookup"><span data-stu-id="fbe81-804">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-805">使用使用者狀態移轉工具 (USMT)</span><span class="sxs-lookup"><span data-stu-id="fbe81-805">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="fbe81-806">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。</span><span class="sxs-lookup"><span data-stu-id="fbe81-806">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="fbe81-807">若要升級電腦，您必須符合下列需求：</span><span class="sxs-lookup"><span data-stu-id="fbe81-807">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-808">來源作業系統： Windows 7 企業版或 Professional、Windows 8.1 企業版或 Professional。</span><span class="sxs-lookup"><span data-stu-id="fbe81-808">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-809">裝置：桌面、筆記本或平板電腦板型。</span><span class="sxs-lookup"><span data-stu-id="fbe81-809">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-810">目標作業系統：視窗 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="fbe81-810">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="fbe81-811">若要升級基礎結構，您必須符合以下需求：</span><span class="sxs-lookup"><span data-stu-id="fbe81-811">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-812">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="fbe81-812">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-813">Configuration Manager 版本必須支援 Windows 10 目標版本。</span><span class="sxs-lookup"><span data-stu-id="fbe81-813">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="fbe81-814">如需詳細資訊，請參閱位於<a href="/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager 對於 Windows 10 的支援</a>的 Configuration Manager 支援表格。</span><span class="sxs-lookup"><span data-stu-id="fbe81-814">For more information, see the Configuration Manager support table at <a href="/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="fbe81-815"><strong>適用於端點的 Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-815"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-816">如需詳細資訊，請參閱<a href="/fasttrack/products-and-capabilities#security-and-compliance">安全性和合規性</a>中<strong>的 Microsoft Defender for Endpoint</strong> 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-816">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="fbe81-817">Windows 虛擬桌面</span><span class="sxs-lookup"><span data-stu-id="fbe81-817">Windows Virtual Desktop</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="fbe81-818">服務</span><span class="sxs-lookup"><span data-stu-id="fbe81-818">Service</span></span></th>
<th><span data-ttu-id="fbe81-819">FastTrack 指引詳細資料</span><span class="sxs-lookup"><span data-stu-id="fbe81-819">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="fbe81-820">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="fbe81-820">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="fbe81-821"><strong>Windows 虛擬桌面</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-821"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="fbe81-822">我們為上架 (桌面和 app virtualization service) 提供 Windows 虛擬桌面的部署指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-822">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="fbe81-823">Windows虛擬桌面利用 Windows 10 多重會話體驗，針對 Microsoft 365 的整合式安全性和管理，針對 Enterprise Microsoft 365 Apps 進行優化。</span><span class="sxs-lookup"><span data-stu-id="fbe81-823">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="fbe81-824">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="fbe81-824">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="fbe81-825">使用下列專案為 Enterprise 部署 Windows 10 企業版多重會話和 Microsoft 365 Apps：</span><span class="sxs-lookup"><span data-stu-id="fbe81-825">Deploying Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="fbe81-826">Azure Marketplace 影像。</span><span class="sxs-lookup"><span data-stu-id="fbe81-826">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="fbe81-827">共用圖像。</span><span class="sxs-lookup"><span data-stu-id="fbe81-827">Shared image.</span></span></li>
<li><span data-ttu-id="fbe81-828">Office部署工具組 (ODT) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-828">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="fbe81-829">在原生 Windows 虛擬桌面中設定 FSLogix 的 Microsoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="fbe81-829">Configuring Microsoft 365 Apps for FSLogix in a native Windows Virtual Desktop.</span></span> <span data-ttu-id="fbe81-830">若為 FSLogix：</span><span class="sxs-lookup"><span data-stu-id="fbe81-830">For FSLogix:</span></span>
<ul>
<li><span data-ttu-id="fbe81-831">部署代理程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-831">Deploying the Agent.</span></span></li>
<li><span data-ttu-id="fbe81-832">設定設定檔及 Office 容器。</span><span class="sxs-lookup"><span data-stu-id="fbe81-832">Configuring Profile and Office containers.</span></span></li>
<li><span data-ttu-id="fbe81-833">為 Microsoft 365 Apps 設定內容排除和資料夾重定向。</span><span class="sxs-lookup"><span data-stu-id="fbe81-833">Configuring content exclusions and folder redirections for Microsoft 365 Apps.</span></span></li>
</ul></li>
<li><span data-ttu-id="fbe81-834">部署 Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="fbe81-834">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="fbe81-835">使用優化部署 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="fbe81-835">Deploying Microsoft Teams with optimization.</span></span></li>
</ul><span data-ttu-id="fbe81-836">

<strong>下列超出範圍</strong>
</span><span class="sxs-lookup"><span data-stu-id="fbe81-836">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="fbe81-837">Project 管理客戶的 Windows 虛擬桌面基礎結構部署。</span><span class="sxs-lookup"><span data-stu-id="fbe81-837">Project management of the customer's Windows Virtual Desktop infrastructure deployment.</span></span></li>
<li><span data-ttu-id="fbe81-838">協力廠商應用程式虛擬化和部署。</span><span class="sxs-lookup"><span data-stu-id="fbe81-838">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="fbe81-839">建立 Windows 虛擬機器的自訂圖像。</span><span class="sxs-lookup"><span data-stu-id="fbe81-839">Creation of custom images for Windows Virtual Desktop.</span></span></li>
<li><span data-ttu-id="fbe81-840">涉及 VMware 和 Citrix 的遷移和案例。</span><span class="sxs-lookup"><span data-stu-id="fbe81-840">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="fbe81-841">Linux 案例。</span><span class="sxs-lookup"><span data-stu-id="fbe81-841">Linux scenarios.</span></span></li>
<li><span data-ttu-id="fbe81-842">轉換或遷移使用者設定檔。</span><span class="sxs-lookup"><span data-stu-id="fbe81-842">Conversion or migrations of user profiles.</span></span></li>
<li><span data-ttu-id="fbe81-843">Windows 虛擬機器 (的 Microsoft Endpoint Configuration Manager 和 Microsoft 端點管理員設定（包括修補與管理) ）。</span><span class="sxs-lookup"><span data-stu-id="fbe81-843">Microsoft Endpoint Configuration Manager and Microsoft Endpoint Manager configuration for Windows Virtual Desktop (including patching and management).</span></span> </li>
<li><span data-ttu-id="fbe81-844">具有 Windows 10 多重會話的 Microsoft 365 Defender。</span><span class="sxs-lookup"><span data-stu-id="fbe81-844">Microsoft 365 Defender with Windows 10 multi-session.</span></span></li>
</ul>
<span data-ttu-id="fbe81-845">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。</span><span class="sxs-lookup"><span data-stu-id="fbe81-845">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="fbe81-846">您應該已經具備下列專案：</span><span class="sxs-lookup"><span data-stu-id="fbe81-846">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="fbe81-847"><a href="/azure/virtual-desktop/overview#requirements">Windows 虛擬機器授權需求</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-847"><a href="/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li> <span data-ttu-id="fbe81-848"><a href="/azure/virtual-desktop/overview">支援 Windows 虛擬 Deskstop 的必要基礎結構</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-848">The <a href="/azure/virtual-desktop/overview"> required infrastructure to support Windows Virtual Deskstop</a>.</span></span> </li>
<ul>
<li><span data-ttu-id="fbe81-849"><a href="/azure/virtual-desktop/store-fslogix-profile">Windows 虛擬 Deskstop 中的 FSLogix 設定檔容器儲存體</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-849"><a href="/azure/virtual-desktop/store-fslogix-profile"> Storage for FSLogix profile containers in Windows Virtual Deskstop</a>.</span></span> </li>
</ul>
<li><span data-ttu-id="fbe81-850">Azure 網路：</span><span class="sxs-lookup"><span data-stu-id="fbe81-850">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="fbe81-851">虛擬網路 (VNET) 建立及子網。</span><span class="sxs-lookup"><span data-stu-id="fbe81-851">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="fbe81-852">防火牆和網路安全性群組。</span><span class="sxs-lookup"><span data-stu-id="fbe81-852">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="fbe81-853">VPN 和 ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="fbe81-853">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="fbe81-854">從內部部署路由傳送至 Azure。</span><span class="sxs-lookup"><span data-stu-id="fbe81-854">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="fbe81-855">允許連線至 Windows 虛擬桌面的防火牆規則。</span><span class="sxs-lookup"><span data-stu-id="fbe81-855">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="fbe81-856">如需詳細資訊，請參閱 <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">支援的遠端桌面用戶端</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-856">For more information, see <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="fbe81-857">Azure AD 一般設定：</span><span class="sxs-lookup"><span data-stu-id="fbe81-857">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="fbe81-858">身分識別策略 <i> (您只能使用下列三個選項) 中的其中一項：</i>
</span><span class="sxs-lookup"><span data-stu-id="fbe81-858">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="fbe81-859">Azure 中使用 Azure AD 連線的 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="fbe81-859">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="fbe81-860">使用 Azure AD 在 VPN 或 ExpressRoute 上內部部署的 Active Directory 連線。</span><span class="sxs-lookup"><span data-stu-id="fbe81-860">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="fbe81-861">Active Directory 網域服務 (AD DS) 。</span><span class="sxs-lookup"><span data-stu-id="fbe81-861">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="fbe81-862">應用程式保證</span><span class="sxs-lookup"><span data-stu-id="fbe81-862">App Assure</span></span>


<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="fbe81-863">服務</span><span class="sxs-lookup"><span data-stu-id="fbe81-863">Service</span></span></th>
<th><span data-ttu-id="fbe81-864">FastTrack 指引詳細資料</span><span class="sxs-lookup"><span data-stu-id="fbe81-864">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="fbe81-865">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="fbe81-865">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="fbe81-866"><strong>應用程式保證</strong></span><span class="sxs-lookup"><span data-stu-id="fbe81-866"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="fbe81-867">應用程式保證是一種服務，旨在解決 Windows 10 和 Microsoft 365 Apps 應用程式相容性的問題。</span><span class="sxs-lookup"><span data-stu-id="fbe81-867">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="fbe81-868">當您要求 App 保證服務時，我們會與您合作，以免費處理有效的應用程式問題，不需要您購買合格的訂閱。</span><span class="sxs-lookup"><span data-stu-id="fbe81-868">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="fbe81-869">我們也會在部署 Windows 虛擬桌面及 Microsoft Edge 時，提供客戶面臨相容性問題的指導方針，並提供解決相容性問題的每一種合理工作。</span><span class="sxs-lookup"><span data-stu-id="fbe81-869">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="fbe81-870">我們會為下列 Microsoft 產品上部署的應用程式提供修正協助：</span><span class="sxs-lookup"><span data-stu-id="fbe81-870">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="fbe81-871"><strong>Windows 10</strong> (包括 ARM64 裝置) </span><span class="sxs-lookup"><span data-stu-id="fbe81-871"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="fbe81-872"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="fbe81-872"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="fbe81-873"><strong>Microsoft Edge-</strong>如需部署指導，請參閱<a href="/DeployEdge/microsoft-edge-channels">Microsoft Edge 通道的概述</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-873"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-874"><strong>Windows 虛擬機器</strong> -如需詳細資訊，請參閱<a href="/azure/virtual-desktop/overview">什麼是 Windows 虛擬機器？</a>及<a href="/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 企業版多重會話常見問題</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-874"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="fbe81-875">

<strong>下列超出範圍 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="fbe81-875">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="fbe81-876">應用程式清查和測試，以判斷可否在 Windows 10 和 Microsoft 365 Apps 上運作。</span><span class="sxs-lookup"><span data-stu-id="fbe81-876">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="fbe81-877">如需有關此程序的詳細指示，請瀏覽<a href="https://go.microsoft.com/fwlink/?linkid=2080140">電腦部署中心</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-877">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="fbe81-878">如果您對於深入的升級整備評估有興趣，請填寫<a href="https://go.microsoft.com/fwlink/?linkid=2053818">客戶要求現代化電腦評估</a>表單。</span><span class="sxs-lookup"><span data-stu-id="fbe81-878">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="fbe81-879">針對 Windows 10 相容性和支援狀態，研究第三方 ISV 應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-879">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="fbe81-880">如需詳細資訊，請參閱<a href="/sccm/desktop-analytics/overview">電腦分析</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-880">For more information, see <a href="/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="fbe81-881">僅限應用程式封裝的服務。</span><span class="sxs-lookup"><span data-stu-id="fbe81-881">App packaging-only services.</span></span> <span data-ttu-id="fbe81-882">不過，應用程式保證小組會將我們針對 Windows 10 修復的應用程式封裝起來，以確保這些應用程式可以在客戶的環境中部署。</span><span class="sxs-lookup"><span data-stu-id="fbe81-882">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="fbe81-883">

<strong>客戶責任包括</strong>  
</span><span class="sxs-lookup"><span data-stu-id="fbe81-883">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="fbe81-884">建立應用程式清查。</span><span class="sxs-lookup"><span data-stu-id="fbe81-884">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="fbe81-885">在 Windows 10 和 Microsoft 365 Apps 上驗證這些應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-885">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="fbe81-886">
<strong>附注：</strong>  Microsoft 無法對您的原始程式碼進行變更。</span><span class="sxs-lookup"><span data-stu-id="fbe81-886">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="fbe81-887">不過，應用程式保證小組可以在原始程式碼適用於您的應用程式時，為應用程式開發人員提供指導方針。</span><span class="sxs-lookup"><span data-stu-id="fbe81-887">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="fbe81-888">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。</span><span class="sxs-lookup"><span data-stu-id="fbe81-888">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="fbe81-889"><strong>Windows 10 和 Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="fbe81-889"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="fbe81-890">可在 Windows 7、Windows 8.1、Office 2010 和 Office 2013 中執行的應用程式也適用於 Windows 10 和 Microsoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="fbe81-890">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="fbe81-891">
<strong>ARM 上的 Windows 10</strong>
</span><span class="sxs-lookup"><span data-stu-id="fbe81-891">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="fbe81-892">處理 Windows 7 上的應用程式、Office 2010 或更新版本的應用程式也會在 ARM64 裝置上 Windows 10 和 Microsoft 365 Apps 運作。</span><span class="sxs-lookup"><span data-stu-id="fbe81-892">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="fbe81-893">
  <strong>注意：</strong> 
</span><span class="sxs-lookup"><span data-stu-id="fbe81-893">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="fbe81-894">在參與<a href="https://insider.windows.com/">Windows 有問必答方案</a>的客戶預覽中，可使用 x64 (64 位) 模擬。</span><span class="sxs-lookup"><span data-stu-id="fbe81-894">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="fbe81-895">針對 Windows 10 版本 2004 (或更新版本) 的非 Windows 內幕用戶端，使用<a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL 和 OpenGL 相容性套件</a>支援 ARM64 Photoshop。</span><span class="sxs-lookup"><span data-stu-id="fbe81-895">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="fbe81-896">Windows 預覽體驗計畫中的客戶可以下載 OpenCL 和 OpenGL 相容性套件的有問必答版本，以與其他應用程式搭配使用。</span><span class="sxs-lookup"><span data-stu-id="fbe81-896">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="fbe81-897">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="fbe81-897">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="fbe81-898">如果您的 web 應用程式或網站在 Internet Explorer 11、支援版本的 Google Chrome 或任何版本的 Microsoft Edge 上運作，也會與 Microsoft Edge 搭配運作。</span><span class="sxs-lookup"><span data-stu-id="fbe81-898">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-899">當網頁不斷演變時，請務必查看此已發佈的已知<a href="/microsoft-edge/web-platform/site-impacting-changes">網站相容性清單-影響 Microsoft Edge 的變更</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-899">As the web is constantly evolving, be sure to review this published list of known <a href="/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="fbe81-900">
  <strong>Windows虛擬桌面</strong>  
</span><span class="sxs-lookup"><span data-stu-id="fbe81-900">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="fbe81-901">在 Windows Server 遠端桌面工作階段主機 (RDSH) 上執行的虛擬化應用程式，也能隨著 Windows 虛擬桌面的一部分在 Windows 10 企業版多重工作階段上執行。</span><span class="sxs-lookup"><span data-stu-id="fbe81-901">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-902">在任何 Windows 7 或 Windows 10 虛擬桌面基礎結構上執行的應用程式 (VDI) 環境也會在 Windows 7 企業版虛擬桌面的 Windows 10 企業版和 Windows 中執行。</span><span class="sxs-lookup"><span data-stu-id="fbe81-902">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-903">在 Windows 7 或 Windows 10 用戶端裝置上執行的應用程式，也能隨著 Windows 虛擬桌面的一部分在 Windows 7 企業版和 Windows 10 企業版上執行。</span><span class="sxs-lookup"><span data-stu-id="fbe81-903">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="fbe81-904">
  <strong>附注：</strong> Windows 10 企業版多會話相容性排除和限制包括：</span><span class="sxs-lookup"><span data-stu-id="fbe81-904">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="fbe81-905">有限的硬體重新導向。</span><span class="sxs-lookup"><span data-stu-id="fbe81-905">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-906">A/V 密集型應用程式可能會以降低的容量執行。</span><span class="sxs-lookup"><span data-stu-id="fbe81-906">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="fbe81-907">64 位元 Windows 虛擬桌面不支援 16 位元應用程式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-907">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="fbe81-908">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="fbe81-908">Microsoft Edge</span></span>


<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="fbe81-909">服務</span><span class="sxs-lookup"><span data-stu-id="fbe81-909">Service</span></span></th>
<th><span data-ttu-id="fbe81-910">FastTrack 指引詳細資料</span><span class="sxs-lookup"><span data-stu-id="fbe81-910">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="fbe81-911">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="fbe81-911">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="fbe81-912"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="fbe81-912"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="fbe81-913">我們提供下列專案的遠端部署和採用指導方針和相容性協助：</span><span class="sxs-lookup"><span data-stu-id="fbe81-913">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="fbe81-914">使用 Microsoft 端點管理員 (Microsoft Endpoint Configuration Manager 或 Intune) 在 Windows 10 上部署 Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="fbe81-914">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-915">使用群組原則或 Intune 應用程式設定和應用程式原則) 設定 Microsoft Edge (。</span><span class="sxs-lookup"><span data-stu-id="fbe81-915">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="fbe81-916">清查可能需要在 Internet Explorer 模式中使用的網站清單。</span><span class="sxs-lookup"><span data-stu-id="fbe81-916">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="fbe81-917">使用現有的 Enterprise 網站清單啟用 Internet Explorer 模式。</span><span class="sxs-lookup"><span data-stu-id="fbe81-917">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="fbe81-918"> (如需詳細資訊，請參閱 <a href="/fasttrack/process-and-expectations#engaging-fasttrack">接洽 FastTrack</a>。</span><span class="sxs-lookup"><span data-stu-id="fbe81-918">(For more information, see <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span></span> <span data-ttu-id="fbe81-919">此外，如果您有可搭配 Internet Explorer 或 Google Chrome 使用的 web 應用程式或網站，且您遇到相容性問題，我們會提供指引來解決問題，而不需額外收費。</span><span class="sxs-lookup"><span data-stu-id="fbe81-919">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="fbe81-920">若要向應用程式保證要求相容性支援，請登入 <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack 入口網站</a> ，以開始預訂。</span><span class="sxs-lookup"><span data-stu-id="fbe81-920">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="fbe81-921">Microsoft 搜尋書簽之 Edge 採用和設定指引的規劃指引。</span><span class="sxs-lookup"><span data-stu-id="fbe81-921">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="fbe81-922">

<strong>下列超出範圍 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="fbe81-922">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="fbe81-923">客戶的 Microsoft Edge 部署的專案管理。</span><span class="sxs-lookup"><span data-stu-id="fbe81-923">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="fbe81-924">現場支援。</span><span class="sxs-lookup"><span data-stu-id="fbe81-924">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
