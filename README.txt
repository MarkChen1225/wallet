日日帳（離線版）

這是一組靜態檔案。放到任何支援 https 的網站空間後，就能在手機上加到主畫面，之後沒有網路也能使用。

【檔案】
index.html            App 本體
sw.js                 離線快取
manifest.webmanifest  安裝資訊
icon-*.png、apple-touch-icon.png  圖示
這些檔案要放在同一個資料夾，不要改檔名。

【放到網路上】
GitHub Pages、Netlify、Cloudflare Pages 都有免費方案。網址必須是 https 開頭。直接在手機上點開檔案，或用 file:// 開啟，都無法離線。

【安裝到手機】
iPhone：用 Safari 開啟網址，點分享，選「加入主畫面」，之後從主畫面圖示開啟。
Android：用 Chrome 開啟網址，從選單選「安裝應用程式」。
第一次需要網路。開過一次之後，不需要網路。

【資料】
資料只存在手機上，不會上傳。到 App 裡的「設定 → 資料」可以備份（JSON）、還原、匯出 CSV。建議每個月備份一次。
換手機：舊手機先備份，新手機再還原。

【從 Claude 版搬資料】
在 Claude 裡的日日帳，到「設定 → 資料」點「備份全部資料」，存下 JSON 檔。再到離線版點「從備份檔還原」。

【更新】
上傳新檔案後，把 App 開啟兩次，就會看到新版。
