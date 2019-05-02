---
title: 來源環境預期
description: 使用 FastTrack Center 權益 ems 來源環境需求
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a512e97f48df7fc3040478f4e35fe0c357ef7ce3
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513148"
---
# <a name="source-environment-expectations"></a><span data-ttu-id="05097-103">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="05097-103">Source Environment Expectations</span></span>

<span data-ttu-id="05097-104">當您要準備好使用 Microsoft Azure Active Directory 進階版、 Microsoft Intune 和 Azure 資訊保護使用[用於 Enterprise Mobility + Security (EMS) 的 FastTrack Center 權益](EMS-fasttrack-benefit-for-EMS.md)時，您的環境必須符合預期下列各節所述。</span><span class="sxs-lookup"><span data-stu-id="05097-104">When you use the [FastTrack Center Benefit for Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) to get Microsoft Azure Active Directory Premium, Microsoft Intune, and Azure Information Protection ready for use, your environment needs to meet the expectations described in the following sections.</span></span>

<span data-ttu-id="05097-105">您可能已經有您想要整合與 Enterprise Mobility + Security (EMS) 或任何使用透過單一主控台的豐富型身分識別管理其個別服務的組織中的內部部署 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="05097-105">You may already have on-premises Active Directory in your organization that you want to integrate with Enterprise Mobility + Security (EMS) or any of its individual services that uses rich identity management from a single console.</span></span> <span data-ttu-id="05097-106">適用於 Enterprise Mobility + Security (EMS) 的 FastTrack 中心權益包含協助您與您現有的內部部署 Active Directory 環境整合 Azure Active Directory。</span><span class="sxs-lookup"><span data-stu-id="05097-106">The FastTrack Center Benefit for Enterprise Mobility + Security (EMS) includes helping you integrate Azure Active Directory with your existing on-premises Active Directory environment.</span></span>

<span data-ttu-id="05097-107">下表顯示登入您現有來源環境預期。</span><span class="sxs-lookup"><span data-stu-id="05097-107">The following table shows expectations for your existing source environment for on-boarding.</span></span>

