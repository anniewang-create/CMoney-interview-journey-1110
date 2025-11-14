# CMoney 面試旅程（RWD 靜態版）

這是可直接部署到 Vercel 的純靜態網站版本。

## 快速部署
1. 下載本專案壓縮檔後解壓縮。
2. 前往 https://vercel.com 新建專案，選擇 **Import**：
   - 直接上傳資料夾（包含 `index.html`、`vercel.json`）。
   - 或推到 GitHub 後在 Vercel 連接該 Repo。
3. Framework Preset 選 **Other**（或 Static），Build Command 留空，Output 留空。
4. Deploy！

> 所有資源為外部圖片 URL 與單一 `index.html`，不需要任何建置流程。

## 結構
.
├─ index.html      # 網站主頁（已內含 CSS/JS）
├─ vercel.json     # Vercel 設定（選填）
└─ README.md
