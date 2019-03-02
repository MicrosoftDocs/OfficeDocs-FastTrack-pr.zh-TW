---
title: 來源環境預期
description: 使用 FastTrack Center 權益 ems 來源環境需求
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 03/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 6b3a5ed24ac254c3a989a584df0cbd89533ff1af
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/01/2019
ms.locfileid: "30359981"
---
# <a name="source-environment-expectations"></a><span data-ttu-id="67a5e-103">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="67a5e-103">Source Environment Expectations</span></span>

<span data-ttu-id="67a5e-104">當您要準備好使用 Microsoft Azure Active Directory Premium 和 Microsoft Intune 使用[用於 Enterprise Mobility + Security (EMS) 的 FastTrack Center 權益](EMS-fasttrack-benefit-for-EMS.md)時，您的環境必須符合下列各節所述的期望。</span><span class="sxs-lookup"><span data-stu-id="67a5e-104">When you use the [FastTrack Center Benefit for Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) to get Microsoft Azure Active Directory Premium and Microsoft Intune ready for use, your environment needs to meet the expectations described in the following sections.</span></span>

<span data-ttu-id="67a5e-p101">您可能已經有您想要整合與 Enterprise Mobility + Security (EMS) 或任何使用透過單一主控台的豐富型身分識別管理其個別服務的組織中的內部部署 Active Directory。適用於 Enterprise Mobility + Security (EMS) 的 FastTrack 中心權益包含協助您與您現有的內部部署 Active Directory 環境整合 Azure Active Directory。</span><span class="sxs-lookup"><span data-stu-id="67a5e-p101">You may already have on-premises Active Directory in your organization that you want to integrate with Enterprise Mobility + Security (EMS) or any of its individual services that uses rich identity management from a single console. The FastTrack Center Benefit for Enterprise Mobility + Security (EMS) includes helping you integrate Azure Active Directory with your existing on-premises Active Directory environment.</span></span>

<span data-ttu-id="67a5e-107">下表顯示登入您現有來源環境預期。</span><span class="sxs-lookup"><span data-stu-id="67a5e-107">The following table shows expectations for your existing source environment for on-boarding.</span></span>

