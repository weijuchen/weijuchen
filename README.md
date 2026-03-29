<h1 align="center">Hi 👋, I'm Alice</h1>

##  About me
✨
Junior**資料分析師**，畢業於**英國伯明罕大學（University of Birmingham）電腦科學碩士**，具備法律與資訊科技**跨領域**背景，曾任國泰世華商業銀行資料分析師，具備資料處理、分析與視覺化能力
，個人經驗包括(1)利用Power BI做超商銷售之**數據分析**，使用者可以利用下拉式選單，了解不同年度、產品分類、地區、州別的銷售狀況，並使用Python做時間序列分析，建立模型，預測未來銷售量的趨勢。(2)建置台灣不動產實價登錄資料自動專案，包括資料收集、清洗與儲存流程，使用Python、Spark、Airflow、Minio與PostgreSQL 建立**ETL Pipeline**。對機器學習、深度學習與 LLM 領域充滿熱情，並積極轉型為 **資料工程師**，專注於**資料管線與數據架構建置**。具備**主動學習、邏輯清晰與良好溝通能力**，樂於在實務中解決問題， 並將數據轉化為可落地的商業決策支持。

🌱 目前正在學習 R 語言，用於資料分析與統計應用

<h2 align="center">Skills</h2>

<div align="center">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20BI-%23F2C811.svg?style=for-the-badge&logo=Power%20BI&logoColor=black" />
  <img src="https://img.shields.io/badge/Apache%20Airflow-%23017CEE.svg?style=for-the-badge&logo=Apache%20Airflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Spark-%23E25A1C.svg?style=for-the-badge&logo=Apache%20Spark&logoColor=white" />
  <img src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" />
</div>

## 工作經驗
### 國泰世華商業銀行<BR>
-  工作期間 2025/01 - 2025/07 <BR>
   職位:數據分析師 <BR>
   * 疑似被害人風險評估專案
      * 根據外部業務需求，清理、整理與分析大量被害人相關資料，透過統計分析檢視既有被害人風險模型準確度不足的問題，並提供數據分析與觀察結果，協助優化疑似被害人風險模型與通知策略。
        在維持相同預警效果的前提下，成功將通知名單規模縮減約30%，提升模型的實用性與分行執行意願。
   * 打詐機制優化專案
      * 依據歷史資料與高風險行為特徵，運用 SQL 與 Excel 進行資料萃取與數據分析，並透過視覺化方式整理結果。針對高風險族群進行行為分群與交叉比對，提出相應的防詐策略建議。
        初步測試結果顯示，攔阻績效可提升約10%。



## 個人經驗    
### 不動產實價登錄自動化數據工作流 (ETL)<BR>
-  期間: 2026/02 ~ 2026/03
-  專案描述： 針對內政部實價登錄不動產交易資訊，規劃完整數據流程 (Data Pipeline)，包括ETL設計及開發、資料管理及分析，範圍涵蓋以網路爬蟲技術收集數據、清洗、處理與多層級存儲，旨在將零散的 CSV 原始數據轉化為具備分析價值的結構化數據湖。
-  透過自動化流水線解決手動處理資料的一致性問題，將數據備份與轉換耗時縮短至5分鐘內，達到維護資料 ETL 流程自動化，確保數據處理效率與可靠性。
-  使用 Docker容器化部署 Apache Airflow 與 Spark 開發環境，實現從爬蟲、解壓縮到儲存到minio，自動化調度與任務監控機制。
-  利用PySpark 進行大規模數據清洗，包含處理民國日期轉換、每坪單價單位轉換(平方公尺轉換為坪)等標準化，並將結果儲存到postgreSQL。
-  專案連結:https://github.com/weijuchen/ETL_realestate

### NLP模型比較<BR>
-  期間: 2025-11 ~ 2025/12
-  比較 NLP 在情感分析與文本分類任務中的表現，範圍包括傳統 ML、深度學習與 Transformer 架構
-  利用 Logistic Regression、Linear SVC與 DistilBERT（Hugging Face）多種模型，並於 Amazon Reviews 與 20 Newsgroups 資料集驗證
-  DistilBERT 達到最高 91%+ accuracy，顯著超越傳統方法
-  專案連結:https://github.com/weijuchen/ETL_realestate
    
### 銷售量分析與預測<BR>   
-  專案期間: 2024年
-  資料來源: https://www.kaggle.com/datasets/tanayatipre/store-sales-forecasting-dataset/data?select=stores_sales_forecasting.csv
-  資料庫是超商銷售數據
-  使用Power BI 為數據分析，使用者可以利用下拉式選單，了解不同年度、產品分類、地區、州別的銷售狀況
-  利用時間序列分析，建立模型，預測未來銷售量的趨勢。
-  專案連結: https://github.com/weijuchen/Sales_Prediction

### LINE BOT 智慧防詐平台<BR>                                                                                 
- 專案期間: 2024年
- 使用 LINE Bot 結合 GPT-3.5-turbo 建立防詐系統
- 整合 Selenium、RAG、FAISS、LangChain、Whisper、Python與Flask
- 提供即時詐騙辨識與資訊輔助服務，幫助使用者提高對潛在詐騙的警覺性，並提供必要的資訊輔助
- 專案連結: https://github.com/weijuchen/chat_bot

### A scuba diving web platform to recommend diving spots<BR>
  - 專案期間: 2023/07~ 2023/09
  - 使用 JavaScript、React、HTML、CSS 開發網站，整合天氣 API 與 Google Maps API，並設計推薦功能；過程中自學並完成從 JavaScript 到 React 的轉換，操作API 串接與前端功能開發。過推薦機     制優化使用者搜尋流程，減少約**20%** 的資料搜尋時間。
  - 利用MongoDB 建置後端資料庫，支援會員註冊、使用者資料（如評論與評分）及網站內容管理；同時負責前端問題排除與除錯，提升系統穩定性與使用體驗。
  - 專案連結: https://github.com/weijuchen/ScubaDiving_fullstack

