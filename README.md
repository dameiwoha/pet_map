# pet_map
寵物友善地圖
# 🐾 台灣寵物友善店家互動地圖 (Pet Friendly Map Taiwan)

一個專為毛孩家長設計的單頁 Web 應用程式（SPA），整合互動式地圖與多元篩選功能，幫助使用者輕鬆探索全台寵物友善餐廳、住宿、公園與醫院。

![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## ✨ 核心特色 (Features)

- 📍 **互動式地圖與動態地標**：基於 Leaflet.js 與 OpenStreetMap，提供順暢的地圖瀏覽與自訂地標體驗。
- 🔍 **多重組合篩選**：
  - **關鍵字搜尋**：可精準搜尋店家名稱、地址或簡介。
  - **縣市與類別過濾**：快速切換不同區域（台北、台中、高雄等）與類別（餐廳、旅宿、公園、醫療）。
  - **寵物友善規範標籤**：支援「可落地」、「提供寵物餐」、「大型犬 OK」、「有草皮」等多選標籤組合篩選。
- 🧭 **GPS 即時定位**：一鍵定位使用者當前位置，快速尋找周邊寵物友善去處。
- ❤️ **收藏清單管理**：提供收藏夾功能，方便記錄私藏口袋名單（資料自動持久化至 LocalStorage）。
- ➕ **社群推薦提交**：使用者可自行新增推薦店家，即時更新地圖與列表。
- 📱 **響應式與行動端優化**：針對手機與平板設計切換式（地圖 / 列表）操作介面。

---

## 🛠️ 技術棧 (Tech Stack)

- **前端框架/語言**：HTML5, JavaScript (ES6+)
- **UI 與樣式**：[Tailwind CSS](https://tailwindcss.com/) (CDN)
- **地圖元件**：[Leaflet.js](https://leafletjs.com/) + [OpenStreetMap](https://www.openstreetmap.org/)
- **圖示庫**：[Lucide Icons](https://lucide.dev/)
- **資料儲存**：瀏覽器 `LocalStorage`（無需後端資料庫即可運作）

---

## 🚀 快速開始 (Quick Start)

本專案為無編譯依賴（Zero-build dependency）的純前端專案，無需安裝 Node.js 或執行打包流程。

### 開發與運行

1. **Clone 本專案**：
   ```bash
   git clone [https://github.com/your-username/pet-friendly-map.git](https://github.com/your-username/pet-friendly-map.git)
   cd pet-friendly-map
