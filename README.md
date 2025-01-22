# supplements-vitamins
Exploring the Supplement &amp; Vitamins E-commerce Market (Webscraping Data Collection, Exploratory Data Analysis)

The objective of this project is to explore the supplements and vitamins e-commerce market by leveraging web scraping and exploratory data analysis (EDA).
An online pharmacy website, recognized as one of the most visited in Greece by consumers, was scraped using Beautiful Soup to collect relevant data for analysis. 

Exploratory Data Analysis (EDA) was conducted on this dataset, covering insights such as the Top 10 most inexpensive products based on normal_price, the Top 10 products with the highest discounts (discount%), an analysis of discounts offered across the pharmacy, and the Top 10 highest-rated products. This analysis aims to uncover market trends and identify consumer preferences in the supplements and vitamins sector.Furthermore, the analysis explored the most commonly seen ingredients and the most popular categories of supplements, contributing to a detailed market mapping of the supplements and vitamins sector.

## Index of files

**.ipynb** files
  **Pharmacy24webscrape_final.ipynb**:  Data collection - webscraping of online pharmacy
  
  **EDA_SupVitDataset.ipynb**:  Data cleaning, processing, analysis and visualization of the extracted dataset
    
**.csv** file
  **SupVit_Dataset.csv**:  The extracted dataset includes detailed information on various products within the category of supplements and vitamins
    **product_name**: a combination of the product's name and a short description)
    **category**: indicating the product's category
    **normal_price**: the original price of the product
    **discount_price**: the price after applying discounts
    **reviews_count**: the number of reviews received
    **rating**: the average product rating
    **discount%**: calculated as (normal_price - discount_price) / normal_price)
    **weighted_average metric**: computed to assess product popularity and quality,using the formula: (rating * 0.6 + reviews_count * 0.4) / (0.6 + 0.4). 
  


