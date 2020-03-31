---
title: FastTrack 程序
description: FastTrack 中心權益上架程序概觀
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 3/03/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: de8a5570478cd0b6317a7b6da8430272983dca68
ms.sourcegitcommit: 7a2535e510420496dabfcea5accbb36ab2fe21d2
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/30/2020
ms.locfileid: "43052318"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a><span data-ttu-id="a7e34-103">適用於 Enterprise Mobility + Security (EMS) 的 FastTrack 中心權益程序</span><span class="sxs-lookup"><span data-stu-id="a7e34-103">FastTrack Center Benefit Process for Enterprise Mobility + Security (EMS)</span></span>
<span data-ttu-id="a7e34-104">如果您的組織符合 EMS 的 FastTrack 中心權益資格，您可以透過遠端方式與 FastTrack 專家合作來預備使用 Microsoft Azure Active Directory 進階版、Microsoft Intune 和 Azure 資訊保護。</span><span class="sxs-lookup"><span data-stu-id="a7e34-104">If your organization is eligible for the FastTrack Center Benefit for EMS, you can work remotely with FastTrack Specialists to get Microsoft Azure Active Directory Premium, Microsoft Intune, and Azure Information Protection ready for use.</span></span> <span data-ttu-id="a7e34-105">您也可以透過 [FastTrack 網站](https://www.microsoft.com/fasttrack/microsoft-365/ems)取得 Azure 資訊保護和 Microsoft 雲端 App 安全性的使用協助。</span><span class="sxs-lookup"><span data-stu-id="a7e34-105">You can also request help through the [FastTrack site](https://www.microsoft.com/fasttrack/microsoft-365/ems) for Azure Information Protection and Microsoft Cloud App Security.</span></span> <span data-ttu-id="a7e34-106">若要了解貴組織是否符合資格，請參閱[符合資格的服務與方案](M365-eligible-services-and-plans.md)。</span><span class="sxs-lookup"><span data-stu-id="a7e34-106">To learn whether your organization is eligible, see [Eligible Services and Plans](M365-eligible-services-and-plans.md).</span></span>


<span data-ttu-id="a7e34-107">以下是我們會說明的上架程序：</span><span class="sxs-lookup"><span data-stu-id="a7e34-107">Here's what we cover about the onboarding process:</span></span>

-   [<span data-ttu-id="a7e34-108">上架程序的概觀</span><span class="sxs-lookup"><span data-stu-id="a7e34-108">Overview of the onboarding process</span></span>](EMS-fasttrack-benefit-overview.md)

-   [<span data-ttu-id="a7e34-109">對您的來源環境的預期</span><span class="sxs-lookup"><span data-stu-id="a7e34-109">Expectations for your source environment</span></span>](EMS-source-environment-expectations.md)

-   [<span data-ttu-id="a7e34-110">上架程序的階段</span><span class="sxs-lookup"><span data-stu-id="a7e34-110">Phases of the onboarding process</span></span>](EMS-onboarding-phases.md)

-   <span data-ttu-id="a7e34-111">各階段的 [FastTrack 責任](EMS-fasttrack-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="a7e34-111">[FastTrack responsibilities](EMS-fasttrack-responsibilities.md) for each phase</span></span>

-   <span data-ttu-id="a7e34-112">各階段的[客戶責任](EMS-your-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="a7e34-112">[Customer responsibilities](EMS-your-responsibilities.md) for each phase</span></span>

<span data-ttu-id="a7e34-113">以下是上架完成後可預期的結果：</span><span class="sxs-lookup"><span data-stu-id="a7e34-113">Here's what you can expect when onboarding is complete:</span></span>

-   <span data-ttu-id="a7e34-114">為您所選的服務建立 EMS 租用戶。</span><span class="sxs-lookup"><span data-stu-id="a7e34-114">Your EMS tenants for your selected services are created.</span></span>

-   <span data-ttu-id="a7e34-115">授權使用者可以使用下列任一個身分識別選項來存取 EMS 服務：</span><span class="sxs-lookup"><span data-stu-id="a7e34-115">Licensed users can access EMS Services by using one of the following identity options:</span></span>

    -   <span data-ttu-id="a7e34-116">雲端身分識別 (唯一的 EMS 帳戶)。</span><span class="sxs-lookup"><span data-stu-id="a7e34-116">Cloud Identities (unique EMS accounts).</span></span>

    -   <span data-ttu-id="a7e34-117">同步處理的身分識別：使用 Azure Active Directory Connect 工具 (密碼雜湊同步處理或通過驗證) 從您的內部部署 Active Directory 同步處理 EMS 帳戶。</span><span class="sxs-lookup"><span data-stu-id="a7e34-117">Synchronized Identities: EMS accounts synchronized from your on-premises Active Directory by using the Azure Active Directory Connect tool (Password Hash Sync or Pass-through Authentication).</span></span> <span data-ttu-id="a7e34-118">這個選項適用於擁有單一樹系或多個 Active Directory 樹系的客戶。</span><span class="sxs-lookup"><span data-stu-id="a7e34-118">This option is for customers with a single forest or multiple Active Directory forests.</span></span>

    -   <span data-ttu-id="a7e34-119">同盟身分識別--包含下列情況的 Microsoft EMS 帳戶：</span><span class="sxs-lookup"><span data-stu-id="a7e34-119">Federated Identities--with Microsoft EMS accounts that are:</span></span>

        -   <span data-ttu-id="a7e34-120">使用 Azure AD Connect 工具，從 Active Directory 同步處理。</span><span class="sxs-lookup"><span data-stu-id="a7e34-120">Synchronized from Active Directory with the Azure AD Connect tool.</span></span> <span data-ttu-id="a7e34-121">這個選項適用於擁有單一 Active Directory 樹系組態的客戶。</span><span class="sxs-lookup"><span data-stu-id="a7e34-121">This option is for customers with a single Active Directory forest configuration.</span></span>

        -   <span data-ttu-id="a7e34-122">從您的內部部署 Active Directory與 Windows Server 2012 R2 Active Directory 同盟服務 (AD FS) 2.0 或更新版本同盟。</span><span class="sxs-lookup"><span data-stu-id="a7e34-122">Federated with Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 or later from your on-premises Active Directory.</span></span>

        -   <span data-ttu-id="a7e34-123">Azure 資訊保護功能可以在靜止和傳輸過程中自動分類和保護資訊。</span><span class="sxs-lookup"><span data-stu-id="a7e34-123">The ability to auto-classify and protect information both at rest and in transit with Azure Information Protection.</span></span> 

        -   <span data-ttu-id="a7e34-124">Azure 資訊保護掃描程式的功能可內部部署檔案共用和 SharePoint 伺服器上探索資訊。</span><span class="sxs-lookup"><span data-stu-id="a7e34-124">The ability to discover information within on-premises file shares and SharePoint servers with the Azure Information Protection scanner.</span></span> 

        -   <span data-ttu-id="a7e34-125">能夠在 Azure 金鑰保存庫中管理 Azure 資訊保護租用戶的金鑰。</span><span class="sxs-lookup"><span data-stu-id="a7e34-125">The ability to manage your Azure Information Protection tenant keys within the Azure Key Vault.</span></span> 

