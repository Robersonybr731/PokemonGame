# PokemonGame
## Introduction
本次專案是利用Visual Studio 2019 IDE 以C++程式語言進行軟體開發。

遊戲是以Pokemon抓寶及道館對戰為方向設計，玩家可以利用W、S、A、D按鍵進行上下左右的移動。

遊戲中有34種Pokemon monsters，地圖是以元智大學校園進行設計，依據不同建設、景觀進行不同的圖樣編排。

在地圖上行經綠地以及湖中時，相對應的草屬性以及水屬性的Pokemon monsters出現的機率將會大幅提升。

挑戰者可以使用抓到的Pokemon monsters對不同道館進行挑戰獲取積分。

最後遊戲結束時將依據積分的高低獲得不同的獎章圖示證明。

## Build Process

本次專案是以Visual Studio 2019 IDE進行編寫，因此流程會以此為中心進行說明。

### 環境建置
1. Open Visual Studio -> 建立新的專案 -> 空白專案 -> 建立
<div style="float:left;border:solid 1px 000;margin:2px;">
<img src="./img/create.png" width = "75%" />
<img src="./img/empty.png" width = "75%" />
</div>
複製所有檔案到專案建立的資料夾中

回到Visual Studio -> 方案總管 -> 資源檔 -> 右鍵加入現有檔案 -> 加入main.cpp

回到Visual Studio -> 方案總管 -> 標頭檔 -> 右鍵加入現有檔案 -> 加入所有header的檔案

專案->屬性->組態屬性->進階->字元集->使用多位元組字元集

