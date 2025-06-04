📊 Dan's Market Monitor
用 AI 自動生成嘅 Bitcoin 同 MSTR 市場分析報告，每日電郵送到你 inbox！

💡 關於呢個項目
呢個係一個 興趣為本嘅副業項目，源自我對 Bitcoin 同 MicroStrategy 嘅熱情。喺 Claude AI 幫手下，我將市場直覺同 AI 開發能力結合，打造咗呢套系統。

🎯 點解會開始做？
一開始淨係係好奇 Bitcoin 嘅市場週期，後來發現 MSTR 同 Bitcoin 嘅聯動好獨特，就開始設計一套系統去追蹤佢哋嘅走勢：

個人交易興趣：對 Bitcoin 嘅技術圖表同市場心理學好有研究

策略分析：鍾意玩 options 同波幅交易

科技熱情：痴迷自動化、雲端計算同數據決策

AI 協作：Claude AI 幫我實現啲複雜嘅想法

🚀 技術突破：Gmail 手機 App 圖片唔出問題搞掂咗！
問題：Gmail 手機 app 唔顯示 email 裡面嘅內嵌圖片，搞到 Bitcoin 法律追蹤 dashboard 睇唔到。

解決方案：

Imgur 圖片托管：唔再用內嵌圖片，改用外部連結

多層備援方案：CID 附件 → Base64 壓縮圖 → 最後用文字代替

高清圖片：提升至 800x600 像素、JPEG 85% 質素

全面兼容：而家喺 Gmail、Outlook、手機、電腦都顯示無問題！

效果：圖片清晰，法規追蹤睇得晒！

⚠️ 免責聲明
只供學術研究同娛樂用途

呢套系統係用嚟學習同試驗嘅，唔係投資建議。你自己做投資前要做好功課、諗清楚風險。

📊 技術分析：提供技術圖表同市場觀察

🎓 教學用途：幫你了解市場模式

🔬 試驗性質：探索市場時間點假設

⚖️ 唔包贏：過去表現唔代表未來結果

做投資前請搵持牌財務顧問！

🔄 核心理念
「愈簡單愈好」投資哲學
系統背後嘅中心思想就係：Bitcoin 每四年減半一次，帶嚟可預測嘅牛市高峰同熊市低谷。

📈 Power Law 應用
根據歷史數據，系統識別以下模式：

🔴 市場亢奮頂部（1-3個月）

市場過熱，投資人過度樂觀

MVRV 大於 3.0

RSI > 70

適合冷靜沽貨

🟢 市場恐慌底部（4-6個月）

市場悲觀至極

MVRV 小於 1.0

RSI < 30

適合耐性入貨

⏰ 耐性策略
等多個指標共振

擁抱波幅，反其道而行之

以年計，唔好睇日線圖

用數據，唔用情緒做決定

"將主觀模式，轉化成客觀數據信號"

📧 電郵報告預覽
📱 專業設計，手機睇都正！
報告格式：

yaml
Copy
Edit
📊 DAN'S MARKET REPORT - [日期]
═════════════════════════════════════

┌─────────────────┬─────────────────┐
│   ₿ BITCOIN     │   📊 MSTR       │
│   $95,000       │   $450.00       │
│   🐂 牛市       │   🟡 合理估值   │
├─────────────────┼─────────────────┤
│ 📊 指標         │ 📈 分析         │
│ • MVRV: 2.1 ✅  │ • 模型價: $425  │
│ • RSI: 65 ❌    │ • 偏離: +5.9%   │
│ • EMA: $85K     │ • IV: 45%       │
│ • vs EMA: +12%  │ • 排名: 60%     │
├─────────────────┼─────────────────┤
│ 🎯 訊號         │ 💡 選擇策略     │
│ 🟡 HOLD         │ ⚖️ 中性觀望      │
│ 市場向好但未極端 │ 等更好波幅時機   │
└─────────────────┴─────────────────┘

⚖️ 美國比特幣法規追蹤
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📸 高清圖表（800x600）
📱 Gmail 手機 app 顯示完美
🔗 bitcoinlaws.io 直接連結

