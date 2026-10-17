AI 人物辨識練習器（iPhone 網頁版）

檔案：
- index.html：完整網頁程式

功能：
- 透過瀏覽器相機辨識畫面中的人物
- 顯示人物框線、中心點與模型信心分數
- 可調整最低信心分數、切換前後鏡頭
- 不連接或控制任何遊戲

重要：
1. 相機權限通常只會在 HTTPS 網址或 localhost 中正常工作；直接點開本機 HTML 檔案可能無法啟動相機。
2. 需要網路載入 TensorFlow.js 與 COCO-SSD 模型。
3. 目前版本需要部署至 HTTPS 靜態網站後再用 iPhone Safari 開啟。
4. 這不是原生 iOS App，也不是已簽署的 IPA。
