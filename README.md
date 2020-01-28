# Foreigner
https://youtu.be/moj4BC_OgjE

# Summary
Information such as foreign residence by Seoul area, trend of inbound foreigners by country, exchange rate, etc. web page.

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
* Utilize Kakao map API for selecting regions on the main page
* Implement crawling function for providing exchange rate information
* Use google pie chart to provide information of foreign residents by region
* Visualize the data using DataFrame from Pandas and Matplotlib library

# Trade-off decisions
At the time of the initial design, we planed to use the fbprophet library to include the prediction of trend of inbound foreigners by country. I had a hard time installing this library in version 3.7 of Python. Therefore, I had to use the results of the analysis through the jupyter lab as an image.

# Challenges
In order to collect exchange rate disclosed by KEB Hana Bank in real time, I had to crawl data from the web page. I needed to understand libraries like 'beautiful soup', 'requests'. Also, i had to analyze DOM tree structure for getting attributes from HTML source.
