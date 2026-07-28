# AI Engineering 心智模型 | AI Engineering Mental Model

一頁式互動網頁，將 AI Engineering 的核心心智模型視覺化——**Build（建構）× Orchestrate（協調）→ Goal & Outcome（成功指標）**，用樹狀漏斗結構呈現兩大主幹、六大構件與五項成功指標，點擊卡片即可展開詳細說明。

原始框架概念參考自HackProduct的 "AI Engineers Mental Model" 貼文，並依教學用途重新設計、擴充說明與繁體中文化。

🔗 **Live Demo**：啟用 GitHub Pages 後可於 `https://<你的帳號>.github.io/<repo名稱>/` 瀏覽

---

## 內容架構

```
AI Engineering
├── Build 建構
│   ├── Prompts 定義意圖        System Prompt / Few-shot / Memory & Context
│   ├── Skills 執行專業任務     Code Interpreter / Data Analyst / Web Researcher
│   └── Plugins/MCPs 連接外部世界  Files & Docs / Databases & APIs / Tools & Services
├── Orchestrate 協調
│   ├── Execution Patterns 精煉決策   Loop / Workflow / Graph Engineering
│   ├── Agent Teams 團隊協作          Planner / Worker / Reviewer
│   └── Guardrails & Memory 安全把關  Rules & Policies / RAG & Memory / State Management
└── Goal & Outcome 終極收斂點
    Accuracy · Reliability · Speed · Cost Efficiency · User Impact
```

**核心心法**：不要死記框架，要理解架構背後的邏輯——心智模型一旦建立，任何新工具（Claude、OpenAI、LangGraph、CrewAI、MCP…）都只是「又一種實作方式」。

---

## 功能特色

- **互動式展開卡片**：六大構件皆可點擊展開／收合詳細說明，適合課堂由淺入深講解
- **樹狀漏斗版面**：保留原始框架「Build → Orchestrate → Goal & Outcome」的邏輯方向，同時用分支呈現子構件
- **響應式設計**：桌機雙欄並排，手機自動改為單欄堆疊
- **無外部依賴**：僅使用 Google Fonts（Noto Sans TC / Montserrat），純 HTML/CSS/JS 撰寫，無需建置工具即可直接開啟

---

## 檔案結構

```
.
├── index.html   主頁面（含完整內容、樣式與互動邏輯）
└── README.md    本說明文件
```

---

## 使用方式

### 本機預覽
直接用瀏覽器開啟 `index.html` 即可，無需安裝任何套件或啟動伺服器。

### 部署到 GitHub Pages
1. 將本專案推送到 GitHub repository
2. 進入 repo 的 **Settings → Pages**
3. Source 選擇 `main` 分支、根目錄 `/ (root)`
4. 儲存後等待數分鐘，即可透過 `https://<帳號>.github.io/<repo名稱>/` 存取

---

## 授權與用途

本頁面為教學輔助教材，供 AI 課程、企業內訓、產業輔導課綱等場合使用。歡迎依需求調整內容與樣式。

---

*Maintained by 血糖教練益力康陳董 · CGM Coach*
