# Demo2-curdor

一個示範專案，用來搭配 Cursor 與 GitHub 測試基本開發流程與版本控制。

## 專案介紹

此專案主要用途：
- 示範如何在本機使用 Cursor 編輯程式碼
- 練習使用 Git 管理版本（commit / push / pull）
- 練習將變更推送到 GitHub 儲存庫

GitHub 儲存庫位址（可在瀏覽器開啟查看原始碼與提交紀錄）：
- `https://github.com/fudamingda/Demo2-curdor`

## 環境需求

- 已安裝 Git
- 已安裝 Node.js（若後續加入前端/後端程式，可使用 npm / pnpm / yarn）
- 建議使用 Cursor / VS Code 進行開發

## 下載與安裝

1. 透過 Git 下載專案：
   ```bash
   git clone https://github.com/fudamingda/Demo2-curdor.git
   cd Demo2-curdor
   ```

2. （如果專案有使用 Node.js）安裝相依套件：
   ```bash
   npm install
   ```

## 使用方式

以下是一般開發與推送到 GitHub 的基本流程：

1. 在 Cursor 中打開專案資料夾 `Demo2-curdor`。
2. 修改程式碼或文件（例如這個 `README.md`）。
3. 在終端機查看變更：
   ```bash
   git status
   ```
4. 將變更加入暫存區：
   ```bash
   git add .
   ```
5. 建立提交（commit）訊息：
   ```bash
   git commit -m "update README"
   ```
6. 將提交推送到 GitHub：
   ```bash
   git push origin main
   ```

## 授權條款

本專案之授權條款請參考同目錄下的 `LICENSE` 檔案。