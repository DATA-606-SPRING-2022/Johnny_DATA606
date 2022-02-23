google_search_returns_urls jupyter Notebook provides urls from google that are based on a time based search of a search term.  

These URLs are placed into a dataframe and stored along side the search term and date.  
The date is a one day span of time for each loop.  The initial run is intended to be for a single term.  AAPL.  Subsequent runs will be for adjacent search terms intended to pull in information about the same stock.  

This is a first step.  the loop in the script will query google but the problem is runing this script will make google mad at you.  Before we run this script we need a vpn script that runs the script through a random vpn to keep google from getting mad at you. 