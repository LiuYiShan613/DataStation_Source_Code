# DataStation_Source_Code

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
  - item2vec.ipynb利用item2vec找出與購買商品最相似的商品
  - RFMbased_customer_value_predict.ipynb 分析高價值顧客作為促銷目標

C. 資料處理
  - IQR.ipynb 去除原始資料的IQR欄位

D. 檔案集
  - specialday13.csv 2020-2021年日銷售額最高的前2%日期列表 (作為促銷常購清單)
  - specialdaylist.csv 2020-2021年日銷售額最高的前20%日期列表 (去除日期成為常態時間)
  - highsale_new.csv 特殊節日的高銷量產品列表
  - value_new.csv 特殊節日高價值商品列表
