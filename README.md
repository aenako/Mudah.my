# Car Listings Data Scraper & Processor

**Project Overview**  
This project focuses on **scraping, cleaning, and processing car listings data from Mudah.my** to facilitate analysis and insights into the Malaysian used car market. Using **web scraping, data transformation, and outlier detection techniques**, the project extracts key attributes from car advertisements, processes the raw data, and prepares it for further analysis or machine learning applications.  

**Objectives**  
1. **Scrape car listing data** from multiple pages of Mudah.my using `requests` and `BeautifulSoup`.  
2. **Extract key attributes**, including product name, manufacturing year, price, condition, region, mileage, and engine capacity.  
3. **Clean and standardize the data**, handling missing values, formatting numerical values, and refining product names.  
4. **Detect and remove outliers** in price and engine capacity using the **Interquartile Range (IQR) method**.  
5. **Store the processed data** in a structured format (`CSV`) for further analysis or machine learning applications.  

**Technologies & Tools Used**  
- **Python** for data extraction, processing, and transformation  
- **Libraries**:  
  - `requests` & `BeautifulSoup` – for web scraping  
  - `pandas` – for data manipulation  
  - `re` – for text processing 

**Potential Applications**  
- **Market Trend Analysis**: Understanding price distributions and regional variations in car listings.  
- **Price Prediction Models**: Training machine learning models to estimate car prices based on features.  
- **Car Popularity Insights**: Identifying commonly listed models and their demand in the market.  

This project serves as a foundation for **further data analysis, visualization, and predictive modeling in the automotive industry**. 🚗📊
