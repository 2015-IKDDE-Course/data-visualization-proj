# 全球14個先進國家近20年來之壽命變化  
#[網站連結] (https://yenwang.github.io/life_span_visualization/)  
#呈現目標  
隨著醫療技術的提升，近年來各個先進國家的人民平均壽命逐漸上升，此專案透過呈現以下14個先進國家：  
台灣、日本、韓國、美國、英國、德國、法國、挪威、瑞士、荷蘭、瑞典、奧地利、義大利、西班牙  
之20年來平均壽命(以1995年、2005年、2015年為取樣年分)的變化，來推論醫療科技的進步和人民平均壽命的正比關係  
並透過這14個國家的平均壽命差距，供人推測可能的成因。(ex:台灣空氣品質的影響......等等)  
#使用到的技術  
[d3.js v3] (https://d3js.org/)  
#設計流程 
1.到[政府資料開放平台] (http://data.gov.tw/)抓取所需的資料(此處使用[主要國家零歲平均餘命] (http://data.gov.tw/node/39495))  
2.讀入資料並繪製成長條圖  
3.供按鈕可以讓使用者依據有興趣的年份去做大小排序  