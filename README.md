供特教師生使用之語音報讀系統：

## 來源

本語音報讀系統改寫自 https://github.com/wxxxcxx/ms-ra-forwarder

## 部署

请参考下列部署方式。

### 部署到 Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/flysupers-projects/import?s=https%3A%2F%2Fgithub.com%2Fflysuper1122%2Fedgetts&hasTrialAvailable=1&showOptionalTeamCreation=false&project-name=edgetts&framework=other&totalProjects=1&remainingProjects=1)

1.本系統可以開啟本地PDF檔案，也可以網址後面加？googlesheetid=試算表id&file=雲端硬碟pdf 檔id，例：https://edgetts-lovat.vercel.app/?googlesheetid=1LX0cOdhO7dI_9zYBTs3MVKz5qEAF4LwDege0OHzghyc&file=17miE5mg1_GPlerNur0eg0BE_6Y3dC1tu<br>
2.googlesheet和googledrive檔案要開放知道連結的使用者檢視權。<br>
3.因為AI有些語詞發音錯誤，可用googlesheet過濾，試算表第一欄為原語詞，第二欄為替換語詞。<br>
例:https://docs.google.com/spreadsheets/d/1LX0cOdhO7dI_9zYBTs3MVKz5qEAF4LwDege0OHzghyc/edit?usp=drive_link

### 部署到 Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### 校內桌機PHP安裝版

https://www.dfes.ntpc.edu.tw/p/404-1000-8135.php

### 瀏覽器內建發音靜態網頁

下載後可部署於黑快馬的形象頁 https://github.com/flysuper1122/edgetts/blob/master/public/localvoice.html



