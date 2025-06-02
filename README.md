# n8n-personal-assistant
一套結合 LINE、n8n、AI 的個人助理流程
# 📌 n8n 個人助理流程備份

這是一套基於 n8n 打造的個人助理自動化流程，整合 LINE、Google Calendar、Google Sheets 與 AI 模型，具備以下功能：

## ✨ 功能特色

- 📅 安排行程：透過 LINE 指令新增 Google Calendar 行事曆事件
- 💰 收支記帳：自動寫入 Google Sheets
- 🌦️ 天氣查詢：使用 OpenWeatherMap API 即時回報
- 📰 新聞提醒：每日抓取 TVBS 最新新聞並推播
- 💬 對話 AI：結合 Google Gemini 模型處理訊息內容與任務指令

## 🛠️ 使用方式

1. 匯入 `個人助理2.json` 至 n8n
2. 設定以下 API 憑證：
   - Google Sheets（OAuth2）
   - Google Calendar
   - OpenWeatherMap API
   - LINE Messaging API
   - Google Gemini (PaLM)
3. 綁定 webhook 路徑，測試 LINE 回覆功能

## 📁 檔案說明

| 檔案名稱          | 用途              |
|------------------|-------------------|
| 個人助理2.json    | n8n 工作流程備份檔 |

## 🙋 作者 Giant

- 📍 台灣家具業經理，致力於 AI 與自動化轉型
- 🔧 熱衷開發 LINE + n8n 智能助手，提升效率與體驗
