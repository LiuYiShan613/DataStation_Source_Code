# DataStation_Source_Code

家樂福－顧客未來購買商品預測

題目詳述：
為了提供顧客個別化行銷，希望透過家樂福會員過往消費紀錄，了解不同顧客購買行為，針對不同顧客的購買習性提供合適的產品組合進行行銷，提升行銷效率，進而提升營收。
將提供2020/01~2021/12期間客戶消費資料，針對此期間消費之客戶，我們將每位客戶最後一筆消費記錄隱藏作為預測目標，敏感資訊皆已進行處理，期望透過客戶消費歷史資料，了解影響客戶未來購買商品的特徵與習慣，建立一模型預測客戶未來消費之訂單所包含商品，模型準確度以F1 score作評斷標準。

期望成果需求：
找出不同顧客類型其各自的購買行為特徵。
預測2020/01~2021/12期間消費之客戶未來下一筆訂單的購買商品，預測結果以F1 score進行準確度評斷

-------------------------------------------------------------------------------------------------------------------------------------------------


A. 精準行銷用相關檔案
  - Apriori.ipynb 購買商品關聯式分析
  - Festival_productlist.ipynb  節日貢獻銷售額高的商品分析
  - RFM_Cluster.ipynb 顧客RFM分群
  - 1_Kmeans_RFM_origin.ipynb 利用RFM進行K-means分群
  - Day_category.ipynb LSTM回測銷售額與特殊節日提取
  - BG_NBD_origin.ipynb(原始資料)單位時間購買次數與金額預測
  - BG_NBD_no_specialday.ipynb(去除特殊節日)單位時間購買次數與金額預測


B. 顧客行為預測相關檔案
  - Predcit_next_purchased_product.ipynb 顧客購買次數最高的商品
  - item2vec_.ipynb 利用item2vec找出與購買商品最相似的商品
  - RFMbased_customer_value_predict.ipynb 分析高價值顧客作為促銷目標

C. 資料處理
  - IQR.ipynb 去除原始資料的IQR欄位

D. 檔案集
  - specialday13.csv 2020-2021年日銷售額最高的前2%日期列表 (作為促銷常購清單)
  - specialdaylist.csv 2020-2021年日銷售額最高的前20%日期列表 (去除日期成為常態時間)
  - highsale_new.csv 特殊節日的高銷量產品列表
  - value_new.csv 特殊節日高價值商品列表
  - dashboard.xlsm 分析與預測結果儀表板
  - 家樂福_Carry4_決賽成果簡報.ppt 最終成果簡報
