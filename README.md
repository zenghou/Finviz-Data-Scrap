#Project Title 
Finviz Data Scrap for Python 3.6. This is my first non-academic related program that I have written to allow users to specifically draw data from Finviz's top gainers page, and export the data into a csv file. Do note that this API only works for scraping data on one page of Finviz's website.'Hope this is of use to some people out there. 

#Prerequisites 

You'll need the following dependencies: 
1. BeautifulSoup4 
2. Pandas 
3. Urllib 
4. Datetime 

# Example usage 
This API can be called in two different ways. 

1. Without an input 
e.g. 'scrap_finviz()'

There is a url that is hard coded in this function based on the top 20 stocks on http://finviz.com/screener.ashx 
Feel free to modify the filters on the website accordingly and you can simply copy the url. 

2. With a url input 
e.g. 'scrap_finviz('http://finviz.com/screener.ashx') 

# Credits and Acknoledgement 
All the data is retrieved from http://finviz.com/screener.ashx 






