# TICKET — feat/calorie-menu-v0-hk-chains

## 做什麼（只改 `/workspace/calorie-menu-app/`）
香港卡路里／營養追蹤可玩原型（優先單檔 `playable.html`，或可安裝最小殼）。路徑 A：Mobile Engineer 在虛擬電腦直接開 Grok Build CLI（`--cwd /workspace/calorie-menu-app`）；CLI 工房僅緊急備援。

功能（v0 一次交齊可驗）：
1. 可選集團餐牌種子資料：大家樂、大快活、譚仔、麥當勞（繁體中文品名＋卡路里；資料標來源或「種子／參考」）。
2. 份量：半份／一份／多於一份（影響卡路里計算）。
3. 非連鎖／茶餐廳：文字餐單輸入 → 拆分估算卡路里，畫面標明「估算」。
4. 當日日誌＋當日總卡路里；簡單「營養是否充足」提示；簡易每日圖表（至少今日／近幾日總量可見）。

介面：繁體中文；手機可點；不必登入、不必後端。

## 怎樣算做完（Done）
- `STATUS.md` = done；記 branch／tip。
- 交付物：`/workspace/calorie-menu-app/playable.html`（或同等可開入口）可點可開。
- 四項功能各有可點證據（截圖或 verify）；checks／`verify-phone-html` 適用則 PASS。
- evidence：`/workspace/scratch/calorie-menu-app-evidence-v0/`（含未能驗證清單）。

## 不要做什麼
- 勿等 Gemini／勿 Path B／勿真鎖屏／勿動水球、014、工法、其他專案。
- 不准讀 `/workspace/notes/`；只准改 `/workspace/calorie-menu-app/`；證據與 john_notes 可寫 scratch。
- 勿推遠端／Pages／上架；勿花銷；勿接健康裝置 API。
- 同一票勿開 Path B。

## 交回什麼證據
- tip／branch、playable 路徑與 bytes、evidence 目錄路徑、checks 結果、「未能驗證」清單。
- 完成後 STATUS=done；回報 Mobile Orchestrator（本席收成後轉領航）。

## 路徑
A — Mobile Engineer（直跑 Grok Build CLI）。

## 筆記
- john_notes: /workspace/scratch/calorie-menu-app-john-notes-v0/
- evidence: /workspace/scratch/calorie-menu-app-evidence-v0/