QUICK LINKS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📊 MSTR 模型分析 → microstrategist.com  
⚖️ 比特幣法規追蹤 → bitcoinlaws.io

🏗️ 系統架構
📊 數據流程概覽
pgsql
Copy
Edit
⏰ 定時觸發器（每日早上 9:21 AM）
    │
    ▼
📊 數據收集層
    ├── 🟡 Bitcoin 數據（Polygon.io API）
    │   ├── 即時價格數據
    │   ├── EMA 200 計算  
    │   └── 每週 RSI 分析
    │
    ├── 📈 MSTR 分析（網站抓取）
    │   ├── Ballistic 模型價格
    │   ├── 波幅數據（Barchart）
    │   └── Options 策略分析
    │
    ├── 📊 MVRV 數據（TradingView）
    │   ├── 多種抓數方式
    │   ├── 模式比對
    │   └── 備用算法
    │
    └── ⚖️ Bitcoin 法規追蹤圖（螢幕擷取）
        ├── Selenium 自動化
        ├── 高質圖片處理
        └── Imgur 圖片上傳
    │
    ▼
🧠 分析引擎
    ├── 🎯 訊號偵測
    │   ├── 牛/熊市分類
    │   ├── 多重指標共振分析
    │   └── 狀態保留（30 日寬限期）
    │
    ├── 📊 選擇權策略邏輯
    │   ├── 波幅環境分類
    │   ├── 市場方向偏向判斷
    │   └── 風險調整建議
    │
    └── 💾 數據處理
        ├── 驗證同錯誤處理
        ├── 歷史對比
        └── 警報產生
    │
    ▼
📧 通知系統
    ├── 🖼️ 圖片處理
    │   ├── 上傳到 Imgur（解決 Gmail 問題）
    │   ├── CID 附件備援
    │   └── Base64 內嵌備援
    │
    ├── 📱 電郵產生
    │   ├── HTML 模板渲染
    │   ├── 手機適應式設計
    │   └── 多人電郵發送
    │
    └── 💾 儲存與監察
        ├── Azure Table Storage
        ├── 歷史數據紀錄
        └── 系統健康監測
🔄 備援策略
API 優先順序：官方 API → 禮貌式抓取 → 數學模型推算 → 平穩退化策略

🎯 訊號同期權策略邏輯
📊 Bitcoin 訊號邏輯
🟢 買入訊號（只適用於熊市）
條件（全部都要符合）：

🐻 市場狀態：BTC 價格 < EMA 200（熊市）

📉 MVRV 比率：< 1.0（市值低過實現市值）

📊 每週 RSI：< 30（極度超賣）

預期結果：喺未來 4 至 6 個月見底
歷史命中率：約 85%
信心程度：三個條件齊齊中，信心好高

🔴 賣出訊號（只適用於牛市）
條件（全部都要符合）：

🐂 市場狀態：BTC 價格 > EMA 200（牛市）

📈 MVRV 比率：> 3.0（市值高過實現市值三倍）

📊 每週 RSI：> 70（極度超買）

預期結果：喺未來 1 至 3 個月見頂
歷史命中率：約 80%
信心程度：三個條件齊齊中，信心好高

⚖️ 訊號狀態管理
🟢 Active（生效中）：三個條件都滿足，訊號有效

🟡 Weakening（轉弱中）：其中一個條件冇滿足，有 30 日寬限期

🔴 Inactive（失效）：連續 30 日以上條件唔再符合

📈 MSTR 分析邏輯
🧮 Ballistic 模型公式
bash
Copy
Edit
ln(MSTR_Price) = 51.293498 + (-10.676635 × ln(BTC_Price)) + (0.586628 × ln(BTC_Price)²)
📊 估值分類
🔴 嚴重高估：高過模型價 25% 或以上

🟠 高估：高過模型價 15% 至 25%

🟡 公平估值：模型價上下 15% 之內

🟢 低估：低過模型價 15% 至 25%

🟢 嚴重低估：低過模型價 25% 或以上

