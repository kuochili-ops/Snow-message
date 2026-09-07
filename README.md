# 𓃥 白六白雪訊息傳遞 (SnowFalls Message Generator)

一個極致療癒、具備 3D 擬真視覺與物理飄雪模擬的 **SnowGlobe 飄雪夜燈訊息傳遞 App**。

點擊連結即可線上體驗：[https://kuochili-ops.github.io/Snow-message/](https://kuochili-ops.github.io/Snow-message/)

---

## ✨ 專案亮點 (Key Features)

* **🔄 360° 立體 X 軸翻轉效果**
  * 模擬實體雪花夜燈（Flowing Night Light），一鍵啟動立體 360 度上下翻轉。
  * 翻轉過程中，堆積在底部的雪花會重新擴散，並隨物理重力再次緩緩落下。

* **❄️ 擬真雪地凹陷刻印文字 (Engraved Snow Effect)**
  * 利用多重陰影與邊緣高光技術，呈現文字宛如被深鑿刻印在厚重雪地上的質感。
  * 支援動態字體演算法：字數少時會自動放大佔滿雪層，文字過多時自動智慧排版與換行（完美支援中文與英文單字完整性）。

* **💡 4 款特色路燈造型**
  1. **經典復古**：歐式多邊形金屬罩燈與溫暖黃光。
  2. **懸臂聚光**：現代彎曲懸臂與單一錐形投射光束 (Spotlight Cone)。
  3. **雙頭歐式**：雙臂對稱華麗花燈。
  4. **極簡圓球**：當代極簡高腳柔光圓球燈。

* **📜 輪播訊息與即時翻轉**
  * **換行即分頁**：在輸入框中按下 Enter，即可設定多頁輪播訊息。
  * **落盡即翻轉**：當畫面上最後一片雪花觸地落盡時，自動觸發 360° 翻轉切換至下一頁訊息。
  * **隨機路燈模式**：可開啟「換頁隨機變換路燈」，每一次翻轉都帶來全新視覺驚喜。

* **🔗 專屬訊息連結分享**
  * 支援將你設定的**客製化訊息、路燈款式與輪播設定**一鍵編碼為專屬網址。
  * 收件人開啟連結即可直接欣賞專屬於他的飄雪祝福動畫！

---

## 🛠️ 技術架構 (Built With)

* **HTML5 Canvas**：粒子系統（Particle System）模擬雪花浮力、風向擺動、沉積與光影輻射。
* **CSS3 3D Transforms**：使用 `perspective` 與 `rotateX` 實現流暢的立體翻轉動畫與鏡面玻璃質感。
* **Vanilla JavaScript (ES6+)**：輕量化無第三方套件依賴，包含自訂動態文字排版與 URL Hash 編解碼邏輯。

---

## 🚀 快速上手 (Quick Start)

1. 克隆此專案：
   ```bash
   git clone [https://github.com/kuochili-ops/Snow-message.git](https://github.com/kuochili-ops/Snow-message.git)
