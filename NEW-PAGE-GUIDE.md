# 新增一個分享頁｜最短流程

1. 複製：`templates/basic-page`
2. 貼到：`pages/`
3. 資料夾改名，例如：`meeting-notice`
4. 修改：`pages/meeting-notice/index.html`
5. 修改首頁：根目錄 `index.html`，增加一張卡片
6. 上傳 GitHub 並 Commit
7. 分享：
   `https://你的帳號.github.io/web-share/pages/meeting-notice/`

## 卡片連結範例

```html
<a class="card" href="./pages/meeting-notice/">
  <div class="cover">
    <div class="type">NOTICE</div>
    <h3>聚會通知</h3>
    <p>時間、地點與注意事項</p>
  </div>
  <div class="body">
    <div class="meta">
      <span class="tag">通知</span>
      <span class="tag">手機版</span>
    </div>
    <div class="open">開啟網頁 →</div>
  </div>
</a>
```
