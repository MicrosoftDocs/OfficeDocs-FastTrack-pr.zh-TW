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
# <a name="windows-virtual-desktop"></a>Windows 虛擬桌面

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
<td>Windows 虛擬桌面</td>
<td><p>FastTrack 提供 Windows 虛擬桌面部署指導，以協助您以輕鬆的方式將此桌面和應用程式虛擬化服務連線至此桌面和應用程式虛擬化服務，以 Windows 10 利用整合的安全性和 Enterprise 的整合式安全性和管理，針對 Microsoft 365 的 Microsoft 365 Apps 優化。</p>
<p>與 FastTrack 專家合作進行以下工作：</p>
<ul>
<li><p>使用下列各項來部署 WVD 環境 Windows 10 企業版多重會話 + Microsoft 365 Apps Enterprise：</p>
<ul>
<li><p>Azure Marketplace 影像</p></li>
<li><p>共用影像</p></li>
<li><p>Office部署工具組 (ODT) </p></li>
</ul></li>
<li><p>設定 FSLogix</p>
<ul>
<li><p>使用設定檔容器部署 FSLogix 代理程式</p></li>
<li><p>使用 Office 容器部署 FSLogix 代理程式</p></li>
<li><p>使用內容排除設定 FSLogix 資料夾</p></li>
</ul></li>
<li><p>部署 Microsoft Edge</p></li>
<li><p>部署 Microsoft Teams</p></li>
<li><p>使用 Windows 虛擬桌面用戶端的連線</p></li>
</ul>
<p><strong>下列超出範圍</strong></p>
<ul>
<li><p>Project 管理客戶的 Windows 虛擬桌面部署。</p></li>
<li><p>現場支援。</p></li>
<li><p>協力廠商應用程式虛擬化/部署。</p></li>
<li><p>自訂圖像。</p></li>
<li><p>涉及 VMware 和 Citrix 的遷移和案例。</p></li>
<li><p>Linux 案例。</p></li>
<li><p>轉換或遷移使用者設定檔。</p></li>
</ul>
<p>請與 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作夥伴</a> 聯繫以取得這些服務。</p></td>
<td><p>您應該已經具備下列專案：</p>
<ul>
<li><p>[WVD 授權需求](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p>Azure 網路：</p>
<ul>
<li><p>VNET 建立 &amp; 子網</p></li>
<li><p>防火牆/網路安全性群組</p></li>
<li><p>VPN/ExpressRoute</p></li>
<li><p>從內部部署路由傳送至 Azure</p></li>
<li><p>允許連線至 WVD 的防火牆規則</p>
<ul>
<li><p>[檔參考](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory一般設定</p>
<ul>
<li><p>身分識別策略 <strong> (只選取下列3個選項中的1個) </strong></p>
<ul>
<li><p>Azure 中使用 Azure AD 連線的 Active Directory</p></li>
<li><p>具有 VPN/ER 之內部部署的 Azure AD 連線 Active Directory</p></li>
<li><p>Active Directory 網域服務</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
