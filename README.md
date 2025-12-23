# gemini-optimizer
gemini-optimizer
Gemini Prompt Optimizer - Obsidian Edition 💎

這是一個專為 Google Gemini (2.0/2.5) 模型設計的高級提示詞（Prompt）優化工具。採用未來感的 Obsidian Dark Mode 設計語彙與 Glassmorphism 磨砂玻璃視覺風格，旨在協助 AI 工程師與內容創作者透過結構化的方式，產出符合 Google 官方最佳實踐的優質提示詞。

✨ 核心特色

1. 未來感 UI/UX 設計

黑曜石深色模式：高對比度背景，減少長時間使用的視覺疲勞。

霓虹元素：使用 Cyan 與 Purple 霓虹色彩標註關鍵動作與數據狀態。

完全響應式 (RWD)：支援從行動裝置到 4K 螢幕的流暢切換。

2. 結構化提示詞工程 (Prompt Engineering)

工具自動將輸入內容封裝進 XML 標籤區塊中，這已被證明能顯著提升 Gemini 的指令遵循能力：

<role>：定義模型的專業身分。

<context>：提供背景知識與長文本脈絡。

<task>：明確最終執行的任務目標。

<examples>：支援 Few-shot 學習模式，提供範例引導。

3. 多重邏輯引擎模式

STANDARD (標準)：直接執行任務。

STRATEGIC_PLAN (策略規劃)：強制模型在執行前先寫出思考步驟。

AGENTIC_REASONING (代理推理)：啟用主動分析邏輯，適合處理複雜、具有風險的決策任務。

🛠 技術架構

前端框架：Tailwind CSS v3 (經由 CDN 載入)。

字體系統：

UI：Inter (兼具現代感與閱讀性)。

Code：JetBrains Mono (程式碼字體首選)。

邏輯層：原生 JavaScript (ES6+)，無須依賴 Node.js 環境。

樣式技術：CSS Backdrop-filter、Radial-gradients、Custom Scrollbar。

🚀 快速上手

安裝與運行

由於此工具為純前端應用程式，您無需安裝任何相依套件：

下載 gemini_prompt_optimizer.html 檔案。

使用任何現代瀏覽器（Chrome, Edge, Safari, Firefox）直接開啟。

使用流程

Shuffle Demo：點擊右上角按鈕載入內建範例，快速了解結構。

參數輸入：填寫角色、脈絡、任務等必要欄位。

編譯 (Compile)：點擊底部的「Compile Prompt」。

複製 (Copy)：點擊輸出終端機右上角的「Copy to Buffer」。

運行：將結果貼上至 Google AI Studio 或 Gemini Web。

📦 檔案結構說明

檔案名稱

說明

gemini_prompt_optimizer.html

核心檔案，包含所有 HTML、CSS (Tailwind) 與 JS 邏輯。

README.md

您正在閱讀的技術說明文件。

⚠️ 佈署注意事項

網路依賴：本工具需要連接網路以加載 Tailwind CSS 與 Google Fonts。

安全性：

不收集數據：所有提示詞編譯均在使用者本地瀏覽器完成。

無 API 密鑰：此版本不直接調用 Gemini API，因此無須擔心金鑰外洩。

RWD 適配：在極小螢幕（如 iPhone Mini）上，側邊欄會自動收合至頂部，請垂直滑動操作。

💡 開發者資訊

維護者：Gemini 提示詞優化團隊

更新日期：2025年12月23日

協議：MIT License

「好的提示詞，是成功生成內容的一半。」 —— 利用結構化思維，釋放 Gemini 的完整潛能。
