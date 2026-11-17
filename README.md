# 島嶼採集所｜台三線生態博物館

一個以台三線山林、茶園、客庄與溪流為題的響應式 3D 風格生態博物館網站。純 HTML、CSS、JavaScript，無建置步驟與套件安裝需求。

## 本機預覽

直接用瀏覽器開啟 `index.html`，或在此資料夾啟動任何靜態網站伺服器。

## 互動功能

- 可拖曳旋轉 3D 風格島嶼地景，點選島嶼查看地方故事
- 使用 WASD、方向鍵或觸控方向按鈕移動角色
- 建立島民名稱與角色，會員狀態保存在目前瀏覽器的 localStorage
- 將選物加入購物袋、調整品項與查看金額
- 手機、平板與桌機版響應式排版

## 部署至 GitHub 與 Vercel

1. 在 GitHub 建立空白 repository，將本資料夾的檔案推送至 repository。
2. 登入 Vercel，選擇 **Add New → Project** 並匯入該 GitHub repository。
3. Framework Preset 選 **Other**，Build Command 與 Output Directory 留空或採用 Vercel 偵測的靜態網站預設值，按 **Deploy**。
4. 之後推送至連結的 GitHub 分支，Vercel 會自動建立新部署。

## 正式服務擴充

目前會員與購物車是前端展示流程，資料存在使用者自己的瀏覽器；訂單結帳僅示範操作回饋。若要提供跨裝置帳號、即時多人角色與對話、庫存同步及實際收款，需另接後端資料庫、即時通訊服務及金流服務。
