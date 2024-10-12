# 01
YouTube Keyword-Based Video Search and Export Script
The main functions of this code are:

Search for videos using the YouTube API: The code uses the YouTube Data API to search for videos related to a specific keyword.
Define a time range: It allows you to adjust the video publication time range, such as from July 1, 2018, to July 1, 2024.
Extract video information: The program extracts the video title, publication date, and YouTube URL from the search results.
Handle multi-page results: If the search results exceed one page, it automatically handles multiple pages until all video data is retrieved.
Data organization and sorting: The extracted video data is stored in a Pandas DataFrame and sorted by publication date from the oldest to the newest.
Export to Excel: Finally, the code exports the organized video data into an Excel file, which is saved to a specified location.
The use case for this code is to collect information about videos related to a specific keyword on YouTube within a defined time period and save the data into an Excel file for further analysis.

這段代碼的主要功能是：

使用 YouTube API 搜尋影片：代碼會通過 YouTube Data API，搜尋與關鍵字相關的影片。
定義時間範圍：它可以自行調整影片的發佈時間範圍，比如從 2018年7月1日 到 2024年7月1日。
提取影片資訊：程式將搜尋到的影片標題、發佈日期和影片的 YouTube 網址提取出來。
多頁結果處理：如果搜尋結果超過一頁，它會自動處理多頁結果，直到所有影片數據被提取完畢。
資料整理與排序：將提取到的影片數據存入一個 Pandas DataFrame，並按發佈日期從最舊到最新進行排序。
導出到 Excel：最終，代碼會將這些整理好的影片數據匯出為 Excel 文件，保存到指定路徑。
這段代碼的應用場景是收集 YouTube 上某個關鍵字在特定時間段內的相關影片資訊，並將其數據保存為 Excel 文件，便於後續的數據分析。
