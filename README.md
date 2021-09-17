# GMail Wordscrape & Data Transformation
This repository aims to instruct users how to convert string formatted tables contained in GMail , into formatted DataFrames. (Example: Hedgeye Risk Ranges)

The first push of this repository aims to provide instruction to anyone attempting to wordscrape a datatable in a GMail account. The first push will include a notebook. It is designed to be run daily with a few minor adjustments to the model. It is designed to take a text table and eliminate data processing and formatting of the table. I ended up scraping the tables from the daily emails. This webscraper primarily uses Regex (regular expressions) to sort the text table on syntax conditions. The end result is a formatted export-ready dataframe of the daily ranges with just a few clicks.

The second push of this repository (now updated) will pull all Risk Range emails in one's Gmail account and will compile the ranges into one dataframe.

If anyone is wondering how I got into GMail API, Norman Benbrahim has a good tutorial on accessing their API (heads up, it is a bit ambiguous but navigable) 
   Youtube: https://youtu.be/vgk7Yio-GQw
      
   Github Repo: https://github.com/NormanBenbrahim/get_emails
      
