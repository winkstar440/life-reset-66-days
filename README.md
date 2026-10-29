# 66 天人生重置計畫 | Life Reset 66 Days

一個以 RPG 遊戲風格呈現的 **66 天科學作息養成 App**（純前端、繁體中文）。

根據倫敦大學學院 (UCL) 心理學家 Phillippa Lally 的研究，養成一個自動化的新習慣平均需要 **66 天**。本專案把這個科學依據變成可玩的日常任務系統，幫助使用者從熬夜循環中走出來。

## 功能特色

- **任務系統**：每日核心作息任務（早睡、早起、飲水、運動、閱讀）
- **RPG 成長**：經驗值 (XP)、等級、連續天數 (Streak)、屬性值（智慧 / 自信 / 力量 / 紀律 / 專注）
- **成就畫廊**：解鎖專屬成就徽章
- **賽季排行榜**：模擬戰友競爭
- **本地儲存**：進度自動保存在瀏覽器 localStorage
- **音效與特效**：完成任務有音效與 XP 浮動動畫、升級彩紙

## 使用方式

1. 直接開啟 `index.html`（建議用手機瀏覽器或 Chrome 開發者工具的手機模擬模式）
2. 或部署到任何靜態託管（GitHub Pages、Vercel、Netlify 等）

### 啟用 GitHub Pages

1. 進入 Repository Settings → Pages
2. Source 選擇 `Deploy from a branch`
3. Branch 選 `main`，資料夾選 `/ (root)`
4. 儲存後等待幾分鐘，即可透過 `https://winkstar440.github.io/life-reset-66-days/` 開啟

## 技術棧

- 純 HTML + Tailwind CSS (CDN)
- Lucide Icons
- Canvas Confetti
- Web Audio API（任務完成音效）
- localStorage 狀態管理

## 預設任務

| 任務 | XP | 提升屬性 |
|------|----|----------|
| 凌晨 02:00 前入睡 | 60 | 紀律 |
| 早上 10:00 起床 | 60 | 力量 |
| 每天飲水 2,000ml | 40 | 自信 |
| 運動 30 分鐘 | 50 | 力量 |
| 閱讀或專注學習 20 分鐘 | 50 | 智慧 |

## 授權

MIT License – 自由使用、修改與分享。

---

**開始你的 66 天重置吧！** 🔥
