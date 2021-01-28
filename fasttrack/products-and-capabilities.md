---
title: 產品與功能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 本主題包括 FastTrack 所支援之工作負載案例的詳細資料，以及在開始之前所需的來源環境預期。 根據您目前的設定，我們會與您合作，建立修復計畫，以將來源環境帶入成功上架的最低需求。
ms.openlocfilehash: abbc97a7b2d70b0b0111f1cbe96904bbe552e463
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016685"
---
# <a name="products-and-capabilities"></a>產品與功能

## <a name="services-and-scenarios-supported-by-fasttrack"></a>FastTrack 所支援的服務和案例

本主題包括 FastTrack 所支援之工作負載案例的詳細資料，以及在開始之前所需的來源環境預期。 根據您目前的設定，我們會與您合作，建立修復計畫，以將來源環境帶入成功上架的最低需求。

FastTrack 提供指引，協助您先瞭解所有 Microsoft Online) 服務 (通用的核心功能，然後再上架每個合格的服務：

  - [一般](#general)
  - [安全性與合規性](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows 虛擬桌面](#windows-virtual-desktop)
  - [應用程式保證](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> 如需有關 Office 365 US Government 來源環境預期的資訊，請參閱 [Office 365 US Government 的來源環境預期](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)。 
 
## <a name="general"></a>一般

<table>
<thead>
<tr class="header">
<th><strong>服務</strong></th>
<th><strong>FastTrack 指引詳細資料</strong></th>
<th><strong>來源環境預期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>核心上架</strong></td>
<td>  我們提供核心上架的遠端指導，包含服務布建、租使用者和身分識別整合。 它也包含為上架服務（如 Exchange Online、SharePoint 線上和 Microsoft 小組）奠定基礎的步驟，包括 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">安全性、網路連線和合規性的討論</a>。  
  將一或多個合格服務上架的動作可以從核心上架完成時開始。
</li>
</ul>  

<strong> 身分識別整合 </strong>

我們提供下列專案的遠端指導：
<ul>
<li>準備內部部署 Active Directory 身分識別，以同步處理至 Azure Active Directory (Azure AD) 包括安裝及設定 Azure AD Connect (單一或多樹系) 和授權 (包括群組型授權) 。</li>
<li>建立雲端身分識別（包括使用以群組為基礎的授權在內的大量匯入和授權）。</li>
<li>為您的雲端旅程選擇和啟用正確的驗證方法、密碼雜湊同步處理、傳遞驗證，或 Active Directory Federation Services (AD FS) 。</li>
<li>針對具有單一 Active Directory 樹系的客戶，與 Azure AD Connect 工具同步處理的身分識別，啟用 AD FS。 這需要 Windows Server 2012 R2 Active Directory Federation Services 2.0 或更新版本。</li>
<li>使用密碼雜湊同步處理或透過驗證，將驗證從 AD FS 遷移至 Azure AD。</li>
<li>遷移預先整合的應用程式 (像 Azure AD 圖庫軟體即服務 (SaaS) 應用程式) 從 AD FS 至 Azure AD for single 登錄 (SSO) 。</li>
<li>從 Azure AD 圖庫啟用 SaaS 應用程式與 SSO 的整合。</li>
<li>針對 <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">應用程式整合教學課程清單</a> 中列出的預先整合的 SaaS 應用程式啟用自動使用者布建， (限制于 Azure AD 圖庫 SaaS 應用程式和輸出布建) 。  </li>
</td>

<td>  <strong>網路啟用 </strong>  
  <br>在 FastTrack 的益處中，我們建議您做為連線至雲端服務的最佳作法，以確保 Microsoft 365 的最高效能等級。  
  
<strong>Active Directory</strong> 樹系這些功能樹系層級已設定為 Windows Server 2003 +，具有下列樹系設定：
<ul>
<li>  單一 Active Directory 樹系。  </li>
<li>  單一 Active Directory 帳戶樹系和資源樹系 (Exchange 和/或 Lync 2010、Lync 2013 或 商務用 Skype) 拓樸。  </li>
<li>  多個 Active Directory 帳戶樹系和資源樹系 (Exchange 和/或 Lync 2010、Lync 2013 或 商務用 Skype) 拓樸。  </li>
<li>  多重 Active Directory 帳戶樹系，其中一個樹系為包含 Exchange 和/或 Lync 2010、Lync 2013 或商務用 Skype 的集中式 Active Directory 帳戶樹系。  </li>
<li>  多個 Active Directory 帳戶樹系，每個都有自己的 Exchange 組織。  </li>
<li>  承租人設定所需的工作，以及與 Azure Active Directory 的整合（如有需要）。   </li>
</ul>
  <strong>重要</strong>  <ul>
<li>  針對多樹系 Active Directory 案例，如果已部署 Lync 2010、Lync 2013 或商務用 Skype，則必須部署在與 Exchange 相同的 Active Directory 樹系中。  </li>
<li>  在 Exchange 多重混合式設定中執行多個具有多個 Exchange 組織的 Active Directory 樹系時，共用使用者主體名稱 (UPN) 不支援來源樹系之間的命名空間。 同時也應該分隔 Exchange 組織之間的主要 SMTP 命名空間。 如需詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?linkid=845444">使用多個 Active Directory 樹系的混合部署</a>。  </li>
<li>  對於所有多重樹系設定，Active Directory Federation Services (AD FS) 部署超出範圍。 請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 Apps</strong></td>
<td>  我們提供下列專案的遠端部署指導：
<ul>
<li>  解決部署問題。  </li>
<li>  使用 Microsoft 365 系統管理中心和 Windows PowerShell 指派以使用者和以裝置為基礎的授權。  </li>
<li>  使用隨選即用從 Office 365 入口網站安裝 Microsoft 365 Apps。  </li>
<li>  在 iOS 或 Android 裝置上安裝 Office Mobile 應用程式 (如 Outlook Mobile、Word Mobile、Excel Mobile 和 PowerPoint Mobile)。  </li>
<li>  使用 Office 365 部署工具來設定更新設定。  </li>
<li>  本地或雲端安裝的選取項目和設定。  </li>
<li>  使用 Office 自訂工具或原生 XML 建立 Office 部署工具，以設定部署套件。  </li>
<li>  使用 Microsoft Endpoint Configuration Manager 部署，包含協助建立 Microsoft Endpoint Configuration Manager 套件。  
  此外，如果您有使用舊版 Office 的宏或增益集，且您遇到相容性問題，我們會提供指導方針以透過應用程式保證計畫來修正相容性問題，而不需要額外收費。 如需詳細資訊，請參閱 <strong>應用程式保證</strong> 部分的 <a href="#windows-10">Windows 10</a> 。 </li>
</ul></td>
<td><ul>
<li>  線上用戶端軟體必須具備 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>網路健康情況</strong></td>
<td>  我們提供的遠端指導，可從您的環境取得及解讀重要的網路連線資料，以顯示組織的網站與 Microsoft 的 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">網路連線原則</a>。 這會強調您的網路得分，它會直接影響到遷移速度、使用者經驗、服務效能和可靠性。  
  我們也會引導您完成此資料所強調的任何修正步驟，以協助您提高網路得分。  </td>
<td><ul>
<li>  Microsoft 365 系統管理中心存取。  </li>
<li>  需要最新版本的 Microsoft 365 應用程式。  </li>
<li>  已啟用位置服務，因為 <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 系統管理中心的 [每個網路效能建議] (預覽) </a>。  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a>安全性及合規性

<table>
<thead>
<tr class="header">
<th><strong>服務</strong></th>
<th><strong>FastTrack 指引詳細資料</strong></th>
<th><strong>來源環境預期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></td>
<td>  在下列情況下，我們會提供遠端指導來保護您的雲端身分識別。  

 <br/>

<strong>安全基礎結構</strong>  </ul>
<ul>
<li>  針對您的身分識別設定和啟用強驗證，包括使用 Azure Multi-Factor 驗證 (MFA)  (雲端僅) 、Microsoft 驗證者應用程式，以及 Azure MFA 和自助密碼重設的組合註冊 (SSPR) 。  </li>
<li>  若為非 Azure AD Premium 客戶，會提供指導方針，以利用安全性預設值來保護您的身分識別。  </li>
<li>  針對 Azure AD premium 客戶，提供指導方針以條件式存取來保護您的身分識別。  </li>
<li>  使用 Azure AD 密碼保護偵測和封鎖弱密碼的使用。  </li>
<li>  使用 Azure AD 應用程式 Proxy，保護內部部署 web 應用程式的遠端存取。  </li>
<li>  使用 Azure 身分識別保護來啟用風險型偵測和修正。  </li>
<li>  啟用自訂的登入畫面，包括徽標、文字和具有自訂商標的影像。  </li>
<li>  使用 Azure AD B2B 與來賓使用者安全地共用應用程式和服務。  </li>
<li>  使用以角色為基礎的存取控制來管理 Office 365 系統管理員的 access (RBAC) 內建管理角色，以及減少特權系統管理員帳戶數目。  </li>
<li>  設定混合式 Azure AD 聯結。  </li>
<li>  設定 Azure AD 聯結。  </li>
</ul>
  
<strong>監視與報告</strong>  
<ul>
<li>  
  使用 Azure AD Connect Health，啟用適用于 AD FS、Azure AD Connect 和網域控制站的遠端監控。  
  </li>
</ul>
  
<strong>治理</strong>  
<ul>
<li>  
  使用 Azure AD 版權管理來管理 Azure AD 身分識別和存取生命週期。
  </li>
<li>  
  使用 Azure AD access 評論管理 Azure AD 群組成員資格、企業應用程式存取和角色指派。  
  </li>
<li>  
  檢查 Azure AD 使用條款。  
  </li>
<li>  
  使用 Azure AD 特權身分識別管理來管理和控制版權管理帳戶的存取。  
  </li>
</ul>
  
<strong>自動化和效率 </strong>  
<ul>
<li>  
  啟用 Azure AD SSPR。  
  </li>
<li>  讓使用者能夠使用 Azure AD 自助群組管理來建立及管理自己的雲端安全性或 Office 365 群組。  </li>
<li>  使用 Azure AD 委派的群組管理來管理企業應用程式的委派存取權。  </li>
<li>  啟用 Azure AD 動態群組。  </li>
<li>  使用集合在「我的應用程式入口網站」中組織應用程式。  </li>
</ul></td>
<td>已針對 Azure AD Premium 準備內部部署 Active Directory 及其環境，包括修正已識別的問題，以防止與 Azure AD 和 Azure AD Premium 功能整合。</td>
</tr>
<tr class="odd">
<td><strong>Azure 資訊保護 </strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  啟用並設定您的租使用者。  </li>
<li>  建立及設定標籤和原則。  </li>
<li>  將資訊保護套用至文件。  </li>
<li>  在 Windows 上執行的 Office 應用程式中，使用 Azure 資訊保護用戶端自動分類資訊並加上標籤 (例如 Word、PowerPoint、Excel 和 Outlook)。  </li>
<li>  使用 Azure 資訊保護掃描程式，在 rest 上探索及標記檔案。  </li>
<li>  使用 Exchange Online 郵件流程規則監視傳輸中的電子郵件。  </li>
</ul>
如果您想要使用 Microsoft Azure Rights Management Services 來套用保護，我們也會提供指導方針。 (Azure RMS) ，Office 365 Message Encryption (OME) ，以及資料遺失防護 (DLP) 。  </td>
<td>  客戶必要的責任包括：
<ul>
<li>  要掃描的檔案共用位置清單。  </li>
<li>  已核准的分類分類。 </li>
<li> 瞭解有關金鑰管理的任何法規限制或需求。  </li>
<li>  為您的內部部署 Active Directory 建立且與 Azure AD 同步處理的服務帳戶。 </li>
<li>  針對分類及保護所設定的標籤。 </li>
<li> Azure 資訊保護掃描程式的所有必要條件皆已到位。 如需詳細資訊，請參閱 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">安裝及部署 Azure 資訊保護統一標記掃描器的必要條件</a>。 </li>
<li>  請確定使用者裝置執行的是支援的作業系統，且已安裝必要的必要條件。 如需詳細資訊，請參閱下列各項。</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">系統管理員指南：安裝 Azure 資訊保護統一標籤用戶端以供使用者</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">IOS 或 Android 的 Azure 資訊保護應用程式為何？</a>  </li>
</ul>
<li> 安裝和設定 Azure RMS 連接器和伺服器（包括 Active Directory RMS (AD RMS) 連接器）以進行混合支援。  </li>
<li> 安裝和設定會將您自己的金鑰 (BYOK) 、雙金鑰加密 (DKE)  (整合標籤用戶端) ，或是只保留您自己的金鑰 (HYOK)  (經典用戶端您應該在部署中的其中一個選項。  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender 是一種整合的後續企業防護套件，其可在端點、身分識別、電子郵件和應用程式上協調偵測、預防、調查和回應，以提供複雜攻擊的整合式防護。 我們提供下列專案的遠端指導： </p> 
<ul>
<li>  提供 Microsoft 365 的安全性中心簡介。  </li>
<li>  檢查跨產品的事件，包括確定完整的攻擊範圍、受影響的資產，以及組合在一起的自動修正動作，以著重于重要專案。  </li>
<li>  示範 Microsoft 365 Defender 如何對資產、使用者、裝置和信箱進行調查，以透過自動自我修復的方式來調查可能已遭破壞的資產、使用者、裝置和信箱。 </li>
<li>  說明及提供客戶如何主動搜尋入侵企圖及破壞您的電子郵件、資料、裝置及帳戶的多個資料組的範例。   </li>
<li> 向客戶展示如何使用 Microsoft 安全評分來複查和提升其安全性狀況 holistically。</li>
</ul>
<p><strong>下列超出範圍</strong></p>
<ul>
<li> 客戶修正活動的專案管理。 </li>
<li> 持續管理、威脅回應及修復。 </li>
<li> 部署指導或教育：
<ul>
<li> 如何修正或轉譯各種警示類型和受監控的活動。 </li>
<li> 如何調查使用者、電腦、側向移動路徑或實體。 </li>
<li> 自訂威脅搜尋。  </li>
</ul>
</li>
<li>  (SIEM) 或 API 整合的安全性資訊和事件管理。</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security 是雲端 Access 安全性經紀人 (CASB) ，可提供豐富的知名度、控制資料旅行，以及完善的分析，以識別和抵禦所有 Microsoft 和協力廠商雲端服務的網路威脅。 我們提供下列專案的遠端指導：
<ul>
<li>  設定入口網站，包括：  </li>
<ul>
<li> 匯入使用者群組。</li>
<li> 管理系統管理存取和設定。  </li>
<li> 確定部署的範圍，以選取要監視或排除監控的特定使用者群組。</li>
<li> 設定 IP 範圍及標記。</li>
<li> 使用您的標誌和自訂訊息，將使用者體驗個人化。</li>
</ul>
<li> 設定 cloud discovery 以提供陰影，使用：</li>
<ul>
<li> Microsoft Defender for 端點。</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> 使用應用程式連接器連接 <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">特色應用程式</a> 。</li>
<li> 在條件式 Access 和 Cloud App Security 入口網站中設定條件式存取應用程式控制，以套用即時會話控制。</li>
<li> 部署 Cloud App Security 和 Cloud Discovery 儀表板。</li>
<li> 根據組織的優先順序自訂應用程式風險分數。</li>
<li> 建立應用程式標記與類別。</li>
<li> Sanctioning 與 unsanctioning 應用程式。</li>
<li> 使用活動和檔記錄。</li>
<li> 管理 OAuth 應用程式。</li>
<li> 瞭解 Microsoft 365 Defender 入口網站中的事件關聯。</li>
<li> 在 CASBs (的 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">前20個使用案例</a> 中提供設定協助，包括建立或更新最多六個 (6) 原則) ，但不包括： </li>
<ul>
<li> 審核網際網路的設定為服務 (IaaS) 環境 ( # 18) 。</li>
<li> 監控使用者活動，以防範 IaaS 環境中的威脅 ( # 19) 。</li>
</ul>
</ul>
<p><strong>下列超出範圍</strong></p>
<ul>
<li> 客戶修正活動的專案管理。</li>
<li> 持續管理、威脅回應及修復。 </li>
<li> 使用 Docker 或記錄收集器，為連續報告設定基礎結構、安裝或部署自動記錄上載。 如需詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">CASBs 的前20個使用案例</a> 。</li>
<li> 建立雲端探索快照報告。</li>
<li> 使用封鎖腳本封鎖應用程式使用方式。</li>
<li> 連接自訂應用程式。</li>
<li> 與協力廠商身分識別提供者整合 (的 Isp) 和資料遺失防護 (DLP) 提供者。</li>
<li> 涵蓋進階搜尋功能的訓練或指導方針。</li>
<li> 自動化調查和修正包括 Microsoft Power 自動化行動手冊。</li>
<li> 安全性資訊和事件管理 (SIEM) 或 API 整合 (包含 Azure Sentinel) 。</li>
<li> 部署雲端應用程式探索以作為概念證明。</li>
</ul></td>
</tr>



<tr class="even">
<td><strong>Microsoft Defender 進階威脅防護 (ATP)</strong></td>
<td>  Microsoft Defender 進階威脅防護 (ATP) 是一個平台，其設計訴求是要協助企業網路預防、偵測、調查及回應進階威脅。  
  我們提供下列專案的遠端指導：
<ul>
<li>  部署技術以保護您的端點。  </li>
<li>  設定 endpoint protection 和裝置限制設定檔。  </li>
<li>  評估 OS 版本和裝置管理 (包括 Intune、Microsoft Endpoint Configuration Manager、群組原則物件 (Gpo) 和協力廠商設定) 以及 Windows Defender AV 服務或其他端點安全性軟體的狀態。  </li>
<li>  評估 Windows AV 服務或其他端點安全性軟體的狀態。  </li>
<li>  評估代理及防火牆，以限制網路流量。  </li>
<li>  透過說明如何使用板載端點部署 ATP 代理程式設定檔，啟用 Microsoft Defender ATP 服務。  </li>
<li>  部署指導方針、設定協助及教育：
<ul>
<li>  
  威脅與弱點管理。  
  </li>
<li>  
  縮小攻擊面。  
  </li>
<li>  
  新一代防護。  
  </li>
<li>  
  端點偵測及回應。  
  </li>
<li>  
  自動化調查與補救措施。  
  </li>
<li>  
  安全分數。  
  </li>
</ul></li>
<li>  查看模擬與示教 (例如練習案例、虛假惡意程式碼和自動調查) 。  </li>
<li>  報表和威脅分析功能的概覽。  </li>
<li>  整合 Office 365 ATP 和 Microsoft Defender ATP。  </li>
<li>  提供 Microsoft Defender 資訊安全中心入口網站的逐步指引。  </li>
<li>  下列作業系統：
<ul>
<li>  
  Windows 10。  
  </li>
<li>  
  Windows Server 2016。  
  </li>
<li>  
  Windows Server 2019。  
  </li>
<li>  
  Windows Server 2019 Core Edition。  
  </li>
<li>  
  Windows Server Semi-Annual 通道 (SAC) 版本1803。  
  </li>
<li>  
  macOS 版本10.13、10.14 及10.15。  
  </li>
</ul>
</li>
</ul>
<strong>附注：</strong> 所有 Windows Server 版本都必須由最新版的 System Center Configuration Manager 2012 (版本 1012 R2、1511或 1602) 或 Microsoft Endpoint Configuration Manager (版本2002或更高版本) 。 

</li>
</ul>

<strong>下列超出範圍 </strong>  
<ul>
<li>  客戶修正活動的專案管理。  </li>
<li>  現場支援。  </li>
<li>  持續性管理和威脅因應。  </li>
<li>  下列 Microsoft Defender ATP 代理程式的上線或組態：
<ul>
<li>  
  Windows Server 2008。  
  </li>
<li>  
  Windows Server 2012。  
  </li>
<li>  
  Linux。  
  </li>
<li>  
  移動裝置 (Android 和 iOS) 。  
  </li>
</ul></li>
<li>  伺服器上架及設定：
<ul>
<li>  
  設定離線通訊的 proxy 伺服器。  
  </li>
<li>  
  設定下層 Configuration Manager 實例和版本的 Configuration Manager 部署套件。  
  </li>
<li>  
  將伺服器上架至 Azure 的安全性中心。  
  </li>
<li>  
  未由 Configuration Manager 管理的伺服器。  
  </li>
</ul></li>
<li>  macOS 上架及設定：
<ul>
<li>  
  手動以 Intune 為基礎的部署。  
  </li>
<li>  
  以 JAMF 為基礎的部署。
  </li>
<li>  
  其他行動裝置管理 (MDM) 以產品為基礎的部署。  
  </li>
<li>  
  手動部署。  
  </li>
</ul></li>
<li>  設定以下能縮小攻擊面的功能：
<ul>
<li>  
  硬體隔離。  
  </li>
<li>  
  應用程式控制。  
  </li>
<li>  
  入侵防護。  
  </li>
<li>  
  網路防火牆。  
  </li>
</ul></li>
<li>  註冊或設定 Microsoft 威脅專家。  </li>
<li>  設定或訓練檢查 API 或安全性資訊和事件管理 (SIEM) 連接。  </li>
<li>  註冊或設定 Microsoft 威脅防護 (MTP)。  </li>
<li>  涵蓋進階搜尋功能的訓練或指導方針。  </li>
<li>  訓練或指引涵蓋使用或建立 Kusto 查詢。</li>
</li>
</ul>
請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender 身分識別 </strong></td>
<td>  適用於身分識別的 Microsoft Defender 是利用內部部署 Active Directory 訊號的雲端型安全性解決方案，它會識別、偵測及調查貴組織中的進階威脅、遭入侵的身分識別，以及惡意內部攻擊動作。 我們提供下列專案的遠端指導：
<ul>
<li>   建立身分識別的 Defender 實例。 </li>
<li>   將 Defender 身分識別連接至 Active Directory。 </li>
<li>   評估您的環境是否準備好在您的網域控制站上部署用於身分識別感應器的 Defender，包括：</li>   
<ul> 
<li>  執行資源容量規劃的調整大小工具。 </li>
<li>  執行審核工具，以評估您的網域控制站與感應器的相容性。 </li>
</ul>
<li>  部署感應器以直接從您的網域控制站捕捉及分析網路流量和 Windows 事件，包括： </li>
<ul> 
<li>  下載感應器套件。 </li>
<li>  設定感應器。 </li>
<li>  在您的網域控制站上無訊息地安裝感應器。 </li>
<li>  將感應器部署至多樹系環境。 </li>
</ul>
<li>  使用 Microsoft Cloud App Security 整合 Defender 以進行身分識別不需要 (Cloud App 安全性授權) 。 </li>
<li>  提供部署指導、設定協助及教育： </li>
<ul>
<li> 調整環境以減少「干擾」。  </li>
<li>  瞭解識別安全狀況評估報告。 </li>
<li>  瞭解使用者調查優先順序分數和使用者調查排名報告。 </li>
<li> 瞭解非使用中的使用者報告。  </li>
<li> 在已遭破壞的帳戶上提供修正選項。  </li>
</ul>
<li>  可促進從高級威脅分析 (ATA) 至 Defender 身分識別的遷移。 </li>
</ul>
<p><strong>下列超出範圍</strong></p>
<ul>

<li> 客戶修正活動的專案管理。 </li>
<li> 持續管理、威脅回應及修復。  </li>
<li> 為身分識別感應器部署 Defender，包括： </li>
<ul>
<li> 手動容量規劃。 </li>
<li> 以獨立的容量部署感應器。 </li>
<li> 使用網路介面卡 (NIC) 編組的配接器部署感應器。 </li>
<li> 透過協力廠商工具部署感應器。 </li>
<li> 透過 web proxy 連線來連線至身分識別雲端服務的 Defender。 </li>
</ul>
<li> Honeytokens 的建立與管理。 </li>
<li> 部署指導或教育： </li>
<ul>
<li> 修正或口譯各種警示類型和受監控的活動。  </li>
<li> 調查使用者、電腦、側向移動路徑或實體。 </li>
<li> 威脅或高級搜尋。 </li>
<li> 事件回應。 </li>
</ul>
<li> 為身分識別提供適用于 Defender 的安全性警示實驗室教學課程。 </li>
<li> 當 Defender 身分識別透過身分識別的感應器傳送安全警示以偵測可疑活動時，提供通知。  </li>
<li> 使用安全帳戶管理員 remote (SAMR) 通訊協定，設定用來執行查詢的 Defender，以識別特定電腦上的本機系統管理員。 </li>
<li> 設定 VPN 解決方案，將 VPN 連線的資訊新增至使用者的設定檔頁面面。  </li>
<li> 安全性資訊和事件管理 (SIEM) 或 API 整合 (包含 Azure Sentinel) 。 </li>
<li> 部署用於身分識別感應器的 Defender 以作為概念證明。</li>
</ul></td>
<td><ul>
<li>  已部署 Active Directory。  </li>
<li>  您想要為身分識別感應器安裝 Defender 的網域控制站，具有對身分識別雲端服務的 internet 連線能力。  </li>
<ul>
<li> 您的防火牆和 proxy 必須開啟才能與 ( 的身分識別，以進行身分識別 cloud service 的 Defender。 atp.azure.com 埠443必須) 開啟。</li>
</ul>
<li> 執行于下列其中一項的網域控制站：</li>
<ul>
<li> Windows Server 2008 R2 SP1。</li>
<li> Windows Server 2012。</li>
<li> Windows Server 2012 R2。</li>
<li> Windows Server 2016。</li>
<li> Windows Server 2019 with KB4487044 (OS 組建 17763.316) 。</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Microsoft 資訊控管</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  保留標籤和原則。  </li>
<li>  記錄管理。  </li>
<li>  刪除原則。  </li>
<li>  通訊合規性。  </li>
<li>  測試人員風險管理。  </li>
<li>  進階電子文件探索。  </li>
</ul>

  <strong>下列超出範圍 </strong>  
<ul>
<li> 記錄管理檔計畫的開發。</li>
<li> 資料連線器。</li>
<li> 資訊障礙。</li>
<li> 特殊許可權存取管理。</li>
<li> 在 SharePoint 中開發資訊架構。</li>
<li> 自訂腳本和編碼。</li>
</td>
<td>除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 資訊保護</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  資料分類。  </li>
<li>  敏感性資訊類型。  </li>
<li>  建立敏感度標籤。  </li>
<li>  套用敏感度標籤。  </li>
<li>  統一標籤。  </li>
<li>  可訓練的分類器。  </li>
<li>  使用內容總管和活動總管瞭解您的資料。  </li>
<li>  使用原則（手動和自動）發布標籤。  </li>
<li>  為 Microsoft Teams 聊天和頻道建立資料外洩防護 (data loss prevention (DLP)) 原則。  </li>
<li>  為 Windows 10 裝置建立端點 DLP 原則。  </li>
</ul>

<strong>下列超出範圍 </strong>  
<ul>
<li>客戶金鑰。</li>
<li>自訂正則運算式 (RegEx 機密資訊類型) 開發。</li>
<li>建立或修改關鍵字字典。</li>
<li>自訂腳本和編碼。</li>
</ul>
<strong>附注：</strong>如需詳細資訊，請參閱<a href="#enterprise-mobility--security">Enterprise 可移動性 + Security</a>中的<strong>Azure 資訊保護</strong>。
<ul>

</td>
<td>除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  我們為您的應用程式和裝置提供準備使用 Intune 做為雲端型行動裝置管理 (MDM) 和行動應用程式管理 (MAM) 提供者的遠端指南。 確切的步驟取決於您的來源環境，而且是根據您的行動裝置和行動裝置應用程式管理需求。 步驟可能包括：
<ul>
<li>  授權使用者。  </li>
<li>  利用您的內部部署 Active Directory 或雲端身分識別 (Azure AD) 設定供 Intune 使用的身分識別。  </li>
<li>  將使用者新增到您的 Intune 訂用帳戶、定義 IT 系統管理員角色，以及建立使用者和裝置群組。  </li>
<li>  根據您的管理需求，設定您的 MDM 授權機構，包括：
<ul>
<li>  當 Intune 為您唯一的 MDM 解決方案時，將 Intune 設定為 MDM 授權單位。  </li>
</ul></li>
<li>  為下列提供 MDM 指引：
<ul>
<li>  設定用於驗證 MDM 管理原則的測試群組。  </li>
<li>  設定 MDM 管理原則和服務，例如：
<ul>
<li>  透過網頁連結或深層連結，為每個支援的平臺部署應用程式。  </li>
<li>  條件式存取原則。  </li>
<li>  如果您的組織中有現有的憑證授權單位、無線網路或 VPN 基礎結構，則部署電子郵件、無線網路和 VPN 設定檔。  </li>
<li>  連接至 Intune 資料倉儲。  </li>
<li>  整合 Intune 與：
<ul>
<li>  小組檢視器針對遠端協助 (需要) 小組檢視器訂閱。  </li>
<li>  行動威脅防護 (MTD) 協力廠商解決方案 (必須) 的 MTD 訂閱。  </li>
<li>  需要)  (電信費用管理解決方案的電訊費用管理解決方案。  </li>

</ul></li>
<li>  將每個支援的平台的裝置註冊到 Intune。  </li>
</ul></li>
</ul></li>
<li>  在下列情況提供應用程式保護指導：
<ul>
<li>  針對每個支援的平台設定應用程式保護原則。  </li>
<li>  為受管理的應用程式設定條件式存取原則。  </li>
<li>  以先前所述的 MAM 原則針對適當的使用者群組。  </li>
<li>  使用受管理的應用程式使用方式報告。  </li>
</ul></li>
<li>  提供從舊版 PC 管理到 Intune MDM 的遷移指南。  </li>
</ul>
 
</li>
</ul>
  
<strong>雲端附加</strong>  

  我們將引導您完成 cloud-附上現有 Configuration Manager 環境與 Intune 的準備工作。 確切的步驟取決於您的來源環境。 這些步驟可能包括：  
<ul>
<li>  授權使用者。  </li>
<li>  利用內部部署 Active Directory 和雲端身分識別來設定 Intune 將使用的身分識別。  </li>
<li>  將使用者新增到您的 Intune 訂用帳戶、定義 IT 系統管理員角色，以及建立使用者和裝置群組。  </li>
<li>  提供指導方針設定混合式 Azure AD 聯結。  </li>
<li>  提供設定適用于 MDM 自動註冊之 Azure AD 的指導方針。  </li>
<li>  提供有關如何設定雲端管理閘道的指導方針，用作遠端網際網路型裝置管理的共同管理解決方案。  </li>
<li>  設定要切換到 Intune 的支援工作負載。  </li>
<li>  將 Configuration Manager 用戶端安裝在 Intune 中註冊的裝置。  </li>
</ul> 

<strong>安全地部署適用于 iOS 和 Android 的 Outlook mobile</strong> 我們可以提供指導方針，協助您在組織中安全地部署 Outlook mobile for iOS 和 Android，以確保您的使用者已安裝所有必要的應用程式。  
  使用 Intune 以安全方式部署 Outlook mobile for iOS 和 Android 的步驟，視您的來源環境而定。 它可以包含：
<ul>
<li>  透過 Apple App Store 或 Google Play Store，下載適用于 iOS 和 Android、Microsoft 驗證者及 Intune 公司入口網站應用程式的 Outlook。  </li>
<li>  提供有關設定的指導方針：
<ul>
<li>  適用于使用 Intune 的 iOS 和 Android、Microsoft 驗證者及 Intune 公司入口網站應用程式部署的 Outlook。  </li>
<li>  應用程式保護原則。  </li>
<li>  條件式存取原則。  </li>
<li>  應用程式佈建原則。  </li>
</ul></li>
</ul>  
  </td>
<td>  在規劃使用 Intune 部署無線網路和 VPN 設定檔時，IT 系統管理員必須具備實際執行環境中使用的憑證授權、無線網路和 VPN 基礎結構。  
  <strong>附注</strong>： FastTrack 服務權益不包括設定或設定憑證授權機構、無線網路、VPN 基礎結構或 Apple MDM push 憑證 for Intune 的協助。  
 
  <strong>附註</strong>: FastTrack 服務權益不包含協助將設定管理員站台伺服器或將設定管理員用戶端設定或升級，以滿足對支援雲端附加所需的最低需求。 請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。

  <strong>Intune 與 Microsoft Defender 進階威脅防護 (ATP) 整合</strong> 
 
  <strong>附注</strong>：我們會提供整合 Intune 與 MICROSOFT Defender ATP 的協助，並根據其 Windows 10 風險等級評估建立裝置規範原則。 我們不會提供有關購買、授權或啟用的協助。 請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。  
  
<strong>Windows Autopilot</strong> (英文) 
 
  IT 系統管理員需負責向組織註冊他們的裝置，方法是讓硬體廠商代表他們上傳或是自行上傳其硬體識別碼到 Windows Autopilot 服務。  
  
</td>
</tr>

<tr class="odd">
<td><strong>Office 365 進階威脅防護（ATP）</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  啟用安全連結、安全附件和防網路釣魚。  </li>
<li>  設定自動化、調查和回應。  </li>
<li>  使用攻擊模擬器。  </li>
<li>  報告和威脅分析。  </li>
</ul></td>
<td>除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<<table>
<thead>
<tr class="header">
<th><strong>服務</strong></th>
<th><strong>FastTrack 指引詳細資料</strong></th>
<th><strong>來源環境預期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  對於 Exchange Online，我們將引導您讓組織準備好使用電子郵件的程序。 具體步驟取決於來源環境和您的電子郵件遷移計畫。  
  我們提供下列專案的遠端指導：
<ul>
<li>  針對在 Office 365 中驗證的所有已啟用郵件的網域設定 Exchange Online Protection (EOP) 功能。  </li>
<li>  將郵件交換 (MX) 記錄指向 Office 365。  </li>
<li>  設定 Office 365 ATP 功能（如果是訂閱服務的一部分）。 如需詳細資訊，請參閱本表中的 <strong>Office 365 高級威脅防護</strong> 部分。  </li>
<li>  為 Office 365 中經驗證之所有已啟用郵件的網域設定資料遺失保護 (DLP) 功能，作為訂閱服務的一部分。將您的 MX 記錄指向 Office 365 之後即完成此項設定。</li>
<li>  為 Office 365 中經驗證之所有已啟用郵件的網域設定 Office 365 訊息加密 (OME) 功能，作為訂閱服務的一部分。將您的 MX 記錄指向 Office 365 之後即完成此項設定。</li>
</ul>
  <strong>附注：</strong> 信箱複寫服務 (MRS) 嘗試將 (IRM) 電子郵件從您的內部部署信箱遷移到對應的 Exchange Online 信箱。 在移轉之後，客戶必須將 Active Directory Rights Management Services (AD RMS) 範本複製到 Azure 版權管理服務 (Azure RMS)，才能讀取受保護的內容。  
<ul>
<li>  設定防火牆連接埠。  </li>
<li>  設定 DNS，包含必要的自動探索、寄件者原則框架 (SPF) 、DomainKeys 識別的郵件 (DKIM) 、以網域為基礎的郵件驗證、報告和一致性 (DMARC) 和 MX 記錄 (如有必要) 。  </li>
<li>  如果需要，則設定您的來源訊息環境與 Exchange Online 間的電子郵件流程。  </li>
<li>  進行從來源郵件環境到 Office 365 的郵件移轉。  </li>
<li>  設定信箱用戶端 (Outlook for Windows、Outlook 網頁版，以及 Outlook for iOS 和 Android)。  </li>
</ul>
  <strong>資料移轉</strong>  <br>
如需使用 FastTrack 將資料移轉至 Office 365 的優點的詳細資訊，請參閱 <a href="https://docs.microsoft.com/fasttrack/data-migration">資料移轉</a>。   
<td>  您的來源環境必須具有下列其中一個基本層級：
<ul>
<li>  含有 Exchange Server 2003 以上版本的單一或多個 Exchange 組織。  </li>
<li>  具備單一網際網路訊息存取通訊協定 (IMAP) 功能的電子郵件環境。  </li>
<li>  單一 G Suite 環境 (僅限 Gmail、連絡人和行事曆)。  </li>
<li>  如需多地理位置功能的詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online 中的多地理位置功能</a>。  </li>
</ul>
線上用戶端軟體（如 Office 365 的專案）、Outlook for Windows、Outlook for iOS 和 Android、商務同步處理用戶端、Power BI Desktop 和商務用 Skype 的 OneDrive，都必須在 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office 的系統需求</a>中所定義的最低層級。  </td>
</tr>
<tr class="even">
<td><strong>Microsoft 資訊控管</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  保留標籤和原則。  </li>
<li>  記錄管理。  </li>
<li>  刪除原則。  </li>
<li>  通訊合規性。  </li>
<li>  測試人員風險管理。  </li>
<li>  進階電子文件探索。  </li>
</ul>

  <strong>下列超出範圍 </strong>  
<ul>
<li> 記錄管理檔計畫的開發。</li>
<li> 資料連線器。</li>
<li> 資訊障礙。</li>
<li> 特殊許可權存取管理。</li>
<li> 在 SharePoint 中開發資訊架構。</li>
<li> 自訂腳本和編碼。</li>
</td>
<td>除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 資訊保護</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  資料分類。  </li>
<li>  敏感性資訊類型。  </li>
<li>  建立敏感度標籤。  </li>
<li>  套用敏感度標籤。  </li>
<li>  統一標籤。  </li>
<li>  可訓練的分類器。  </li>
<li>  使用內容總管和活動總管瞭解您的資料。  </li>
<li>  使用原則（手動和自動）發布標籤。  </li>
<li>  為 Microsoft Teams 聊天和頻道建立資料外洩防護 (data loss prevention (DLP)) 原則。  </li>
<li>  為 Windows 10 裝置建立端點 DLP 原則。  </li>
</ul>

<strong>下列超出範圍 </strong>  
<ul>
<li>客戶金鑰。</li>
<li>自訂正則運算式 (RegEx 機密資訊類型) 開發。</li>
<li>建立或修改關鍵字字典。</li>
<li>自訂腳本和編碼。</li>
</ul>
<strong>附注：</strong>如需詳細資訊，請參閱<a href="#enterprise-mobility--security">Enterprise 可移動性 + Security</a>中的<strong>Azure 資訊保護</strong>。
<ul>

</td>
<td>除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  確認 Exchange Online 中的最低需求、SharePoint 線上、Office 365 群組和 Azure AD 以支援小組。  </li>
<li>  設定防火牆連接埠。  </li>
<li>  設立 DNS。  </li>
<li>  確認您的 Office 365 租用戶上已啟用 Teams。  </li>
<li>  啟用或停用使用者授權。  </li>
<li>  小組網路評估：
<ul>
<li>  連接埠和端點檢查。  </li>
<li>  連線品質檢查。  </li>
<li>  頻寬估計。  </li>
</ul>
<ul>
<li>  設定小組應用程式原則 (小組 web app、小組桌面應用程式，以及 iOS 和 Android 應用程式) 的團隊。  </li>
</ul>
如果適用，我們也會提供下列專案的指引。。
<ul>
<li>  Microsoft 團隊會議室裝置：  </li>
<ul>
<li>  建立 <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams 裝置目錄</a>中列出的受支援電話和會議室裝置所需的線上帳戶。  </li>
<li>  遠端協助，包含已認證 Microsoft 團隊聊天室裝置的服務端設定。  </li>
<li>  啟用音訊會議：  </li>
<li>  會議橋接預設設定的組織設定。  </li>
<li>  對授權使用者會議橋接的指派。  </li>
</ul>
<li>  電話系統：
<ul>
<li>  雲端語音預設設定的組織設定。  </li>
<li>  通話方案指引 (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">可用市場</a>) ：
<ul>
<li>  授權使用者號碼的指派。  </li>
<li>  透過使用者介面 (UI) 的本機號碼移轉指引最多至 999。  </li>
<li>  本機號碼移轉服務要求 (SR) 支援超過 999。  </li>
</ul></li>
<li>  直接路由指引：
<ul>
<li>  組織安裝指導，以供協力廠商託管案例的直接路由設計，或最多10個網站的客戶部署案例。  </li>
<li> 會話邊界控制器 (SBC) 設定複查。 </li>

<li> 使用撥號對應表設定的遠端協助。 </li>

<li> 語音路由設定。</li>

<li> 媒體旁路和本機媒體優化。 </li>

</ul></li>
</ul></li>
<li>  啟用 Teams 即時活動。  </li>
<li>  組織設定與 Microsoft Stream 整合。  </li>
<li>  商務用 Skype to 小組的指導方針。  </li>
</ul></td>
<td><ul>
<li>  Azure AD for Office 365 中啟用的身分識別。  </li>
<li>  已啟用 SharePoint Online 的使用者。  </li>
<li>  Exchange 混合式設定) 中有 (線上和內部部署的 exchange 信箱。  </li>
<li>  啟用 Office 365 群組。  </li>
</ul>
  <strong>附注：</strong> 如果未使用 SharePoint 線上授權指派及啟用使用者，則在 Office 365 中不會有商務儲存 OneDrive。 檔案共用仍可在通道中運作，但是使用者無法在聊天時共用檔，但不 OneDrive Office 365 中的商務儲存。 團隊不支援內部部署 SharePoint。  <br>
  <strong>附注：</strong> 「理想」狀態是讓所有使用者將其信箱置於 Exchange Online。 在內部部署信箱的使用者，必須透過 Azure AD Connect，將其身分識別與 Office 365 目錄同步。 針對這些 Exchange 混合式客戶，如果使用者的信箱在內部部署中，使用者就無法新增或設定連接器。  
  Microsoft Teams Windows 安裝程式和 Mac 桌面用戶端可以從這裡下載：<a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>。  </td>
</tr>
<tr class="odd">
<td><strong>Office 365 進階威脅防護（ATP）</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  啟用安全連結、安全附件和防網路釣魚。  </li>
<li>  設定自動化、調查和回應。  </li>
<li>  使用攻擊模擬器。  </li>
<li>  報告和威脅分析。  </li>
</ul></td>
<td>除了<a href="#general">一般</a>的<strong>核心上架</strong>部分之外，沒有最低的系統需求。</td>
</tr>
<tr class="even">
<td><strong>Outlook for iOS 和 Android</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  從 Apple App Store 和 Google Play 下載 Outlook for iOS 和 Android。  </li>
<li>  設定帳戶並存取 Exchange Online 信箱。  </li>
<li>  保護 Outlook mobile (請參閱 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">在 Exchange Online 中保護 iOS 和 Android 的 outlook</a> 以取得詳細資訊) 。  </li>
</ul></td>
<td><ul>
<li>  Azure AD for Office 365 中啟用的身分識別。  </li>
<li>  已設定 Exchange Online 並指派授權。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  指派 Power BI 的授權。  </li>
<li>  部署 Power BI Desktop 應用程式。  </li>
</ul></td>
<td>線上用戶端軟體（如 Power BI Desktop）必須具備 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</td>
</tr>
<tr class="even">
<td><strong>Microsoft Project Online</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  確認 Microsoft Project Online 依賴的基本 SharePoint 功能。  </li>
<li>  將 Microsoft Project Online 服務新增到您的租用戶中 (包括新增使用者的訂閱)。  </li>
<li>  設定企業資源資料庫​​ (ERP)。  </li>
<li>  建立您的第一個專案。  </li>
</ul></td>
<td>線上用戶端軟體（如 365 Office 的專案）必須至少是 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</td>
</tr>
<tr class="odd">
<td><strong>Project Online 專業版和 Premium</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  解決部署問題。  </li>
<li>  使用 Microsoft 365 系統管理中心和 Windows PowerShell 指派使用者授權。  </li>
<li>  使用隨選即用從 Office 365 入口網站安裝 Project Online 桌面用戶端。  </li>
<li>  使用 Office 365 部署工具來設定更新設定。  </li>
<li>  設定 Project Online 桌面用戶端的單一內部網站發佈伺服器，包含建立搭配 Office 365 部署工具使用之 configuration.xml 檔案的相關協助。  </li>
<li>  正在將 Project Online 桌面用戶端連線至 Project Online 專業版或 Project Online 進階版。  </li>
</ul></td>
<td>線上用戶端軟體（如 365 Office 的專案）必須至少是 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online 和商務用 OneDrive</strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  設立 DNS。  </li>
<li>  設定防火牆連接埠。  </li>
<li>  佈建使用者和授權。  </li>
<li>啟用 SharePoint Online 管理員的網站架設。</li>
<li>規劃網站集合。</li>
<li>保護內容與管理權限。</li>
<li>設定 SharePoint Online 功能。</li>
<li>  設定 SharePoint 混合式功能，如混合式搜尋、混合式網站、混合式分類、內容類型、混合式自助網站架設 (僅限 SharePoint Server 2013)、擴充的應用程式啟動器、混合式商務用 OneDrive，以及外部網路網站。  </li>
<li>  您的遷移方法。  </li>
</ul>
根據您的 SharePoint 版本，針對 Business OneDrive 提供其他指導方針，如下所示：
<ul>
<li>  識別整合選項，並複查內部部署和線上網路基礎結構和頻寬。  </li>
<li>  安裝 SharePoint Online 2013 SP1 (（如果適用）) 、規劃及執行同步和身分識別需求，以及識別您的 Business sync 用戶端 OneDrive。  </li>
<li>  為所有使用者規劃及實施單一推廣 (或分階段的展示) 。  </li>
<li>  指派授權、將「我的網站」和個人文件庫重新導向至 Office 365 (適用于 SharePoint 線上 2013) ，設定物件，以控制 OneDrive (SharePoint Online 2013) 的存取權。  </li>
<li>在 OneDrive 中重新導向或移動已知的資料夾。</li>
<li>  部署商務用戶端同步處理的 OneDrive。  </li>
</ul>
  <strong>資料移轉</strong>  <br>
如需使用 FastTrack 將資料移轉至 Office 365 的優點的詳細資訊，請參閱 <a href="https://docs.microsoft.com/fasttrack/data-migration">資料移轉</a>。
</ul></td>
<td><br><strong>SharePoint 混合：</strong>  
<ul>
<li>  SharePoint 混合式設定包括設定混合式搜尋、網站、分類法、內容類型、商務 OneDrive、擴充的應用程式啟動器、外部網路網站，以及從內部部署至單一目標 SharePoint 線上環境的自助網站架設。  </li>
</ul>
  <strong>附注：</strong> 自助網站架設不在執行 SharePoint 2013 的內部部署伺服器範圍內。  
<ul>
<li>  若要啟用 SharePoint 混合式，您必須具有下列其中一個內部部署 SharePoint 伺服器環境：2013、2016或2019。  </li>
</ul>
  <strong>附注：</strong> SharePoint 伺服器的內部部署 SharePoint 環境升級為不在範圍內。 請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。 如需詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint 混合式功能的最小公用更新層級</a><em>。</em>  <br>
  <strong>附注：</strong> 如需多地理位置功能的詳細資訊，請參閱 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365 中 OneDrive 和 SharePoint Online 中的多地理位置功能</a><em>。</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
我們提供啟用 Yammer Enterprise 服務的遠端指導方針。  
</ul></td>
<td>線上用戶端軟體必須具備 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系統需求</a>中所定義的最低層級。</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security

<table>
<thead>
<tr class="header">
<th><strong>服務</strong></th>
<th><strong>FastTrack 指引詳細資料</strong></th>
<th><strong>來源環境預期</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></td>
<td>  在下列情況下，我們會提供遠端指導來保護您的雲端身分識別。  

 <br/>

<strong>安全基礎結構</strong>  </ul>
<ul>
<li>  針對您的身分識別設定和啟用強驗證，包括使用 Azure Multi-Factor 驗證 (MFA)  (雲端僅) 、Microsoft 驗證者應用程式，以及 Azure MFA 和自助密碼重設的組合註冊 (SSPR) 。  </li>
<li>  若為非 Azure AD Premium 客戶，會提供指導方針，以利用安全性預設值來保護您的身分識別。  </li>
<li>  針對 Azure AD premium 客戶，提供指導方針以條件式存取來保護您的身分識別。  </li>
<li>  使用 Azure AD 密碼保護偵測和封鎖弱密碼的使用。  </li>
<li>  使用 Azure AD 應用程式 Proxy，保護內部部署 web 應用程式的遠端存取。  </li>
<li>  使用 Azure 身分識別保護來啟用風險型偵測和修正。  </li>
<li>  啟用自訂的登入畫面，包括徽標、文字和具有自訂商標的影像。  </li>
<li>  使用 Azure AD B2B 與來賓使用者安全地共用應用程式和服務。  </li>
<li>  使用以角色為基礎的存取控制來管理 Office 365 系統管理員的 access (RBAC) 內建管理角色，以及減少特權系統管理員帳戶數目。  </li>
<li>  設定混合式 Azure AD 聯結。  </li>
<li>  設定 Azure AD 聯結。  </li>
</ul>
  
<strong>監視與報告</strong>  
<ul>
<li>  
  使用 Azure AD Connect Health，啟用適用于 AD FS、Azure AD Connect 和網域控制站的遠端監控。  
  </li>
</ul>
  
<strong>治理</strong>  
<ul>
<li>  
  使用 Azure AD 版權管理來管理 Azure AD 身分識別和存取生命週期。
  </li>
<li>  
  使用 Azure AD access 評論管理 Azure AD 群組成員資格、企業應用程式存取和角色指派。  
  </li>
<li>  
  檢查 Azure AD 使用條款。  
  </li>
<li>  
  使用 Azure AD 特權身分識別管理來管理和控制版權管理帳戶的存取。  
  </li>
</ul>
  
<strong>自動化和效率 </strong>  
<ul>
<li>  
  啟用 Azure AD SSPR。  
  </li>
<li>  讓使用者能夠使用 Azure AD 自助群組管理來建立及管理自己的雲端安全性或 Office 365 群組。  </li>
<li>  使用 Azure AD 委派的群組管理來管理企業應用程式的委派存取權。  </li>
<li>  啟用 Azure AD 動態群組。  </li>
<li>  使用集合在「我的應用程式入口網站」中組織應用程式。  </li>
</ul></td>
<td>已針對 Azure AD Premium 準備內部部署 Active Directory 及其環境，包括修正已識別的問題，以防止與 Azure AD 和 Azure AD Premium 功能整合。</td>
</tr>
<tr class="odd">
<td><strong>Azure 資訊保護 </strong></td>
<td>  我們提供下列專案的遠端指導：
<ul>
<li>  啟用並設定您的租使用者。  </li>
<li>  建立及設定標籤和原則。  </li>
<li>  將資訊保護套用至文件。  </li>
<li>  在 Windows 上執行的 Office 應用程式中，使用 Azure 資訊保護用戶端自動分類資訊並加上標籤 (例如 Word、PowerPoint、Excel 和 Outlook)。  </li>
<li>  使用 Azure 資訊保護掃描程式，在 rest 上探索及標記檔案。  </li>
<li>  使用 Exchange Online 郵件流程規則監視傳輸中的電子郵件。  </li>
</ul>
如果您想要使用 Microsoft Azure Rights Management Services 來套用保護，我們也會提供指導方針。 (Azure RMS) ，Office 365 Message Encryption (OME) ，以及資料遺失防護 (DLP) 。  </td>
<td>  客戶必要的責任包括：
<ul>
<li>  要掃描的檔案共用位置清單。  </li>
<li>  已核准的分類分類。 </li>
<li> 瞭解有關金鑰管理的任何法規限制或需求。  </li>
<li>  為您的內部部署 Active Directory 建立且與 Azure AD 同步處理的服務帳戶。 </li>
<li>  針對分類及保護所設定的標籤。 </li>
<li> Azure 資訊保護掃描程式的所有必要條件皆已到位。 如需詳細資訊，請參閱 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">安裝及部署 Azure 資訊保護統一標記掃描器的必要條件</a>。 </li>
<li>  請確定使用者裝置執行的是支援的作業系統，且已安裝必要的必要條件。 如需詳細資訊，請參閱下列各項。</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">系統管理員指南：安裝 Azure 資訊保護統一標籤用戶端以供使用者</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">IOS 或 Android 的 Azure 資訊保護應用程式為何？</a>  </li>
</ul>
<li> 安裝和設定 Azure RMS 連接器和伺服器（包括 Active Directory RMS (AD RMS) 連接器）以進行混合支援。  </li>
<li> 安裝和設定會將您自己的金鑰 (BYOK) 、雙金鑰加密 (DKE)  (整合標籤用戶端) ，或是只保留您自己的金鑰 (HYOK)  (經典用戶端您應該在部署中的其中一個選項。  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  我們為您的應用程式和裝置提供準備使用 Intune 做為雲端型行動裝置管理 (MDM) 和行動應用程式管理 (MAM) 提供者的遠端指南。 確切的步驟取決於您的來源環境，而且是根據您的行動裝置和行動裝置應用程式管理需求。 步驟可能包括：
<ul>
<li>  授權使用者。  </li>
<li>  利用您的內部部署 Active Directory 或雲端身分識別 (Azure AD) 設定供 Intune 使用的身分識別。  </li>
<li>  將使用者新增到您的 Intune 訂用帳戶、定義 IT 系統管理員角色，以及建立使用者和裝置群組。  </li>
<li>  根據您的管理需求，設定您的 MDM 授權機構，包括：
<ul>
<li>  當 Intune 為您唯一的 MDM 解決方案時，將 Intune 設定為 MDM 授權單位。  </li>
</ul></li>
<li>  為下列提供 MDM 指引：
<ul>
<li>  設定用於驗證 MDM 管理原則的測試群組。  </li>
<li>  設定 MDM 管理原則和服務，例如：
<ul>
<li>  透過網頁連結或深層連結，為每個支援的平臺部署應用程式。  </li>
<li>  條件式存取原則。  </li>
<li>  如果您的組織中有現有的憑證授權單位、無線網路或 VPN 基礎結構，則部署電子郵件、無線網路和 VPN 設定檔。  </li>
<li>  連接至 Intune 資料倉儲。  </li>
<li>  整合 Intune 與：
<ul>
<li>  小組檢視器針對遠端協助 (需要) 小組檢視器訂閱。  </li>
<li>  行動威脅防護 (MTD) 協力廠商解決方案 (必須) 的 MTD 訂閱。  </li>
<li>  需要)  (電信費用管理解決方案的電訊費用管理解決方案。  </li>
</ul></li>
<li>  將每個支援的平台的裝置註冊到 Intune。  </li>
</ul></li>
</ul></li>
<li>  在下列情況提供應用程式保護指導：
<ul>
<li>  針對每個支援的平台設定應用程式保護原則。  </li>
<li>  為受管理的應用程式設定條件式存取原則。  </li>
<li>  以先前所述的 MAM 原則針對適當的使用者群組。  </li>
<li>  使用受管理的應用程式使用方式報告。  </li>
</ul></li>
<li>  提供從舊版 PC 管理到 Intune MDM 的遷移指南。  </li>
</ul>
  
</li>
</ul>
  
<strong>雲端附加</strong>  

  我們將引導您完成 cloud-附上現有 Configuration Manager 環境與 Intune 的準備工作。 確切的步驟取決於您的來源環境。 這些步驟可能包括：  
<ul>
<li>  授權使用者。  </li>
<li>  利用內部部署 Active Directory 和雲端身分識別來設定 Intune 將使用的身分識別。  </li>
<li>  將使用者新增到您的 Intune 訂用帳戶、定義 IT 系統管理員角色，以及建立使用者和裝置群組。  </li>
<li>  提供指導方針設定混合式 Azure AD 聯結。  </li>
<li>  提供設定適用于 MDM 自動註冊之 Azure AD 的指導方針。  </li>
<li>  提供有關如何設定雲端管理閘道的指導方針，用作遠端網際網路型裝置管理的共同管理解決方案。  </li>
<li>  設定要切換到 Intune 的支援工作負載。  </li>
<li>  將 Configuration Manager 用戶端安裝在 Intune 中註冊的裝置。  </li>
</ul> 

<strong>安全地部署適用于 iOS 和 Android 的 Outlook mobile</strong> 我們可以提供指導方針，協助您在組織中安全地部署 Outlook mobile for iOS 和 Android，以確保您的使用者已安裝所有必要的應用程式。  
  使用 Intune 以安全方式部署 Outlook mobile for iOS 和 Android 的步驟，視您的來源環境而定。 它可以包含：
<ul>
<li>  透過 Apple App Store 或 Google Play Store，下載適用于 iOS 和 Android、Microsoft 驗證者及 Intune 公司入口網站應用程式的 Outlook。  </li>
<li>  提供有關設定的指導方針：
<ul>
<li>  適用于使用 Intune 的 iOS 和 Android、Microsoft 驗證者及 Intune 公司入口網站應用程式部署的 Outlook。  </li>
<li>  應用程式保護原則。  </li>
<li>  條件式存取原則。  </li>
<li>  應用程式佈建原則。  </li>
</ul></li>
</ul>  
  </td>
<td>  在規劃使用 Intune 部署無線網路和 VPN 設定檔時，IT 系統管理員必須具備實際執行環境中使用的憑證授權、無線網路和 VPN 基礎結構。  
  <strong>附注</strong>： FastTrack 服務權益不包括設定或設定憑證授權機構、無線網路、VPN 基礎結構或 Apple MDM push 憑證 for Intune 的協助。  
 
  <strong>附註</strong>: FastTrack 服務權益不包含協助將設定管理員站台伺服器或將設定管理員用戶端設定或升級，以滿足對支援雲端附加所需的最低需求。 請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。

  <strong>Intune 與 Microsoft Defender 進階威脅防護 (ATP) 整合</strong> 
 
  <strong>附注</strong>：我們會提供整合 Intune 與 MICROSOFT Defender ATP 的協助，並根據其 Windows 10 風險等級評估建立裝置規範原則。 我們不會提供有關購買、授權或啟用的協助。 請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得協助。  
  
<strong>Windows Autopilot</strong> (英文) 
 
  IT 系統管理員需負責向組織註冊他們的裝置，方法是讓硬體廠商代表他們上傳或是自行上傳其硬體識別碼到 Windows Autopilot 服務。  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>服務</strong></th>
<th><strong>FastTrack 指引詳細資料</strong></th>
<th><strong>來源環境預期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  我們提供將 Windows 7 Professional 和 Windows 8.1 專業版升級至 Windows 10 企業版的指導方針。  
  我們提供下列專案的遠端指導：
<ul>
<li>  瞭解您的 Windows 10 意圖。  </li>
<li>  評估來源環境和需求 (確定 Microsoft 端點 Configuration Manager 已升級至所需的層級，以支援 Windows 10 部署) 。  </li>
<li>  使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 部署 Windows 10 企業版和 Microsoft 365 應用程式。  </li>
<li>  建議您評估 Windows 10 應用程式的選項。  </li>
<li>  啟用桌面 analytics 的使用，以及建立桌面分析部署計畫的指導方針。  </li>
<li>  Microsoft 365 應用程式相容性評估的方式是利用 Configuration Manager 中的 Office 365 準備儀表板，或搭配 Office 的獨立準備人工具組，以及部署 Microsoft 365 應用程式的協助。  </li>
<li>  針對成功部署的最低需求，建立修復檢查清單，以達到您需要執行的動作。  </li>
<li>  在 Windows 10 企業版滿足必要的裝置硬體需求時，提供現有裝置的升級指導方針。  </li>
<li>  提供升級指導以支援現有的部署動作。 FastTrack 會建議並提供 Windows 10 就地升級的指引。 也提供 Windows 全新映像安裝和 Windows Autopilot 部署案例的指引。  </li>
<li>  使用 Configuration Manager 部署 Microsoft 365 應用程式做為 Windows 10 部署的一部分。   </li>
<li>  提供指導方針，以協助您的組織使用您現有的 Configuration Manager 環境或 Microsoft 365 來保持最新的 Windows 10 企業版和 Microsoft 365 應用程式。  </li>
</ul>
  <strong>下列超出範圍 </strong>  
<ul>
<li>  將 Configuration Manager 升級至最新分支。  </li>
<li>  建立適用於 Windows 10 部署的自訂映像。  </li>
<li>  建立及支援 Windows 10 部署的部署指令碼。  </li>
<li>  將 Windows 10 系統從 BIOS 轉換為整合可延伸韌體介面 (UEFI)。  </li>
<li>  啟用 Windows 10 的安全性功能。  </li>
<li>  將 Windows 部署服務 (WDS) 設定為開機前執行環境 (PXE) 啟動。  </li>
<li>  使用 Microsoft Deployment Toolkit (MDT) 來擷取及部署 Windows 10 映像。  </li>
<li>  使用使用者狀態移轉工具 (USMT)  </li>
</ul>
請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。  </td>
<td>  若要升級電腦，您必須符合下列需求：
<ul>
<li>  來源作業系統： Windows 7 Enterprise or Professional，Windows 8.1 Enterprise or Professional。  </li>
<li>  裝置：桌面、筆記本或平板電腦板型。  </li>
<li>  目標作業系統：視窗10企業版。  </li>
</ul>
若要升級基礎結構，您必須符合以下需求：
<ul>
<li>  Microsoft 端點 Configuration Manager。  </li>
<li>  Windows 10 目標版本必須支援 Configuration Manager 版本。 如需詳細資訊，請參閱位於<a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager 對於 Windows 10 的支援</a>的 Configuration Manager 支援表格。  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender 進階威脅防護 (ATP)</strong></td>
<td>  Microsoft Defender 進階威脅防護 (ATP) 是一個平台，其設計訴求是要協助企業網路預防、偵測、調查及回應進階威脅。  
  我們提供下列專案的遠端指導：
<ul>
<li>  部署技術以保護您的端點。  </li>
<li>  設定 endpoint protection 和裝置限制設定檔。  </li>
<li>  評估 OS 版本和裝置管理 (包括 Intune、Microsoft Endpoint Configuration Manager、群組原則物件 (Gpo) 和協力廠商設定) 以及 Windows Defender AV 服務或其他端點安全性軟體的狀態。  </li>
<li>  評估 Windows AV 服務或其他端點安全性軟體的狀態。  </li>
<li>  評估代理及防火牆，以限制網路流量。  </li>
<li>  透過說明如何使用板載端點部署 ATP 代理程式設定檔，啟用 Microsoft Defender ATP 服務。  </li>
<li>  部署指導方針、設定協助及教育：
<ul>
<li>  
  威脅與弱點管理。  
  </li>
<li>  
  縮小攻擊面。  
  </li>
<li>  
  新一代防護。  
  </li>
<li>  
  端點偵測及回應。  
  </li>
<li>  
  自動化調查與補救措施。  
  </li>
<li> 需要) microsoft Defender ATP (Windows E5 或 Microsoft 365 E5 授權。  </li>
<li>  
  安全分數。  
  </li>
</ul></li>
<li>  查看模擬與示教 (例如練習案例、虛假惡意程式碼和自動調查) 。  </li>
<li>  報表和威脅分析功能的概覽。  </li>
<li>  整合 Office 365 ATP 和 Microsoft Defender ATP。  </li>
<li>  提供 Microsoft Defender 資訊安全中心入口網站的逐步指引。  </li>
<li>  下列作業系統：
<ul>
<li>  
  Windows 10。  
  </li>
<li>  
  Windows Server 2016。  
  </li>
<li>  
  Windows Server 2019。  
  </li>
<li>  
  Windows Server 2019 Core Edition。  
  </li>
<li>  
  Windows Server Semi-Annual 通道 (SAC) 版本1803。  
  </li>
<li>  
  macOS 版本10.13、10.14 及10.15。  
  </li>
</ul>
</li>
</ul>
<strong>附注：</strong> 所有 Windows Server 版本都必須由最新版的 System Center Configuration Manager 2012 (版本 1012 R2、1511或 1602) 或 Microsoft Endpoint Configuration Manager (版本2002或更高版本) 。 

</li>
</ul>

<strong>下列超出範圍 </strong>  
<ul>
<li>  客戶修正活動的專案管理。  </li>
<li>  現場支援。  </li>
<li>  持續性管理和威脅因應。  </li>
<li>  下列 Microsoft Defender ATP 代理程式的上線或組態：
<ul>
<li>  
  Windows Server 2008。  
  </li>
<li>  
  Windows Server 2012。  
  </li>
<li>  
  Linux。  
  </li>
<li>  
  移動裝置 (Android 和 iOS) 。  
  </li>
</ul></li>
<li>  伺服器上架及設定：
<ul>
<li>  
  設定離線通訊的 proxy 伺服器。  
  </li>
<li>  
  設定下層 Configuration Manager 實例和版本的 Configuration Manager 部署套件。  
  </li>
<li>  
  將伺服器上架至 Azure 的安全性中心。  
  </li>
<li>  
  未由 Configuration Manager 管理的伺服器。  
  </li>
</ul></li>
<li>  macOS 上架及設定：
<ul>
<li>  
  手動以 Intune 為基礎的部署。  
  </li>
<li>  
  以 JAMF 為基礎的部署。
  </li>
<li>  
  其他行動裝置管理 (MDM) 以產品為基礎的部署。  
  </li>
<li>  
  手動部署。  
  </li>
</ul></li>
<li>  設定以下能縮小攻擊面的功能：
<ul>
<li>  
  硬體隔離。  
  </li>
<li>  
  應用程式控制。  
  </li>
<li>  
  入侵防護。  
  </li>
<li>  
  網路防火牆。  
  </li>
</ul></li>
<li>  註冊或設定 Microsoft 威脅專家。  </li>
<li>  設定或訓練檢查 API 或安全性資訊和事件管理 (SIEM) 連接。  </li>
<li>  註冊或設定 Microsoft 威脅防護 (MTP)。  </li>
<li>  涵蓋進階搜尋功能的訓練或指導方針。  </li>
<li>  訓練或指引涵蓋使用或建立 Kusto 查詢。</li>
</li>
</ul>
請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Windows 虛擬桌面

<table>
<thead>
<tr class="header">
<th><strong>服務</strong></th>
<th><strong>FastTrack 指引詳細資料</strong></th>
<th><strong>來源環境預期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 虛擬桌面</strong></td>
<td><p>我們為上架至 Windows Virtual Desktop 提供部署指導 (桌面和應用程式虛擬化服務) 。 Windows 虛擬桌面利用 Windows 10 多會話體驗，並針對使用 Microsoft 365 的整合式安全性和管理，針對適用于企業的 Microsoft 365 應用程式進行優化。</p>
<p>我們提供下列專案的遠端指導：</p>
<ul>
<li>使用下列各項部署 Windows 虛擬桌面環境與 Windows 10 企業版的多重會話和 Microsoft 365 應用程式（適用于企業）：
<ul>
<li>Azure Marketplace 影像。</li>
<li>共用圖像。</li>
<li>Office 部署工具組 (ODT) 。</li>
</ul></li>
<li>設定 FSLogix：
<ul>
<li>使用設定檔容器部署 FSLogix 代理程式。</li>
<li>使用 Office 容器部署 FSLogix 代理程式。</li>
<li>使用內容排除設定 FSLogix 資料夾。</li>
</ul></li>
<li>部署 Microsoft Edge。</li>
<li>部署 Microsoft 團隊。</li>
<li>使用 Windows 虛擬桌面用戶端連接。</li>
</ul>

<strong>下列超出範圍</strong>
<ul>
<li>客戶 Windows 虛擬桌面部署的專案管理。</li>
<li>協力廠商應用程式虛擬化和部署。</li>
<li>自訂圖像。</li>
<li>涉及 VMware 和 Citrix 的遷移和案例。</li>
<li>Linux 案例。</li>
<li>轉換或遷移使用者設定檔。</li>
</ul>
請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。</td>
<td>您應該已經具備下列專案：
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows 虛擬桌面授權的需求</a>。</li>
<li>Azure 網路：
<ul>
<li>虛擬網路 (VNET) 建立及子網。</li>
<li>防火牆和網路安全性群組。</li>
<li>VPN 和 ExpressRoute。</li>
<li>從內部部署路由傳送至 Azure。</li>
<li>允許連線至 Windows 虛擬桌面的防火牆規則。
</ul>
如需詳細資訊，請參閱 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> 支援的遠端桌面用戶端</a>。
</ul>
<ul><li>Azure AD 一般設定：
<ul>
<li>身分識別策略 <i> (您只能使用下列三個選項) 中的其中一項：</i>
<ul>
<li>Azure 中使用 Azure AD Connect 的 Active Directory。</li>
<li>使用 Azure AD 的 Active Directory Connect over VPN 或 ExpressRoute 的內部部署。</li>
<li>Active Directory 網域服務 (AD DS) 。</li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a>應用程式保證


<table>
<thead>
<tr class="header">
<th><strong>服務</strong></th>
<th><strong>FastTrack 指引詳細資料</strong></th>
<th><strong>來源環境預期</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>應用程式保證</strong></td>
<td>  應用程式保證是一種服務，旨在解決 Windows 10 和 Microsoft 365 應用程式相容性的問題。 當您要求 App 保證服務時，我們會與您合作，以免費處理有效的應用程式問題，不需要您購買合格的訂閱。 我們也會針對在部署 Windows 虛擬桌面和 Microsoft Edge 時面臨相容性問題的客戶，提供指導，並為解決相容性問題提供各種合理的努力。 我們會為下列 Microsoft 產品上部署的應用程式提供修正協助：
<ul>
<li>  <strong>Windows 10 </strong> (包括 ARM64 裝置) </li>
<li> <strong>Microsoft 365 應用程式</strong>  </li>
<li>  <strong>Microsoft Edge-</strong> 如需部署指導，請參閱 <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Microsoft Edge 通道概述</a>。  </li>
<li>  <strong>Windows 虛擬桌面</strong> - 如需詳細資訊，請參閱 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">何謂 Windows Virtual Desktop？</a> 和 <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 企業版多會話常見問題</a>。  </li>
</ul>

<strong>下列超出範圍 </strong>  
<ul>
<li>  應用程式清查和測試，以判斷可否在 Windows 10 和 Microsoft 365 Apps 上運作。 如需有關此程序的詳細指示，請瀏覽<a href="https://go.microsoft.com/fwlink/?linkid=2080140">電腦部署中心</a>。 如果您對於深入的升級整備評估有興趣，請填寫<a href="https://go.microsoft.com/fwlink/?linkid=2053818">客戶要求現代化電腦評估</a>表單。</li>
<li>  針對 Windows 10 相容性和支援狀態，研究第三方 ISV 應用程式。 如需詳細資訊，請參閱<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">電腦分析</a>。</li>
<li>僅限應用程式封裝的服務。 不過，應用程式保證小組會將我們針對 Windows 10 修復的應用程式封裝起來，以確保這些應用程式可以在客戶的環境中部署。</li>
</ul>

<strong>客戶責任包括</strong>  
<ul>
<li>  建立應用程式清查。</li>
<li>  在 Windows 10 和 Microsoft 365 Apps 上驗證這些應用程式。</li>
</ul>
<strong>附注：</strong>  Microsoft 無法對您的原始程式碼進行變更。 不過，應用程式保證小組可以在原始程式碼適用於您的應用程式時，為應用程式開發人員提供指導方針。 


  請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。  </td>

</td>
<td><strong>Windows 10 和 Microsoft 365 應用程式</strong>
<ul>
<li>  
  可在 Windows 7、Windows 8.1、Office 2010 和 Office 2013 中執行的應用程式也適用於 Windows 10 和 Microsoft 365 Apps。  
  </li>
</ul>
<strong>ARM 上的 Windows 10</strong>
<ul>
<li>  
在 Windows 7、Office 2010 或更新版本上運作的應用程式也可在 ARM64 裝置上的 Windows 10 和 Microsoft 365 應用程式上運作。 
  </li>
</ul>
  <strong>注意：</strong> 
<ul>
<li> 在參與 Windows 預覽人員 <a href="https://insider.windows.com/">計畫</a>的客戶預覽中，可使用 x64 (64 位) 模擬。  </li>
<li>  
 針對 Windows 10 版本2004上的非 Windows 有問必答客戶 (或更新版本) ，使用 <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL 和 OpenGL 相容性套件</a>支援 ARM64 Photoshop。 
  </li>
<li>  
  Windows 預覽體驗計畫中的客戶可以下載 OpenCL 和 OpenGL 相容性套件的有問必答版本，以與其他應用程式搭配使用。    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  如果您的 web 應用程式或網站在 Internet Explorer 11、支援的 Google Chrome 或任何版本的 Microsoft edge 中運作，也會與 Microsoft Edge 搭配使用。  
  </li>
<li>  
  當網頁不斷演變時，請務必查看此已發佈的已知 <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">網站相容性清單-Microsoft Edge 的變更</a>。  
  </li>
</ul>
  <strong>Windows 虛擬桌面 </strong>  
<ul>
<li>  
  在 Windows Server 遠端桌面工作階段主機 (RDSH) 上執行的虛擬化應用程式，也能隨著 Windows 虛擬桌面的一部分在 Windows 10 企業版多重工作階段上執行。  
  </li>
<li>  
  在任何 Windows 7 或 Windows 10 虛擬桌面基礎結構上執行的應用程式 (VDI) 環境也會在 windows 7 企業版和 Windows 10 Enterprise 上執行，成為 Windows 虛擬桌面的一部分。  
  </li>
<li>  
  在 Windows 7 或 Windows 10 用戶端裝置上執行的應用程式，也能隨著 Windows 虛擬桌面的一部分在 Windows 7 企業版和 Windows 10 企業版上執行。  
  </li>
</ul>
  <strong>附注：</strong> Windows 10 企業版多會話相容性排除和限制包括：
<ul>
<li>  
  有限的硬體重新導向。  
  </li>
<li>  
  A/V 密集型應用程式可能會以降低的容量執行。  
  </li>
<li>  
  64 位元 Windows 虛擬桌面不支援 16 位元應用程式。  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a>Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>服務</strong></th>
<th><strong>FastTrack 指引詳細資料</strong></th>
<th><strong>來源環境預期</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td>Windows 10 企業版客戶的<strong>Microsoft Edge</strong> () </td>
<td><ul>
<li>  我們會為下列專案提供遠端部署指導和相容性協助：在 Windows 10 企業版上使用 Microsoft 端點管理員 (Microsoft 端點 Configuration Manager 或 Intune) 部署 Microsoft Edge。  </li>
<li>  Microsoft Edge 設定 (使用群組原則或 Intune 應用程式設定和應用程式原則) 。  </li>
<li>  清點可能需要在 Internet Explorer 模式中使用的網站清單。  </li>
<li>  啟用具有現有企業網站清單的 Internet Explorer 模式。  
  此外，如果您有可搭配 Internet Explorer 或 Google Chrome 使用的 web 應用程式或網站，且您遇到相容性問題，我們會提供指引來解決問題，而不需額外收費。 如需詳細資訊，請參閱 <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">應用程式</a> 。  </li>
</ul>

<strong>下列超出範圍 </strong>  
<ul>
<li>客戶的 Microsoft Edge 部署的專案管理。</li>
<li>  現場支援。</li>

</td>
<td></td>
</tr>
</tbody>
</table>
