# 寄居蟹影音工具箱（PWA v2.0）

- 響應式介面，適合桌機、手機、平板
- 支援選擇本機檔案、拖曳多個檔案匯入\n- 可嘗試匯入合法授權的 HTTPS 直接影音檔案網址（需來源允許 CORS；不支援登入頁或分享頁）\n- 批次轉換 MP3（128/192/256/320 kbps，預設 320 kbps）或 MP4
- 轉換在瀏覽器端執行，來源檔案不會上傳本工具伺服器
- 不抓取 YouTube 觀看網址、不繞過平台限制；YouTube 內容請使用官方下載方式取得檔案後匯入\n- 直接網址匯入由瀏覽器直接請求來源，不經本工具伺服器；若 CORS 阻擋，請先手動下載再匯入
- 首次使用需連網載入 FFmpeg WebAssembly CDN；並非完全離線
- 手機可能受記憶體限制，大型影片建議使用電腦

## 開啟 GitHub Pages
Repository Settings → Pages → Build and deployment → Deploy from a branch → Branch: main → Folder: /(root) → Save。

部署網址預計為 https://giligowla33.github.io/hermit-media-toolbox/ 。

## 安裝到手機
- iPhone/iPad：Safari 開啟網站 → 分享 → 加入主畫面
- Android：Chrome 開啟網站 → 選單 → 安裝應用程式／加到主畫面