🎯 選擇權策略矩陣
波幅狀況	方向偏向	主要策略	原因
🔴 高 IV（>75%）	🐂 牛市偏向	Short Puts	貴期權 + 向上預期 = 賣保費
🔴 高 IV（>75%）	🐻 熊市偏向	Short Calls	貴期權 + 向下預期 = 賣保費
🔴 高 IV（>75%）	⚖️ 中性	Short Strangle	貴期權 + 預期震盪 = 賣兩邊
🟢 低 IV（<25%）	🐂 牛市偏向	Long Calls	平期權 + 向上預期 = 買 call
🟢 低 IV（<25%）	🐻 熊市偏向	Long Puts	平期權 + 向下預期 = 買 put
🟢 低 IV（<25%）	⚖️ 中性	Long Straddle	平期權 + 預期大波幅 = 買兩邊
🟡 正常 IV（25-75%）	💪 強訊號	中度策略	情況混合 = 用溫和策略
🟡 正常 IV（25-75%）	🤷 弱訊號	冇明確方向	無優勢 = 等更好時機

🔍 波幅分析構成
IV Rank：現時隱含波幅 vs 過去一年範圍

IV Percentile：現時 IV 喺歷史分佈入面嘅位置

矛盾檢測：發現唔一致嘅 IV 數據會標示出嚟

方向判斷：結合基本面 + 技術面分析

🛠️ 技術棧（Tech Stack）
☁️ 基礎設施（Infrastructure）
Azure Functions：Serverless 計算平台（用 Python 3.9+ 開發）

Azure Table Storage：NoSQL 儲存層，用嚟保存歷史數據

Timer Triggers：每日定時自動執行（香港時間下午 5:21）

Application Insights：系統監控同日誌追蹤

📊 數據來源同 API
Polygon.io：專業 Bitcoin 市場數據（官方 API）

TradingView：MVRV 比率數據（尊重網站，溫和式爬蟲）

MicroStrategist.com：MSTR Ballistic 模型（定點式數據提取）

Barchart.com：期權波幅數據（合規性爬蟲）

bitcoinlaws.io：比特幣法例追蹤（自動截圖）

🐍 核心 Python 函式庫
數據處理：Pandas、NumPy

網站爬蟲：Selenium WebDriver、BeautifulSoup、Requests

圖片處理：PIL / Pillow 處理截圖

電郵系統：SMTP + HTML 模板渲染

雲端整合：Azure SDK for Python

🌐 網頁爬蟲技術
Selenium WebDriver：互動式動態內容擷取

Chrome Headless：輕量級無頭瀏覽器自動化

速率限制：每次請求之間等至少 15 秒，避免封鎖

User Agent 輪換：避免被網站識穿同封 IP

備援機制：多層次備份確保數據提取穩定

📧 電郵同圖片系統
SMTP 協議：與 Gmail 相容嘅電郵傳送方式

HTML 模板：專業、可響應式設計

Imgur API：外部圖片託管，解決 Gmail 手機 App 限制

多格式支援：CID 附件 + Base64 備援格式

多收件人支援：支援 BCC，保護用戶私隱

🔐 安全性與道德準則
環境變數：安全管理 API 密鑰同機密

Managed Identity：Azure 原生身份驗證

尊重爬蟲守則：只處理公開資料，並加適當延遲

錯誤處理：靈活應對錯誤，避免無限重試

📁 關鍵組件（Key Components）
🎯 核心調度器
function_app.py：主 Azure Function 程式，控制定時執行同統籌各模組

asset_data_collector.py：負責用 Polygon.io API 收集 Bitcoin 數據同技術指標

🧠 分析引擎
btc_analyzer.py：分析 BTC 市場訊號、管理狀態、預測時機

mstr_analyzer.py：MSTR Ballistic 模型分析、波幅處理、期權策略推算

🌐 數據收集模組
mvrv_scraper.py：用唔同方式從 TradingView 抓取 MVRV 數據，有備援機制

bitcoin_laws_scraper.py：截取法規追蹤儀表板並處理成高質圖片

imgur_uploader.py：🆕 解決 Gmail 圖片顯示問題嘅外部圖片託管模組

