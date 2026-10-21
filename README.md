# vocab-quiz-maker 產品介紹網頁

一頁式靜態網頁（無需後端），可直接用 GitHub Pages 發布。

## 檔案
- `index.html`：完整網頁（文字、圖片已內嵌）
- `promo.jpg`、`promo.mp4`、`promo_poster.jpg`：海報與自動播放影片
- `src/`：原始碼。修改 `template.html` 後在 `src` 資料夾執行 `python3 build.py`，會重新產生上一層的 `index.html`
- `.nojekyll`：讓 GitHub Pages 原樣發布

## 發布到 GitHub Pages
1. 建立新 repo（例如 `vocab-quiz-maker-site`），把這些檔案上傳到根目錄
2. Settings → Pages → Branch 選 `main`、資料夾 `/ (root)` → Save
3. 約 1 分鐘後網址為 `https://<帳號>.github.io/<repo名稱>/`

## 修改聯絡方式
`index.html` 內搜尋 `CONTACT=`，改 email 即可。
