# AC_2-3_A4_RestaurantList
這是Alpha Camp 2-3後端專修的A4作業。

本作業功能清單如下：
  1. 載入種子資料後，首頁(index)可顯示來自restaurant.json中的所有餐廳資訊，包含餐廳名稱、種類、評分、圖片。
  2. 使用者可於搜尋框輸入餐廳名稱、英文名稱或分類之關鍵字，點下搜尋鍵後可顯示分類或名稱符合關鍵字的餐廳列表。
  3. 使用者點擊某一餐廳，或點下"詳細資訊"連結後，可瀏覽該餐廳的詳細資訊，包含餐廳地址、電話號碼及描述，並可編輯餐廳資訊或刪除該餐廳，或是返回首頁。
  4. 使用者可針對某一餐廳，點擊"編輯資訊"來編輯該餐廳資訊。
  5. 使用者可刪除餐廳。
  6. 使用者可新增餐廳。

安裝步驟:
1. 指令 git clone https://github.com/Cindy-Chiu/restaurant_list.git
2. 指令 cd (存放資料夾)
3. 指令npm install
4. 指令npm i nodemon
5. 指令 npm i express@4.17.1
6. 指令npm i mongoose@5.9.7
7. 指令npm i express-handlebars@4.0.2
8. 指令 npm i body-parser
9. 指令 npm run seed載入種子資料
10. 指令npm run dev 並會看見終端機回傳
"Express is listening on localhost:3000
mongodb connected!"
