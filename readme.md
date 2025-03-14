# 視野科技官網

## 環境需求

請確保你的系統已安裝以下環境：

- PHP `^7.x`
- Composer
- Laravel `^5.x`
- MySQL 或其他相容的資料庫

## 安裝步驟

請依照以下步驟安裝並執行專案：

## clone專案
```
git clone https://github.com/你的帳號/你的專案.git
```
## 進入專案
```
cd 你的專案
```
## 下載套件
```
composer install
```
## 設定環境變數
```
cp .env.example .env
```
##### 資料庫連線資訊
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=你的資料庫名稱
DB_USERNAME=你的資料庫使用者名稱
DB_PASSWORD=你的資料庫密碼
```
## 產專案金鑰
```
php artisan key:generate
```
## 資料庫migrate
```
php artisan migrate
```
