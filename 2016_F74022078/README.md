#動機(目的)
人們在旅遊的時候通常會希望能夠知道哪邊的景點最多，這樣才能在相同時間內拜訪最多地方，出於此發想，本程式統計台南各區的景點數量，並以柱狀圖的方式向使用者呈現台南各區的景點數量
#open data 來源
http://data.gov.tw/node/gov/resource/309
#注意事項
需enable cross-origin resource sharing<br>
建議方式: 安裝Google Chrome套件 Allow-Control-Allow-Origin: * <br>
套件連結: https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi?hl=zh-TW <br>
#使用到的技術
D3.js
#設計流程
1. 讀入cvs檔
2. parse各景點所屬的行政區
3. 計算各行政區內所包含的景點數
4. 產生柱狀圖表(並加入動態效果)
