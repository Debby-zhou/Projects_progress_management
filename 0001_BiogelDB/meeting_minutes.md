# 仿生水膠每週會議紀錄
## 2021.03.28
---
1. 網站選擇欄位分成**Mechanical properties**和**Cell differentiation**
2. 設定一組帳密登入welcome/，保護實驗資料
3. 匯入新版互動式html表格與分割好的score table並直接取代原表
   
   > 03/21更新先不放互動式html表格
4. 網站架構重整：將三端拆分成app，且各自連上相對應的database
5. http更改為https
   
   > https with SSL varification 需處理
6. db.smagel.nchc.org subdomain name取代ip address:81

## 2021.04.09
---
1. analysis/也分成**Predicted engine**和**Cell differentiation**
   
   - Predicted engine:
      * mechanical property
      * Light curing agent
   
   - Cell defferentiation:
      * Tissue category
      * Target gene
2. 完整資料庫使用功能
3. <font color=#ff0000>6/1最終繳交成果</font>

## 2021.04.16

---

1. 兩欄只能點選其中一欄，防止打架情況發生
2. 下週一、二明確網站給予功能評估

## 2021.04.24

---

1. smagel.nchc.org.tw只能連接到仿生水膠平台網站
2. 反向代理各個網址至不同端口，但不顯示在頁面上

## 2021.04.29

---

1. 使用者可自行上傳符合規格的檔案進資料庫
2. 自行上傳的檔案可以顯示在網頁上