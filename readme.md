# IG Follower 變動追蹤器 Pro+ (v1.2.0)
# IG Follower Tracker Pro+ (v1.2.0)

![Instagram](https://img.shields.io/badge/Tools-Instagram-pink?style=for-the-badge&logo=instagram)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.2.0-green?style=for-the-badge)

---

## 🇺🇸 English Version

A lightweight, privacy-focused Instagram follower analysis tool. No password required. Runs entirely in your local browser to ensure your data stays private.

### 🌟 Key Features
* **Change Tracking**: Accurate identification of "New Followers" and "Unfollowers" by comparing JSON files.
* **Local Storage**: Data is saved in browser LocalStorage; no data lost on refresh.
* **Privacy First**: **No data is uploaded to any server**. Your information stays on your machine.
* **Enhanced UI**:
  * Real-time profile picture preview with Lightbox zoom.
  * Direct links to anonymous story viewing tools.
  * Sorting by Index, Name, Status, or Date, plus keyword search.
* **Backup System**: Export/Import JSON backups with format: `IG_Tool_Backup_YYYYMMDDhhmm.json`.

### 🚀 How to Use
1. **Get Data**: IG Settings -> Download Your Information -> "Followers and Following" -> **JSON** format.
2. **Import**: Copy the content of `followers_1.json`.
3. **Analyze**: Paste into the tool and click "🔍 Update List".

### 🛠 Tech Stack
* HTML5 / JavaScript (ES6+)
* Tailwind CSS
* LocalStorage API
* Unavatar API

---
## 🇹🇼 中文版說明 (Traditional Chinese)

一個輕量化、隱私至上的 Instagram 追蹤者變動分析工具。無需提供帳號密碼，完全透過本地瀏覽器執行，確保您的數據安全不外洩。

### 🌟 核心功能
* **變動對比**：比對不同時間點的 `followers.json` 檔案，精確找出「新加入」與「已退追」的用戶。
* **本地存儲**：數據儲存在您的瀏覽器快取 (LocalStorage)，關閉網頁後資料不丟失。
* **隱私安全**：純前端邏輯，**不將任何數據上傳至伺服器**，保障 IG 帳號隱私。
* **增強 UI**：
  * 支援帳號頭像即時預覽與 Lightbox 放大功能。
  * 一鍵跳轉至第三方匿名看限動工具。
  * 多維度排序（序號、名稱、狀態、日期）與關鍵字搜尋。
* **備份機制**：支援導出/導入 JSON 備份檔，檔名格式：`IG_Tool_Backup_YYYYMMDDhhmm.json`。

### 🚀 如何使用
1. **獲取資料**：前往 IG 設定 -> 下載您的資訊 -> 選擇「追蹤者與追蹤中」 -> 格式選 **JSON**。
2. **導入工具**：將解壓縮後的 `followers_1.json` 內容全選複製。
3. **執行分析**：將內容貼入本工具輸入框，點擊「🔍 更新名單」。

### 🛠 技術棧
* HTML5 / JavaScript (ES6+)
* Tailwind CSS (UI 介面)
* LocalStorage API (數據持久化)
* Unavatar API (頭像預覽)
## ⚖️ 授權條款 / License

本專案採用 **MIT License**。您可以自由地使用、修改及分發本程式碼，但請保留原作者的版權聲明。

This project is licensed under the **MIT License**. You are free to use, modify, and distribute the code, provided that the original copyright notice is retained.

---
*Disclaimer: This tool is for educational and personal management purposes only and is not affiliated with Instagram/Meta.*
