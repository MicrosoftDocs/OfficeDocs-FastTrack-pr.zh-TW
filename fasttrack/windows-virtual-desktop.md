---
title: Windows 虛擬桌面
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: FastTrack 提供 Windows 虛擬桌面部署指導，以協助您在此桌面上架上。
ms.openlocfilehash: bdec1f6438a34b5ec023be5159329617bc5a78f9
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592436"
---
# <a name="windows-virtual-desktop"></a><span data-ttu-id="2e77e-103">Windows 虛擬桌面</span><span class="sxs-lookup"><span data-stu-id="2e77e-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2e77e-104"><strong>服務</strong></span><span class="sxs-lookup"><span data-stu-id="2e77e-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2e77e-105"><strong>FastTrack 指引詳細資料</strong></span><span class="sxs-lookup"><span data-stu-id="2e77e-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="2e77e-106"><strong>來源環境預期</strong></span><span class="sxs-lookup"><span data-stu-id="2e77e-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2e77e-107">Windows 虛擬桌面</span><span class="sxs-lookup"><span data-stu-id="2e77e-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="2e77e-108">FastTrack 提供 Windows 虛擬桌面部署指導，以協助您以輕鬆的方式將此桌面和應用程式虛擬化服務連線至此桌面和應用程式虛擬化服務，以 Windows 10 利用整合的安全性和 Enterprise 的整合式安全性和管理，針對 Microsoft 365 的 Microsoft 365 Apps 優化。</span><span class="sxs-lookup"><span data-stu-id="2e77e-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="2e77e-109">與 FastTrack 專家合作進行以下工作：</span><span class="sxs-lookup"><span data-stu-id="2e77e-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="2e77e-110">使用下列各項來部署 WVD 環境 Windows 10 企業版多重會話 + Microsoft 365 Apps Enterprise：</span><span class="sxs-lookup"><span data-stu-id="2e77e-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="2e77e-111">Azure Marketplace 影像</span><span class="sxs-lookup"><span data-stu-id="2e77e-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="2e77e-112">共用影像</span><span class="sxs-lookup"><span data-stu-id="2e77e-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="2e77e-113">Office部署工具組 (ODT) </span><span class="sxs-lookup"><span data-stu-id="2e77e-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="2e77e-114">設定 FSLogix</span><span class="sxs-lookup"><span data-stu-id="2e77e-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="2e77e-115">使用設定檔容器部署 FSLogix 代理程式</span><span class="sxs-lookup"><span data-stu-id="2e77e-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="2e77e-116">使用 Office 容器部署 FSLogix 代理程式</span><span class="sxs-lookup"><span data-stu-id="2e77e-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="2e77e-117">使用內容排除設定 FSLogix 資料夾</span><span class="sxs-lookup"><span data-stu-id="2e77e-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="2e77e-118">部署 Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="2e77e-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="2e77e-119">部署 Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="2e77e-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="2e77e-120">使用 Windows 虛擬桌面用戶端的連線</span><span class="sxs-lookup"><span data-stu-id="2e77e-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="2e77e-121"><strong>下列超出範圍</strong></span><span class="sxs-lookup"><span data-stu-id="2e77e-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="2e77e-122">Project 管理客戶的 Windows 虛擬桌面部署。</span><span class="sxs-lookup"><span data-stu-id="2e77e-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="2e77e-123">現場支援。</span><span class="sxs-lookup"><span data-stu-id="2e77e-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="2e77e-124">協力廠商應用程式虛擬化/部署。</span><span class="sxs-lookup"><span data-stu-id="2e77e-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="2e77e-125">自訂圖像。</span><span class="sxs-lookup"><span data-stu-id="2e77e-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="2e77e-126">涉及 VMware 和 Citrix 的遷移和案例。</span><span class="sxs-lookup"><span data-stu-id="2e77e-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="2e77e-127">Linux 案例。</span><span class="sxs-lookup"><span data-stu-id="2e77e-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="2e77e-128">轉換或遷移使用者設定檔。</span><span class="sxs-lookup"><span data-stu-id="2e77e-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="2e77e-129">請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。</span><span class="sxs-lookup"><span data-stu-id="2e77e-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="2e77e-130">您應該已經具備下列專案：</span><span class="sxs-lookup"><span data-stu-id="2e77e-130">You should already have the following:</span></span></p>
<ul>
<li><p>[<span data-ttu-id="2e77e-131">WVD 授權需求</span><span class="sxs-lookup"><span data-stu-id="2e77e-131">WVD Licensing Requirements</span></span>](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p><span data-ttu-id="2e77e-132">Azure 網路：</span><span class="sxs-lookup"><span data-stu-id="2e77e-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="2e77e-133">VNET 建立 &amp; 子網</span><span class="sxs-lookup"><span data-stu-id="2e77e-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="2e77e-134">防火牆/網路安全性群組</span><span class="sxs-lookup"><span data-stu-id="2e77e-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="2e77e-135">VPN/ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="2e77e-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="2e77e-136">從內部部署路由傳送至 Azure</span><span class="sxs-lookup"><span data-stu-id="2e77e-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="2e77e-137">允許連線至 WVD 的防火牆規則</span><span class="sxs-lookup"><span data-stu-id="2e77e-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p>[<span data-ttu-id="2e77e-138">檔參考</span><span class="sxs-lookup"><span data-stu-id="2e77e-138">Docs Reference</span></span>](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="2e77e-139">Azure Active Directory一般設定</span><span class="sxs-lookup"><span data-stu-id="2e77e-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="2e77e-140">身分識別策略 <strong> (只選取下列3個選項中的1個) </strong></span><span class="sxs-lookup"><span data-stu-id="2e77e-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="2e77e-141">Azure 中使用 Azure AD 連線的 Active Directory</span><span class="sxs-lookup"><span data-stu-id="2e77e-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="2e77e-142">具有 VPN/ER 之內部部署的 Azure AD 連線 Active Directory</span><span class="sxs-lookup"><span data-stu-id="2e77e-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="2e77e-143">Active Directory 網域服務</span><span class="sxs-lookup"><span data-stu-id="2e77e-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
