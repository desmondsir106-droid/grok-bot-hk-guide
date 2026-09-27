# Grok Bot 教學｜香港老師版

給香港老師講解 Grok Bot 的靜態網頁：它是甚麼、新手 5 步上手、訂閱三條產品線（Cursor、SuperGrok、X Premium／Premium+）、安全與登入，以及 AI Manager 公開範本。

內容整理自 **2026-09-27** 研究資料包。價錢與功能以官方結帳頁為準。

## 本地開啟

用瀏覽器直接打開 `index.html`，或在此目錄執行：

```bash
python3 -m http.server 8765
```

然後前往 `http://127.0.0.1:8765/`。

## GitHub Pages

此庫不需要建置。在倉庫設定裡把 Pages 的來源選為分支根目錄（`/`），網站即由 `index.html` 提供。

## AI Manager 分享連結

主按鈕在 `index.html` 的 `id="ai-manager-share-url"`，指向公開範本：

https://x.ai/bot/8jdoGq6js67DSIedm0NWG

按鈕下方另有一行 Grok Bot app 深層連結：`grokbot://app/v1/bot-template?id=8jdoGq6js67DSIedm0NWG`。頁面沒有 iframe。範本是匯入用的副本，不會連結到 Des Sir 的帳戶，也不會附帶私人 token。老師須自行連接自己的 Gmail、GitHub 等服務。
