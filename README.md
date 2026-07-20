# Hermes Agent Deck

互動式簡報：介紹如何把 **Hermes** 當成 Slack 裡的通用 AI 團隊助理——不是單一專家工具，而是接住團隊日常流動的工作夥伴。

**線上簡報：** https://triekai.github.io/hermes-agent-deck/

## 簡報內容

共 23 頁，涵蓋：

- Hermes 定位：團隊助理 vs 專家工具
- Slack 內的 Ambient Operations（請假、會議辨識等）
- 六個應用場景：會議 Action Item、每日看板早報、Quality Layer、Continuous Handoff、CXAS × SCRAPI、Fast Verification
- Skill 自動進化與成長實例
- Hermes × Ponytail：選擇性啟用與情境驗證
- 模型／額度串接、企業導入適配與落地建議

## 本機預覽

純靜態頁面，無需建置。任選一種方式開啟即可：

```bash
# 直接開檔
open index.html

# 或起一個本機伺服器（建議，避免部分瀏覽器限制）
python3 -m http.server 8080
# 然後開啟 http://localhost:8080
```

## 操作方式

| 操作 | 說明 |
|------|------|
| `→` / `PageDown` / `Space` | 下一頁 |
| `←` / `PageUp` | 上一頁 |
| 滑鼠滾輪 / 觸控滑動 | 切換頁面 |

## 專案結構

```
.
├── index.html      # 簡報本體（單檔 HTML + CSS + JS）
├── images/         # 流程圖、截圖與插圖素材
├── .nojekyll       # GitHub Pages 略過 Jekyll
└── README.md
```

## 部署

此 repo 透過 **GitHub Pages** 發布。推送到預設分支後，Pages 會提供上述線上網址。