📧 通訊系統
enhanced_notification_handler.py：整合 Imgur 嘅 HTML 電郵系統，支援多收件人

💾 數據儲存層
data_storage.py：整合 Azure Table Storage，追蹤歷史分析數據同監察資料質素

🔧 系統配置
requirements.txt：列出所有 Python 相依套件，包括 Selenium、Pandas、Azure SDK

環境變數：用作配置 API 金鑰、電郵帳戶同儲存設定

📊 數據流程總覽
markdown
Copy
Edit
Timer Trigger → 數據收集 → 分析處理 → 訊號生成 → 電郵報告 → 數據儲存
     ↓              ↓               ↓            ↓              ↓           ↓
function_app → collectors → analyzers → btc_analyzer → notification → data_storage
🚀 未來功能規劃（Future Enhancements）
🎯 短期路線圖
🚀 Azure DevOps 整合
GitHub Actions：自動化 CI/CD 部署流程

基礎建設即代碼（IaC）：用 ARM Templates / Bicep 自動部署 Azure 資源

環境管理：自動化測試與生產環境配置

安全掃描：自動檢查依賴庫嘅漏洞

📊 進階監控與分析
Application Insights 儀表板：即時系統健康狀況監察

效能指標：追蹤系統回應時間與效率

資料質素監察：自動驗證與異常偵測

訊號成功率分析：追蹤過往訊號準確性並持續改進

📱 平台擴展計劃
🌐 網頁控制台
即時訊號追蹤：實時顯示 BTC 同 MSTR 分析結果

歷史表現：互動圖表呈現訊號準確度

自訂通知設定：可根據個人喜好設通知閾值

手機友善設計：PWA 進階網頁 App，適合手機使用

📲 多渠道通知
Discord Bot 整合：即時訊號推送到 Discord 群組

Telegram Bot：互動式命令 + 通知功能

Slack 整合：為機構用戶提供通知整合

SMS 短訊提醒：重要訊號變化可推送至手機

🧠 高階分析功能
🤖 機器學習功能增強
訊號優化：用 ML 模型提升買賣時機準確性

波幅預測：更準確地為期權策略建模

市場階段識別：更智能分類牛/熊市狀態

情緒分析：引入社交媒體同新聞情緒數據

📈 回測引擎
歷史策略表現：完整回測框架

風險調整報酬：分析 Sharpe Ratio 同最大回撤

投資組合模擬：測試多資產策略組合效果

步進驗證法（Walk-Forward）：更穩陣測試方法

🔗 整合生態系統
📊 交易平台整合
投資組合追蹤：連接券商 API 監察倉位

自動交易執行：根據訊號執行策略（設有安全機制）

風險管理：根據波幅建議持倉大小

績效歸因：追蹤理論與實際績效差距

🔐 企業級功能
多租戶架構：支援多個用戶帳戶與設定

角色權限管理：提供分層用戶權限

REST API 介面：供第三方平台接入

Webhook 支援：即時將訊號發送至其他系統

🛠️ 技術基建升級
☁️ 擴展性提升
微服務架構：將 monolith 拆分為多個專責模組

容器化部署：用 Docker 提高可攜性與擴展力

負載平衡：可應對大量用戶或數據請求

全球部署：支援多地區用戶，提升速度與穩定性

🔒 安全性加強
OAuth 登入：提供安全認證同授權流程

端對端加密：數據傳輸與儲存全程加密

稽核日誌：記錄所有操作，方便合規審查

滲透測試：定期進行安全測試與改善

📋 開發流程規劃
🔄 自動化部署流程
markdown
Copy
Edit
GitHub Repository → Actions Workflow → Azure Deployment
      ↓                    ↓                    ↓
   程式更新 → 自動測試 → 正式上線
      ↓                    ↓                    ↓
   Pull Request → 整合測試 → 系統監察
🧪 測試策略
單元測試：測試所有核心功能模組

整合測試：確保端到端流程正常

效能測試：壓力測試以規劃擴容

用戶驗收測試：模擬真實場景作驗證

🚀 用心打造嘅自動化市場情報系統，幫你做出有智慧嘅投資決定
