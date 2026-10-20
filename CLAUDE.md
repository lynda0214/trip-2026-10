# 2026 東京・河口湖・伊豆 行程網站

- 網站只有一個檔案：`index.html`，用 GitHub Pages 從 `main` 分支根目錄發布。
- 改完內容後 commit 並 push 到 `main`，約 1 分鐘後 https://lynda0214.github.io/trip-2026-10/ 會更新。
- 行程資料都在 `index.html` 的 `<script>` 裡：`P` 是地點座標，`DAYS` 是每天的停靠點、交通、天氣、穿搭。
- 天氣來源是氣象廳 JSON：`https://www.jma.go.jp/bosai/forecast/data/forecast/{130000|190000|220000}.json`（東京、山梨、靜岡）。更新天氣時一併改頁首和頁尾的發表時間。

## 隱私規則（網站是公開的）
- 不寫飯店或住宿的名稱，只寫地區（例如「河口湖住宿」）。
- 住宿座標只用車站或地區的大概位置，不用飯店的精確座標。
- 不寫航班號碼和航班時間。
