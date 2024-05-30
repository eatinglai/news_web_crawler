
這段程式碼的目的是從UDN Money網站抓取即時新聞的標題和連結。
主要步驟如下：
設置HTTP請求頭: 使用指定的用戶代理來模擬瀏覽器請求。
發送請求並解析HTML: 發送GET請求到目標網址，並使用BeautifulSoup解析回應的HTML內容。
抓取新聞項目: 找到所有具有"latest story"類別的列表項，這些項目包含新聞的標題和連結。
提取並儲存連結: 提取每個新聞的標題和連結，將連結添加到 new_list 列表中，並打印新聞標題和連結到控制台。