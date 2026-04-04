# GPS / 陀螺儀 軌跡紀錄器 BG+

這個版本支援：

- GPS 與陀螺儀可同時開始記錄
- GPS 軌跡與陀螺儀軌跡分色顯示
- 使用最新 GPS 定位點校準陀螺儀軌跡
- PWA 安裝到手機主畫面
- GitHub Pages 自動部署

## 使用方式

1. 開啟網站
2. iPhone / iPad 第一次使用陀螺儀時允許動作感測權限
3. 可分別按「開始 GPS」與「開始陀螺儀」
4. 若 IMU 軌跡飄移，可按「校準陀螺儀到 GPS」

## 發佈

保留 `.github/workflows/deploy-pages.yml`、`.nojekyll`、`manifest.json`、`service-worker.js` 與 `icons/`，
直接推到 GitHub repository 即可用 GitHub Pages 發佈。
