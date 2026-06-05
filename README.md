# 🌤️ 晴天餅乾 Happiness Cookie

![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge\&logo=vite\&logoColor=FFD62E)
![EJS](https://img.shields.io/badge/EJS-B4CA65?style=for-the-badge)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge\&logo=sass\&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge\&logo=bootstrap\&logoColor=white)

> 晴天餅乾（Happiness Cookie）為甜點品牌形象網站切版練習專案。
>
> 以手工餅乾品牌為主題，規劃首頁、商品列表、商品詳細頁、購物車、結帳頁與會員中心等頁面。
>
> 專案採用 EJS 模板管理與 SCSS 架構化開發方式，透過團隊協作完成多頁面切版與 RWD 響應式設計練習。
>
> 本專案以前端介面開發為主，著重於版面規劃、元件拆分與跨裝置瀏覽體驗。

---

## 📦 Demo

🔗 https://min82814.github.io/Happinesscookie/

---

## 📸 功能展示

### 首頁

![首頁](./docs/home.gif)

### 商品列表頁

![商品列表](./docs/product-list.gif)

### 商品詳細頁

![商品詳細頁](./docs/product-detail.gif)

### 購物車頁面

![購物車](./docs/cart.gif)

---

## 👨‍💻 我的負責內容

### 商品詳細頁開發

* 商品詳細頁 UI 規劃與版面設計
* 商品詳細頁 RWD 響應式切版
* 商品圖片輪播功能製作
* 顧客評價輪播功能製作
* 側邊購物車（Offcanvas）介面設計
* 加入購物車後側邊購物車展開效果整合

### 首頁共同開發

* 首頁部分區塊切版
* SCSS 樣式維護與整合

### 共用元件

* 共用按鈕樣式設計與 hover / active 互動效果製作

### 團隊協作

* Git 版本控制
* EJS 模板整合
* 團隊協作開發流程

---

## 🌟 頁面規劃

| 頁面    | 說明            |
| ----- | ------------- |
| 首頁    | 品牌形象與主打商品展示   |
| 商品列表頁 | 商品瀏覽介面        |
| 商品詳細頁 | 商品資訊展示與購買流程介面 |
| 購物車頁  | 購物車版面展示       |
| 結帳頁   | 訂購資訊填寫介面      |
| 會員中心  | 個人資料與訂單資訊介面   |

> 本專案以靜態前端切版練習為主，頁面功能以介面展示及互動效果呈現為主。

---

## 🔧 技術棧

### 開發工具

* Vite

### 模板引擎

* EJS

### UI / 樣式

* Bootstrap 5
* SCSS (Sass)

### 版本控制

* Git
* GitHub

---

## 🤝 團隊分工

| 成員        | 負責內容                                                                                    |
| --------- | --------------------------------------------------------------------------------------- |
| **孟**     | ✦會員中心頁面 RWD 切版<br>✦首頁共同開發<br>✦Footer 切版與整合                                              |
| **YiHan** | ✦商品列表頁 RWD 切版<br>✦首頁共同開發<br>✦Navbar 切版與整合                                                  |
| **Wayne** | ✦購物車頁 RWD 切版<br>✦首頁共同開發<br>✦全域 SCSS 變數設定                                                |
| **Min**   | ✦商品詳細頁規劃設計與 RWD 切版<br>✦商品圖片輪播製作<br>✦顧客評價輪播製作<br>✦側邊購物車介面設計與互動整合<br>✦首頁共同開發<br>✦共用按鈕樣式設計與 hover / active 互動效果製作 |

---

## 🖥️ 本地安裝與啟動

### 環境需求

* Node.js v18 以上

### 安裝步驟

```bash
# Clone 專案
git clone https://github.com/MIN82814/Happinesscookie.git

# 進入專案資料夾
cd Happinesscookie

# 安裝套件
npm install

# 啟動開發環境
npm run dev
```

---

## 🗂️ 資料夾結構

```text
.
├─ assets
│  ├─ images
│  └─ scss
│     ├─ base
│     ├─ components
│     ├─ layout
│     ├─ pages
│     └─ utils
│
├─ layout
│  ├─ header.ejs
│  ├─ footer.ejs
│  └─ header-variant.ejs
│
├─ pages
│  ├─ index.html
│  ├─ productlist.html
│  ├─ product.html
│  ├─ shopping-cart.html
│  ├─ checkout.html
│  └─ user.html
│
├─ public
├─ package.json
├─ vite.config.js
└─ main.js
```
