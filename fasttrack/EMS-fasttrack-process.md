---
title: FastTrack 程序
description: FastTrack 中心權益上架程序概觀
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 12/03/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 21eb392fc0cfd3f9c41f40686843c6a16eee4566
ms.sourcegitcommit: 39616c06c0617700b1393e055894acb6aa6f7776
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 12/02/2019
ms.locfileid: "39662842"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>適用於 Enterprise Mobility + Security (EMS) 的 FastTrack 中心權益程序
如果您的組織符合 EMS 的 FastTrack 中心權益資格，您可以透過遠端方式與 FastTrack 專家合作來預備使用 Microsoft Azure Active Directory 進階版、Microsoft Intune 和 Azure 資訊保護。 您也可以透過 [FastTrack 網站](https://www.microsoft.com/fasttrack/microsoft-365/ems)取得 Azure 資訊保護和 Microsoft 雲端 App 安全性的使用協助。 若要了解貴組織是否符合資格，請參閱[符合資格的服務與方案](M365-eligible-services-and-plans.md)。


以下是我們會說明的上架程序：

-   [上架程序的概觀](EMS-fasttrack-benefit-overview.md)

-   [對您的來源環境的預期](EMS-source-environment-expectations.md)

-   [上架程序的階段](EMS-onboarding-phases.md)

-   各階段的 [FastTrack 責任](EMS-fasttrack-responsibilities.md)

-   各階段的[客戶責任](EMS-your-responsibilities.md)

以下是上架完成後可預期的結果：

-   為您所選的服務建立 EMS 租用戶。

-   授權使用者可以使用下列任一個身分識別選項來存取 EMS 服務：

    -   雲端身分識別 (唯一的 EMS 帳戶)。

    -   同步處理的身分識別：使用 Azure Active Directory Connect 工具 (密碼雜湊同步處理或通過驗證) 從您的內部部署 Active Directory 同步處理 EMS 帳戶。 這個選項適用於擁有單一樹系或多個 Active Directory 樹系的客戶。

    -   同盟身分識別--包含下列情況的 Microsoft EMS 帳戶：

        -   使用 Azure AD Connect 工具，從 Active Directory 同步處理。 這個選項適用於擁有單一 Active Directory 樹系組態的客戶。

        -   從您的內部部署 Active Directory與 Windows Server 2012 R2 Active Directory 同盟服務 (AD FS) 2.0 或更新版本同盟。

        -   Azure 資訊保護功能可以在靜止和傳輸過程中自動分類和保護資訊。 

        -   Azure 資訊保護掃描程式的功能可內部部署檔案共用和 SharePoint 伺服器上探索資訊。 

        -   能夠在 Azure 金鑰保存庫中管理 Azure 資訊保護租用戶的金鑰。 
