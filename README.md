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

## 補上 AI Manager 分享連結

分享位在 `index.html` 的 `id="ai-manager-share-url"`。現時文字是「即將補上」。

日後只替換那一行，例如改成正式公開範本連結。不要加入 `grokbot://` 網址，也不要加入 iframe。範本是匯入用的副本，不會連結到分享者的帳戶，也不會附帶私人 token。
