# Kalimba 17-Key Simulator (拇指琴模擬器)

一個基於 Web 技術開發的 17 音 Kalimba 模擬器。單一 HTML 檔案設計，輕量、無需安裝，支援手機與電腦瀏覽器，帶給您隨身攜帶的療癒音樂體驗。

## ✨ 特色 (Features)

*   **真實物理模擬**：不使用錄製的 MP3，而是透過 Web Audio API 即時合成聲音，模擬金屬撥片的物理振動特性。
*   **單一檔案**：所有程式碼 (HTML/CSS/JS) 整合在一個 `.html` 檔案中，方便分享與離線使用。
*   **響應式設計**：
    *   針對手機直式螢幕優化。
    *   琴鍵長度自動適應，並預留底部空間以防被手機瀏覽器工具列遮擋。
    *   支援多點觸控 (Multi-touch)，可同時彈奏和弦。
*   **視覺風格**：
    *   溫暖的木紋質感琴身。
    *   經典的圓形音孔設計。
    *   標準簡譜標示 (數字 + 八度點)。

## 🚀 如何使用 (Usage)

1.  **下載**：將 `kalimba.html` 下載至您的電腦或手機。
2.  **開啟**：直接使用瀏覽器 (Chrome, Safari, Edge 等) 開啟該檔案。
3.  **彈奏**：
    *   **手機**：輕觸琴鍵即可發聲，支援雙手拇指操作。
    *   **電腦**：使用滑鼠點擊琴鍵。
    *   *注意：首次進入可能需要點擊畫面任意處以啟動音效引擎。*

## 🛠️ 技術細節 (Technical Details)

*   **Language**: HTML5, CSS3, JavaScript (ES6)
*   **Audio**: Web Audio API (OscillatorNode, GainNode)
*   **Layout**: Flexbox, CSS Variables, CSS Clamp()
*   **Notation System**: Jianpu (Numbered Musical Notation)
    *   No dot: Middle range (中音)
    *   One dot: High range (高音)
    *   Two dots: Very high range (倍高音)

## 📝 版本紀錄

*   **v1.0**: 基礎功能與音頻合成。
*   **v1.1**: 視覺優化 (木紋、笑臉音孔)。
*   **v1.2**: 手機版面配置調整 (琴鍵上移、防遮擋優化)。
*   **v1.3**: 音質優化 (修正高音刺耳問題)。

---
*Created by Gemini CLI*
