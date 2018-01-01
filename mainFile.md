# #OpenCart/系統主要文件#

> Model 數據庫層 |
> View 模版展示 |
> Controller 主要代碼層 | 
> Language 本地化 |

---
## 前台的產品頁面，主要有4個相關文件: 
　　M: \catalog\model\catalog\product.php 

　　V: \catalog\view\template\product\product.tpl 

　　C: \catalog\controller\product\product.php 

　　L: \catalog\language\english\product\product.php 

## 管理後台, 如要編輯這些文件, 也主要有下面這4個文件: 
　　M: \admin\model\catalog\product.php 

　　V: \admin\view\template\catalog\product.tpl 

　　C: \admin\controller\catalog\product.php 

　　L: \admin\language\english\catalog\product.php

---
## C-前台控制程序列表-catalog/controller  
### Catalog / controller 49

* account 會員功能 13

　　|—— account.php 會員功能主頁 

　　|—— address.php 會員功能-地址管理 

　　|—— create.php 創建賬號 

　　|—— download.php 會員功能-商品下載 

　　|—— edit.php 會員功能-編輯個人資料 

　　|—— forgotten.php 取回密碼 

　　|—— history.php 會員功能-訂單記錄列表 

　　|—— invoice.php 折扣券接收處理程序 

　　|—— login.php 登入 

　　|—— logout.php 登出完成頁 

　　|—— newsletter.php 會員功能-電子報訂閱取消 

　　|—— password.php 會員功能-密碼變更 

　　|—— success.php 創建賬號成功訊息 

---
* checkout 結賬功能 9

　　|—— address.php 結賬功能-地址處理(配送,賬單..地址) 

　　|—— cart.php 瀏覽購物清單(購物車) 

　　|—— confirm.php 結賬功能-最後確認 

　　|—— guest_step_1.php 免登入結賬第一步 

　　|—— guest_step_2.php 免登入結賬第二步 

　　|—— guest_step_3.php 免登入結賬第三步 

　　|—— payment.php 結賬功能-選擇付款方式 

　　|—— shipping.php 結賬功能-選擇配送方式 

　　|—— success.php 完成結賬成功消息 

---
* ::common 主要版面:: 7

　　|—— column_left.php 左欄模塊載入 

　　|—— column_right.php 右欄模塊載入 

　　|—— footer.php 頁腳 

　　|—— header.php 頁頭 

　　|—— home.php 首頁 

　　|—— maintenance.php 維護中顯示頁 

　　|—— seo_url.php 網址最佳化處理程序之一(縮短網址) 

---
* error 404錯誤 1

　　|—— not_found.php 無此頁 

---
* feed 網站地圖和訂閱 2

　　|—— google_base.php 網站訂閱(feed) 

　　|—— google_sitemap.php 網站地圖

---
* information 網站資訊 3

　　|—— contact.php 發送信件給店家 

　　|—— information.php 商店文章 

　　|—— sitemap.php 網站導覽

---
* ::module 功能模塊:: 9

　　|—— bestseller.php 暢銷商品 

　　|—— cart.php 購物清單(側欄) 

　　|—— category.php 目錄(側欄) 

　　|—— featured.php 推薦商品 

　　|—— google_talk.php google即時通(側欄) 

　　|—— information.php 商店文章(側欄) 

　　|—— latest.php 最新商品 

　　|—— manufacturer.php 品牌選單 

　　|—— special.php 特價商品 

---
* product 商品功能 5

　　|—— category.php 同目錄商品列表 

　　|—— manufacturer.php 同品牌商品列表 

　　|—— product.php 商品詳細內容頁 

　　|—— search.php 搜索功能 

　　|—— special.php 特價商品列表 

---

> 參考資料[OpenCart - Open Source Shopping Cart Solution](https://www.opencart.com/)


　　#OpenCart