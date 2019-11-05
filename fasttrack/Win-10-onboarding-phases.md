---
title: 上架階段
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 11/02/2019
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: Windows 10 上架有四個主要階段 - 起始、評估、修復與啟用。
ms.openlocfilehash: c2c9515f0e3cefed133da74d41e84995724ed042
ms.sourcegitcommit: f8d7e570b60a55c244af0eceb6fbb0e591257f11
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/01/2019
ms.locfileid: "37921887"
---
# <a name="onboarding-phases"></a>上架階段

Windows 10 上架有四個主要階段 - 起始、評估、修復與啟用。

## <a name="initiate"></a>起始

在這個階段期間，我們將討論上架程序、驗證資料並設定專案啟動會議。 這包括與您一起了解您安裝 Windows 10 的用途。

## <a name="assess"></a>評估

FastTrack 專家會與您一起評估您的來源環境和需求。 請確定 System Center Configuration Manager 已升級至支援 Windows 10 部署所需的層級。 

我們會為您提供評估 Windows 10 應用程式的建議選項。 FastTrack 提供指導方針來啟用桌面分析的使用，並引導您建立電腦分析部署計劃。

FastTrack 還可以透過 Configuration Manager 中的Office 365 整備儀表板或使用獨立的 Readiness Toolkit for Office 來引導您進行 Office 365 專業增強版相容性評估。 如需可用服務的詳細資訊，請參閱[適用於 Office 365 的 FastTrack 中心權益](O365-fasttrack-benefit-for-office-365.md)。 

FastTrack 也會為您評估新式管理策略，包括透過雲端連結 Configuration Manager 與 Microsoft Intune，或將 Intune 部署為單獨的雲端管理解決方案。

## <a name="remediate"></a>修復

您可以根據來源環境執行修復工作，以便滿足上架需求。 我們提供了一個修復清單，用於準備您的環境並驗證這些元素是否就位，以讓您的來源環境符合成功部署的最低需求。 

## <a name="enable"></a>啟用

FastTrack 提供將現有裝置升級至 Windows 10 企業版的指引，只要它們符合必要的裝置硬體需求即可進行升級。 升級指引可支援您現有的部署動作。 FastTrack 會建議並提供 Windows 10 就地升級的指引。 也提供 Windows 全新映像安裝和 [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot) 部署案例的指引。 

我們針對使用 Configuration Manager 在部署 Windows 10 期間同時部署 Office 365 專業增強版，提供相關指引。 如需關聯服務的詳細資訊，請參閱 [Office 365 專業增強版](O365-onboarding-and-migration.md#office-365-proplus)。

我們提供指引，幫助貴組織使用現有的 Configuration Manager 環境或 Microsoft 365 與 Windows 10 企業版和 Office 365 專業增強版保持同步。

如有需要，FastTrack 可以引導客戶透過雲端將 Configuration Manager 連結至 Intune，或部署獨立的 Intune，藉以啟用新式管理。 如需相關服務的詳細資訊，請參閱[適用於 Enterprise Mobility + Security (EMS) 的 FastTrack 中心權益程序](EMS-fasttrack-process.md)。

> [!NOTE]
> 如果您目前沒有部署和維護的計劃或程序，我們可以根據就地升級案例 (建議) 或 [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot) 提供最佳作法指引。

## <a name="out-of-scope"></a>超出範圍

FastTrack 未提供以下指引：

- 將 Configuration Manager 升級至最新分支。
- 建立適用於 Windows 10 部署的自訂映像。
- 建立及支援 Windows 10 部署的部署指令碼。
- 將 Windows 10 系統從 BIOS 轉換為整合可延伸韌體介面 (UEFI)。
- 啟用 Windows 10 的安全性功能。 
- 將 Windows 部署服務 (WDS) 設定為開機前執行環境 (PXE) 啟動。
- 使用 Microsoft Deployment Toolkit (MDT) 來擷取及部署 Windows 10 映像。
- 使用使用者狀態移轉工具 (USMT)

  > [!NOTE]
  > 請連絡 [Microsoft 合作夥伴](https://go.microsoft.com/fwlink/?linkid=2080150) 以提供協助和視為範圍外的服務。

 