|<span data-ttu-id="05097-108">Activity</span><span class="sxs-lookup"><span data-stu-id="05097-108">Activity</span></span>|<span data-ttu-id="05097-109">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="05097-109">Source environment expectation</span></span>|
|------------|----------------------------------|
|<span data-ttu-id="05097-110">核心登入</span><span class="sxs-lookup"><span data-stu-id="05097-110">Core on-boarding</span></span>|<span data-ttu-id="05097-111">Active Directory 樹系，功能樹系層級設定至 Windows Server 2008 以上，使用下列樹系組態：</span><span class="sxs-lookup"><span data-stu-id="05097-111">Active Directory forests with the functional forest level set to Windows Server 2008 or above, with the following forest configuration:</span></span><br /><br /><span data-ttu-id="05097-112">-單一 Active Directory 樹系</span><span class="sxs-lookup"><span data-stu-id="05097-112">-   Single Active Directory forest</span></span><br /><span data-ttu-id="05097-113">對多個 Active Directory 樹系</span><span class="sxs-lookup"><span data-stu-id="05097-113">-   Multiple Active Directory forests</span></span> </br></br><span data-ttu-id="05097-114">**附註**： 對於所有多重樹系組態，Active Directory Federation Services (AD FS) 部署是在 FastTrack Center 權益的範圍。</span><span class="sxs-lookup"><span data-stu-id="05097-114">**Note**: For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope for the FastTrack Center Benefit.</span></span>|
|<span data-ttu-id="05097-115">Azure AD Premium 登入</span><span class="sxs-lookup"><span data-stu-id="05097-115">Azure AD Premium on-boarding</span></span>|<span data-ttu-id="05097-116">Azure AD Premium，其中包含已識別的問題，導致與 Azure AD 整合的補救已經準備內部部署 Active Directory 和其環境與 Azure AD Premium 功能。</span><span class="sxs-lookup"><span data-stu-id="05097-116">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, which includes remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span>|
|<span data-ttu-id="05097-117">Intune 登入</span><span class="sxs-lookup"><span data-stu-id="05097-117">Intune on-boarding</span></span>| <span data-ttu-id="05097-118">IT 系統管理員必須擁有現有的憑證授權單位、 WiFi 和 VPN 基礎結構規劃部署使用 Intune WiFi 和 VPN 設定檔時，已使用其實際執行環境中。</span><span class="sxs-lookup"><span data-stu-id="05097-118">IT admins need to have existing Certificate Authority, WiFi, and VPN infrastructures already working in their production environments when planning on deploying WiFi and VPN profiles with Intune.</span></span><br /><br /> <span data-ttu-id="05097-119">**附註**： 服務權益不包括設定，或設定憑證授權單位、 WiFi，VPN 基礎結構的協助，或 Apple MDM 推入的憑證</span><span class="sxs-lookup"><span data-stu-id="05097-119">**Note**: The service benefit doesn’t include assistance for setting up or configuring Certificate Authorities, WiFi, VPN infrastructures, or Apple MDM push certificates for</span></span>  |
|<span data-ttu-id="05097-120">Comanagement</span><span class="sxs-lookup"><span data-stu-id="05097-120">Comanagement</span></span>|<span data-ttu-id="05097-121">使用 Comanagement IT 系統管理員負責準備內部部署環境，其中可能包含修復問題使您從同時管理使用 Configuration Manager 和 Intune 的 Windows 10 裝置。</span><span class="sxs-lookup"><span data-stu-id="05097-121">With Comanagement IT admins are responsible for preparing the on-premises environment, which might include remediation of issues that prevent you from concurrently manage Windows 10 devices using both Configuration Manager and Intune.</span></span><br /><br /><span data-ttu-id="05097-122">**附註**： FastTrack 服務權益不包括設定，或將 Configuration Manager 站台伺服器及/或 Configuration Manager 用戶端升級至 Windows 10 裝置支援 Comanagement 所需的最低需求的協助。</span><span class="sxs-lookup"><span data-stu-id="05097-122">**Note**: The FastTrack service benefit doesn't include assistance for setting up or upgrading Configuration Manager site server and/or Configuration Manager client to the minimum requirements needed to support Comanagement with Windows 10 devices.</span></span> |
|<span data-ttu-id="05097-123">Intune 整合 Windows Defender 進階威脅防護 (Windows Defender ATP)</span><span class="sxs-lookup"><span data-stu-id="05097-123">Intune integrated with Windows Defender Advanced Threat Protection (Windows Defender ATP)</span></span>|<span data-ttu-id="05097-124">Windows Defender ATP 訂閱已啟動並設定您的公司安全性需求為基礎。</span><span class="sxs-lookup"><span data-stu-id="05097-124">Your Windows Defender ATP subscription has been activated and configured based on your company security requirements.</span></span><br /><br /><span data-ttu-id="05097-125">**附註**： FastTrack 服務權益提供協助整合 Intune 與 Windows Defender ATP，以及建立裝置合規性原則根據其 Windows 10 風險層級評定。</span><span class="sxs-lookup"><span data-stu-id="05097-125">**Note**: The FastTrack service benefit provides assistance on integrating Intune with Windows Defender ATP, and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="05097-126">FastTrack 服務權益不購買、 授權、 啟動，或使用 Windows Defender ATP 和其資訊安全中心主控台上提供的協助。</span><span class="sxs-lookup"><span data-stu-id="05097-126">The FastTrack service benefit does not provide assistance on purchasing, licensing, activating, or using Windows Defender ATP and its Security Center console.</span></span> |
|<span data-ttu-id="05097-127">Windows Autopilot</span><span class="sxs-lookup"><span data-stu-id="05097-127">Windows Autopilot</span></span>|<span data-ttu-id="05097-128">IT 系統管理員負責註冊其組織其裝置所需硬體供應商上傳其代理其硬體識別碼或上傳其本身恢復 Windows Autopilot 服務。</span><span class="sxs-lookup"><span data-stu-id="05097-128">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span> |
|<span data-ttu-id="05097-129">部署 Outlook for iOS 和 Android 安全地使用 Intune</span><span class="sxs-lookup"><span data-stu-id="05097-129">Deploy Outlook for iOS and Android securely with Intune</span></span>|<br /><br /><span data-ttu-id="05097-130">啟用 Azure AD 中 Office 365 的使用者身分識別。</span><span class="sxs-lookup"><span data-stu-id="05097-130">-   User identities enabled in Azure AD for Office 365.</span></span><br /><span data-ttu-id="05097-131">Exchange Online 或混合式 Exchange 設有指派使用者授權。</span><span class="sxs-lookup"><span data-stu-id="05097-131">-   Exchange Online or Hybrid Exchange configured with user licenses assigned.</span></span><br />|
|<span data-ttu-id="05097-132">Azure 資訊保護 （P2 或 EMS E5）</span><span class="sxs-lookup"><span data-stu-id="05097-132">Azure Information Protection (P2 or EMS E5)</span></span>|<br /><br /><span data-ttu-id="05097-133">客戶應該已經：</span><span class="sxs-lookup"><span data-stu-id="05097-133">Customers should already:</span></span> <br /> <span data-ttu-id="05097-134">-使用 Azure AD。</span><span class="sxs-lookup"><span data-stu-id="05097-134">- Use Azure AD.</span></span><br /><span data-ttu-id="05097-135">-使用 [Windows] 或 [iOS （其他 OSs 會超出範圍）。</span><span class="sxs-lookup"><span data-stu-id="05097-135">- Use either Windows or iOS (other OSs are out of scope).</span></span><br /> <span data-ttu-id="05097-136">-使用 Office 用戶端比 Office 2010 SP2 更新不依賴 Office Online 做為主要用戶端。</span><span class="sxs-lookup"><span data-stu-id="05097-136">- Use Office clients newer than Office 2010 SP2 that don't rely on Office Online as the main client.</span></span> <br /> <span data-ttu-id="05097-137">-有其主要的檔案共用位置。</span><span class="sxs-lookup"><span data-stu-id="05097-137">- Have their main file share locations.</span></span>  <br /> <span data-ttu-id="05097-138">-已升級從 Active Directory Rights Management Services (AD RMS)。</span><span class="sxs-lookup"><span data-stu-id="05097-138">- Have upgraded from Active Directory Rights Management Services (AD RMS).</span></span> <br /> <span data-ttu-id="05097-139">-已核准的分類分類。</span><span class="sxs-lookup"><span data-stu-id="05097-139">- Have an approved classification taxonomy.</span></span> <br /> <span data-ttu-id="05097-140">-了解其受保護的金鑰管理任何法規限制。</span><span class="sxs-lookup"><span data-stu-id="05097-140">- Understand any regulatory restrictions for their protected key management.</span></span> <br />|
|<span data-ttu-id="05097-141">Azure 資訊保護掃描器</span><span class="sxs-lookup"><span data-stu-id="05097-141">Azure Information Protection scanner</span></span>|<br /><br /> <span data-ttu-id="05097-142">客戶應該已經：</span><span class="sxs-lookup"><span data-stu-id="05097-142">Customers should already:</span></span> <br /> <span data-ttu-id="05097-143">-使用 Windows Server 2012 R2 或 Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="05097-143">- Use Windows Server 2012 R2 or Windows Server 2016.</span></span><br /> <span data-ttu-id="05097-144">-具有網際網路連線。</span><span class="sxs-lookup"><span data-stu-id="05097-144">- Have an internet connection.</span></span> <br /> <span data-ttu-id="05097-145">-本機或遠端執行個體中具有 Microsoft SQL Server 2012 +。</span><span class="sxs-lookup"><span data-stu-id="05097-145">- Have Microsoft SQL Server 2012 onward in a local or remote instance.</span></span>  <br /> <span data-ttu-id="05097-146">-已建立其內部部署 Active directory 並同步處理與 Azure AD 的服務帳戶。</span><span class="sxs-lookup"><span data-stu-id="05097-146">- Have a service account created for their on-premises Active Directory and synchronized with Azure AD.</span></span>  <br /> <span data-ttu-id="05097-147">-已下載 AzInfoProtection.exe。</span><span class="sxs-lookup"><span data-stu-id="05097-147">- Have downloaded AzInfoProtection.exe.</span></span> <br /> <span data-ttu-id="05097-148">-已設定為自動分類/保護的標籤。</span><span class="sxs-lookup"><span data-stu-id="05097-148">- Have labels configured for Automatic Classification/Protection.</span></span><br />|

> [!NOTE]
> <span data-ttu-id="05097-149">**想要了解更多？**
> [企業行動力 + 安全性](https://www.microsoft.com/cloud-platform/enterprise-mobility)</span><span class="sxs-lookup"><span data-stu-id="05097-149">**Want to learn more?**
[Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)</span></span>

## <a name="next-steps"></a><span data-ttu-id="05097-150">後續步驟</span><span class="sxs-lookup"><span data-stu-id="05097-150">Next steps</span></span>

[<span data-ttu-id="05097-151">適用於 EMS 上架階段 FastTrack 中心權益</span><span class="sxs-lookup"><span data-stu-id="05097-151">FastTrack Center Benefit for EMS onboarding phases</span></span>](EMS-onboarding-phases.md)