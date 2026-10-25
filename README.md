# 空靈鼓治癒音樂 — GitHub Pages

- [播放器](https://teabonvivant.github.io/tongue-drum-music-player/)
- [管理頁](https://teabonvivant.github.io/tongue-drum-music-player/admin.html)

純 GitHub Pages；所有音檔公開。管理頁用 GitHub fine-grained token（只選此 repository，Contents: Read and write）更新 visibility.json，再由 Pages 重新部署。Token 只保留頁面記憶體，不寫入 storage 或 repository。原 Oliver 密碼登入不適用。

隱藏專輯／歌曲只影響播放器列表，不能限制直接音檔網址。原先隱藏的兩張試聽專輯仍預設隱藏。共 9 張歌單、95 個曲目版本，長版音檔在 Releases，普通版及獨奏音檔在 audio/。

新增歌單：新增音檔及封面，更新 catalog.json 與 credits.json，保留既有 ID。超過 100 MB 的音檔放 Releases。提交 main 後等待 Pages 部署，再檢查實際播放。

本次遷移未停用原網站。歌曲為採樣編排及連播整理，非 YuE2 生成；署名見 credits.json。
