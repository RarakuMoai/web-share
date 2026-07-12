# Web Share｜通用 HTML 分享站

這是一個可直接發布到 GitHub Pages 的通用 HTML 分享中心，不限定旅行用途。

## 建議 Repository 名稱

`web-share`

發布後的網址：

- 分享首頁：`https://你的帳號.github.io/web-share/`
- 嘉義行程：`https://你的帳號.github.io/web-share/pages/2026-chiayi-trip/`

## 網站結構

```text
web-share/
├─ index.html
├─ 404.html
├─ .nojekyll
├─ pages/
│  └─ 2026-chiayi-trip/
│     └─ index.html
└─ templates/
   └─ basic-page/
      └─ index.html
```

## 第一次發布

1. GitHub 右上角 `+` → `New repository`。
2. Repository name 輸入 `web-share`。
3. 建議選 `Public`，不要預先建立 README。
4. 建立後按 `Add file` → `Upload files`。
5. 上傳本資料夾內的所有檔案與資料夾。
6. Commit changes。
7. 進入 `Settings` → `Pages`。
8. Source 選 `Deploy from a branch`。
9. Branch 選 `main`，Folder 選 `/(root)`，按 `Save`。

## 新增任意 HTML 分享頁

假設要新增一份「手機比較」：

1. 複製 `templates/basic-page` 資料夾。
2. 將副本移到 `pages/`。
3. 把資料夾改名為英文字，例如 `phone-comparison-2026`。
4. 編輯裡面的 `index.html`。
5. 在根目錄 `index.html` 複製一張卡片，修改：
   - href
   - 類型
   - 標題
   - 說明
   - 標籤
6. 上傳並 Commit。

網址會是：

`https://你的帳號.github.io/web-share/pages/phone-comparison-2026/`

## 資料夾命名原則

建議只使用：

- 小寫英文字母
- 數字
- 連字號 `-`

例如：

- `2026-chiayi-trip`
- `phone-comparison-2026`
- `birthday-invitation`
- `project-introduction`

避免空白、中文、括號與特殊符號，網址比較乾淨。

## 更新網頁

- 小修改：直接在 GitHub 開啟 `index.html`，按鉛筆圖示編輯。
- 大修改：在電腦完成新版後，上傳到相同路徑覆蓋。
- 路徑不變，原本分享出去的網址就不會改變。

## 隱私

`noindex` 只是降低搜尋引擎收錄機率，不是密碼保護。知道網址的人仍可查看內容。
不要放入密碼、證件、私人電話、完整住址、訂單憑證或登入連結。
