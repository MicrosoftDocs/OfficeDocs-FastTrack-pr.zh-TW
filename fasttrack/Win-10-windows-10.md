---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: None
ms.collection: FastTrack
description: FastTrack 提供 Windows 10 部署指引，可幫助您從 Windows 7 專業版和 Windows 8.1 專業版升級到 Windows 10 企業版。
ms.openlocfilehash: e4cebb463833c71cc9129155e86821c69f180a27
ms.sourcegitcommit: de2cc20b4ab297633cb254d42532719022bb8d99
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/02/2020
ms.locfileid: "47338123"
---
# <a name="windows-10"></a><span data-ttu-id="4ba5f-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="4ba5f-103">Windows 10</span></span>

> [!CAUTION]
> <span data-ttu-id="4ba5f-104">此內容已不再是最新的，且已排定移除。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-104">This content is no longer current and is scheduled for removal.</span></span> <span data-ttu-id="4ba5f-105">請使用目前內容左側瀏覽的目錄。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-105">Use the table of contents in the left-hand navigation for current content.</span></span>

<span data-ttu-id="4ba5f-106">FastTrack 提供 Windows 10 部署指引，可幫助您從 Windows 7 專業版和 Windows 8.1 專業版升級到 Windows 10 企業版。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-106">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="4ba5f-107">與 FastTrack 專家合作進行以下工作：</span><span class="sxs-lookup"><span data-stu-id="4ba5f-107">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="4ba5f-108">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 來部署 Windows 10 企業版。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-108">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="4ba5f-109">部署 Microsoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-109">Deploy Microsoft 365 Apps.</span></span> 
- <span data-ttu-id="4ba5f-110">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 來更新 Windows 10 企業版和 Microsoft 365 Apps。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-110">Update Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="4ba5f-111">透過雲端連結 Configuration Manager 與 Microsoft Intune，或將 Intune 部署為單獨的雲端管理解決方案。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-111">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="4ba5f-112">FastTrack 為客戶提供建議方法、指引和經設計的最佳作法，以提供快速且可預測的結果。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-112">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="4ba5f-113">如果您選擇在部署時不使用本指引，您的體驗可能會受到影響。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-113">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="4ba5f-114">指引是指口頭協助和書面協助的組合。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-114">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="4ba5f-115">當 FastTrack 專家提供指引時，FastTrack 人員無法代替您操作。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-115">When FastTrack Specialists provide guidance, FastTrack personnel can't act on your behalf.</span></span> <span data-ttu-id="4ba5f-116">只要您的訂閱是最新的，您就可以在合格計劃中使用 FastTrack 服務。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-116">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="4ba5f-117">下表列出該程序的角色與責任。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-117">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="4ba5f-118">**角色**</span><span class="sxs-lookup"><span data-stu-id="4ba5f-118">**Role**</span></span> <br/> |<span data-ttu-id="4ba5f-119">**責任**</span><span class="sxs-lookup"><span data-stu-id="4ba5f-119">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="4ba5f-120">**FastTrack 專家**</span><span class="sxs-lookup"><span data-stu-id="4ba5f-120">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="4ba5f-121">從遠端提供所有部署和更新服務。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-121">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="4ba5f-122">將使用工具和發行的說明文件組合，從遠端協助您。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-122">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="4ba5f-123">直接與您或您的代表配合。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-123">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="4ba5f-124">**FastTrack 中心**</span><span class="sxs-lookup"><span data-stu-id="4ba5f-124">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="4ba5f-125">提供規劃及部署 Windows 10 企業版的指引。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-125">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="4ba5f-126">提供協助，並且是在指定地區的一般上班時段提供。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-126">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="4ba5f-127">以下列語言提供協助：繁體中文和簡體中文 (僅限說中文的資源)、英文、法文、德文、義大利文、日文、韓文、葡萄牙文 (巴西)、西班牙文、泰文以及越南文。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-127">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="4ba5f-128">您可以透過 [Microsoft 365 系統管理中心](https://go.microsoft.com/fwlink/?linkid=2032704)或 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)取得協助。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-128">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="4ba5f-129">若要登入，您必須具有作用中租用戶上的作用中公司或學校帳戶 (組織識別碼或 Azure Active Directory 識別碼)。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-129">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="4ba5f-130">若要透過 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)取得協助：</span><span class="sxs-lookup"><span data-stu-id="4ba5f-130">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="4ba5f-131">登入 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-131">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="4ba5f-132">從登陸頁面上方的 **快速動作** 選取 **使用 Microsoft 365 要求協助**。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-132">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="4ba5f-133">填妥**使用 Microsoft 365 要求協助** 表單。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-133">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="4ba5f-p105">合作夥伴也可以透過 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)代表客戶取得協助。作法如下：</span><span class="sxs-lookup"><span data-stu-id="4ba5f-p105">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.    <span data-ttu-id="4ba5f-136">登入 [FastTrack 網站](https://go.microsoft.com/fwlink/?linkid=780698)。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-136">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="4ba5f-137">從登陸頁面上方的 **快速動作** 選取 **使用 Microsoft 365 要求協助**。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-137">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="4ba5f-138">輸入客戶名稱、網域或 TPID 來搜尋您的客戶。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-138">Search for your customer by entering the customer name, domain, or TPID.</span></span>
4.    <span data-ttu-id="4ba5f-139">從搜尋結果中選取客戶。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-139">Select customer from the search results.</span></span>
5.    <span data-ttu-id="4ba5f-140">填妥**使用 Microsoft 365 要求協助** 表單。</span><span class="sxs-lookup"><span data-stu-id="4ba5f-140">Complete the **Request Assistance with Microsoft 365** form.</span></span>
 
