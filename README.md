# Foreigner

# Summary
Information such as foreign residence information by Seoul area (old district), trend of inbound foreigners by country, exchange rate information, etc. web page.

# Languages
* Python
* Html5
* SQLite
* JavaScript
* CSS

# Tools
* PyCharm
* DB Browser
* Anaconda(Jupyterlab)

# Frameworks and Technologies
* Django
* MVT Design pattern
* jQuery(Ajax)
* Bootstrap
* REST API

# APIs & Library
* Kakao map API
* Google PieChart API
* Pandas
* Matplotlib
* BeautifulSoup
* Requests

# Features
* Utilize the Kakao map API for selecting regions on the main page
* Implement crawling function for providing exchange rate information
* Use google pie chart to provide foreign residents' information by region
* Visualize the data using pandas DataFrame and matplotlib

# Trade-off decisions
At the time of the initial design, we were going to use the fbprophet library to include the prediction of trend of inbound foreigners by country. I had a hard time installing this library in version 3.7 of Python. So I had to use the results of the analysis through the jupyter lab as an image.

# Challenges
In order to retrieve currency exchange rate information disclosed by KEB Hana Bank in real time, I had to crawl data from the web page. I needed to understand libraries like 'beautiful soup', 'requests'. Also, i needed to understand dom tree structure for getting attributes needed to be crawled.
