# car_24

![WhatsApp Image 2024-07-21 at 17 58 12](https://github.com/user-attachments/assets/3392afb0-4ed6-4476-87b1-4e47e2ab3fdc)

# **Title**: Cars24 Data Analytics
### **overview**
This project involves a comprehensive analysis of data sourced from the Cars24 website, focusing on approximately 600 cars across three distinct locations. Our goal is to extract meaningful insights that will aid our client in understanding market trends, pricing dynamics, and consumer preferences within the Cars24 marketplace. Through detailed analysis of various parameters such as brand, model, year, price, kilometers driven, and location, we aim to provide actionable recommendations based on robust data-driven insights.

### **Objectives** :

Evaluate Price Trends:
Compare average car prices from different brands between the current year and the previous year to identify any notable changes or trends.

Assess Usage Patterns:
Determine the average kilometers driven by the cars in our dataset to understand typical usage patterns and consumer preferences.

Identify Extremes:
Identify the most expensive and least expensive cars listed on Cars24 to provide insights into the price range and market positioning.

Analyze Market Share:
Analyze the distribution of listings by car brands to identify which brands dominate the market on the Cars24 platform.

### **Tools used** :

-Requests library
-Selenium and bs4(BeautifulSoup) library
-Pandas library
-NumPy library
-powerBI Tool


### **Methodology** 🛠️

1) Getting Data: first we request to car24 server to allow us for data scraping using class request.get() of requests package. we install requests package using pip install requests and than passing request using request.get(url of cars24). after getting a response code 200 we are able to do scraping.

2) Web scrapping: after getting permission the process of web scrapping is done with the help of BeautifulSoup and Selenium.using different tags of HTML we fetch the text part and store in a dictionary. after successfully storing the data in dictionary we convert the dictionary into a DataFrame with the help of padas library.

3) data cleaning: we get data without any Nan values or  missing value. In data cleaning we only split the column to get data. we mostly use replace,remove,split and slicing method of pandas library to get the other column data

4) data visualization: for data visualization part we use PowerBI.



### **Quick Summary**
1.Using Selenium And BeautifulSoup libraries of Python we Extracted data present on page and stored it in series and merging them to get DatFram
