# 寄居蟹影音工具箱（PWA v2.1）

- 響應式介面，適合桌機、手機、平板
- 支援選擇本機檔案、拖曳多個檔案匯入
- 支援在瀏覽器本機讀取官方資料匯出的 ZIP，篩選常見影音檔案
- 辨識 YouTube、Facebook、Instagram、Google Drive 網址，提供合法取得檔案的官方指引；不抓取平台串流
- 可嘗試匯入合法授權的 HTTPS 直接影音檔案網址（需來源允許 CORS；不支援登入頁或分享頁）
- 批次轉換 MP3（128/192/256/320 kbps，預設 320 kbps）或 MP4
- 轉換與 ZIP 解壓在瀏覽器端執行，來源檔案不會上傳本工具伺服器
- 首次使用需連網載入 FFmpeg、ZIP 解壓程式 CDN；並非完全離線
- ZIP 解壓後總量上限 1 GB，單一影音檔案上限 500 MB；手機可能受記憶體限制，大型影片建議使用電腦

## 官方來源入口
- YouTube Studio：https://studio.youtube.com/
- Meta 帳號管理中心：https://accountscenter.facebook.com/info_and_permissions/
- Instagram 帳號管理中心：https://accountscenter.instagram.com/info_and_permissions/
- Google Drive：https://drive.google.com/

## 開啟 GitHub Pages
Repository Settings → Pages → Build and deployment → Deploy from a branch → Branch: main → Folder: /(root) → Save。

網站：https://giligowla33.github.io/hermit-media-toolbox/

## 安裝到手機
- iPhone/iPad：Safari 開啟網站 → 分享 → 加入主畫面
- Android：Chrome 開啟網站 → 選單 → 安裝應用程式／加到主畫面
