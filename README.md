# Web Scraping and Market Analysis of Smartwatches on Flipkart

## Project Overview
This project focuses on collecting and analyzing smartwatch product data from Flipkart Explore Pulse.  
The data was collected using web scraping techniques and analyzed to understand patterns in pricing, ratings, reviews, brand distribution, and promotional tags.

The project demonstrates the complete data analysis workflow, including:
- Data collection through web scraping
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Data visualization and insight generation

## Data Source
The dataset was collected from **Flipkart Explore Pulse**, an analytics platform that provides insights into product trends on Flipkart.

Web scraping was performed using:
- BeautifulSoup
- Requests
- Python

## Project Workflow

### 1. Web Scraping
Smartwatch product data was scraped from Flipkart Explore Pulse using Python libraries such as **Requests** and **BeautifulSoup**.

The scraping process extracted key product attributes including:
- Brand
- Price
- Original Price
- Discount
- Ratings
- Reviews
- Strap Color
- Size
- Flipkart Assured tag
- Sponsored tag

### 2. Data Cleaning and Preprocessing
The raw scraped data was cleaned and processed to prepare it for analysis.

The following steps were performed:
- Handling missing values
- Correcting data types
- Creating price categories
- Removing inconsistencies
- Preparing the dataset for analysis

All cleaning operations are documented in:

**01_Data_Cleaning.ipynb**

### 3. Exploratory Data Analysis (EDA)
EDA was conducted to understand the structure and patterns in the dataset.

Key analyses performed include:
- Price distribution analysis
- Brand distribution analysis
- Ratings and reviews analysis
- Strap color distribution
- Flipkart Assured vs Sponsored products
- Outlier detection in price
- Multivariate relationships between price, ratings, and reviews

The visual analysis is available in:

**02_EDA_Visualization.ipynb**

## Data Visualization
Various visualization techniques were used to explore the dataset, including:
- Bar plots
- Box plots
- Violin plots
- Pair plots
- Scatter plots
- Density plots
- Lollipop charts
- Pie charts

These visualizations helped uncover patterns and trends in smartwatch pricing and customer engagement.

## Project Structure

Flipkart-smartwatch-analysis

- 01_Data_Cleaning.ipynb – Data preprocessing and cleaning  
- 02_EDA_Visualization.ipynb – Exploratory data analysis and visualizations  
- flipkart_smartwatch_dataset.csv – Dataset used for analysis  

## Tools and Technologies
- Python
- Requests
- BeautifulSoup
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Insights
Some of the important insights from the analysis include:
- Most smartwatches fall within the budget and mid-range price categories.
- Product ratings are generally concentrated between 4.0 and 4.5.
- Certain brands contribute significantly to price outliers.
- Reviews vary widely across different price segments.
- Promotional tags such as Sponsored and Flipkart Assured influence product visibility.

## Author
Chandrika Tadikonda
