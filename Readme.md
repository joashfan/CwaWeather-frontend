🤖 NEURAL_WEATHER_LINK v2.0 - 夜城氣象節點
這是一個充滿賽博龐克 (Cyberpunk) 氛圍的個人天氣終端機。我們將原始的氣象數據，轉化為未來風格的戰術面板報告，讓查看天氣變得像駭入神經網路讀取機密數據一樣酷炫。

📂 專案結構
本專案採用純靜態網頁結構，無需複雜的編譯協議即可啟動。

Plaintext

NEURAL_WEATHER_LINK/
├── images/               # 💾 視覺資料庫
│   ├── bg1.jpg           # 🌃 預設背景：霓虹夜城 (陰天/夜晚)
│   ├── bg2.jpg           # 🌧️ 雨天背景：雨中貓咪
│   ├── bg3.jpg           # ☀️ 晴天背景：荒野日出
│   └── icon-v2.png       # 系統圖示 (Favicon)
├── index.html            # 🧬 核心啟動檔案 (HTML/CSS/JS)
└── .gitignore            # 版本控制遮罩
✨ 特色功能
沉浸式未來介面：

依據時間與天氣狀態切換「夜城」、「荒野」或「雨巷」場景。

玻璃擬態 (Glassmorphism) 風格的資訊懸浮視窗。

霓虹游標：操作網頁時，滑鼠會化身為帶有光暈軌跡的準心。

互動全息效果：滑鼠懸停在天氣卡片上時，會產生 3D 視差 (Parallax Tilt) 與故障 (Glitch) 特效，如同操作全息投影。

戰術生存建議：

將降雨機率轉化為「酸雨護盾 / 防水力場」的裝備建議。

將氣溫轉化為「散熱模組 / 核心保溫」的系統調節指南。

即時衛星串接：

串接中央氣象署 API (透過加密通道連線)。

載入時顯示「神經網路同步率」風格的 Loading 動畫與 CRT 掃描線特效。

🚀 如何啟動
確認 images 資料夾內已載入以下視覺素材：

bg1.jpg (核心背景)

bg2.jpg (雨天變體)

bg3.jpg (晴天變體)

icon-v2.png

直接使用瀏覽器 (Chrome, Edge 等 Cyberdeck 終端) 開啟 index.html 即可建立連線。

🛠️ 技術說明
HTML5 / CSS3 / Vanilla JavaScript：無依賴外部框架，極致輕量化代碼。

Google Fonts：使用 Orbitron (標題) 與 Share Tech Mono (數據)，營造終端機與數位儀表板的視覺風格。

CSS Variables：定義霓虹色系變數 (--neon-cyan, --neon-pink)，方便快速調整主題色調。

RWD 響應式設計：支援手持裝置與桌面戰情室版面瀏覽。