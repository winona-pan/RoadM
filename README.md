# 旋律日記 Melody Diary

用歌記錄每一天，也用歌記住每一本書。

- **心情日記**：每天選一個心情（😭 😔 😐 🙂 🥰）、寫幾句話，貼上當天的歌。月曆會依心情上色。
- **書櫃**：記錄在讀／讀完／想讀的書，可以搜尋書名自動帶入作者、頁數和封面。每本書可以配好幾首歌，並寫下「為什麼是這首」，還有心得和喜歡的句子。
- **閱讀回顧與里程碑**：像 Apple Music Replay 一樣，每年統計讀了幾頁、幾本書，並頒發里程碑徽章（讀完的書、頁數、作者、書的配樂、心得、日記天數），標上達成日期。
- **支援的歌曲連結**：Apple Music、Spotify、YouTube Music／YouTube，可以直接在頁面上播放。

## 使用方式

整個 app 就是一個 `index.html`，不需要安裝或建置。

1. 到 repo 的 **Settings → Pages**，Source 選 `Deploy from a branch`，Branch 選 `main` / `(root)`，儲存。
2. 約一分鐘後打開 `https://winona-pan.github.io/RoadM/`。
3. 在 iPhone Safari 按「分享 → 加入主畫面」，就像一個 app。

## 資料與備份

日記和書只存在你這台裝置的瀏覽器（localStorage），不會上傳到任何地方，所以 repo 公開也不會洩漏內容。
換手機或清除 Safari 資料前，請到「設定 → 匯出 JSON」備份，之後再「匯入 JSON」即可。
