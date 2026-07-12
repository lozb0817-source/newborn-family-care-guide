# 新生兒家庭照護指南

這是「新生兒家庭照護指南」的 Vercel / GitHub 版本。

## 建議部署方式

1. 在 GitHub 建立一個新 repository，例如：
   `newborn-family-care-guide`
2. 將本資料夾內所有檔案上傳到 repository 根目錄。
3. 到 Vercel 新增專案，選擇 Import Git Repository。
4. 選擇剛剛建立的 GitHub repository。
5. Framework Preset 選 `Other`。
6. Build Command 留空。
7. Output Directory 留空。
8. 點 Deploy。

之後只要在 GitHub 修改 `index.html` 或替換 `assets/` 圖片，Vercel 會自動重新部署。

## 檔案說明

- `index.html`：網站主頁與所有文字內容。
- `assets/`：網站圖片素材。
- `vercel.json`：Vercel 靜態站設定。

## 常見更新

### 修改文字

直接編輯 `index.html`。

### 替換圖片

把新圖片放進 `assets/`，再修改 `index.html` 中的圖片路徑。

### 修改網站標題或分享預覽

修改 `index.html` 最上方 `<head>` 裡的：

- `<title>`
- `<meta name="description">`
- `og:title`
- `og:description`
- `og:image`
