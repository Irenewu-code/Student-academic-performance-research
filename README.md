# 國中教育設施品質、教學效能與學生學習表現關係之研究

### 研究目的
本研究旨在瞭解教育設施品質、教學效能與學生學業成績關係之研究；分析不同個別背景變項在教育設施品質、教學效能之差異情形；探討教育設施品質、教學效能與學生學習表現之間的關係與影響力
### 資料名稱
國民中學教育設施品質、教學效能與學生學業成績關係之研究 
### 資料來源
學術調查研究資料庫（SRDA）https://srda.sinica.edu.tw/datasearch_detail.php?id=3522
### 資料變數
  #### 基本資料
  含性別、現任職務、學歷、年資與年齡
  #### 教育設施品質
  分為5類(A1-A5)，每類有5小題，每小題依程度勾選（非常符合5-非常不符合1）
  #### 教學效能
  有四個部分(B1-B4)，其中 B4學生學習表現 為本次研究的預測目標

### 資料前處理
#### 對檔案型態的前處理
將原始的 sav 檔轉檔成 xlsx 檔
#### 對缺失值的前處理：
捨去基本資料缺失、其他特徵有5個以上缺失值的資料，再對剩餘的缺失值使用 mice 方法進行多重插補。

### 資料分析
#### 描述性統計

#### 線性迴歸（linear regression）
使用 lm 套件進行迴歸分析。可以從 p-value 看到 A2充實的教學設備， A3多元的教育設施， A4完善的設施功能 和 A5良好的設施維護 的 p-value 非常小，表示他們對 B4學生學習表現 有顯著影響。 A1舒適的教室環境的 p-value 非常大 (=0.739329)，表示對 B4 學生學習表現沒有顯著影響。
![image]()

### 結論

### 給利害關係人的行動方案



