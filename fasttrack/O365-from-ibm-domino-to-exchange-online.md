---
title: 附錄 A：從 IBM Domino 移轉至 Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 05/02/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 從 IBM Domino 移轉至 Exchange Online 包含幾個重要的層面，包括下列階段期間發生的情況：
ms.openlocfilehash: ce800ae7bab16946346133df5f1d4df4c27304a3
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513796"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a>附錄 A：從 IBM Domino 移轉至 Exchange Online

從 IBM Domino 移轉至 Exchange Online 包含幾個重要的層面，包括下列階段期間發生的情況： 
- [始階段](#initiate-phase)   
- [評估階段](#assess-phase)
- [修復階段](#remediate-phase)  
- [啟用階段](#enable-phase)  
- [移轉階段](#migrate-phase)
    
## <a name="identities"></a>身分識別

您負責建立和管理身分識別 (僅限雲端、同步處理，或與其內部部署 Active Directory 同盟)。 您必須在上架的早期階段，完成 Domino 與內部部署 Active Directory 或 Azure Active Directory 之間的身份識別對應 (若未存在)。
  
## <a name="coexistence"></a>共存

「適用於 Office 365 的 FastTrack 中心權益」提供內部部署 Domino 環境與 Exchange Online 之間的雙向郵件流量給所有客戶。
  
## <a name="migration"></a>移轉

從 Domino 移轉到 Exchange Online 的標準 FastTrack Center 程序牽涉到先預先接移資料至 Azure 再移轉至 Exchange Online 信箱。 FastTrack 移轉要求 FastTrack Center 和您在不同的上架階段中執行活動。我們在以下幾節中會說明這些活動。
  
> [!NOTE]
> 透過 FastTrack 服務來轉移的資料，得於美國或任何一處 Microsoft 的維護設備間進行傳輸、儲存及處理。FastTrack 服務並非專為受特殊法律或法規規範所約束之資料而設計。 
  
## <a name="initiate-phase"></a>起始階段

 **關鍵動作**
  
- 將 Domino 識別為來源郵件平台。   
- 決定 FastTrack Center 是否執行移轉。
    
 **客戶責任**
  
- 提供來源訊息平台的基本資訊，並與 FastTrack Center 確認移轉目的。 
- 參與 FastTrack Center 權益程序的逐步解說。  
- 簽署 FastTrack 服務合約。
    
## <a name="assess-phase"></a>評估階段

 **關鍵動作**
  
- FastTrack Center 與客戶召開移轉研討會。 
- 您完成移轉必要元件，像是移轉問卷和佈建系統管理工作站。    
- 移轉 Domino 的評估會在您的內部部署環境中執行。
    
 **客戶責任**
  
- 佈建 FastTrack Center 用來管理上架和移轉工作的系統管理工作站，如評估、建立複本、稽核、在移轉期間設定轉寄等。
    > [!NOTE]
    > 評估對成功計劃和執行速移轉很重要。它是由需要特定存取 Domino 環境的移轉架構設計人員執行。必要的系統管理工作站元件包括設定來存取所有來源 Domino 郵件伺服器的 Notes 用戶端，和 Azure Domino 複本預備伺服器。 
- 提供移轉小組遠端存取系統管理工作站、帳戶及權限來執行評估與移轉活動。這包括在內部部署和在 Exchange Online 中，佈建移轉所需的系統管理權限的多個帳戶。    
- 開啟防火牆連接埠。輸出連接埠必須在來源 Domino 郵件伺服器與 Azure 預備伺服器之間開啟。其他通訊用連接埠 (如系統管理工作站、來源 Domino 伺服器和 Exchange 伺服器內部部署 (如果有的話)) 也必須開啟。 
- 啟用來源 Domino 環境與 Azure Domino 預備伺服器之間的交互憑證以進行複寫。交互憑證工作是在客戶的 Domino 系統管理員與 FastTrack Center 之間協調。  
- 完成移轉份問卷，會擷取在 Azure 中設定移轉環境所需的資訊 (如工具、指令碼和移轉伺服器)。   
- 請確定 Office 365 的目標信箱已啟用 Messaging Application Program Interface (MAPI) 通訊協定。  
> [!NOTE]
> 某些 Office 365 方案不支援 MAPI 通訊協定。若要移轉資料，這些方案的信箱必須在移轉事件發生之前轉換為支援 MAPI 的方案。移轉完畢之後，可以重新變更這些方案。 
  
## <a name="remediate-phase"></a>修復階段

 **關鍵動作**
  
- FastTrack Center 會檢閱移轉評估報告，並測試您使用問卷所提供的詳細資料。   
- 必須為您完成 FastTrack Center 所建議的修復項目。
    
 **客戶責任**
  
- 依據 FastTrack Cente 提供的指導方針修復 Domino 環境 (例如，在郵件檔案中，設定識別為遺失的任何必要權限)。  
- 確定 Domino 信箱低於移轉所允許的最大大小。
    > [!NOTE]
    >  雖然 FastTrack 會移轉多達允許的總目標大小的 85% 信箱，但嘗試移轉大於 2 GB 的信箱會帶來額外的風險，如：    <br/> 延長移轉持續時間。    <br/> 佔用移轉其他信箱時所用的資源。    <br/> 大幅增加錯誤率。 
- 準備要移轉的郵件資料庫及其存取控制清單 (ACL)。您必須執行一些修復步驟，才能將郵件資料庫及其權限成功移轉至 Exchange Online 的共用信箱。其中部分步驟如下： 
  - 移除 Domino 目錄中的現有郵件資料庫項目並建立新的個人記錄。
  - 在內部部署 Active Directory 中建立擁有郵件功能的萬用安全性群組，其同步至 Office 365 Azure Active Directory，並且用來在 Exchange Online 中設定共用信箱上的權限。 這會將郵件資料庫的權限集轉移至 Exchange Online 的共用信箱。
    
> [!NOTE]
> 當一般使用者準備就緒，並且經過新的郵件系統與用戶端訓練後，即可立即啟動。 
  
## <a name="enable-phase"></a>啟用階段

 **關鍵動作**
  
- FastTrack Center： 
    - 在 Azure 中設立移轉環境。  
    - 在內部部署系統管理工作站上設定移轉工具。 
    - 設定並示範如何使用自動匯入工具。  
    - 進行所有移轉元件驗證，並執行測試移轉。
    
 **客戶責任**
  
- 負責排程信箱移轉的人員，必須瞭解如何使用自動匯入工具。您可以使用這個工具將移轉排程匯入排程資料庫中，讓 FastTrack Center 用來執行預先移轉活動。 
- 執行預先移轉活動，如匯入使用者排程、分析稽核報告、修復任何問題，以及重新匯入有問題的使用者帳戶。
    
預先移轉活動是在您與 FastTrack Center 之間協調。匯入使用者移轉排程後複寫至 Azure。 
    
> [!NOTE]
> 複寫所需的時間視資料量而定。FastTrack Center 接著會執行稽核來判斷移轉整備度。會將稽核結果提供給您，通常需要進行後續修復。由於它們必須在使用者的排程移轉之前開始，因此將這些步驟統稱為「T-minus」。 
  
## <a name="migrate-phase"></a>移轉階段

 **關鍵動作**
  
- FastTrack Center：
    - 執行試驗與快速移轉。  
    - 執行移轉事件和 T-minus 活動。
    - 提供移轉後協助。
    
 **客戶責任**
  
- 在移轉 21 天前識別並匯入移轉排程。
    > [!NOTE]
    > 這項工作很重要，因為預先移轉活動牽涉到修復，並可能在實際移轉日 (T-0) 之前重試在不同階段建立複本。移轉一些信箱時，正在其他信箱上執行 T-minus 活動。這必須適當規劃和協調。 
- 修正在 T-minus 活動過程中識別的問題。
- 解決並修正會影響移轉活動的任何 Domino 伺服器問題。 
- 與一般使用者溝通即將來臨的移轉日期。
- 為新的郵件系統與用戶端執行一般使用者整備活動和訓練。   
- 識別並報告移轉後問題。FastTrack Center 會提供移轉後協助直到移轉後 T+5 日，之後您必須自行負責。您可以記錄移轉後票證問題，像是遺漏電子郵件、行事曆項目和連絡人，或信箱中有重複的項目。
    
FastTrack Center 不涵蓋部署、授權費用，或支援目錄準備 (包括 Domino 至 Active Directory 目錄同步處理)、Notes 應用程式交互操作性的軟體附加元件、自我服務移轉，或封存檔移轉等相關事宜。
  

  

