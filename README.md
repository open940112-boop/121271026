# 內湖科技園區通勤看板

以純 HTML、CSS、JavaScript 製作的 GitHub Pages 靜態網站，顯示臺北市 YouBike 2.0 即時資料，預設篩選內湖區。

## 功能

- 直接向臺北市政府交通局 API 讀取資料，每分鐘更新，也能手動更新。
- 依行政區、站名或地址篩選；列出各站可借車輛與可還空位。
- 標示可借車輛低於站點總車位 20% 的站點。
- 顯示即時摘要與頁面開啟後的車量趨勢。
- 支援手機版版面。

## 資料

- API：<https://tcgbusfs.blob.core.windows.net/dotapp/youbike/v2/youbike_immediate.json>
- 資料集：<https://data.gov.tw/dataset/137993>

## 部署

推送至 `main` 後，GitHub Actions 會部署到 GitHub Pages。預期網址：<https://open940112-boop.github.io/121271026/>。

署名：資通四勤　121271026　高權伯

