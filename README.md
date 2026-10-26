# 空靈鼓治癒音樂 — GitHub Pages

- [播放器](https://teabonvivant.github.io/tongue-drum-music-player/)
- [管理頁](https://teabonvivant.github.io/tongue-drum-music-player/admin.html)

純 GitHub Pages；所有音檔公開。管理頁用 GitHub fine-grained token（只選此 repository，Contents: Read and write）更新 visibility.json，再由 Pages 重新部署。Token 只保留頁面記憶體，不寫入 storage 或 repository。原 Oliver 密碼登入不適用。

隱藏專輯／歌曲只影響播放器列表，不能限制直接音檔網址。原先隱藏的兩張試聽專輯仍預設隱藏。目前 11 張歌單、119 個播放項目（包括原版及音源對照），長版音檔在 Releases，普通版及獨奏音檔在 audio/。

新增歌單：新增音檔及封面，更新 catalog.json 與 credits.json，保留既有 ID。超過 100 MB 的音檔放 Releases。提交 main 後等待 Pages 部署，再檢查實際播放。

本次遷移未停用原網站。歌曲為採樣編排及連播整理，非 YuE2 生成；署名見 credits.json。

## 真實音源對照（2026-10-26）

[試聽鋼琴與結他 A/B 對照](https://teabonvivant.github.io/tongue-drum-music-player/#playlist=realistic-accompaniment-v11)。新增兩首伴奏升級版本，原版亦列入同一歌單方便比較。空靈鼓分軌保持原錄音、原音量及原拍點。製作記錄及音源署名見 production/realistic-accompaniment-v11。

2026-10-26 試聽調整：使用者接受新鋼琴／結他音源，將兩首新音源版的伴奏平均電平調整為低於主奏約 10 dB，空靈鼓分軌原樣保留。往後新版本以此平衡作起點，再按實際樂句檢查。

## 晴光同行二十首音源升級（2026-10-26）

[開啟完整升級專輯](https://teabonvivant.github.io/tongue-drum-music-player/#playlist=daylight-realistic-v12)。原二十首主旋律、空靈鼓分軌、速度及長度保留；更新伴奏音源／演奏處理，伴奏平均 RMS 電平校準至主奏以下 10 dB。原版專輯保留。來源與限制見 production/daylight-realistic-v12。
