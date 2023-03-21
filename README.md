# WebScraping_TextAnalysis

Using BeautifulSoup and Requests library, data was scraped from a news fact checking website called PolitiFact and a custom dataset of 300 article URLs was created in excel, amd was named 'Links.xlsx'.

Following this, in a second jupyter file, links were extracted to a list and iterated over to extract the web based articles to a text file. These files were accessed through a loop and text analysis was performed on them using NLTK library and various parameters were employed. The results of text analysis were stored in another excel file called 'Output.xlsx'.

The extracted news article links are stored in a 'NEWS.csv' file while Scraped_text folder contains individual txt files containing the articles scraped from the links in the 'Links.xlsx' excel sheet named by their index number starting from '0.txt'
