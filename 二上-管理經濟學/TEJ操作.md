# TEJ軟體操作
## 下載與登入
> 當前版本 1.7.4.2

> 可以參考老師的影片[TEJ下載與安裝-10012024](https://drive.google.com/drive/folders/11t9PUlSAXrryReSPdRjcH8X_5qRKeKgv)

1. 從[學校網站](https://tej.lib.nkust.edu.tw/main.htm)下載
2. 安裝檔案的時候記得點擊Smart Wizard，並且要先關掉所有的Excel檔案
3. 進入帳號 (USER ID)：NKUST ，密碼(PASSWORD)： TEJ

## 在Excel中使用TEJ smart Wizard
> 可以參考老師的影片[TEJ使用說明-10012024](https://drive.google.com/file/d/1257qDeWq6To9T7KMIArs0Qrfq24vU3RL/view?usp=sharing)

### 第一步：打開TEJ smart Wizard
1. 點擊Excel增益集中有一支筆的那個鈕
<img width="360" alt="image" src="https://github.com/user-attachments/assets/61b36832-9fe3-449a-ba8f-a22bb910c1e3">

2. 確認出現這個畫面，這次會用到的欄位如圖片中打勾的地方
<img width="570" alt="image" src="https://github.com/user-attachments/assets/3ed43aac-5d94-4f58-9cf2-241336b60664">

### 第二步：抓出公司資料
1. 選取資料－－「DB類別」選取資料所在資料庫＞「資料名稱」選取＞「可選取欄位」選取需要資料，點選下方的選取按鈕
3. 設定日期－－依需要的日期選，如果要從之前的月份排到現在，記得取消"降冪"的勾勾後再重案一次查詢；然後點選資料頻率（這次用月）
4. 選取公司－－從公司分類選取公司，分類部分可以從產業找，也可以直接key公司名稱下去找
5. 匯出至Excel－－一般來說直接點就好，如果要調整版面可以先點下一步

### More TIPs
- 不知道想要的資料在哪個DB可以打開TEJ+，直接在裡面的搜尋輸入關鍵字，會跳出來對應的DB，再回去Wizard選就可以了
- 這次要的資料在這些DB
   - 收盤價 --> TEJ股價資料庫＞未調整股價(月)＞收盤價(元)
   - 成交量 --> TEJ股價資料庫＞未調整股價(月)＞成交量(百萬股)_月
   - PE-ratio --> TEJ股價資料庫＞未調整股價(月)＞本益比-TEJ
   - 單月營收成長率 --> TEJ Company DB＞月營收盈餘＞單月營收成長率％
   - 每股盈餘 --> TEJ IFRS Finance-國際會計準則＞IFRS以合併為主簡表(累計)-全產業＞每股盈餘(記得日期是要下載季資料)
