# 甘油高值化環氧氯丙烷之製程改善

### The Improved Process of Producing Epichlorohydrin from Glycerol 

#### pdf檔：關於模擬參數調整的細節及文字敘述
#### PPT檔：本報告的邏輯思路及流程解析

### 簡介
我於大四上學期修習化工程序實作課程，將全班分為四人一組，進行文獻查找、動力學模擬、設計製程、使用模擬程式「ASPEN PLUS」進行工業製程模擬，並粗估成本及收益。我在小組內主要負責文獻蒐集查找、設計製程、少部分ASPEN模擬及投影片整理及美觀的部分。

### 專題概述
由於近年來國外的生質柴油產業蓬勃發展，甘油作為生質柴油的副產物，世界上也產生甘油過剩的問題；因此若將甘油作為反應物，並且轉換為較高價值的環氧氯丙烷，便可以有效且有利得解決上述問題。環氧氯丙烷為一種有機材料，常見用途為複合材料、黏合劑或環氧樹脂地坪。加上傳統工業製作環氧氯丙烷的產業有（以acyl chloride + HOCl 製備）有產率低、耗能大的問題；而若以 acyl chloride + H2O2 製備，則需擔心雙氧水儲存或一爆炸的危險；因此我們選擇以甘油作為反應物進行探討。

### 內容
#### 目錄：
![image](https://user-images.githubusercontent.com/84501216/119268189-6be5d100-bc24-11eb-9d6c-b7deaab78143.png)

本製程設計參考了2016年Almena等人的文獻，進行一些小部分修改，並以ASPEN進行模擬。

##### 主要參考文獻：Almena, Alberto, and Mariano Martín. "Technoeconomic analysis of the production of epichlorohydrin from glycerol." Industrial & Engineering Chemistry Research 55.12 (2016): 3226-3238.

### 反應概念：![image](https://user-images.githubusercontent.com/84501216/119268898-95ecc280-bc27-11eb-8b78-58a4bd8fba8b.png)
### 反應流程：![image](https://user-images.githubusercontent.com/84501216/119268354-270e6a00-bc25-11eb-9a47-b68ae7e5a1be.png)

  其中我們針對甘油氯化反應的動力學有多加探討，針對不同文獻所提出的反應機制及動力學參數都有嘗試。嘗試後發現兩種產率最好的催化劑為乙酸（Acetic acid）及己酸（Hexanoic acid），且在查找文獻的過程中發現，由於他們分子量、物化性的不同，會進行不同的反應機制，因此對於兩種dichlorohydrin幾何異構物產生的比例及動力學都有差異。因此我們對於兩種催化劑都進行了模擬及比較。（細節皆於投影片中）

#### 不同催化劑於甘油氯化反應的反應途徑
![image](https://user-images.githubusercontent.com/84501216/119268650-786b2900-bc26-11eb-85ae-b05431cedff4.png)

### 改良文獻製程：
#### 文獻製程：
![image](https://user-images.githubusercontent.com/84501216/119268737-e44d9180-bc26-11eb-8f27-f121cf21a9e3.png)
#### 改良後製程：
![image](https://user-images.githubusercontent.com/84501216/119268771-05ae7d80-bc27-11eb-9266-eb3cc436cacf.png)
![image](https://user-images.githubusercontent.com/84501216/119268795-1c54d480-bc27-11eb-88de-825efc024786.png)

### 經濟評估
數值討論及分析皆在檔案內，預估設廠於美國加州，第一年淨收入1,972,000 USD，第二到十年淨收入4,240,000 USD（儀器設備價格來源多於網路上或ASPEN內建，廠商也大多採報價制，因此可能有些成本過於樂觀評估）。

### 分工
蘇峰玉：甘油純化部分模擬、少部分氯化反應模擬、投影片整理及排版
（關於投影片製作：使用簡單圖形拼湊、畫出反應器或蒸餾塔等單元，順著邏輯製作動畫配合口頭報告，在網路上公開的圖庫找一些icon製作目錄條等等）

林夢蝶：氯化反應動力學模擬（催化劑AA）、DCH反應模擬

余浩安：氯化反應動力學模擬（催化劑HA）、DCH反應模擬

胡昇旻：文獻整理、紙本報告統整
