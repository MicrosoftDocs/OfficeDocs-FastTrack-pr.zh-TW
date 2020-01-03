---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 1/03/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack 提供 Windows 10 部署指引，可幫助您從 Windows 7 專業版和 Windows 8.1 專業版升級到 Windows 10 企業版。
ms.openlocfilehash: e4f048f826ea42b462ca973cbd48a1d2914f5f98
ms.sourcegitcommit: d7f4c9eafe7855c6ae02c2bd0fe3b700c458007c
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/02/2020
ms.locfileid: "40929363"
---
# <a name="windows-10"></a><span data-ttu-id="98bfc-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="98bfc-103">Windows 10</span></span>

<span data-ttu-id="98bfc-104">FastTrack 提供 Windows 10 部署指引，可幫助您從 Windows 7 專業版和 Windows 8.1 專業版升級到 Windows 10 企業版。</span><span class="sxs-lookup"><span data-stu-id="98bfc-104">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="98bfc-105">與 FastTrack 專家合作進行以下工作：</span><span class="sxs-lookup"><span data-stu-id="98bfc-105">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="98bfc-106">使用 Microsoft System Center Configuration Manager 或 Microsoft 365 來部署 Windows 10 企業版。</span><span class="sxs-lookup"><span data-stu-id="98bfc-106">Deploy Windows 10 Enterprise using Microsoft System Center Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="98bfc-107">部署 Office 365 專業增強版。</span><span class="sxs-lookup"><span data-stu-id="98bfc-107">Deploy Office 365 ProPlus.</span></span> 
- <span data-ttu-id="98bfc-108">使用 System Center Configuration Manager 或 Microsoft 365 來更新 Windows 10 企業版和 Office 365 專業增強版。</span><span class="sxs-lookup"><span data-stu-id="98bfc-108">Update Windows 10 Enterprise and Office 365 ProPlus using System Center Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="98bfc-109">透過雲端連結 Configuration Manager 與 Microsoft Intune，或將 Intune 部署為單獨的雲端管理解決方案。</span><span class="sxs-lookup"><span data-stu-id="98bfc-109">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="98bfc-110">FastTrack 為客戶提供建議方法、指引和經設計的最佳作法，以提供快速且可預測的結果。</span><span class="sxs-lookup"><span data-stu-id="98bfc-110">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="98bfc-111">如果您選擇在部署時不使用本指引，您的體驗可能會受到影響。</span><span class="sxs-lookup"><span data-stu-id="98bfc-111">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="98bfc-112">指引是指口頭協助和書面協助的組合。</span><span class="sxs-lookup"><span data-stu-id="98bfc-112">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="98bfc-113">當 FastTrack 專家提供指引時，FastTrack 人員無法代替您操作。</span><span class="sxs-lookup"><span data-stu-id="98bfc-113">When FastTrack Specialists provide guidance, FastTrack personnel can’t act on your behalf.</span></span> <span data-ttu-id="98bfc-114">只要您的訂閱是最新的，您就可以在合格計劃中使用 FastTrack 服務。</span><span class="sxs-lookup"><span data-stu-id="98bfc-114">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="98bfc-115">下表列出該程序的角色與責任。</span><span class="sxs-lookup"><span data-stu-id="98bfc-115">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="98bfc-116">**角色**</span><span class="sxs-lookup"><span data-stu-id="98bfc-116">**Role**</span></span> <br/> |<span data-ttu-id="98bfc-117">**責任**</span><span class="sxs-lookup"><span data-stu-id="98bfc-117">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="98bfc-118">**FastTrack 專家**</span><span class="sxs-lookup"><span data-stu-id="98bfc-118">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="98bfc-119">從遠端提供所有部署和更新服務。</span><span class="sxs-lookup"><span data-stu-id="98bfc-119">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="98bfc-120">將使用工具和發行的說明文件組合，從遠端協助您。</span><span class="sxs-lookup"><span data-stu-id="98bfc-120">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="98bfc-121">直接與您或您的代表配合。</span><span class="sxs-lookup"><span data-stu-id="98bfc-121">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="98bfc-122">**FastTrack 中心**</span><span class="sxs-lookup"><span data-stu-id="98bfc-122">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="98bfc-123">提供規劃及部署 Windows 10 企業版的指引。</span><span class="sxs-lookup"><span data-stu-id="98bfc-123">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="98bfc-124">提供協助，並且是在指定地區的一般上班時段提供。</span><span class="sxs-lookup"><span data-stu-id="98bfc-124">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="98bfc-125">以下列語言提供協助：繁體中文和簡體中文 (僅限說中文的資源)、英文、法文、德文、義大利文、日文、韓文、葡萄牙文 (巴西)、西班牙文、泰文以及越南文。</span><span class="sxs-lookup"><span data-stu-id="98bfc-125">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="98bfc-126">您可以透過 [Microsoft 365 系統管理中心](https://go.microsoft.com/fwlink/?linkid=2032704)或 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)取得協助。</span><span class="sxs-lookup"><span data-stu-id="98bfc-126">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="98bfc-127">若要登入，您必須具有作用中租用戶上的作用中公司或學校帳戶 (組織識別碼或 Azure Active Directory 識別碼)。</span><span class="sxs-lookup"><span data-stu-id="98bfc-127">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="98bfc-128">若要透過 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)取得協助：</span><span class="sxs-lookup"><span data-stu-id="98bfc-128">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.  <span data-ttu-id="98bfc-129">登入 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)。</span><span class="sxs-lookup"><span data-stu-id="98bfc-129">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="98bfc-130">選取 [服務]\*\*\*\*。</span><span class="sxs-lookup"><span data-stu-id="98bfc-130">Select **Services**.</span></span>
3.  <span data-ttu-id="98bfc-131">填妥**要求協助使用 Microsoft 365** 表單。</span><span class="sxs-lookup"><span data-stu-id="98bfc-131">Complete the **Request for Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="98bfc-p104">合作夥伴也可以透過 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)代表客戶取得協助。作法如下：</span><span class="sxs-lookup"><span data-stu-id="98bfc-p104">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.  <span data-ttu-id="98bfc-134">登入 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)。</span><span class="sxs-lookup"><span data-stu-id="98bfc-134">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="98bfc-135">選取 [我的客戶]\*\*\*\*。</span><span class="sxs-lookup"><span data-stu-id="98bfc-135">Select **My Customers**.</span></span>
3.  <span data-ttu-id="98bfc-136">搜尋您的客戶或從客戶清單中選取他們。</span><span class="sxs-lookup"><span data-stu-id="98bfc-136">Search for your customer or select them from your customer list.</span></span>
4.  <span data-ttu-id="98bfc-137">選取 [服務]\*\*\*\*。</span><span class="sxs-lookup"><span data-stu-id="98bfc-137">Select **Services**.</span></span>
5.  <span data-ttu-id="98bfc-138">選取**要求協助使用 Microsoft 365** 表單。</span><span class="sxs-lookup"><span data-stu-id="98bfc-138">Select the **Request for Assistance with Microsoft 365** form.</span></span>
6.  <span data-ttu-id="98bfc-139">選取 Windows 10 產品選項並完成表單。</span><span class="sxs-lookup"><span data-stu-id="98bfc-139">Select the Windows 10 product option and complete the form.</span></span>
 