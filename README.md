# 🎣 極限釣客 3D Pro：全戰術實戰競技場 (Ultimate Angler 3D Pro)

<p align="center">
  <img src="watermarked_img_2634906738711937652.jpg" alt="Ultimate Angler 3D Pro Poster" width="800" style="border-radius: 16px;">
</p>

<p align="center">
  <b>一元化單頁（Single-File）網頁版 3D 擬真釣魚競技與遊戲化學習平台</b><br>
  <i>「告別新手陣痛期！從操竿手感、浮標訊號、煞車（Drag）調校到 AI 對手競技，帶你掌握實戰釣術。」</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Three.js-3D%20Engine-brightgreen?style=for-the-badge&logo=three.js" alt="Three.js">
  <img src="https://img.shields.io/badge/HTML5-Canvas%20WebGL-orange?style=for-the-badge&logo=html5" alt="HTML5">
  <img src="https://img.shields.io/badge/Web%20Audio-Procedural%20Sound-blue?style=for-the-badge&logo=webaudio" alt="Web Audio">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-Responsive%20UI-38bdf8?style=for-the-badge&logo=tailwindcss" alt="Tailwind CSS">
</p>

---

## 📖 專案緣由與動機 (Motivation & Story)

### 💡 緣由 (Origin)
許多釣魚初學者在剛接觸釣魚時，常面臨**「魚訊難判讀」、「拋投容易掛底斷線」、「缺乏實戰操竿手感」**等門檻，導致頻頻挫折。傳統的教學多為文字或影片，缺乏**即時互動與反覆練習**的機制。

### 🎯 動機 (Goal)
本專案旨在打造一個**兼具娛樂性與教學價值的網頁版 3D 模擬器**，將真實釣魚的核心知識（如煞車車力控制、構造/地形尋魚、真餌與路亞搭配、浮標頓點判讀）轉化為直觀的 3D 遊戲機制。透過**擬真物理計算、音效反饋與 AI 對手競技**，讓使用者能夠在零成本的環境下反覆練習，直到徹底掌握釣術！

---

## 🔥 核心特色 (Key Features)

### 1. 🌊 四大實戰釣法系統 (4 Fishing Disciplines)
* **路亞擬餌 (Lure Fishing)**：支援 Minnow、Popper、VIB 等假餌，搭配 Jerking、Jigging、Popping 等抽竿動作誘發水花爆咬。
* **前打釣法 (Chinu Front-Strike)**：高敏感度竿尾，咬鉛深度控制，專攻消波塊與防波堤縫隙的底棲黑鯛與石斑。
* **浮標磯釣 (Iso Float Fishing)**：棚高精準調校，模擬實時水流與浮標「頓點」、「沉標」、「走標」咬鉤訊號。
* **遠投沉底 (Surf & Bottom Rig)**：重鉛遠投搏擊遠岸深場魚群，搭配竿尖鈴聲與警示音訊。

### 2. 🎮 原生 3D 第一人稱視角與極速相容引擎
* **零依賴單檔案結構**：採用原生 HTML5 Canvas / Three.js 數學透視繪圖，免安裝、免跨域，任何瀏覽器點開即玩。
* **第一人稱視角 (FPS)**：滑鼠靈敏拖曳視角、動態 3D 釣竿與釣線張力渲染。
* **動態晝夜與白天地圖**：包含「東防波堤」、「陽光湖畔」、「碧海礁岩」與「深海船釣」四大場景。

### 3. ⚔️ 搏魚物理與 AI 對手聯賽 (Fight Physics & AI Competitor)
* **煞車 (Drag) 與張力調校**：獨家 Tension Bar 物理機制，需實時調整煞車拉力（Drag 1.0kg ~ 10.0kg），避免張力過高斷線。
* **AI 競技對手**：實時連線排行榜模擬，與 NPC 對手（如「路亞狂人·阿豪」）進行總重量限時比拼。