|<span data-ttu-id="67a5e-108">活動</span><span class="sxs-lookup"><span data-stu-id="67a5e-108">Activity</span></span>|<span data-ttu-id="67a5e-109">來源環境預期</span><span class="sxs-lookup"><span data-stu-id="67a5e-109">Source environment expectation</span></span>|
|------------|----------------------------------|
|<span data-ttu-id="67a5e-110">核心登入</span><span class="sxs-lookup"><span data-stu-id="67a5e-110">Core on-boarding</span></span>|<span data-ttu-id="67a5e-111">Active Directory 樹系，功能樹系層級設定至 Windows Server 2008 以上，使用下列樹系組態：</span><span class="sxs-lookup"><span data-stu-id="67a5e-111">Active Directory forests with the functional forest level set to Windows Server 2008 or above, with the following forest configuration:</span></span><br /><br /><span data-ttu-id="67a5e-112">-單一 Active Directory 樹系</span><span class="sxs-lookup"><span data-stu-id="67a5e-112">-   Single Active Directory forest</span></span><br /><span data-ttu-id="67a5e-113">對多個 Active Directory 樹系</span><span class="sxs-lookup"><span data-stu-id="67a5e-113">-   Multiple Active Directory forests</span></span> </br></br><span data-ttu-id="67a5e-114">**附註**： 對於所有多重樹系組態，Active Directory Federation Services (AD FS) 部署是在 FastTrack Center 權益的範圍。</span><span class="sxs-lookup"><span data-stu-id="67a5e-114">**Note**: For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope for the FastTrack Center Benefit.</span></span>|
|<span data-ttu-id="67a5e-115">Azure AD Premium 登入</span><span class="sxs-lookup"><span data-stu-id="67a5e-115">Azure AD Premium on-boarding</span></span>|<span data-ttu-id="67a5e-116">Azure AD Premium，其中包含已識別的問題，導致與 Azure AD 整合的補救已經準備內部部署 Active Directory 和其環境與 Azure AD Premium 功能。</span><span class="sxs-lookup"><span data-stu-id="67a5e-116">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, which includes remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span>|
|<span data-ttu-id="67a5e-117">Intune 登入</span><span class="sxs-lookup"><span data-stu-id="67a5e-117">Intune on-boarding</span></span>| <span data-ttu-id="67a5e-118">IT 系統管理員必須擁有現有的憑證授權單位、 WiFi 和 VPN 基礎結構規劃部署使用 Intune WiFi 和 VPN 設定檔時，已使用其實際執行環境中。</span><span class="sxs-lookup"><span data-stu-id="67a5e-118">IT admins need to have existing Certificate Authority, WiFi, and VPN infrastructures already working in their production environments when planning on deploying WiFi and VPN profiles with Intune.</span></span><br /><br /> <span data-ttu-id="67a5e-119">**附註**： 服務權益不包括設定，或設定憑證授權單位、 WiFi，VPN 基礎結構的協助，或 Apple MDM 推入的憑證</span><span class="sxs-lookup"><span data-stu-id="67a5e-119">**Note**: The service benefit doesn’t include assistance for setting up or configuring Certificate Authorities, WiFi, VPN infrastructures, or Apple MDM push certificates for</span></span>  |
|<span data-ttu-id="67a5e-120">Comanagement</span><span class="sxs-lookup"><span data-stu-id="67a5e-120">Comanagement</span></span>|<span data-ttu-id="67a5e-121">使用 Comanagement IT 系統管理員負責準備內部部署環境，其中可能包含修復問題使您從同時管理使用 Configuration Manager 和 Intune 的 Windows 10 裝置。</span><span class="sxs-lookup"><span data-stu-id="67a5e-121">With Comanagement IT admins are responsible for preparing the on-premises environment, which might include remediation of issues that prevent you from concurrently manage Windows 10 devices using both Configuration Manager and Intune.</span></span><br /><br /><span data-ttu-id="67a5e-122">**附註**： FastTrack 服務權益不包括設定，或將 Configuration Manager 站台伺服器及/或 Configuration Manager 用戶端升級至 Windows 10 裝置支援 Comanagement 所需的最低需求的協助。</span><span class="sxs-lookup"><span data-stu-id="67a5e-122">**Note**: The FastTrack service benefit doesn't include assistance for setting up or upgrading Configuration Manager site server and/or Configuration Manager client to the minimum requirements needed to support Comanagement with Windows 10 devices.</span></span> |
|<span data-ttu-id="67a5e-123">Intune 整合 Windows Defender 進階威脅防護 (Windows Defender ATP)</span><span class="sxs-lookup"><span data-stu-id="67a5e-123">Intune integrated with Windows Defender Advanced Threat Protection (Windows Defender ATP)</span></span>|<span data-ttu-id="67a5e-124">Windows Defender ATP 訂閱已啟動並設定您的公司安全性需求為基礎。</span><span class="sxs-lookup"><span data-stu-id="67a5e-124">Your Windows Defender ATP subscription has been activated and configured based on your company security requirements.</span></span><br /><br /><span data-ttu-id="67a5e-p102">**附註**： FastTrack 服務權益提供協助整合 Intune 與 Windows Defender ATP，以及建立裝置合規性原則根據其 Windows 10 風險層級評定。FastTrack 服務權益不購買、 授權、 啟動，或使用 Windows Defender ATP 和其資訊安全中心主控台上提供的協助。</span><span class="sxs-lookup"><span data-stu-id="67a5e-p102">**Note**: The FastTrack service benefit provides assistance on integrating Intune with Windows Defender ATP, and creating device compliance policies based on its Windows 10 risk level assessment. The FastTrack service benefit does not provide assistance on purchasing, licensing, activating, or using Windows Defender ATP and its Security Center console.</span></span> |
|<span data-ttu-id="67a5e-127">Windows Autopilot</span><span class="sxs-lookup"><span data-stu-id="67a5e-127">Windows Autopilot</span></span>|<span data-ttu-id="67a5e-128">IT 系統管理員負責註冊其組織其裝置所需硬體供應商上傳其代理其硬體識別碼或上傳其本身恢復 Windows Autopilot 服務。</span><span class="sxs-lookup"><span data-stu-id="67a5e-128">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span> |
|<span data-ttu-id="67a5e-129">部署 Outlook for iOS 和 Android 安全地使用 Intune</span><span class="sxs-lookup"><span data-stu-id="67a5e-129">Deploy Outlook for iOS and Android securely with Intune</span></span>|<br /><br /><span data-ttu-id="67a5e-130">啟用 Azure AD 中 Office 365 的使用者身分識別。</span><span class="sxs-lookup"><span data-stu-id="67a5e-130">-   User identities enabled in Azure AD for Office 365.</span></span><br /><span data-ttu-id="67a5e-131">Exchange Online 或混合式 Exchange 設有指派使用者授權。</span><span class="sxs-lookup"><span data-stu-id="67a5e-131">-   Exchange Online or Hybrid Exchange configured with user licenses assigned.</span></span><br />|

> [!NOTE]
> <span data-ttu-id="67a5e-132">**想要了解更多？**
> [企業行動力 + 安全性](https://www.microsoft.com/cloud-platform/enterprise-mobility)</span><span class="sxs-lookup"><span data-stu-id="67a5e-132">**Want to learn more?**
[Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)</span></span>

## <a name="next-steps"></a><span data-ttu-id="67a5e-133">後續步驟</span><span class="sxs-lookup"><span data-stu-id="67a5e-133">Next steps</span></span>

[<span data-ttu-id="67a5e-134">適用於 EMS 上架階段 FastTrack 中心權益</span><span class="sxs-lookup"><span data-stu-id="67a5e-134">FastTrack Center Benefit for EMS onboarding phases</span></span>](EMS-onboarding-phases.md)
