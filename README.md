## 我的餐廳清單 (S2-3 CRUD)

## 專案畫面

![This is an image](https://github.com/Playpaper/restaurant-list-crud/blob/main/public/images/home.png)
![This is an image](https://github.com/Playpaper/restaurant-list-crud/blob/main/public/images/detail.png)
![This is an image](https://github.com/Playpaper/restaurant-list-crud/blob/main/public/images/new.png)

## Features - 產品功能
:one: 使用者可以瀏覽所有的餐廳。

:two: 使用者可以瀏覽一家餐廳的詳細資訊。

:three: 使用者可以新增一家餐廳。

:four: 使用者可以修改一家餐廳的資訊。

:five: 使用者可以刪除一家餐廳。

:six: 使用者可以依 "餐廳中/英文名稱、分類、評分" 等組合搜尋。

## Environment SetUp - 環境建置
- Runtime : Node.js
- Framework : Express@4.17.1
- Template Engine : Express-handlebars@4.0.2
- Database : MongoDB + mongoose@5.9.7
> :heavy_check_mark : Check package.json for other dependencies

## Installing - 專案安裝流程
:one: 開啟終端機, 複製此專案至本機電腦:
```
git clone https://github.com/Playpaper/restaurant-list-crud.git
```
:two: 進入存放此專案的資料夾
```
cd restaurant-list-crud
```
:three: 安裝 express
```
npm i express@4.17.1
```
:four: 安裝 handlebars
```
npm i express-handlebars@4.0.2
```
:five: 安裝 nodemon (如已安裝可跳過此步驟)
```
npm install -g nodemon
```
:six: 新增種子資料
```
npm run seed
```
當終端機出現以下字樣時，表示種子資料已新增至資料庫，按下 ctrl + c 結束執行

> MONGODB connected!

> done!

:seven: 啟動伺服器
```
npm run dev
```
:eight: 當終端機出現以下字樣時，表示伺服器已啟動
```
The express server is listening on http://localhost:3000
```
