# LeafletIndoor
以 `22.924312, 120.286200` （沙崙）為中心，`zoom = 19`，並以高鐵台南站一二樓平面圖繪製室內地圖。
### Step1. 使用JOSM繪製室內地圖CAD
### Step2. 使用JOSM編輯tag
### Step2. 匯出成json檔
### Step3. 使用Leaflet及[Leaflet Indoor plugin](https://github.com/cbaines/leaflet-indoor)建構web版室內地圖
### Step4. 模擬使用NILM的方法分隔電器，冷氣顏色隨使用狀況改變 → [DEMO](https://itsuki8606.github.io/LeafletIndoor/)
粉色為使用中，白色為閒置中，目前為每三秒變換一次。
![demo](https://i.imgur.com/EcTnX2d.png)
