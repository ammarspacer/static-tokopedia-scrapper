# static-tokopedia-scrapper
Static Tokopedia Web Scrapper using HTMLUnit and Java Language

The process is using HTMLUnit to access specific class name and extract the text contained within it.
This code has several limitations:
1. It didn't do dynamic web scraping, so if the page is dynamic it will not scrape the entire data from the page, only retrieving the data from first HTTP Request
2. It cannot traverse data from another link using the same window, so external data like Product Description that need to visit the store page cannot be retrieved or the you will get SocketTimeError  
