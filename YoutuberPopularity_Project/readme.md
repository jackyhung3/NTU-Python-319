Youtuber Popularity and Analytics

Selenium suite and Pyquery collect data of a selected Youtuber’s subscription number, quarterly number of videos posted, number of views, average video length, advertising revenue, as well as viewer to subscriber ratio. 
After conducting data analysis, a report compared the quarterly performances of the selected Youtuber.

使用selenium套件 + PyQuery 做網頁爬蟲
蒐集該名 Youtuber 加入日期、頻道總觀看次數、頻道訂閱數、至6個月前所有影片數量、標題字數、時間長度、觀看次數
以一季 ( 3個月 ) 做數據分析

程式執行步驟
1. 輸入 Youtube 頻道網址
2. webdriver點擊簡介，蒐集加入日期和頻道總觀看次數
3. 使用 datetime 算出經營天數，以90天為一季算出現在是第幾季
4. webdriver點擊影片，開始捲動頁面 ( 設定為拉到底十次 )
5. 以訂閱數判定其為 微型 or 小型 or 中型 or 大型 Youtuber
6. 蒐集這一季所有影片數量、時間長度、觀看次數
7. 算出總影片數、標題總字數、標題平均字數、總觀看次數、平均觀看次數、營利播放次數、Youtube廣告收益、Youtuber廣告收益、影片長度、影片平均長度
這一季觀看次數佔頻道總觀看次數的百分比
8. 這一季觀眾黏著度 ( 平均觀看次數 / 頻道訂閱數 ) 判定其表現為 再加油 or 尚可 or 不錯 or 超棒
9. 蒐集上一季影片資料 ( 標的同這一季 )
10. 兩季比較 
