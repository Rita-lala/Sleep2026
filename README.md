# SLEEP 2026 GitHub Sync 版

## 檔案
- index.html：前台
- admin.html：後台
- data.json：所有資料

## GitHub Pages 使用方式
1. 建立 repository
2. 上傳這三個檔案到根目錄，或放在 /docs
3. 到 Settings → Pages 啟用 GitHub Pages
4. 前台開啟 index.html
5. 後台開啟 admin.html

## 自動同步
在 admin.html 輸入：
- GitHub Owner
- Repository
- Branch
- data.json 路徑
- Fine-grained Personal Access Token

Token 權限建議只給指定 repository 的 Contents: Read and Write。