### 4. 🎵 Suno AI 專屬主題曲與聲學引擎
* **《揮桿！極限釣客 (Fishing Groove)》**：內建由 Suno AI 產出的 Funk / Jazz / Country 樂風主題曲與音效 prompt。
* **Web Audio 聲學**：程序化生成捲線器齒輪聲、水花噴濺聲與咬鉤警報。

---

## 🚀 開發與進化歷程 (Development Timeline)

```text
[階段 1: 需求發想] ───► [階段 2: 四大釣法] ───► [階段 3: 3D白天地圖] ───► [階段 4: Suno主題曲] ───► [階段 5: 一頁式官網]
「想學釣魚卻做不好」     擴充前打、磯釣、       陽光天空、透明水面      創作 Acoustic Funk     整合歷程、線上3D
 網頁遊戲化平台雛形       路亞、遠投與真餌       與消波塊/礁岩地圖        樂曲與提示詞 Copier    試玩與典藏海報展示
```

1. **雛形建立**：針對新手缺乏操竿手感問題，設計 Canvas 2D 釣魚學習模擬器。
2. **戰術擴充**：應使用者需求，導入真餌（活蟹、青蝦、沙蟲）與路亞擬餌，並實現前打、磯釣、路亞與遠投 4 大釣法邏輯。
3. **3D 視效升級**：升級為第一人稱 3D 視角，加入晴朗天空、動態水波與防波堤、湖畔等多樣化白天地圖。
4. **主題曲創作**：運用 Suno AI 開發專屬主題曲《揮桿！極限釣客》，融合 Acoustic Funk, Country, 木吉他 Solo 與流水音效。
5. **一頁式旗艦官網與高相容引擎**：整合一頁式（One-Page）品牌官網、典藏遊戲海報，並重構零依賴的 3D Canvas 遊戲引擎，解決瀏覽器相容性與 Pointer Lock 衝突。

---

## 🛠️ 技術架構 (Technology Stack)

* **前端框架 / 繪圖引擎**：HTML5, JavaScript (ES6+), Canvas 2D / WebGL, Three.js
* **UI 與視覺設計**：Tailwind CSS, Glassmorphism, Font Awesome 6
* **音效與音樂**：Web Audio API (Procedural Audio Synthesis), Suno AI Engine
* **部署與相容性**：100% Single-File Architecture (無跨域 CORS 限制，支援跨平台桌面與行動裝置瀏覽器)

---

## 🎮 操作指南 (Controls & How to Play)

| 操作動作 | 控制方式 | 說明 |
| :--- | :--- | :--- |
| **旋轉視角** | 滑鼠左鍵拖曳 / 觸控拖曳 | 360 度觀察水面與周遭地形結構 |
| **蓄力拋投** | 點擊【🎯 蓄力拋投】按鈕 | 第一次點擊開始蓄力，第二次點擊確定拋投距離 |
| **咬鉤警報** | 自動判定 | 浮標沉入水中並發出警告聲，進入搏魚模式 |
| **持續收線** | 長按【🔄 持續收線】按鈕 | 控制釣線張力將魚拉近岸邊 |
| **煞車 (Drag) 調校**| 點擊【+】/【-】按鈕 | 調整捲線器車力，防止張力條爆表斷線 |

---

## 🎵 Suno AI 主題曲 Prompts

若您想使用 Suno AI 重新生成或擴充主題曲，可直接使用以下標籤：

```text
Style of Music:
Acoustic Funk, Jazz Country Fusion, Smooth Groove, Upbeat, Wood Guitar Solo, Conga, Bongo, River Water Sound FX, Bright, Relaxing Masterpiece
```

---

## 📄 授權條款 (License)

本專案採用 **MIT License** 授權，歡迎自由分發、修改與作為教學用途。

```text
Copyright (c) 2026 Ultimate Angler 3D Pro Team
Permission is hereby granted, free of charge, to any person obtaining a copy...
```
