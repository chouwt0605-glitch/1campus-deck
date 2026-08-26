# 1Campus 智慧校園平台簡報

以 GitHub Pages 發布的網頁版簡報。

## 線上瀏覽

發布後的網址會是：`https://<你的帳號>.github.io/<repo 名稱>/`
（根目錄會自動跳轉到 `site/index.html`）

## 資料夾說明

- `site/index.html` — 簡報本體
- `site/deck-stage.js`、`site/support.js`、`site/image-slot.offline.js` — 簡報執行所需的程式
- `site/uploads/` — 簡報使用的圖片與影片
- `.nojekyll` — 告訴 GitHub Pages 直接原樣提供檔案，不要額外處理

## 更新內容的方式

修改 `site/` 底下的檔案後，執行：

```bash
git add -A
git commit -m "更新簡報內容"
git push
```

推上去後約 1 分鐘，網站就會更新。
