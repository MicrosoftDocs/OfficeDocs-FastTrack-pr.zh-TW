---
title: 產品與功能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 本主題包括 FastTrack 所支援之工作負載案例的詳細資料，以及在開始之前所需的來源環境預期。 根據您目前的設定，我們會與您合作，建立修復計畫，以將來源環境帶入成功上架的最低需求。
ms.openlocfilehash: 70e279268f33591884c6bebb8625688ca724480d
ms.sourcegitcommit: b8762897f4d286636a3dd4e2ff6473ab5346b232
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/21/2021
ms.locfileid: "51927031"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="c83af-104">產品與功能</span><span class="sxs-lookup"><span data-stu-id="c83af-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="c83af-105">FastTrack 所支援的服務和案例</span><span class="sxs-lookup"><span data-stu-id="c83af-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="c83af-106">本主題包括 FastTrack 所支援之工作負載案例的詳細資料，以及在開始之前所需的來源環境預期。</span><span class="sxs-lookup"><span data-stu-id="c83af-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="c83af-107">根據您目前的設定，我們會與您合作，建立修復計畫，以將來源環境帶入成功上架的最低需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="c83af-108">FastTrack 提供指引，協助您先瞭解所有 Microsoft Online) 服務 (通用的核心功能，然後再上架每個合格的服務：</span><span class="sxs-lookup"><span data-stu-id="c83af-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="c83af-109">一般</span><span class="sxs-lookup"><span data-stu-id="c83af-109">General</span></span>](#general)
  - [<span data-ttu-id="c83af-110">安全性與合規性</span><span class="sxs-lookup"><span data-stu-id="c83af-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="c83af-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="c83af-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="c83af-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="c83af-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="c83af-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="c83af-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="c83af-114">Windows 虛擬桌面</span><span class="sxs-lookup"><span data-stu-id="c83af-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="c83af-115">應用程式保證</span><span class="sxs-lookup"><span data-stu-id="c83af-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="c83af-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="c83af-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="c83af-117">如需有關 Office 365 US Government 來源環境預期的資訊，請參閱 [Office 365 US Government 的來源環境預期](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)。</span><span class="sxs-lookup"><span data-stu-id="c83af-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="c83af-118">一般</span><span class="sxs-lookup"><span data-stu-id="c83af-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c83af-119"><strong>服務</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="c83af-120"><strong>FastTrack 指引詳細資料</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="c83af-121"><strong>來源環境預期</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c83af-122"><strong>核心上架</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="c83af-123">我們提供核心上架的遠端指導，包含服務布建、租使用者和身分識別整合。</span><span class="sxs-lookup"><span data-stu-id="c83af-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="c83af-124">它也包含為上架服務（如 Exchange Online、SharePoint 線上和 Microsoft 小組）奠定基礎的步驟，包括 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">安全性、網路連線和合規性的討論</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="c83af-125">將一或多個合格服務上架的動作可以從核心上架完成時開始。</span><span class="sxs-lookup"><span data-stu-id="c83af-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="c83af-126"></li>
</ul>  

<strong> 身分識別整合 </strong></span><span class="sxs-lookup"><span data-stu-id="c83af-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="c83af-127">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="c83af-128">準備內部部署 Active Directory 身分識別，以同步處理至 Azure Active Directory (Azure AD) 包括安裝及設定 Azure AD Connect (單一或多樹系) 和授權 (包括群組型授權) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="c83af-129">建立雲端身分識別（包括使用以群組為基礎的授權在內的大量匯入和授權）。</span><span class="sxs-lookup"><span data-stu-id="c83af-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="c83af-130">為您的雲端旅程選擇和啟用正確的驗證方法、密碼雜湊同步處理、傳遞驗證，或 Active Directory Federation Services (AD FS) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="c83af-131">使用 passwordless 驗證，為您的使用者選擇及啟用更為便利的驗證經驗 (Fast Identity Online (FIDO) 2 或 Microsoft 驗證應用程式) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="c83af-132">針對具有單一 Active Directory 樹系的客戶，與 Azure AD Connect 工具同步處理的身分識別，啟用 AD FS。</span><span class="sxs-lookup"><span data-stu-id="c83af-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="c83af-133">這需要 Windows Server 2012 R2 Active Directory Federation Services 2.0 或更新版本。</span><span class="sxs-lookup"><span data-stu-id="c83af-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="c83af-134">使用密碼雜湊同步處理或透過驗證，將驗證從 AD FS 遷移至 Azure AD。</span><span class="sxs-lookup"><span data-stu-id="c83af-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="c83af-135">遷移預先整合的應用程式 (像 Azure AD 圖庫軟體即服務 (SaaS) 應用程式) 從 AD FS 至 Azure AD for single 登錄 (SSO) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="c83af-136">從 Azure AD 圖庫啟用 SaaS 應用程式與 SSO 的整合。</span><span class="sxs-lookup"><span data-stu-id="c83af-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="c83af-137">針對 <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">應用程式整合教學課程清單</a> 中列出的預先整合的 SaaS 應用程式啟用自動使用者布建， (限制于 Azure AD 圖庫 SaaS 應用程式和輸出布建) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="c83af-138"><strong>網路啟用 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="c83af-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="c83af-139">在 FastTrack 的益處中，我們建議您做為連線至雲端服務的最佳作法，以確保 Microsoft 365 的最高效能等級。</span><span class="sxs-lookup"><span data-stu-id="c83af-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="c83af-140"><strong>Active Directory</strong> 樹系這些功能樹系層級已設定為 Windows Server 2003 +，具有下列樹系設定：</span><span class="sxs-lookup"><span data-stu-id="c83af-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-141">單一 Active Directory 樹系。</span><span class="sxs-lookup"><span data-stu-id="c83af-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="c83af-142">單一 Active Directory 帳戶樹系和資源樹系 (Exchange 和/或 Lync 2010、Lync 2013 或 商務用 Skype) 拓樸。</span><span class="sxs-lookup"><span data-stu-id="c83af-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="c83af-143">多個 Active Directory 帳戶樹系和資源樹系 (Exchange 和/或 Lync 2010、Lync 2013 或 商務用 Skype) 拓樸。</span><span class="sxs-lookup"><span data-stu-id="c83af-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="c83af-144">多重 Active Directory 帳戶樹系，其中一個樹系為包含 Exchange 和/或 Lync 2010、Lync 2013 或商務用 Skype 的集中式 Active Directory 帳戶樹系。</span><span class="sxs-lookup"><span data-stu-id="c83af-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="c83af-145">多個 Active Directory 帳戶樹系，每個都有自己的 Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="c83af-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="c83af-146">承租人設定所需的工作，以及與 Azure Active Directory 的整合（如有需要）。</span><span class="sxs-lookup"><span data-stu-id="c83af-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="c83af-147">
  <strong>重要</strong>  </span><span class="sxs-lookup"><span data-stu-id="c83af-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="c83af-148">針對多樹系 Active Directory 案例，如果已部署 Lync 2010、Lync 2013 或商務用 Skype，則必須部署在與 Exchange 相同的 Active Directory 樹系中。</span><span class="sxs-lookup"><span data-stu-id="c83af-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="c83af-149">在 Exchange 多重混合式設定中執行多個具有多個 Exchange 組織的 Active Directory 樹系時，共用使用者主體名稱 (UPN) 不支援來源樹系之間的命名空間。</span><span class="sxs-lookup"><span data-stu-id="c83af-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="c83af-150">同時也應該分隔 Exchange 組織之間的主要 SMTP 命名空間。</span><span class="sxs-lookup"><span data-stu-id="c83af-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="c83af-151">如需詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?linkid=845444">使用多個 Active Directory 樹系的混合部署</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="c83af-152">對於所有多重樹系設定，Active Directory Federation Services (AD FS) 部署超出範圍。</span><span class="sxs-lookup"><span data-stu-id="c83af-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="c83af-153">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。</span><span class="sxs-lookup"><span data-stu-id="c83af-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c83af-154"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="c83af-155">我們提供下列專案的遠端部署指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-156">解決部署問題。</span><span class="sxs-lookup"><span data-stu-id="c83af-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="c83af-157">使用 Microsoft 365 系統管理中心和 Windows PowerShell 指派以使用者和以裝置為基礎的授權。</span><span class="sxs-lookup"><span data-stu-id="c83af-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="c83af-158">使用隨選即用從 Office 365 入口網站安裝 Microsoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="c83af-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="c83af-159">在 iOS 或 Android 裝置上安裝 Office Mobile 應用程式 (如 Outlook Mobile、Word Mobile、Excel Mobile 和 PowerPoint Mobile)。</span><span class="sxs-lookup"><span data-stu-id="c83af-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="c83af-160">使用 Office 365 部署工具來設定更新設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="c83af-161">本地或雲端安裝的選取項目和設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="c83af-162">使用 Office 自訂工具或原生 XML 建立 Office 部署工具，以設定部署套件。</span><span class="sxs-lookup"><span data-stu-id="c83af-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="c83af-163">使用 Microsoft Endpoint Configuration Manager 部署，包含協助建立 Microsoft Endpoint Configuration Manager 套件。</span><span class="sxs-lookup"><span data-stu-id="c83af-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="c83af-164">此外，如果您有使用舊版 Office 的宏或增益集，且您遇到相容性問題，我們會提供指導方針以透過應用程式保證計畫來修正相容性問題，而不需要額外收費。</span><span class="sxs-lookup"><span data-stu-id="c83af-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="c83af-165">如需詳細資訊，請參閱 <strong>應用程式保證</strong> 部分的 <a href="#windows-10">Windows 10</a> 。</span><span class="sxs-lookup"><span data-stu-id="c83af-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="c83af-166">線上用戶端軟體必須具備 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="c83af-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c83af-167"><strong>網路健康情況</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="c83af-168">我們提供的遠端指導，可從您的環境取得及解讀重要的網路連線資料，以顯示組織的網站與 Microsoft 的 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">網路連線原則</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="c83af-169">這會強調您的網路得分，它會直接影響到遷移速度、使用者經驗、服務效能和可靠性。</span><span class="sxs-lookup"><span data-stu-id="c83af-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="c83af-170">我們也會引導您完成此資料所強調的任何修正步驟，以協助您提高網路得分。</span><span class="sxs-lookup"><span data-stu-id="c83af-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="c83af-171">Microsoft 365 系統管理中心存取。</span><span class="sxs-lookup"><span data-stu-id="c83af-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="c83af-172">需要最新版本的 Microsoft 365 應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="c83af-173">已啟用位置服務，因為 <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 系統管理中心的 [每個網路效能建議] (預覽) </a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-173">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="c83af-174">安全性及合規性</span><span class="sxs-lookup"><span data-stu-id="c83af-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c83af-175"><strong>服務</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="c83af-176"><strong>FastTrack 指引詳細資料</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="c83af-177"><strong>來源環境預期</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="c83af-178"><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="c83af-179">在下列情況下，我們會提供遠端指導來保護您的雲端身分識別。</span><span class="sxs-lookup"><span data-stu-id="c83af-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="c83af-180">

<strong>安全基礎結構</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="c83af-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="c83af-181">針對您的身分識別設定和啟用強驗證，包括使用 Azure Multi-Factor 驗證 (MFA)  (雲端僅) 、Microsoft 驗證者應用程式，以及 Azure MFA 和自助密碼重設的組合註冊 (SSPR) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="c83af-182">部署 FIDO2 或 Microsoft 驗證器應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="c83af-183">若為非 Azure AD Premium 客戶，會提供指導方針，以利用安全性預設值來保護您的身分識別。</span><span class="sxs-lookup"><span data-stu-id="c83af-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="c83af-184">針對 Azure AD premium 客戶，提供指導方針以條件式存取來保護您的身分識別。</span><span class="sxs-lookup"><span data-stu-id="c83af-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="c83af-185">使用 Azure AD 密碼保護偵測和封鎖弱密碼的使用。</span><span class="sxs-lookup"><span data-stu-id="c83af-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="c83af-186">使用 Azure AD 應用程式 Proxy，保護內部部署 web 應用程式的遠端存取。</span><span class="sxs-lookup"><span data-stu-id="c83af-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="c83af-187">使用 Azure 身分識別保護來啟用風險型偵測和修正。</span><span class="sxs-lookup"><span data-stu-id="c83af-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="c83af-188">啟用自訂的登入畫面，包括徽標、文字和具有自訂商標的影像。</span><span class="sxs-lookup"><span data-stu-id="c83af-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="c83af-189">使用 Azure AD B2B 與來賓使用者安全地共用應用程式和服務。</span><span class="sxs-lookup"><span data-stu-id="c83af-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="c83af-190">使用以角色為基礎的存取控制來管理 Office 365 系統管理員的 access (RBAC) 內建管理角色，以及減少特權系統管理員帳戶數目。</span><span class="sxs-lookup"><span data-stu-id="c83af-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="c83af-191">設定混合式 Azure AD 聯結。</span><span class="sxs-lookup"><span data-stu-id="c83af-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="c83af-192">設定 Azure AD 聯結。</span><span class="sxs-lookup"><span data-stu-id="c83af-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="c83af-193">
  
<strong>監視與報告</strong>  
</span><span class="sxs-lookup"><span data-stu-id="c83af-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="c83af-194">使用 Azure AD Connect Health，啟用適用于 AD FS、Azure AD Connect 和網域控制站的遠端監控。</span><span class="sxs-lookup"><span data-stu-id="c83af-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="c83af-195">
  
<strong>治理</strong>  
</span><span class="sxs-lookup"><span data-stu-id="c83af-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="c83af-196">使用 Azure AD 版權管理來管理 Azure AD 身分識別和存取生命週期。</span><span class="sxs-lookup"><span data-stu-id="c83af-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="c83af-197">使用 Azure AD access 評論管理 Azure AD 群組成員資格、企業應用程式存取和角色指派。</span><span class="sxs-lookup"><span data-stu-id="c83af-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-198">檢查 Azure AD 使用條款。</span><span class="sxs-lookup"><span data-stu-id="c83af-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-199">使用 Azure AD 特權身分識別管理來管理和控制版權管理帳戶的存取。</span><span class="sxs-lookup"><span data-stu-id="c83af-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="c83af-200">
  
<strong>自動化和效率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="c83af-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="c83af-201">啟用 Azure AD SSPR。</span><span class="sxs-lookup"><span data-stu-id="c83af-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="c83af-202">讓使用者能夠使用 Azure AD 自助群組管理來建立及管理自己的雲端安全性或 Office 365 群組。</span><span class="sxs-lookup"><span data-stu-id="c83af-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="c83af-203">使用 Azure AD 委派的群組管理來管理企業應用程式的委派存取權。</span><span class="sxs-lookup"><span data-stu-id="c83af-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="c83af-204">啟用 Azure AD 動態群組。</span><span class="sxs-lookup"><span data-stu-id="c83af-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="c83af-205">使用集合在「我的應用程式入口網站」中組織應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c83af-206">已針對 Azure AD Premium 準備內部部署 Active Directory 及其環境，包括修正已識別的問題，以防止與 Azure AD 和 Azure AD Premium 功能整合。</span><span class="sxs-lookup"><span data-stu-id="c83af-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c83af-207"><strong>Azure 資訊保護 </strong></span><span class="sxs-lookup"><span data-stu-id="c83af-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="c83af-208">如需 Azure 資訊保護的詳細資訊，請參閱下表中的 [ <strong>Microsoft 資訊保護</strong> ]。</span><span class="sxs-lookup"><span data-stu-id="c83af-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="c83af-209"><strong>探索 & 回應</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="c83af-210"><strong>進階 eDiscovery</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="c83af-211">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="c83af-212">建立新的案例。</span><span class="sxs-lookup"><span data-stu-id="c83af-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="c83af-213">將保管人置於保留狀態。</span><span class="sxs-lookup"><span data-stu-id="c83af-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="c83af-214">執行搜尋。</span><span class="sxs-lookup"><span data-stu-id="c83af-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="c83af-215">將搜尋結果新增至審閱集。</span><span class="sxs-lookup"><span data-stu-id="c83af-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="c83af-216">對複查集執行分析。</span><span class="sxs-lookup"><span data-stu-id="c83af-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="c83af-217">審閱及標記檔。</span><span class="sxs-lookup"><span data-stu-id="c83af-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="c83af-218">從審閱集中匯出資料。</span><span class="sxs-lookup"><span data-stu-id="c83af-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="c83af-219">匯入非 Office 365 資料。</span><span class="sxs-lookup"><span data-stu-id="c83af-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="c83af-220">只有 E5 支援的<strong>高級審計</strong> () </span><span class="sxs-lookup"><span data-stu-id="c83af-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="c83af-221">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="c83af-222">啟用高級審核。</span><span class="sxs-lookup"><span data-stu-id="c83af-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="c83af-223">執行搜尋審核記錄 UI 和基本審核 PowerShell 命令。</span><span class="sxs-lookup"><span data-stu-id="c83af-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="c83af-224">

<strong> 合規性管理員</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="c83af-225">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="c83af-226">審閱角色類型。</span><span class="sxs-lookup"><span data-stu-id="c83af-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="c83af-227">新增及設定評估。</span><span class="sxs-lookup"><span data-stu-id="c83af-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="c83af-228">實施改進動作和決定這會如何影響您的合規性分數，以評估法規遵從性。</span><span class="sxs-lookup"><span data-stu-id="c83af-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="c83af-229">審閱內建控制項對應及評估控制項。</span><span class="sxs-lookup"><span data-stu-id="c83af-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="c83af-230">在評估中產生報表。</span><span class="sxs-lookup"><span data-stu-id="c83af-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="c83af-231">

<strong>下列超出範圍 </strong> 
</span><span class="sxs-lookup"><span data-stu-id="c83af-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="c83af-232">自訂腳本或編碼。</span><span class="sxs-lookup"><span data-stu-id="c83af-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="c83af-233">電子檔探索 API。</span><span class="sxs-lookup"><span data-stu-id="c83af-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="c83af-234">資料連線器。</span><span class="sxs-lookup"><span data-stu-id="c83af-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="c83af-235">規範界限和安全性篩選器。</span><span class="sxs-lookup"><span data-stu-id="c83af-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="c83af-236">資料調查。</span><span class="sxs-lookup"><span data-stu-id="c83af-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="c83af-237">資料主體要求。</span><span class="sxs-lookup"><span data-stu-id="c83af-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="c83af-238">設計、設計架構和協力廠商檔審閱。</span><span class="sxs-lookup"><span data-stu-id="c83af-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="c83af-239">遵守行業和地區性法規和需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="c83af-240">在合規性管理員中針對評估建議的改進動作的實際執行。</span><span class="sxs-lookup"><span data-stu-id="c83af-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="c83af-241">除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="c83af-242"><strong>有問必答風險管理</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="c83af-243">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="c83af-244">建立原則及檢查設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="c83af-245">存取報告和警示。</span><span class="sxs-lookup"><span data-stu-id="c83af-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="c83af-246">建立案例。</span><span class="sxs-lookup"><span data-stu-id="c83af-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="c83af-247">建立通知範本。</span><span class="sxs-lookup"><span data-stu-id="c83af-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="c83af-248"> (HR) 連接器建立人力資源的指導方針。</span><span class="sxs-lookup"><span data-stu-id="c83af-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="c83af-249">

<strong> 通訊相容性 </strong></span><span class="sxs-lookup"><span data-stu-id="c83af-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="c83af-250">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="c83af-251">建立原則及檢查設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="c83af-252">存取報告和警示。</span><span class="sxs-lookup"><span data-stu-id="c83af-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="c83af-253">建立通知範本。</span><span class="sxs-lookup"><span data-stu-id="c83af-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="c83af-254">

<strong> 合規性管理員</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="c83af-255">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="c83af-256">審閱角色類型。</span><span class="sxs-lookup"><span data-stu-id="c83af-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="c83af-257">新增及設定評估。</span><span class="sxs-lookup"><span data-stu-id="c83af-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="c83af-258">實施改進動作和決定這會如何影響您的合規性分數，以評估法規遵從性。</span><span class="sxs-lookup"><span data-stu-id="c83af-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="c83af-259">審閱內建控制項對應及評估控制項。</span><span class="sxs-lookup"><span data-stu-id="c83af-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="c83af-260">在評估中產生報表。</span><span class="sxs-lookup"><span data-stu-id="c83af-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="c83af-261">

<strong>下列超出範圍 </strong> 
</span><span class="sxs-lookup"><span data-stu-id="c83af-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="c83af-262">建立及管理電源自動化流程。</span><span class="sxs-lookup"><span data-stu-id="c83af-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="c83af-263">在 HR 連接器) 以外 (的資料連線器。</span><span class="sxs-lookup"><span data-stu-id="c83af-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="c83af-264">自訂正則運算式 (RegEx) 設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="c83af-265">設計、設計架構和協力廠商檔審閱。</span><span class="sxs-lookup"><span data-stu-id="c83af-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="c83af-266">資訊障礙。</span><span class="sxs-lookup"><span data-stu-id="c83af-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="c83af-267">特殊許可權存取管理。</span><span class="sxs-lookup"><span data-stu-id="c83af-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="c83af-268">遵守行業和地區性法規和需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="c83af-269">在合規性管理員中針對評估建議的改進動作的實際執行。</span><span class="sxs-lookup"><span data-stu-id="c83af-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="c83af-270">除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="c83af-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="c83af-272">Microsoft 365 Defender 是一種整合的後續企業防護套件，其可在端點、身分識別、電子郵件和應用程式上協調偵測、預防、調查和回應，以提供複雜攻擊的整合式防護。</span><span class="sxs-lookup"><span data-stu-id="c83af-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="c83af-273">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="c83af-274">提供 Microsoft 365 的安全性中心簡介。</span><span class="sxs-lookup"><span data-stu-id="c83af-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="c83af-275">檢查跨產品的事件，包括確定完整的攻擊範圍、受影響的資產，以及組合在一起的自動修正動作，以著重于重要專案。</span><span class="sxs-lookup"><span data-stu-id="c83af-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="c83af-276">示範 Microsoft 365 Defender 如何對資產、使用者、裝置和信箱進行調查，以透過自動自我修復的方式來調查可能已遭破壞的資產、使用者、裝置和信箱。</span><span class="sxs-lookup"><span data-stu-id="c83af-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="c83af-277">說明及提供客戶如何主動搜尋入侵企圖及破壞您的電子郵件、資料、裝置及帳戶的多個資料組的範例。</span><span class="sxs-lookup"><span data-stu-id="c83af-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="c83af-278">向客戶展示如何使用 Microsoft 安全評分來複查和提升其安全性狀況 holistically。</span><span class="sxs-lookup"><span data-stu-id="c83af-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="c83af-279"><strong>下列超出範圍</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="c83af-280">客戶修正活動的專案管理。</span><span class="sxs-lookup"><span data-stu-id="c83af-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="c83af-281">持續管理、威脅回應及修復。</span><span class="sxs-lookup"><span data-stu-id="c83af-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="c83af-282">部署指導或教育：</span><span class="sxs-lookup"><span data-stu-id="c83af-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="c83af-283">如何修正或轉譯各種警示類型和受監控的活動。</span><span class="sxs-lookup"><span data-stu-id="c83af-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="c83af-284">如何調查使用者、電腦、側向移動路徑或實體。</span><span class="sxs-lookup"><span data-stu-id="c83af-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="c83af-285">自訂威脅搜尋。</span><span class="sxs-lookup"><span data-stu-id="c83af-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="c83af-286"> (SIEM) 或 API 整合的安全性資訊和事件管理。</span><span class="sxs-lookup"><span data-stu-id="c83af-286">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c83af-287"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-287"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="c83af-288">Microsoft Cloud App Security 是雲端 Access 安全性經紀人 (CASB) ，可提供豐富的知名度、控制資料旅行，以及完善的分析，以識別和抵禦所有 Microsoft 和協力廠商雲端服務的網路威脅。</span><span class="sxs-lookup"><span data-stu-id="c83af-288">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="c83af-289">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-289">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-290">設定入口網站，包括：</span><span class="sxs-lookup"><span data-stu-id="c83af-290">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="c83af-291">匯入使用者群組。</span><span class="sxs-lookup"><span data-stu-id="c83af-291">Importing user groups.</span></span></li>
<li> <span data-ttu-id="c83af-292">管理系統管理存取和設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-292">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="c83af-293">確定部署的範圍，以選取要監視或排除監控的特定使用者群組。</span><span class="sxs-lookup"><span data-stu-id="c83af-293">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="c83af-294">設定 IP 範圍及標記。</span><span class="sxs-lookup"><span data-stu-id="c83af-294">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="c83af-295">使用您的標誌和自訂訊息，將使用者體驗個人化。</span><span class="sxs-lookup"><span data-stu-id="c83af-295">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="c83af-296">設定 cloud discovery 以提供陰影，使用：</span><span class="sxs-lookup"><span data-stu-id="c83af-296">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="c83af-297">Microsoft Defender for 端點。</span><span class="sxs-lookup"><span data-stu-id="c83af-297">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="c83af-298">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="c83af-298">Zscaler.</span></span></li>
<li> <span data-ttu-id="c83af-299">iboss.</span><span class="sxs-lookup"><span data-stu-id="c83af-299">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="c83af-300">使用應用程式連接器連接 <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">特色應用程式</a> 。</span><span class="sxs-lookup"><span data-stu-id="c83af-300">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="c83af-301">在條件式 Access 和 Cloud App Security 入口網站中設定條件式存取應用程式控制，以套用即時會話控制。</span><span class="sxs-lookup"><span data-stu-id="c83af-301">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="c83af-302">部署 Cloud App Security 和 Cloud Discovery 儀表板。</span><span class="sxs-lookup"><span data-stu-id="c83af-302">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="c83af-303">根據組織的優先順序自訂應用程式風險分數。</span><span class="sxs-lookup"><span data-stu-id="c83af-303">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="c83af-304">建立應用程式標記與類別。</span><span class="sxs-lookup"><span data-stu-id="c83af-304">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="c83af-305">Sanctioning 與 unsanctioning 應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-305">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="c83af-306">使用活動和檔記錄。</span><span class="sxs-lookup"><span data-stu-id="c83af-306">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="c83af-307">管理 OAuth 應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-307">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="c83af-308">瞭解 Microsoft 365 Defender 入口網站中的事件關聯。</span><span class="sxs-lookup"><span data-stu-id="c83af-308">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="c83af-309">在 CASBs (的 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">前20個使用案例</a> 中提供設定協助，包括建立或更新最多六個 (6) 原則) ，但不包括：</span><span class="sxs-lookup"><span data-stu-id="c83af-309">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="c83af-310">審核網際網路的設定為服務 (IaaS) 環境 (#18) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-310">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="c83af-311">監控使用者活動，以防範 IaaS 環境中的威脅 (#19) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-311">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="c83af-312"><strong>下列超出範圍</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-312"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="c83af-313">客戶修正活動的專案管理。</span><span class="sxs-lookup"><span data-stu-id="c83af-313">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="c83af-314">持續管理、威脅回應及修復。</span><span class="sxs-lookup"><span data-stu-id="c83af-314">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="c83af-315">使用 Docker 或記錄收集器，為連續報告設定基礎結構、安裝或部署自動記錄上載。</span><span class="sxs-lookup"><span data-stu-id="c83af-315">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="c83af-316">如需詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">CASBs 的前20個使用案例</a> 。</span><span class="sxs-lookup"><span data-stu-id="c83af-316">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="c83af-317">建立雲端探索快照報告。</span><span class="sxs-lookup"><span data-stu-id="c83af-317">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="c83af-318">使用封鎖腳本封鎖應用程式使用方式。</span><span class="sxs-lookup"><span data-stu-id="c83af-318">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="c83af-319">連接自訂應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-319">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="c83af-320">與協力廠商身分識別提供者整合 (的 Isp) 和資料遺失防護 (DLP) 提供者。</span><span class="sxs-lookup"><span data-stu-id="c83af-320">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="c83af-321">涵蓋進階搜尋功能的訓練或指導方針。</span><span class="sxs-lookup"><span data-stu-id="c83af-321">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="c83af-322">自動化調查和修正包括 Microsoft Power 自動化行動手冊。</span><span class="sxs-lookup"><span data-stu-id="c83af-322">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="c83af-323">安全性資訊和事件管理 (SIEM) 或 API 整合 (包含 Azure Sentinel) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-323">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="c83af-324">部署雲端應用程式探索以作為概念證明。</span><span class="sxs-lookup"><span data-stu-id="c83af-324">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="c83af-325"><strong>適用於端點的 Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-325"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="c83af-326">Microsoft Defender for Endpoint 是專門設計用來協助商業網路避免、偵測、調查和回應高級威脅的平臺。</span><span class="sxs-lookup"><span data-stu-id="c83af-326">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="c83af-327">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-328">部署技術以保護您的端點。</span><span class="sxs-lookup"><span data-stu-id="c83af-328">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="c83af-329">設定 endpoint protection 和裝置限制設定檔。</span><span class="sxs-lookup"><span data-stu-id="c83af-329">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="c83af-330">評估 OS 版本和裝置管理 (包括 Intune、Microsoft Endpoint Configuration Manager、群組原則物件 (Gpo) 和協力廠商設定) 以及 Windows Defender AV 服務或其他端點安全性軟體的狀態。</span><span class="sxs-lookup"><span data-stu-id="c83af-330">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="c83af-331">評估 Windows AV 服務或其他端點安全性軟體的狀態。</span><span class="sxs-lookup"><span data-stu-id="c83af-331">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="c83af-332">評估代理及防火牆，以限制網路流量。</span><span class="sxs-lookup"><span data-stu-id="c83af-332">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="c83af-333">說明如何使用板載端點為端點代理程式設定檔部署 Defender，以啟用 Microsoft Defender for Endpoint service。</span><span class="sxs-lookup"><span data-stu-id="c83af-333">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="c83af-334">部署指導方針、設定協助及教育：</span><span class="sxs-lookup"><span data-stu-id="c83af-334">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="c83af-335">威脅與弱點管理。</span><span class="sxs-lookup"><span data-stu-id="c83af-335">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-336">縮小攻擊面。</span><span class="sxs-lookup"><span data-stu-id="c83af-336">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-337">新一代防護。</span><span class="sxs-lookup"><span data-stu-id="c83af-337">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-338">端點偵測及回應。</span><span class="sxs-lookup"><span data-stu-id="c83af-338">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-339">自動化調查與補救措施。</span><span class="sxs-lookup"><span data-stu-id="c83af-339">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-340">安全分數。</span><span class="sxs-lookup"><span data-stu-id="c83af-340">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="c83af-341">查看模擬與示教 (例如練習案例、虛假惡意程式碼和自動調查) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-341">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="c83af-342">報表和威脅分析功能的概覽。</span><span class="sxs-lookup"><span data-stu-id="c83af-342">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="c83af-343">整合 Microsoft Defender for Office 365 與 Microsoft Defender for Endpoint。</span><span class="sxs-lookup"><span data-stu-id="c83af-343">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="c83af-344">提供 Microsoft Defender 資訊安全中心入口網站的逐步指引。</span><span class="sxs-lookup"><span data-stu-id="c83af-344">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="c83af-345">下列作業系統：</span><span class="sxs-lookup"><span data-stu-id="c83af-345">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="c83af-346">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="c83af-346">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-347">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="c83af-347">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-348">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="c83af-348">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-349">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="c83af-349">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-350">Windows Server Semi-Annual 通道 (SAC) 版本1803。</span><span class="sxs-lookup"><span data-stu-id="c83af-350">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-351">macOS 版本10.13、10.14 及10.15。</span><span class="sxs-lookup"><span data-stu-id="c83af-351">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="c83af-352">
<strong>附注：</strong> 所有 Windows Server 版本都必須由最新版的 System Center Configuration Manager 2012 (版本 1012 R2、1511或 1602) 或 Microsoft Endpoint Configuration Manager (版本2002或更高版本) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-352">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="c83af-353"></li>
</ul>

<strong>下列超出範圍 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="c83af-353"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="c83af-354">客戶修正活動的專案管理。</span><span class="sxs-lookup"><span data-stu-id="c83af-354">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="c83af-355">現場支援。</span><span class="sxs-lookup"><span data-stu-id="c83af-355">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="c83af-356">持續性管理和威脅因應。</span><span class="sxs-lookup"><span data-stu-id="c83af-356">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="c83af-357">上架或設定下列 Microsoft Defender for Endpoint agent：</span><span class="sxs-lookup"><span data-stu-id="c83af-357">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="c83af-358">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="c83af-358">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-359">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="c83af-359">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-360">Linux。</span><span class="sxs-lookup"><span data-stu-id="c83af-360">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-361">移動裝置 (Android 和 iOS) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-361">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="c83af-362">虛擬桌面基礎結構 (VDI)  (持續或非持續性) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-362">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="c83af-363">伺服器上架及設定：</span><span class="sxs-lookup"><span data-stu-id="c83af-363">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="c83af-364">設定離線通訊的 proxy 伺服器。</span><span class="sxs-lookup"><span data-stu-id="c83af-364">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-365">設定下層 Configuration Manager 實例和版本的 Configuration Manager 部署套件。</span><span class="sxs-lookup"><span data-stu-id="c83af-365">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-366">將伺服器上架至 Azure 的安全性中心。</span><span class="sxs-lookup"><span data-stu-id="c83af-366">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-367">未由 Configuration Manager 管理的伺服器。</span><span class="sxs-lookup"><span data-stu-id="c83af-367">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="c83af-368">macOS 上架及設定：</span><span class="sxs-lookup"><span data-stu-id="c83af-368">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="c83af-369">手動以 Intune 為基礎的部署。</span><span class="sxs-lookup"><span data-stu-id="c83af-369">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-370">以 JAMF 為基礎的部署。</span><span class="sxs-lookup"><span data-stu-id="c83af-370">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="c83af-371">其他行動裝置管理 (MDM) 以產品為基礎的部署。</span><span class="sxs-lookup"><span data-stu-id="c83af-371">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-372">手動部署。</span><span class="sxs-lookup"><span data-stu-id="c83af-372">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="c83af-373">設定以下能縮小攻擊面的功能：</span><span class="sxs-lookup"><span data-stu-id="c83af-373">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="c83af-374">硬體隔離。</span><span class="sxs-lookup"><span data-stu-id="c83af-374">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-375">應用程式控制。</span><span class="sxs-lookup"><span data-stu-id="c83af-375">App control.</span></span>  
  </li>
<li> <span data-ttu-id="c83af-376">裝置控制。</span><span class="sxs-lookup"><span data-stu-id="c83af-376">Device control.</span></span></li>
<li>  
  <span data-ttu-id="c83af-377">入侵防護。</span><span class="sxs-lookup"><span data-stu-id="c83af-377">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-378">網路防火牆。</span><span class="sxs-lookup"><span data-stu-id="c83af-378">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="c83af-379">帳戶保護功能的設定或管理，例如：</span><span class="sxs-lookup"><span data-stu-id="c83af-379">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="c83af-380">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="c83af-380">Windows Hello</span></span></li>
<li> <span data-ttu-id="c83af-381">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="c83af-381">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="c83af-382">BitLocker 的設定或管理。</span><span class="sxs-lookup"><span data-stu-id="c83af-382">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="c83af-383">註冊或設定 Microsoft 威脅專家。</span><span class="sxs-lookup"><span data-stu-id="c83af-383">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="c83af-384">設定或訓練檢查 API 或安全性資訊和事件管理 (SIEM) 連接。</span><span class="sxs-lookup"><span data-stu-id="c83af-384">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="c83af-385">註冊或設定 Microsoft 威脅防護 (MTP)。</span><span class="sxs-lookup"><span data-stu-id="c83af-385">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="c83af-386">涵蓋進階搜尋功能的訓練或指導方針。</span><span class="sxs-lookup"><span data-stu-id="c83af-386">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="c83af-387">訓練或指引涵蓋使用或建立 Kusto 查詢。</span><span class="sxs-lookup"><span data-stu-id="c83af-387">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="c83af-388">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。</span><span class="sxs-lookup"><span data-stu-id="c83af-388">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="c83af-389"><strong>Microsoft Defender 身分識別 </strong></span><span class="sxs-lookup"><span data-stu-id="c83af-389"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="c83af-390">適用於身分識別的 Microsoft Defender 是利用內部部署 Active Directory 訊號的雲端型安全性解決方案，它會識別、偵測及調查貴組織中的進階威脅、遭入侵的身分識別，以及惡意內部攻擊動作。</span><span class="sxs-lookup"><span data-stu-id="c83af-390">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="c83af-391">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-391">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="c83af-392">建立身分識別的 Defender 實例。</span><span class="sxs-lookup"><span data-stu-id="c83af-392">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="c83af-393">將 Defender 身分識別連接至 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="c83af-393">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="c83af-394">評估您的環境是否準備好在您的網域控制站上部署用於身分識別感應器的 Defender，包括：</span><span class="sxs-lookup"><span data-stu-id="c83af-394">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="c83af-395">執行資源容量規劃的調整大小工具。</span><span class="sxs-lookup"><span data-stu-id="c83af-395">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="c83af-396">執行審核工具，以評估您的網域控制站與感應器的相容性。</span><span class="sxs-lookup"><span data-stu-id="c83af-396">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="c83af-397">部署感應器以直接從您的網域控制站捕捉及分析網路流量和 Windows 事件，包括：</span><span class="sxs-lookup"><span data-stu-id="c83af-397">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="c83af-398">下載感應器套件。</span><span class="sxs-lookup"><span data-stu-id="c83af-398">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="c83af-399">設定感應器。</span><span class="sxs-lookup"><span data-stu-id="c83af-399">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="c83af-400">在您的網域控制站上無訊息地安裝感應器。</span><span class="sxs-lookup"><span data-stu-id="c83af-400">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="c83af-401">將感應器部署至多樹系環境。</span><span class="sxs-lookup"><span data-stu-id="c83af-401">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="c83af-402">使用 Microsoft Cloud App Security 整合 Defender 以進行身分識別不需要 (Cloud App 安全性授權) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-402">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="c83af-403">提供部署指導、設定協助及教育：</span><span class="sxs-lookup"><span data-stu-id="c83af-403">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="c83af-404">調整環境以減少「干擾」。</span><span class="sxs-lookup"><span data-stu-id="c83af-404">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="c83af-405">瞭解識別安全狀況評估報告。</span><span class="sxs-lookup"><span data-stu-id="c83af-405">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="c83af-406">瞭解使用者調查優先順序分數和使用者調查排名報告。</span><span class="sxs-lookup"><span data-stu-id="c83af-406">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="c83af-407">瞭解非使用中的使用者報告。</span><span class="sxs-lookup"><span data-stu-id="c83af-407">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="c83af-408">在已遭破壞的帳戶上提供修正選項。</span><span class="sxs-lookup"><span data-stu-id="c83af-408">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="c83af-409">可促進從高級威脅分析 (ATA) 至 Defender 身分識別的遷移。</span><span class="sxs-lookup"><span data-stu-id="c83af-409">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="c83af-410"><strong>下列超出範圍</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-410"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="c83af-411">客戶修正活動的專案管理。</span><span class="sxs-lookup"><span data-stu-id="c83af-411">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="c83af-412">持續管理、威脅回應及修復。</span><span class="sxs-lookup"><span data-stu-id="c83af-412">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="c83af-413">為身分識別感應器部署 Defender，包括：</span><span class="sxs-lookup"><span data-stu-id="c83af-413">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="c83af-414">手動容量規劃。</span><span class="sxs-lookup"><span data-stu-id="c83af-414">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="c83af-415">以獨立的容量部署感應器。</span><span class="sxs-lookup"><span data-stu-id="c83af-415">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="c83af-416">使用網路介面卡 (NIC) 編組的配接器部署感應器。</span><span class="sxs-lookup"><span data-stu-id="c83af-416">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="c83af-417">透過協力廠商工具部署感應器。</span><span class="sxs-lookup"><span data-stu-id="c83af-417">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="c83af-418">透過 web proxy 連線來連線至身分識別雲端服務的 Defender。</span><span class="sxs-lookup"><span data-stu-id="c83af-418">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="c83af-419">Honeytokens 的建立與管理。</span><span class="sxs-lookup"><span data-stu-id="c83af-419">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="c83af-420">部署指導或教育：</span><span class="sxs-lookup"><span data-stu-id="c83af-420">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="c83af-421">修正或口譯各種警示類型和受監控的活動。</span><span class="sxs-lookup"><span data-stu-id="c83af-421">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="c83af-422">調查使用者、電腦、側向移動路徑或實體。</span><span class="sxs-lookup"><span data-stu-id="c83af-422">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="c83af-423">威脅或高級搜尋。</span><span class="sxs-lookup"><span data-stu-id="c83af-423">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="c83af-424">事件回應。</span><span class="sxs-lookup"><span data-stu-id="c83af-424">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="c83af-425">為身分識別提供適用于 Defender 的安全性警示實驗室教學課程。</span><span class="sxs-lookup"><span data-stu-id="c83af-425">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="c83af-426">當 Defender 身分識別透過身分識別的感應器傳送安全警示以偵測可疑活動時，提供通知。</span><span class="sxs-lookup"><span data-stu-id="c83af-426">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="c83af-427">使用安全帳戶管理員 remote (SAMR) 通訊協定，設定用來執行查詢的 Defender，以識別特定電腦上的本機系統管理員。</span><span class="sxs-lookup"><span data-stu-id="c83af-427">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="c83af-428">設定 VPN 解決方案，將 VPN 連線的資訊新增至使用者的設定檔頁面面。</span><span class="sxs-lookup"><span data-stu-id="c83af-428">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="c83af-429">安全性資訊和事件管理 (SIEM) 或 API 整合 (包含 Azure Sentinel) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-429">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="c83af-430">部署用於身分識別感應器的 Defender 以作為概念證明。</span><span class="sxs-lookup"><span data-stu-id="c83af-430">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="c83af-431">已部署 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="c83af-431">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="c83af-432">您想要為身分識別感應器安裝 Defender 的網域控制站，具有對身分識別雲端服務的 internet 連線能力。</span><span class="sxs-lookup"><span data-stu-id="c83af-432">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="c83af-433">您的防火牆和 proxy 必須開啟才能與 ( 的身分識別，以進行身分識別 cloud service 的 Defender。 atp.azure.com 埠443必須) 開啟。</span><span class="sxs-lookup"><span data-stu-id="c83af-433">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="c83af-434">執行于下列其中一項的網域控制站：</span><span class="sxs-lookup"><span data-stu-id="c83af-434">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="c83af-435">Windows Server 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="c83af-435">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="c83af-436">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="c83af-436">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="c83af-437">Windows Server 2012 R2。</span><span class="sxs-lookup"><span data-stu-id="c83af-437">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="c83af-438">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="c83af-438">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="c83af-439">Windows Server 2019 with KB4487044 (OS 組建 17763.316) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-439">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="c83af-440"><strong>適用於 Office 365 的 Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-440"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="c83af-441">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-441">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-442">啟用安全連結、安全附件和防網路釣魚。</span><span class="sxs-lookup"><span data-stu-id="c83af-442">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="c83af-443">設定自動化、調查和回應。</span><span class="sxs-lookup"><span data-stu-id="c83af-443">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="c83af-444">使用攻擊模擬器。</span><span class="sxs-lookup"><span data-stu-id="c83af-444">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="c83af-445">報告和威脅分析。</span><span class="sxs-lookup"><span data-stu-id="c83af-445">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c83af-446">除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-446">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="c83af-447"><strong>Microsoft 資訊控管</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-447"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="c83af-448">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-448">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-449">僅限 E5) 支援建立及發佈保留標籤和原則 (。</span><span class="sxs-lookup"><span data-stu-id="c83af-449">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="c83af-450">僅限 E5) 支援記錄管理 (。</span><span class="sxs-lookup"><span data-stu-id="c83af-450">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="c83af-451">查看檔計畫建立。</span><span class="sxs-lookup"><span data-stu-id="c83af-451">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="c83af-452">建立及記錄管理 (包括事件記錄) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-452">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="c83af-453">審閱處置。</span><span class="sxs-lookup"><span data-stu-id="c83af-453">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="c83af-454">

<strong> 合規性管理員</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-454">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="c83af-455">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-455">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="c83af-456">審閱角色類型。</span><span class="sxs-lookup"><span data-stu-id="c83af-456">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="c83af-457">新增及設定評估。</span><span class="sxs-lookup"><span data-stu-id="c83af-457">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="c83af-458">實施改進動作和決定這會如何影響您的合規性分數，以評估法規遵從性。</span><span class="sxs-lookup"><span data-stu-id="c83af-458">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="c83af-459">審閱內建控制項對應及評估控制項。</span><span class="sxs-lookup"><span data-stu-id="c83af-459">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="c83af-460">在評估中產生報表。</span><span class="sxs-lookup"><span data-stu-id="c83af-460">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="c83af-461">

  <strong>下列超出範圍 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="c83af-461">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="c83af-462">記錄管理檔計畫的開發。</span><span class="sxs-lookup"><span data-stu-id="c83af-462">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="c83af-463">資料連線器。</span><span class="sxs-lookup"><span data-stu-id="c83af-463">Data connectors.</span></span></li>
<li> <span data-ttu-id="c83af-464">在 SharePoint 中開發資訊架構。</span><span class="sxs-lookup"><span data-stu-id="c83af-464">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="c83af-465">自訂腳本和編碼。</span><span class="sxs-lookup"><span data-stu-id="c83af-465">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="c83af-466">設計、設計架構和協力廠商檔審閱。</span><span class="sxs-lookup"><span data-stu-id="c83af-466">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="c83af-467">E3 的支援。</span><span class="sxs-lookup"><span data-stu-id="c83af-467">Support for E3.</span></span></li>
<li> <span data-ttu-id="c83af-468">遵守行業和地區性法規和需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-468">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="c83af-469">在合規性管理員中針對評估建議的改進動作的實際執行。</span><span class="sxs-lookup"><span data-stu-id="c83af-469">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="c83af-470">除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-470">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c83af-471"><strong>Microsoft 資訊保護</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-471"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="c83af-472">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-472">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-473">在 E3 和 E5) 中支援資料分類 (。</span><span class="sxs-lookup"><span data-stu-id="c83af-473">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="c83af-474">在 E3 和 E5) 中支援的敏感資訊類型 (。</span><span class="sxs-lookup"><span data-stu-id="c83af-474">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="c83af-475">在 E3 和 E5) 中建立 (支援的靈敏度標籤。</span><span class="sxs-lookup"><span data-stu-id="c83af-475">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="c83af-476">在 E3 和 E5) 中套用敏感度標籤 (支援。</span><span class="sxs-lookup"><span data-stu-id="c83af-476">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="c83af-477">Trainable 中的分類器 (支援的 E5) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-477">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="c83af-478">使用 E5) 支援的內容瀏覽器和活動瀏覽器 (，知道您的資料。</span><span class="sxs-lookup"><span data-stu-id="c83af-478">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="c83af-479">使用原則發佈標籤 (手動和自動) E5) 中 (支援。</span><span class="sxs-lookup"><span data-stu-id="c83af-479">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="c83af-480">在 E5) 中建立 (支援 Windows 10 裝置的 (DLP) 原則的端點資料遺失防護。</span><span class="sxs-lookup"><span data-stu-id="c83af-480">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="c83af-481">建立適用于 Microsoft 小組聊天和頻道的 DLP 原則。</span><span class="sxs-lookup"><span data-stu-id="c83af-481">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="c83af-482">

<strong> 合規性管理員</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-482">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="c83af-483">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-483">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="c83af-484">審閱角色類型。</span><span class="sxs-lookup"><span data-stu-id="c83af-484">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="c83af-485">新增及設定評估。</span><span class="sxs-lookup"><span data-stu-id="c83af-485">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="c83af-486">實施改進動作和決定這會如何影響您的合規性分數，以評估法規遵從性。</span><span class="sxs-lookup"><span data-stu-id="c83af-486">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="c83af-487">審閱內建控制項對應及評估控制項。</span><span class="sxs-lookup"><span data-stu-id="c83af-487">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="c83af-488">在評估中產生報表。</span><span class="sxs-lookup"><span data-stu-id="c83af-488">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="c83af-489">

<strong> Azure 資訊保護</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-489">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="c83af-490">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-490">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="c83af-491">啟用並設定您的租使用者。</span><span class="sxs-lookup"><span data-stu-id="c83af-491">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="c83af-492">在 P1 和 P2) 中建立及設定 (支援的標籤和原則。</span><span class="sxs-lookup"><span data-stu-id="c83af-492">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="c83af-493">在 P1 和 P2) 支援的檔中套用資訊保護 (。</span><span class="sxs-lookup"><span data-stu-id="c83af-493">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="c83af-494">在 Office 應用程式中自動分類及標記資訊 (例如 Word、PowerPoint、Excel 和 Outlook) 在 Windows 上執行，並使用 P2) 支援的 Azure 資訊保護用戶端 (。</span><span class="sxs-lookup"><span data-stu-id="c83af-494">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="c83af-495">在使用 Azure 資訊保護掃描程式時，在 rest 上探索和標示檔案 (在 P1 和 P2) 中支援。</span><span class="sxs-lookup"><span data-stu-id="c83af-495">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="c83af-496">使用 Exchange Online 郵件流程規則監視傳輸中的電子郵件。</span><span class="sxs-lookup"><span data-stu-id="c83af-496">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="c83af-497">如果您想要使用 Microsoft Azure Rights Management Services 來套用保護，我們也會提供指導方針。 (Azure RMS) ，Office 365 Message Encryption (OME) ，以及資料遺失防護 (DLP) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-497">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="c83af-498"><strong>下列超出範圍 </strong></span><span class="sxs-lookup"><span data-stu-id="c83af-498"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="c83af-499">客戶金鑰。</span><span class="sxs-lookup"><span data-stu-id="c83af-499">Customer key.</span></span></li>
<li><span data-ttu-id="c83af-500">自訂正則運算式 (RegEx 機密資訊類型) 開發。</span><span class="sxs-lookup"><span data-stu-id="c83af-500">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="c83af-501">建立或修改關鍵字字典。</span><span class="sxs-lookup"><span data-stu-id="c83af-501">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="c83af-502">自訂腳本和編碼。</span><span class="sxs-lookup"><span data-stu-id="c83af-502">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="c83af-503">Azure Purview。</span><span class="sxs-lookup"><span data-stu-id="c83af-503">Azure Purview.</span></span></li>
<li> <span data-ttu-id="c83af-504">設計、設計架構和協力廠商檔審閱。</span><span class="sxs-lookup"><span data-stu-id="c83af-504">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="c83af-505">遵守行業和地區性法規和需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-505">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="c83af-506">在合規性管理員中針對評估建議的改進動作的實際執行。</span><span class="sxs-lookup"><span data-stu-id="c83af-506">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="c83af-507">除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，Azure 資訊保護例外情況下沒有最低的系統需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-507">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="c83af-508"><strong>Azure 資訊保護</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-508"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="c83af-509">客戶必要的責任包括：</span><span class="sxs-lookup"><span data-stu-id="c83af-509">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="c83af-510">要掃描的檔案共用位置清單。</span><span class="sxs-lookup"><span data-stu-id="c83af-510">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="c83af-511">已核准的分類分類。</span><span class="sxs-lookup"><span data-stu-id="c83af-511">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="c83af-512">瞭解有關金鑰管理的任何法規限制或需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-512">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="c83af-513">為您的內部部署 Active Directory 建立且與 Azure AD 同步處理的服務帳戶。</span><span class="sxs-lookup"><span data-stu-id="c83af-513">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="c83af-514">針對分類及保護所設定的標籤。</span><span class="sxs-lookup"><span data-stu-id="c83af-514">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="c83af-515">Azure 資訊保護掃描程式的所有必要條件皆已到位。</span><span class="sxs-lookup"><span data-stu-id="c83af-515">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="c83af-516">如需詳細資訊，請參閱 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">安裝及部署 Azure 資訊保護統一標記掃描器的必要條件</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-516">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="c83af-517">請確定使用者裝置執行的是支援的作業系統，且已安裝必要的必要條件。</span><span class="sxs-lookup"><span data-stu-id="c83af-517">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="c83af-518">如需詳細資訊，請參閱下列各項。</span><span class="sxs-lookup"><span data-stu-id="c83af-518">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="c83af-519"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">系統管理員指南：安裝 Azure 資訊保護統一標籤用戶端以供使用者</a>   </span><span class="sxs-lookup"><span data-stu-id="c83af-519"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="c83af-520"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">IOS 或 Android 的 Azure 資訊保護應用程式為何？</a>  </span><span class="sxs-lookup"><span data-stu-id="c83af-520"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="c83af-521">安裝和設定 Azure RMS 連接器和伺服器（包括 Active Directory RMS (AD RMS) 連接器）以進行混合支援。</span><span class="sxs-lookup"><span data-stu-id="c83af-521">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="c83af-522">安裝和設定會將您自己的金鑰 (BYOK) 、雙金鑰加密 (DKE)  (整合標籤用戶端) ，或是只保留您自己的金鑰 (HYOK)  (經典用戶端您應該在部署中的其中一個選項。</span><span class="sxs-lookup"><span data-stu-id="c83af-522">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="c83af-523"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-523"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="c83af-524">我們為您的應用程式和裝置提供準備使用 Intune 做為雲端型行動裝置管理 (MDM) 和行動應用程式管理 (MAM) 提供者的遠端指南。</span><span class="sxs-lookup"><span data-stu-id="c83af-524">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="c83af-525">確切的步驟取決於您的來源環境，而且是根據您的行動裝置和行動裝置應用程式管理需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-525">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="c83af-526">步驟可能包括：</span><span class="sxs-lookup"><span data-stu-id="c83af-526">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-527">授權使用者。</span><span class="sxs-lookup"><span data-stu-id="c83af-527">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="c83af-528">利用您的內部部署 Active Directory 或雲端身分識別 (Azure AD) 設定供 Intune 使用的身分識別。</span><span class="sxs-lookup"><span data-stu-id="c83af-528">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="c83af-529">將使用者新增到您的 Intune 訂用帳戶、定義 IT 系統管理員角色，以及建立使用者和裝置群組。</span><span class="sxs-lookup"><span data-stu-id="c83af-529">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="c83af-530">根據您的管理需求，設定您的 MDM 授權機構，包括：</span><span class="sxs-lookup"><span data-stu-id="c83af-530">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-531">當 Intune 為您唯一的 MDM 解決方案時，將 Intune 設定為 MDM 授權單位。</span><span class="sxs-lookup"><span data-stu-id="c83af-531">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="c83af-532">為下列提供 MDM 指引：</span><span class="sxs-lookup"><span data-stu-id="c83af-532">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-533">設定用於驗證 MDM 管理原則的測試群組。</span><span class="sxs-lookup"><span data-stu-id="c83af-533">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="c83af-534">設定 MDM 管理原則和服務，例如：</span><span class="sxs-lookup"><span data-stu-id="c83af-534">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-535">透過網頁連結或深層連結，為每個支援的平臺部署應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-535">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="c83af-536">條件式存取原則。</span><span class="sxs-lookup"><span data-stu-id="c83af-536">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="c83af-537">如果您的組織中有現有的憑證授權單位、無線網路或 VPN 基礎結構，則部署電子郵件、無線網路和 VPN 設定檔。</span><span class="sxs-lookup"><span data-stu-id="c83af-537">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="c83af-538">連接至 Intune 資料倉儲。</span><span class="sxs-lookup"><span data-stu-id="c83af-538">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="c83af-539">整合 Intune 與：</span><span class="sxs-lookup"><span data-stu-id="c83af-539">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-540">小組檢視器針對遠端協助 (需要) 小組檢視器訂閱。</span><span class="sxs-lookup"><span data-stu-id="c83af-540">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="c83af-541">行動威脅防護 (MTD) 協力廠商解決方案 (必須) 的 MTD 訂閱。</span><span class="sxs-lookup"><span data-stu-id="c83af-541">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="c83af-542">需要)  (電信費用管理解決方案的電訊費用管理解決方案。</span><span class="sxs-lookup"><span data-stu-id="c83af-542">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="c83af-543">將每個支援的平台的裝置註冊到 Intune。</span><span class="sxs-lookup"><span data-stu-id="c83af-543">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="c83af-544">在下列情況提供應用程式保護指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-544">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-545">針對每個支援的平台設定應用程式保護原則。</span><span class="sxs-lookup"><span data-stu-id="c83af-545">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="c83af-546">為受管理的應用程式設定條件式存取原則。</span><span class="sxs-lookup"><span data-stu-id="c83af-546">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="c83af-547">以先前所述的 MAM 原則針對適當的使用者群組。</span><span class="sxs-lookup"><span data-stu-id="c83af-547">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="c83af-548">使用受管理的應用程式使用方式報告。</span><span class="sxs-lookup"><span data-stu-id="c83af-548">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="c83af-549">提供從舊版 PC 管理到 Intune MDM 的遷移指南。</span><span class="sxs-lookup"><span data-stu-id="c83af-549">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="c83af-550">
 
</li>
</ul>
  
<strong>雲端附加</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-550">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="c83af-551">我們將引導您完成 cloud-附上現有 Configuration Manager 環境與 Intune 的準備工作。</span><span class="sxs-lookup"><span data-stu-id="c83af-551">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="c83af-552">確切的步驟取決於您的來源環境。</span><span class="sxs-lookup"><span data-stu-id="c83af-552">The exact steps depend on your source environment.</span></span> <span data-ttu-id="c83af-553">這些步驟可能包括：</span><span class="sxs-lookup"><span data-stu-id="c83af-553">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="c83af-554">授權使用者。</span><span class="sxs-lookup"><span data-stu-id="c83af-554">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="c83af-555">利用內部部署 Active Directory 和雲端身分識別來設定 Intune 將使用的身分識別。</span><span class="sxs-lookup"><span data-stu-id="c83af-555">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="c83af-556">將使用者新增到您的 Intune 訂用帳戶、定義 IT 系統管理員角色，以及建立使用者和裝置群組。</span><span class="sxs-lookup"><span data-stu-id="c83af-556">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="c83af-557">提供指導方針設定混合式 Azure AD 聯結。</span><span class="sxs-lookup"><span data-stu-id="c83af-557">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="c83af-558">提供設定適用于 MDM 自動註冊之 Azure AD 的指導方針。</span><span class="sxs-lookup"><span data-stu-id="c83af-558">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="c83af-559">提供有關如何設定雲端管理閘道的指導方針，用作遠端網際網路型裝置管理的共同管理解決方案。</span><span class="sxs-lookup"><span data-stu-id="c83af-559">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="c83af-560">設定要切換到 Intune 的支援工作負載。</span><span class="sxs-lookup"><span data-stu-id="c83af-560">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="c83af-561">將 Configuration Manager 用戶端安裝在 Intune 中註冊的裝置。</span><span class="sxs-lookup"><span data-stu-id="c83af-561">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="c83af-562"><strong>安全地部署適用于 iOS 和 Android 的 Outlook mobile</strong> 我們可以提供指導方針，協助您在組織中安全地部署 Outlook mobile for iOS 和 Android，以確保您的使用者已安裝所有必要的應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-562"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="c83af-563">使用 Intune 以安全方式部署 Outlook mobile for iOS 和 Android 的步驟，視您的來源環境而定。</span><span class="sxs-lookup"><span data-stu-id="c83af-563">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="c83af-564">它可以包含：</span><span class="sxs-lookup"><span data-stu-id="c83af-564">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-565">透過 Apple App Store 或 Google Play Store，下載適用于 iOS 和 Android、Microsoft 驗證者及 Intune 公司入口網站應用程式的 Outlook。</span><span class="sxs-lookup"><span data-stu-id="c83af-565">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="c83af-566">提供有關設定的指導方針：</span><span class="sxs-lookup"><span data-stu-id="c83af-566">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-567">適用于使用 Intune 的 iOS 和 Android、Microsoft 驗證者及 Intune 公司入口網站應用程式部署的 Outlook。</span><span class="sxs-lookup"><span data-stu-id="c83af-567">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="c83af-568">應用程式保護原則。</span><span class="sxs-lookup"><span data-stu-id="c83af-568">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="c83af-569">條件式存取原則。</span><span class="sxs-lookup"><span data-stu-id="c83af-569">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="c83af-570">應用程式佈建原則。</span><span class="sxs-lookup"><span data-stu-id="c83af-570">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="c83af-571">在規劃使用 Intune 部署無線網路和 VPN 設定檔時，IT 系統管理員必須具備實際執行環境中使用的憑證授權、無線網路和 VPN 基礎結構。</span><span class="sxs-lookup"><span data-stu-id="c83af-571">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="c83af-572"><strong>附注</strong>： FastTrack 服務權益不包括設定或設定憑證授權機構、無線網路、VPN 基礎結構或 Apple MDM push 憑證 for Intune 的協助。</span><span class="sxs-lookup"><span data-stu-id="c83af-572"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="c83af-573"><strong>附註</strong>: FastTrack 服務權益不包含協助將設定管理員站台伺服器或將設定管理員用戶端設定或升級，以滿足對支援雲端附加所需的最低需求。</span><span class="sxs-lookup"><span data-stu-id="c83af-573"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="c83af-574">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。</span><span class="sxs-lookup"><span data-stu-id="c83af-574">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="c83af-575"><strong>與 Microsoft Defender for Endpoint 整合的 Intune</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-575"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="c83af-576"><strong>附注</strong>：我們會提供整合 Intune 與 Microsoft Defender for Endpoint 的協助，並根據其 Windows 10 風險等級評估建立裝置規範原則。</span><span class="sxs-lookup"><span data-stu-id="c83af-576"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="c83af-577">我們不會提供有關購買、授權或啟用的協助。</span><span class="sxs-lookup"><span data-stu-id="c83af-577">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="c83af-578">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。</span><span class="sxs-lookup"><span data-stu-id="c83af-578">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="c83af-579"><strong>Windows Autopilot</strong> </span><span class="sxs-lookup"><span data-stu-id="c83af-579"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="c83af-580">IT 系統管理員需負責向組織註冊他們的裝置，方法是讓硬體廠商代表他們上傳或是自行上傳其硬體識別碼到 Windows Autopilot 服務。</span><span class="sxs-lookup"><span data-stu-id="c83af-580">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="c83af-581">Office 365</span><span class="sxs-lookup"><span data-stu-id="c83af-581">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c83af-582"><strong>服務</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-582"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="c83af-583"><strong>FastTrack 指引詳細資料</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-583"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="c83af-584"><strong>來源環境預期</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-584"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c83af-585"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-585"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="c83af-586">對於 Exchange Online，我們將引導您讓組織準備好使用電子郵件的程序。</span><span class="sxs-lookup"><span data-stu-id="c83af-586">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="c83af-587">具體步驟取決於來源環境和您的電子郵件遷移計畫。</span><span class="sxs-lookup"><span data-stu-id="c83af-587">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="c83af-588">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-588">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-589">針對在 Office 365 中驗證的所有已啟用郵件的網域設定 Exchange Online Protection (EOP) 功能。</span><span class="sxs-lookup"><span data-stu-id="c83af-589">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="c83af-590">將郵件交換 (MX) 記錄指向 Office 365。</span><span class="sxs-lookup"><span data-stu-id="c83af-590">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="c83af-591">設定 Microsoft Defender for Office 365 功能（如果是訂閱服務的一部分）。</span><span class="sxs-lookup"><span data-stu-id="c83af-591">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="c83af-592">如需詳細資訊，請參閱此表格的 <strong>Microsoft Defender For Office 365</strong> 部分。</span><span class="sxs-lookup"><span data-stu-id="c83af-592">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="c83af-p127">為 Office 365 中經驗證之所有已啟用郵件的網域設定資料遺失保護 (DLP) 功能，作為訂閱服務的一部分。將您的 MX 記錄指向 Office 365 之後即完成此項設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="c83af-p128">為 Office 365 中經驗證之所有已啟用郵件的網域設定 Office 365 訊息加密 (OME) 功能，作為訂閱服務的一部分。將您的 MX 記錄指向 Office 365 之後即完成此項設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="c83af-597">
  <strong>附注：</strong> 信箱複寫服務 (MRS) 嘗試將 (IRM) 電子郵件從您的內部部署信箱遷移到對應的 Exchange Online 信箱。</span><span class="sxs-lookup"><span data-stu-id="c83af-597">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="c83af-598">在移轉之後，客戶必須將 Active Directory Rights Management Services (AD RMS) 範本複製到 Azure 版權管理服務 (Azure RMS)，才能讀取受保護的內容。</span><span class="sxs-lookup"><span data-stu-id="c83af-598">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="c83af-599">設定防火牆連接埠。</span><span class="sxs-lookup"><span data-stu-id="c83af-599">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="c83af-600">設定 DNS，包含必要的自動探索、寄件者原則框架 (SPF) 、DomainKeys 識別的郵件 (DKIM) 、以網域為基礎的郵件驗證、報告和一致性 (DMARC) 和 MX 記錄 (如有必要) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-600">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="c83af-601">如果需要，則設定您的來源訊息環境與 Exchange Online 間的電子郵件流程。</span><span class="sxs-lookup"><span data-stu-id="c83af-601">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="c83af-602">進行從來源郵件環境到 Office 365 的郵件移轉。</span><span class="sxs-lookup"><span data-stu-id="c83af-602">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="c83af-603">設定信箱用戶端 (Outlook for Windows、Outlook 網頁版，以及 Outlook for iOS 和 Android)。</span><span class="sxs-lookup"><span data-stu-id="c83af-603">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="c83af-604">
  <strong>資料移轉</strong>  </span><span class="sxs-lookup"><span data-stu-id="c83af-604">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="c83af-605">如需使用 FastTrack 將資料移轉至 Office 365 的優點的詳細資訊，請參閱 <a href="https://docs.microsoft.com/fasttrack/data-migration">資料移轉</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-605">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="c83af-606">您的來源環境必須具有下列其中一個基本層級：</span><span class="sxs-lookup"><span data-stu-id="c83af-606">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-607">含有 Exchange Server 2003 以上版本的單一或多個 Exchange 組織。</span><span class="sxs-lookup"><span data-stu-id="c83af-607">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="c83af-608">具備單一網際網路訊息存取通訊協定 (IMAP) 功能的電子郵件環境。</span><span class="sxs-lookup"><span data-stu-id="c83af-608">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="c83af-609">單一 G Suite 環境 (僅限 Gmail、連絡人和行事曆)。</span><span class="sxs-lookup"><span data-stu-id="c83af-609">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="c83af-610">如需多地理位置功能的詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online 中的多地理位置功能</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-610">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="c83af-611">線上用戶端軟體（如 Office 365 的專案）、Outlook for Windows、Outlook for iOS 和 Android、商務同步處理用戶端、Power BI Desktop 和商務用 Skype 的 OneDrive，都必須在 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="c83af-611">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="c83af-612"><strong>適用於 Office 365 的 Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-612"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="c83af-613">如需詳細資訊，請參閱在<a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">安全性和合規性</a>中<strong>的 Microsoft Defender for Office 365</strong> 。</span><span class="sxs-lookup"><span data-stu-id="c83af-613">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="c83af-614"><strong>Microsoft 資訊控管</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-614"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="c83af-615">如需詳細資訊，請參閱<a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">安全性和合規性</a>中的<strong>Microsoft 資訊管理</strong>。</span><span class="sxs-lookup"><span data-stu-id="c83af-615">For more information, see <strong> Microsoft Information Governance</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c83af-616"><strong>Microsoft 資訊保護</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-616"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="c83af-617">如需詳細資訊，請參閱 <strong>Microsoft 資訊保護 </strong> 的 <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">安全性和合規性</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-617">For more information, see <strong>Microsoft Information Protection </strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="c83af-618"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-618"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="c83af-619">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-619">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-620">確認 Exchange Online 中的最低需求、SharePoint 線上、Office 365 群組和 Azure AD 以支援小組。</span><span class="sxs-lookup"><span data-stu-id="c83af-620">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="c83af-621">設定防火牆連接埠。</span><span class="sxs-lookup"><span data-stu-id="c83af-621">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="c83af-622">設立 DNS。</span><span class="sxs-lookup"><span data-stu-id="c83af-622">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="c83af-623">確認您的 Office 365 租用戶上已啟用 Teams。</span><span class="sxs-lookup"><span data-stu-id="c83af-623">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="c83af-624">啟用或停用使用者授權。</span><span class="sxs-lookup"><span data-stu-id="c83af-624">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="c83af-625">小組網路評估：</span><span class="sxs-lookup"><span data-stu-id="c83af-625">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-626">連接埠和端點檢查。</span><span class="sxs-lookup"><span data-stu-id="c83af-626">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="c83af-627">連線品質檢查。</span><span class="sxs-lookup"><span data-stu-id="c83af-627">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="c83af-628">頻寬估計。</span><span class="sxs-lookup"><span data-stu-id="c83af-628">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="c83af-629">設定小組應用程式原則 (小組 web app、小組桌面應用程式，以及 iOS 和 Android 應用程式) 的團隊。</span><span class="sxs-lookup"><span data-stu-id="c83af-629">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="c83af-630">如果適用，我們也會提供下列專案的指引。。</span><span class="sxs-lookup"><span data-stu-id="c83af-630">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-631">Microsoft 團隊會議室裝置：</span><span class="sxs-lookup"><span data-stu-id="c83af-631">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="c83af-632">建立 <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams 裝置目錄</a>中列出的受支援電話和會議室裝置所需的線上帳戶。</span><span class="sxs-lookup"><span data-stu-id="c83af-632">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="c83af-633">遠端協助，包含已認證 Microsoft 團隊聊天室裝置的服務端設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-633">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="c83af-634">啟用音訊會議：</span><span class="sxs-lookup"><span data-stu-id="c83af-634">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="c83af-635">會議橋接預設設定的組織設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-635">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="c83af-636">對授權使用者會議橋接的指派。</span><span class="sxs-lookup"><span data-stu-id="c83af-636">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="c83af-637">電話系統：</span><span class="sxs-lookup"><span data-stu-id="c83af-637">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-638">雲端語音預設設定的組織設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-638">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="c83af-639">通話方案指引 (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">可用市場</a>) ：</span><span class="sxs-lookup"><span data-stu-id="c83af-639">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="c83af-640">授權使用者號碼的指派。</span><span class="sxs-lookup"><span data-stu-id="c83af-640">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="c83af-641">透過使用者介面 (UI) 的本機號碼移轉指引最多至 999。</span><span class="sxs-lookup"><span data-stu-id="c83af-641">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="c83af-642">本機號碼移轉服務要求 (SR) 支援超過 999。</span><span class="sxs-lookup"><span data-stu-id="c83af-642">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="c83af-643">直接路由指引：</span><span class="sxs-lookup"><span data-stu-id="c83af-643">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-644">組織安裝指導，以供協力廠商託管案例的直接路由設計，或最多10個網站的客戶部署案例。</span><span class="sxs-lookup"><span data-stu-id="c83af-644">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="c83af-645">會話邊界控制器 (SBC) 設定複查。</span><span class="sxs-lookup"><span data-stu-id="c83af-645">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="c83af-646">使用撥號對應表設定的遠端協助。</span><span class="sxs-lookup"><span data-stu-id="c83af-646">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="c83af-647">語音路由設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-647">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="c83af-648">媒體旁路和本機媒體優化。</span><span class="sxs-lookup"><span data-stu-id="c83af-648">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="c83af-649">啟用 Teams 即時活動。</span><span class="sxs-lookup"><span data-stu-id="c83af-649">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="c83af-650">組織設定與 Microsoft Stream 整合。</span><span class="sxs-lookup"><span data-stu-id="c83af-650">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="c83af-651">商務用 Skype to 小組的指導方針。</span><span class="sxs-lookup"><span data-stu-id="c83af-651">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="c83af-652">Azure AD for Office 365 中啟用的身分識別。</span><span class="sxs-lookup"><span data-stu-id="c83af-652">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="c83af-653">已啟用 SharePoint Online 的使用者。</span><span class="sxs-lookup"><span data-stu-id="c83af-653">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="c83af-654">Exchange 混合式設定) 中有 (線上和內部部署的 exchange 信箱。</span><span class="sxs-lookup"><span data-stu-id="c83af-654">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="c83af-655">啟用 Office 365 群組。</span><span class="sxs-lookup"><span data-stu-id="c83af-655">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="c83af-656">
  <strong>附注：</strong> 如果未使用 SharePoint 線上授權指派及啟用使用者，則在 Office 365 中不會有商務儲存 OneDrive。</span><span class="sxs-lookup"><span data-stu-id="c83af-656">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="c83af-657">檔案共用仍可在通道中運作，但是使用者無法在聊天時共用檔，但不 OneDrive Office 365 中的商務儲存。</span><span class="sxs-lookup"><span data-stu-id="c83af-657">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="c83af-658">團隊不支援內部部署 SharePoint。</span><span class="sxs-lookup"><span data-stu-id="c83af-658">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="c83af-659">
  <strong>附注：</strong> 「理想」狀態是讓所有使用者將其信箱置於 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="c83af-659">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="c83af-660">在內部部署信箱的使用者，必須透過 Azure AD Connect，將其身分識別與 Office 365 目錄同步。</span><span class="sxs-lookup"><span data-stu-id="c83af-660">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="c83af-661">針對這些 Exchange 混合式客戶，如果使用者的信箱在內部部署中，使用者就無法新增或設定連接器。</span><span class="sxs-lookup"><span data-stu-id="c83af-661">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="c83af-662">Microsoft Teams Windows 安裝程式和 Mac 桌面用戶端可以從這裡下載：<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-662">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="c83af-663"><strong>Outlook for iOS 和 Android</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-663"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="c83af-664">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-665">從 Apple App Store 和 Google Play 下載 Outlook for iOS 和 Android。</span><span class="sxs-lookup"><span data-stu-id="c83af-665">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="c83af-666">設定帳戶並存取 Exchange Online 信箱。</span><span class="sxs-lookup"><span data-stu-id="c83af-666">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="c83af-667">保護 Outlook mobile (請參閱 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">在 Exchange Online 中保護 iOS 和 Android 的 outlook</a> 以取得詳細資訊) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-667">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="c83af-668">Azure AD for Office 365 中啟用的身分識別。</span><span class="sxs-lookup"><span data-stu-id="c83af-668">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="c83af-669">已設定 Exchange Online 並指派授權。</span><span class="sxs-lookup"><span data-stu-id="c83af-669">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c83af-670"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-670"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="c83af-671">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-671">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-672">指派 Power BI 的授權。</span><span class="sxs-lookup"><span data-stu-id="c83af-672">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="c83af-673">部署 Power BI Desktop 應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-673">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c83af-674">線上用戶端軟體（如 Power BI Desktop）必須具備 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="c83af-674">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c83af-675"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-675"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="c83af-676">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-676">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-677">確認 Microsoft Project Online 依賴的基本 SharePoint 功能。</span><span class="sxs-lookup"><span data-stu-id="c83af-677">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="c83af-678">將 Microsoft Project Online 服務新增到您的租用戶中 (包括新增使用者的訂閱)。</span><span class="sxs-lookup"><span data-stu-id="c83af-678">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="c83af-679">設定企業資源資料庫​​ (ERP)。</span><span class="sxs-lookup"><span data-stu-id="c83af-679">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="c83af-680">建立您的第一個專案。</span><span class="sxs-lookup"><span data-stu-id="c83af-680">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c83af-681">線上用戶端軟體（如 365 Office 的專案）必須至少是 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="c83af-681">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c83af-682"><strong>Project Online 專業版和 Premium</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-682"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="c83af-683">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-683">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-684">解決部署問題。</span><span class="sxs-lookup"><span data-stu-id="c83af-684">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="c83af-685">使用 Microsoft 365 系統管理中心和 Windows PowerShell 指派使用者授權。</span><span class="sxs-lookup"><span data-stu-id="c83af-685">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="c83af-686">使用隨選即用從 Office 365 入口網站安裝 Project Online 桌面用戶端。</span><span class="sxs-lookup"><span data-stu-id="c83af-686">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="c83af-687">使用 Office 365 部署工具來設定更新設定。</span><span class="sxs-lookup"><span data-stu-id="c83af-687">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="c83af-688">設定 Project Online 桌面用戶端的單一內部網站發佈伺服器，包含建立搭配 Office 365 部署工具使用之 configuration.xml 檔案的相關協助。</span><span class="sxs-lookup"><span data-stu-id="c83af-688">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="c83af-689">正在將 Project Online 桌面用戶端連線至 Project Online 專業版或 Project Online 進階版。</span><span class="sxs-lookup"><span data-stu-id="c83af-689">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="c83af-690">線上用戶端軟體（如 365 Office 的專案）必須至少是 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="c83af-690">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c83af-691"><strong>SharePoint Online 和商務用 OneDrive</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-691"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="c83af-692">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-692">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-693">設立 DNS。</span><span class="sxs-lookup"><span data-stu-id="c83af-693">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="c83af-694">設定防火牆連接埠。</span><span class="sxs-lookup"><span data-stu-id="c83af-694">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="c83af-695">佈建使用者和授權。</span><span class="sxs-lookup"><span data-stu-id="c83af-695">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="c83af-696">啟用 SharePoint Online 管理員的網站架設。</span><span class="sxs-lookup"><span data-stu-id="c83af-696">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="c83af-697">規劃網站集合。</span><span class="sxs-lookup"><span data-stu-id="c83af-697">Planning site collections.</span></span></li>
<li><span data-ttu-id="c83af-698">保護內容與管理權限。</span><span class="sxs-lookup"><span data-stu-id="c83af-698">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="c83af-699">設定 SharePoint Online 功能。</span><span class="sxs-lookup"><span data-stu-id="c83af-699">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="c83af-700">設定 SharePoint 混合式功能，如混合式搜尋、混合式網站、混合式分類、內容類型、混合式自助網站架設 (僅限 SharePoint Server 2013)、擴充的應用程式啟動器、混合式商務用 OneDrive，以及外部網路網站。</span><span class="sxs-lookup"><span data-stu-id="c83af-700">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="c83af-701">您的遷移方法。</span><span class="sxs-lookup"><span data-stu-id="c83af-701">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="c83af-702">根據您的 SharePoint 版本，針對 Business OneDrive 提供其他指導方針，如下所示：</span><span class="sxs-lookup"><span data-stu-id="c83af-702">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-703">識別整合選項，並複查內部部署和線上網路基礎結構和頻寬。</span><span class="sxs-lookup"><span data-stu-id="c83af-703">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="c83af-704">安裝 SharePoint Online 2013 SP1 (（如果適用）) 、規劃及執行同步和身分識別需求，以及識別您的 Business sync 用戶端 OneDrive。</span><span class="sxs-lookup"><span data-stu-id="c83af-704">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="c83af-705">為所有使用者規劃及實施單一推廣 (或分階段的展示) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-705">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="c83af-706">指派授權、將「我的網站」和個人文件庫重新導向至 Office 365 (適用于 SharePoint 線上 2013) ，設定物件，以控制 OneDrive (SharePoint Online 2013) 的存取權。</span><span class="sxs-lookup"><span data-stu-id="c83af-706">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="c83af-707">在 OneDrive 中重新導向或移動已知的資料夾。</span><span class="sxs-lookup"><span data-stu-id="c83af-707">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="c83af-708">部署商務用戶端同步處理的 OneDrive。</span><span class="sxs-lookup"><span data-stu-id="c83af-708">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="c83af-709">
  <strong>資料移轉</strong>  </span><span class="sxs-lookup"><span data-stu-id="c83af-709">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="c83af-710">如需使用 FastTrack 將資料移轉至 Office 365 的優點的詳細資訊，請參閱 <a href="https://docs.microsoft.com/fasttrack/data-migration">資料移轉</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-710">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="c83af-711"><strong>SharePoint 混合：</strong>  
</span><span class="sxs-lookup"><span data-stu-id="c83af-711"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="c83af-712">SharePoint 混合式設定包括設定混合式搜尋、網站、分類法、內容類型、商務 OneDrive、擴充的應用程式啟動器、外部網路網站，以及從內部部署至單一目標 SharePoint 線上環境的自助網站架設。</span><span class="sxs-lookup"><span data-stu-id="c83af-712">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="c83af-713">
  <strong>附注：</strong> 自助網站架設不在執行 SharePoint 2013 的內部部署伺服器範圍內。</span><span class="sxs-lookup"><span data-stu-id="c83af-713">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="c83af-714">若要啟用 SharePoint 混合式，您必須具有下列其中一個內部部署 SharePoint 伺服器環境：2013、2016或2019。</span><span class="sxs-lookup"><span data-stu-id="c83af-714">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="c83af-715">
  <strong>附注：</strong> SharePoint 伺服器的內部部署 SharePoint 環境升級為不在範圍內。</span><span class="sxs-lookup"><span data-stu-id="c83af-715">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="c83af-716">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。</span><span class="sxs-lookup"><span data-stu-id="c83af-716">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="c83af-717">如需詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint 混合式功能的最小公用更新層級</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="c83af-717">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="c83af-718">
  <strong>附注：</strong> 如需多地理位置功能的詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365 中 OneDrive 和 SharePoint Online 中的多地理位置功能</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="c83af-718">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c83af-719"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-719"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="c83af-720">我們提供啟用 Yammer Enterprise 服務的遠端指導方針。</span><span class="sxs-lookup"><span data-stu-id="c83af-720">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="c83af-721">線上用戶端軟體必須具備 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</span><span class="sxs-lookup"><span data-stu-id="c83af-721">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="c83af-722">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="c83af-722">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c83af-723"><strong>服務</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-723"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="c83af-724"><strong>FastTrack 指引詳細資料</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-724"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="c83af-725"><strong>來源環境預期</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-725"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="c83af-726"><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-726"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="c83af-727">如需詳細資訊，請參閱 <strong> Azure Active Directory (AZURE ad) 和 AZURE Ad Premium</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security 和合規性</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-727">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c83af-728"><strong>Azure 資訊保護 </strong></span><span class="sxs-lookup"><span data-stu-id="c83af-728"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="c83af-729">如需 Azure 資訊保護的詳細資訊，請參閱 <strong>Microsoft 資訊保護</strong> 的 <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> 安全性和合規性。</span><span class="sxs-lookup"><span data-stu-id="c83af-729">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="c83af-730"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-730"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="c83af-731">如需詳細資訊，請參閱<a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">安全性和合規性</a>中的<strong>Microsoft Intune</strong> 。</span><span class="sxs-lookup"><span data-stu-id="c83af-731">For more information, see <strong> Microsoft Intune</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="c83af-732">Windows 10</span><span class="sxs-lookup"><span data-stu-id="c83af-732">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c83af-733"><strong>服務</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-733"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="c83af-734"><strong>FastTrack 指引詳細資料</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-734"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="c83af-735"><strong>來源環境預期</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-735"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c83af-736"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-736"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="c83af-737">我們提供將 Windows 7 Professional 和 Windows 8.1 專業版升級至 Windows 10 企業版的指導方針。</span><span class="sxs-lookup"><span data-stu-id="c83af-737">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="c83af-738">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-738">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-739">瞭解您的 Windows 10 意圖。</span><span class="sxs-lookup"><span data-stu-id="c83af-739">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="c83af-740">評估來源環境和需求 (確定 Microsoft 端點 Configuration Manager 已升級至所需的層級，以支援 Windows 10 部署) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-740">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="c83af-741">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 部署 Windows 10 企業版和 Microsoft 365 應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-741">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="c83af-742">建議您評估 Windows 10 應用程式的選項。</span><span class="sxs-lookup"><span data-stu-id="c83af-742">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="c83af-743">啟用桌面 analytics 的使用，以及建立桌面分析部署計畫的指導方針。</span><span class="sxs-lookup"><span data-stu-id="c83af-743">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="c83af-744">Microsoft 365 應用程式相容性評估的方式是利用 Configuration Manager 中的 Office 365 準備儀表板，或搭配 Office 的獨立準備人工具組，以及部署 Microsoft 365 應用程式的協助。</span><span class="sxs-lookup"><span data-stu-id="c83af-744">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="c83af-745">針對成功部署的最低需求，建立修復檢查清單，以達到您需要執行的動作。</span><span class="sxs-lookup"><span data-stu-id="c83af-745">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="c83af-746">在 Windows 10 企業版滿足必要的裝置硬體需求時，提供現有裝置的升級指導方針。</span><span class="sxs-lookup"><span data-stu-id="c83af-746">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="c83af-747">提供升級指導以支援現有的部署動作。</span><span class="sxs-lookup"><span data-stu-id="c83af-747">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="c83af-748">FastTrack 會建議並提供 Windows 10 就地升級的指引。</span><span class="sxs-lookup"><span data-stu-id="c83af-748">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="c83af-749">也提供 Windows 全新映像安裝和 Windows Autopilot 部署案例的指引。</span><span class="sxs-lookup"><span data-stu-id="c83af-749">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="c83af-750">使用 Configuration Manager 部署 Microsoft 365 應用程式做為 Windows 10 部署的一部分。</span><span class="sxs-lookup"><span data-stu-id="c83af-750">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="c83af-751">提供指導方針，以協助您的組織使用您現有的 Configuration Manager 環境或 Microsoft 365 來保持最新的 Windows 10 企業版和 Microsoft 365 應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-751">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="c83af-752">
  
<strong>下列超出範圍 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="c83af-752">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="c83af-753">將 Configuration Manager 升級至最新分支。</span><span class="sxs-lookup"><span data-stu-id="c83af-753">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="c83af-754">建立適用於 Windows 10 部署的自訂映像。</span><span class="sxs-lookup"><span data-stu-id="c83af-754">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="c83af-755">建立及支援 Windows 10 部署的部署指令碼。</span><span class="sxs-lookup"><span data-stu-id="c83af-755">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="c83af-756">將 Windows 10 系統從 BIOS 轉換為整合可延伸韌體介面 (UEFI)。</span><span class="sxs-lookup"><span data-stu-id="c83af-756">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="c83af-757">啟用 Windows 10 的安全性功能。</span><span class="sxs-lookup"><span data-stu-id="c83af-757">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="c83af-758">將 Windows 部署服務 (WDS) 設定為開機前執行環境 (PXE) 啟動。</span><span class="sxs-lookup"><span data-stu-id="c83af-758">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="c83af-759">使用 Microsoft Deployment Toolkit (MDT) 來擷取及部署 Windows 10 映像。</span><span class="sxs-lookup"><span data-stu-id="c83af-759">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="c83af-760">使用使用者狀態移轉工具 (USMT)</span><span class="sxs-lookup"><span data-stu-id="c83af-760">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="c83af-761">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。</span><span class="sxs-lookup"><span data-stu-id="c83af-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="c83af-762">若要升級電腦，您必須符合下列需求：</span><span class="sxs-lookup"><span data-stu-id="c83af-762">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-763">來源作業系統： Windows 7 Enterprise or Professional，Windows 8.1 Enterprise or Professional。</span><span class="sxs-lookup"><span data-stu-id="c83af-763">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="c83af-764">裝置：桌面、筆記本或平板電腦板型。</span><span class="sxs-lookup"><span data-stu-id="c83af-764">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="c83af-765">目標作業系統：視窗10企業版。</span><span class="sxs-lookup"><span data-stu-id="c83af-765">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="c83af-766">若要升級基礎結構，您必須符合以下需求：</span><span class="sxs-lookup"><span data-stu-id="c83af-766">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-767">Microsoft 端點 Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="c83af-767">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="c83af-768">Windows 10 目標版本必須支援 Configuration Manager 版本。</span><span class="sxs-lookup"><span data-stu-id="c83af-768">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="c83af-769">如需詳細資訊，請參閱位於<a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager 對於 Windows 10 的支援</a>的 Configuration Manager 支援表格。</span><span class="sxs-lookup"><span data-stu-id="c83af-769">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="c83af-770"><strong>適用於端點的 Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-770"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="c83af-771">如需詳細資訊，請參閱<a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">安全性和合規性</a>中<strong>的 Microsoft Defender for Endpoint</strong> 。</span><span class="sxs-lookup"><span data-stu-id="c83af-771">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="c83af-772">Windows 虛擬桌面</span><span class="sxs-lookup"><span data-stu-id="c83af-772">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c83af-773"><strong>服務</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-773"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="c83af-774"><strong>FastTrack 指引詳細資料</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-774"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="c83af-775"><strong>來源環境預期</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-775"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c83af-776"><strong>Windows 虛擬桌面</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-776"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="c83af-777">我們為上架至 Windows Virtual Desktop 提供部署指導 (桌面和應用程式虛擬化服務) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-777">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="c83af-778">Windows 虛擬桌面利用 Windows 10 多會話體驗，並針對使用 Microsoft 365 的整合式安全性和管理，針對適用于企業的 Microsoft 365 應用程式進行優化。</span><span class="sxs-lookup"><span data-stu-id="c83af-778">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="c83af-779">我們提供下列專案的遠端指導：</span><span class="sxs-lookup"><span data-stu-id="c83af-779">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="c83af-780">使用下列各項部署 Windows 虛擬桌面環境與 Windows 10 企業版的多重會話和 Microsoft 365 應用程式（適用于企業）：</span><span class="sxs-lookup"><span data-stu-id="c83af-780">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="c83af-781">Azure Marketplace 影像。</span><span class="sxs-lookup"><span data-stu-id="c83af-781">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="c83af-782">共用圖像。</span><span class="sxs-lookup"><span data-stu-id="c83af-782">Shared image.</span></span></li>
<li><span data-ttu-id="c83af-783">Office 部署工具組 (ODT) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-783">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="c83af-784">設定 FSLogix：</span><span class="sxs-lookup"><span data-stu-id="c83af-784">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="c83af-785">使用設定檔容器部署 FSLogix 代理程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-785">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="c83af-786">使用 Office 容器部署 FSLogix 代理程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-786">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="c83af-787">使用內容排除設定 FSLogix 資料夾。</span><span class="sxs-lookup"><span data-stu-id="c83af-787">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="c83af-788">部署 Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="c83af-788">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="c83af-789">部署 Microsoft 團隊。</span><span class="sxs-lookup"><span data-stu-id="c83af-789">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="c83af-790">使用 Windows 虛擬桌面用戶端連接。</span><span class="sxs-lookup"><span data-stu-id="c83af-790">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="c83af-791">

<strong>下列超出範圍</strong>
</span><span class="sxs-lookup"><span data-stu-id="c83af-791">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="c83af-792">客戶 Windows 虛擬桌面部署的專案管理。</span><span class="sxs-lookup"><span data-stu-id="c83af-792">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="c83af-793">協力廠商應用程式虛擬化和部署。</span><span class="sxs-lookup"><span data-stu-id="c83af-793">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="c83af-794">自訂圖像。</span><span class="sxs-lookup"><span data-stu-id="c83af-794">Custom images.</span></span></li>
<li><span data-ttu-id="c83af-795">涉及 VMware 和 Citrix 的遷移和案例。</span><span class="sxs-lookup"><span data-stu-id="c83af-795">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="c83af-796">Linux 案例。</span><span class="sxs-lookup"><span data-stu-id="c83af-796">Linux scenarios.</span></span></li>
<li><span data-ttu-id="c83af-797">轉換或遷移使用者設定檔。</span><span class="sxs-lookup"><span data-stu-id="c83af-797">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="c83af-798">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。</span><span class="sxs-lookup"><span data-stu-id="c83af-798">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="c83af-799">您應該已經具備下列專案：</span><span class="sxs-lookup"><span data-stu-id="c83af-799">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="c83af-800"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows 虛擬桌面授權的需求</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-800"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="c83af-801">Azure 網路：</span><span class="sxs-lookup"><span data-stu-id="c83af-801">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="c83af-802">虛擬網路 (VNET) 建立及子網。</span><span class="sxs-lookup"><span data-stu-id="c83af-802">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="c83af-803">防火牆和網路安全性群組。</span><span class="sxs-lookup"><span data-stu-id="c83af-803">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="c83af-804">VPN 和 ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="c83af-804">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="c83af-805">從內部部署路由傳送至 Azure。</span><span class="sxs-lookup"><span data-stu-id="c83af-805">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="c83af-806">允許連線至 Windows 虛擬桌面的防火牆規則。</span><span class="sxs-lookup"><span data-stu-id="c83af-806">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="c83af-807">如需詳細資訊，請參閱 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> 支援的遠端桌面用戶端</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-807">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="c83af-808">Azure AD 一般設定：</span><span class="sxs-lookup"><span data-stu-id="c83af-808">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="c83af-809">身分識別策略 <i> (您只能使用下列三個選項) 中的其中一項：</i>
</span><span class="sxs-lookup"><span data-stu-id="c83af-809">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="c83af-810">Azure 中使用 Azure AD Connect 的 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="c83af-810">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="c83af-811">使用 Azure AD 的 Active Directory Connect over VPN 或 ExpressRoute 的內部部署。</span><span class="sxs-lookup"><span data-stu-id="c83af-811">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="c83af-812">Active Directory 網域服務 (AD DS) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-812">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="c83af-813">應用程式保證</span><span class="sxs-lookup"><span data-stu-id="c83af-813">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c83af-814"><strong>服務</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-814"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="c83af-815"><strong>FastTrack 指引詳細資料</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-815"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="c83af-816"><strong>來源環境預期</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-816"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="c83af-817"><strong>應用程式保證</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-817"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="c83af-818">應用程式保證是一種服務，旨在解決 Windows 10 和 Microsoft 365 應用程式相容性的問題。</span><span class="sxs-lookup"><span data-stu-id="c83af-818">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="c83af-819">當您要求 App 保證服務時，我們會與您合作，以免費處理有效的應用程式問題，不需要您購買合格的訂閱。</span><span class="sxs-lookup"><span data-stu-id="c83af-819">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="c83af-820">我們也會針對在部署 Windows 虛擬桌面和 Microsoft Edge 時面臨相容性問題的客戶，提供指導，並為解決相容性問題提供各種合理的努力。</span><span class="sxs-lookup"><span data-stu-id="c83af-820">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="c83af-821">我們會為下列 Microsoft 產品上部署的應用程式提供修正協助：</span><span class="sxs-lookup"><span data-stu-id="c83af-821">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="c83af-822"><strong>Windows 10 </strong> (包括 ARM64 裝置) </span><span class="sxs-lookup"><span data-stu-id="c83af-822"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="c83af-823"><strong>Microsoft 365 應用程式</strong>  </span><span class="sxs-lookup"><span data-stu-id="c83af-823"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="c83af-824"><strong>Microsoft Edge-</strong> 如需部署指導，請參閱 <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Microsoft Edge 通道概述</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-824"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="c83af-825"><strong>Windows 虛擬桌面</strong> - 如需詳細資訊，請參閱 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">何謂 Windows Virtual Desktop？</a> 和 <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 企業版多會話常見問題</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-825"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="c83af-826">

<strong>下列超出範圍 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="c83af-826">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="c83af-827">應用程式清查和測試，以判斷可否在 Windows 10 和 Microsoft 365 Apps 上運作。</span><span class="sxs-lookup"><span data-stu-id="c83af-827">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="c83af-828">如需有關此程序的詳細指示，請瀏覽<a href="https://go.microsoft.com/fwlink/?linkid=2080140">電腦部署中心</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-828">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="c83af-829">如果您對於深入的升級整備評估有興趣，請填寫<a href="https://go.microsoft.com/fwlink/?linkid=2053818">客戶要求現代化電腦評估</a>表單。</span><span class="sxs-lookup"><span data-stu-id="c83af-829">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="c83af-830">針對 Windows 10 相容性和支援狀態，研究第三方 ISV 應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-830">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="c83af-831">如需詳細資訊，請參閱<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">電腦分析</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-831">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="c83af-832">僅限應用程式封裝的服務。</span><span class="sxs-lookup"><span data-stu-id="c83af-832">App packaging-only services.</span></span> <span data-ttu-id="c83af-833">不過，應用程式保證小組會將我們針對 Windows 10 修復的應用程式封裝起來，以確保這些應用程式可以在客戶的環境中部署。</span><span class="sxs-lookup"><span data-stu-id="c83af-833">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="c83af-834">

<strong>客戶責任包括</strong>  
</span><span class="sxs-lookup"><span data-stu-id="c83af-834">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="c83af-835">建立應用程式清查。</span><span class="sxs-lookup"><span data-stu-id="c83af-835">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="c83af-836">在 Windows 10 和 Microsoft 365 Apps 上驗證這些應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-836">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="c83af-837">
<strong>附注：</strong>  Microsoft 無法對您的原始程式碼進行變更。</span><span class="sxs-lookup"><span data-stu-id="c83af-837">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="c83af-838">不過，應用程式保證小組可以在原始程式碼適用於您的應用程式時，為應用程式開發人員提供指導方針。</span><span class="sxs-lookup"><span data-stu-id="c83af-838">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="c83af-839">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。</span><span class="sxs-lookup"><span data-stu-id="c83af-839">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="c83af-840"><strong>Windows 10 和 Microsoft 365 應用程式</strong>
</span><span class="sxs-lookup"><span data-stu-id="c83af-840"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="c83af-841">可在 Windows 7、Windows 8.1、Office 2010 和 Office 2013 中執行的應用程式也適用於 Windows 10 和 Microsoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="c83af-841">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="c83af-842">
<strong>ARM 上的 Windows 10</strong>
</span><span class="sxs-lookup"><span data-stu-id="c83af-842">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="c83af-843">在 Windows 7、Office 2010 或更新版本上運作的應用程式也可在 ARM64 裝置上的 Windows 10 和 Microsoft 365 應用程式上運作。</span><span class="sxs-lookup"><span data-stu-id="c83af-843">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="c83af-844">
  <strong>注意：</strong> 
</span><span class="sxs-lookup"><span data-stu-id="c83af-844">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="c83af-845">在參與 Windows 預覽人員 <a href="https://insider.windows.com/">計畫</a>的客戶預覽中，可使用 x64 (64 位) 模擬。</span><span class="sxs-lookup"><span data-stu-id="c83af-845">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="c83af-846">針對 Windows 10 版本2004上的非 Windows 有問必答客戶 (或更新版本) ，使用 <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL 和 OpenGL 相容性套件</a>支援 ARM64 Photoshop。</span><span class="sxs-lookup"><span data-stu-id="c83af-846">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="c83af-847">Windows 預覽體驗計畫中的客戶可以下載 OpenCL 和 OpenGL 相容性套件的有問必答版本，以與其他應用程式搭配使用。</span><span class="sxs-lookup"><span data-stu-id="c83af-847">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="c83af-848">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="c83af-848">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="c83af-849">如果您的 web 應用程式或網站在 Internet Explorer 11、支援的 Google Chrome 或任何版本的 Microsoft edge 中運作，也會與 Microsoft Edge 搭配使用。</span><span class="sxs-lookup"><span data-stu-id="c83af-849">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-850">當網頁不斷演變時，請務必查看此已發佈的已知 <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">網站相容性清單-Microsoft Edge 的變更</a>。</span><span class="sxs-lookup"><span data-stu-id="c83af-850">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="c83af-851">
  <strong>Windows 虛擬桌面 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="c83af-851">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="c83af-852">在 Windows Server 遠端桌面工作階段主機 (RDSH) 上執行的虛擬化應用程式，也能隨著 Windows 虛擬桌面的一部分在 Windows 10 企業版多重工作階段上執行。</span><span class="sxs-lookup"><span data-stu-id="c83af-852">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-853">在任何 Windows 7 或 Windows 10 虛擬桌面基礎結構上執行的應用程式 (VDI) 環境也會在 windows 7 企業版和 Windows 10 Enterprise 上執行，成為 Windows 虛擬桌面的一部分。</span><span class="sxs-lookup"><span data-stu-id="c83af-853">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-854">在 Windows 7 或 Windows 10 用戶端裝置上執行的應用程式，也能隨著 Windows 虛擬桌面的一部分在 Windows 7 企業版和 Windows 10 企業版上執行。</span><span class="sxs-lookup"><span data-stu-id="c83af-854">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="c83af-855">
  <strong>附注：</strong> Windows 10 企業版多會話相容性排除和限制包括：</span><span class="sxs-lookup"><span data-stu-id="c83af-855">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="c83af-856">有限的硬體重新導向。</span><span class="sxs-lookup"><span data-stu-id="c83af-856">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-857">A/V 密集型應用程式可能會以降低的容量執行。</span><span class="sxs-lookup"><span data-stu-id="c83af-857">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="c83af-858">64 位元 Windows 虛擬桌面不支援 16 位元應用程式。</span><span class="sxs-lookup"><span data-stu-id="c83af-858">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="c83af-859">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="c83af-859">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c83af-860"><strong>服務</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-860"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="c83af-861"><strong>FastTrack 指引詳細資料</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-861"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="c83af-862"><strong>來源環境預期</strong></span><span class="sxs-lookup"><span data-stu-id="c83af-862"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="c83af-863"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="c83af-863"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="c83af-864">我們提供下列專案的遠端部署和採用指導方針和相容性協助：</span><span class="sxs-lookup"><span data-stu-id="c83af-864">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="c83af-865">使用 Microsoft 端點管理員 (Microsoft 端點 Configuration Manager 或 Intune) ，在 Windows 10 上部署 Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="c83af-865">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="c83af-866">使用群組原則或 Intune 應用程式設定和應用程式原則) 設定 Microsoft Edge (。</span><span class="sxs-lookup"><span data-stu-id="c83af-866">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="c83af-867">清查可能需要在 Internet Explorer 模式中使用的網站清單。</span><span class="sxs-lookup"><span data-stu-id="c83af-867">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="c83af-868">啟用具有現有企業網站清單的 Internet Explorer 模式。</span><span class="sxs-lookup"><span data-stu-id="c83af-868">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="c83af-869"> (如需詳細資訊，請參閱 <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">接洽 FastTrack</a>) 。</span><span class="sxs-lookup"><span data-stu-id="c83af-869">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="c83af-870">此外，如果您有可搭配 Internet Explorer 或 Google Chrome 使用的 web 應用程式或網站，且您遇到相容性問題，我們會提供指引來解決問題，而不需額外收費。</span><span class="sxs-lookup"><span data-stu-id="c83af-870">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="c83af-871">若要向應用程式保證要求相容性支援，請登入 <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack 入口網站</a> ，以開始預訂。</span><span class="sxs-lookup"><span data-stu-id="c83af-871">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="c83af-872">Microsoft 搜尋書簽之 Edge 採用和設定指引的規劃指引。</span><span class="sxs-lookup"><span data-stu-id="c83af-872">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="c83af-873">

<strong>下列超出範圍 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="c83af-873">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="c83af-874">客戶的 Microsoft Edge 部署的專案管理。</span><span class="sxs-lookup"><span data-stu-id="c83af-874">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="c83af-875">現場支援。</span><span class="sxs-lookup"><span data-stu-id="c83af-875">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
