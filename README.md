# 🚀 APEX SNOW ACADEMY | 極速滑雪學堂 

![Apex Snow Academy Banner](https://images.unsplash.com/photo-1551524559-8af4e6624178?q=80&w=1200&auto=format&fit=crop)

**APEX Snow Academy（極速滑雪學堂）** 是一個專為亞洲滑雪愛好者設計的高質感響應式單頁 Web 應用程式 (Single-Page Application)。結合「台灣室內高科技滑雪機訓練」與「日本越後湯澤、北海道二世谷、長野白馬」實地雪場小班制教學，並以強烈運動速度感與霓虹視覺吸引年輕族群。

---

## 🌟 網站核心特色與亮點 (Key Features)

### 1. ⚡ 速度感品牌視覺設計 (High-Energy Visual Style)
- **暗黑極速風格**：採用 `#0b0f19` 鋼鐵暗黑背景，搭配電光藍 (`#00f2fe`)、霓虹綠 (`#39ff14`) 與冰藍色光暈。
- **傾斜速度切邊 (Skew Effect)**：大量運用 12° 斜角切邊標籤與按鈕，凸顯極速切雪的動態快感。
- **全站 RWD 響應式佈局**：支援 Mobile、Tablet、Desktop 跨裝置順暢瀏覽。

### 2. 🎬 Hero 區動態廣告輪播 (Ad Carousel)
- 自動與手動切換雙廣告 Banner：
  1. **CARVE YOUR LIMITLESS PATH**：主打 2026-2027 雪季預約開放與台灣-日本雙基地無縫訓練。
  2. **HOKKAIDO & YUZAWA POWDER MASTER**：主打亞洲教練 1:1 精緻小班與北海道/越後湯澤深雪粉雪特訓。

### 3. ❄️ 日本主要雪場實時雪況與天氣預報 (Live Snow & Weather Forecast)
- 即時呈現 **新潟越後湯澤 (苗場/神樂)**、**北海道二世谷**、**長野白馬山谷** 與 **台灣室內館** 的天候數據：
  - 氣溫 (°C)
  - 24 小時降雪量 (Fresh Snow)
  - 積雪深度 (Snow Depth)
  - 雪質分類 (Powder / Fine Snow)
- 卡片整合「直達行事曆」快捷預約按鈕。

### 4. 🏂 課程系統與【極速雕刻 Carving 專修班】
- **階梯式課程介紹**：初學者體驗班 (L1) ➔ 連續換刃 S-Turn 班 (L2) ➔ 全山粉雪導滑班 (L3)。
- **Scroll-Reveal 動態驚喜卡片**：【極速雕刻 Carving 專修班】卡片採用 `IntersectionObserver` 監聽，當使用者滑動至該區域時才平滑浮現並綻放青藍色霓虹光脈，不會產生左右搖晃的視覺不適。

### 5. 🏔️ 亞洲專業教練團隊 (Pro Asian Coaches)
- 嚴選熟悉亞洲語言（中文/廣東話/英文/日文）且持有 CASI / SAJ / CSIA 國際執照之專業教練。
- 搭配高清晰 **日本雪場實景個人動作照** 與健全的 `onerror` 備用圖像邏輯。

### 6. 📅 彈窗式互動預約行事曆 (Modal Calendar with Booking System)
- **動態跨月切換**：可自由切換選擇 2026 年 12 月、2027 年 1 月、2 月等不同月份。
- **過去日期鎖定**：自動判斷當前日期，**過往日期自動呈灰色劃線並禁選 (`cursor-not-allowed`)**。
- **熱門/額滿狀態提示**：
  - **藍字/綠框**：剩餘名額，點擊可直接帶入預約表單。
  - **灰色/劃線**：顯示「已額滿」，禁止點擊預約。

### 7. 📷 【日本雪景】沉浸式相片集與彈窗放大 (Japan Snowscapes & Lightbox)
- 展示越後湯澤神樂、北海道羊蹄山、苗場夜滑煙火等高畫質實景照片。
- **Lightbox 彈窗放大**：點擊任意相片即可開啟全螢幕高解析放大圖，附帶地點說明與預約快捷鍵。

### 8. 🎿 雪具租借動態試算表單 (Gear Rental Calculator)
- 提供單板/雙板全套裝備、防護套組與租借天數即時價格試算，支援站前門市取件或飯店直送。

---

## 🛠️ 技術架構 (Tech Stack)

| 技術項目 | 說明 / 函式庫 |
| :--- | :--- |
| **Frontend Framework** | HTML5, Tailwind CSS (via CDN) |
| **Icon Library** | Lucide Icons (`lucide.createIcons()`) |
| **Typography** | Google Fonts (`Teko`, `Noto Sans TC`) |
| **JavaScript** | Vanilla ES6+ (原生 JavaScript，零額外框架依賴) |
| **Design Pattern** | Single Page Application (SPA), Modal Overlay System, Lightbox Pattern |

---

## 📁 檔案結構 (Project Structure)
