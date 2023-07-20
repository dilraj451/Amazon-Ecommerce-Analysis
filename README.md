# Amazon E-Commerce Analysis

## Objective
To present a comprehensive competitor analysis within the online headphone market to advise a new/existing company involved in headphone sales to inform their business strategies.

## File Links

[Raw Data](https://github.com/dilraj451/Amazon-Ecommerce-Analysis/raw/main/raw_data.xlsx)

[Cleaned Data](https://github.com/dilraj451/Amazon-Ecommerce-Analysis/raw/main/amazon_data_FINAL.xlsx)

[Exploratory Data Analysis](https://github.com/dilraj451/Amazon-Ecommerce-Analysis/blob/main/eda.ipynb)

[Dashboard](https://public.tableau.com/app/profile/dilraj.sidhu/viz/Book1_16897739973890/Dashboard_Final?publish=yes)

## Methodology
Amazon search results webpages for 'headphones and earbuds' were scraped using [Junglee's Amazon Product Scraper](https://apify.com/junglee/free-amazon-product-scraper), which extracted 1147 product results alongside a variety of features for each product (e.g. price, brand etc.).

Data cleaning was primarily carried out on MS Excel and included: removing irrelevant features; removing duplicate samples and filling blanks fields with appropriate values; correctly formatting dates and currencies.

Initial exploratory data analysis (EDA) was carried out using Pivot Tables to visualize large-scale trends such as brand popularity and whether additional factors, such as price and coupons, affect product ratings. Most EDA was executed in a [Jupyter Notebook](https://github.com/dilraj451/Amazon-Ecommerce-Analysis/blob/main/eda.ipynb), where numerous different visualizations were applied to: observe individual feature data distribution such that outliers could be removed if necessary; potential trends between speciifc features were investigated and evaluated.

The most relevant trends were summarized within an interactive [Tableau Dashboard](https://public.tableau.com/app/profile/dilraj.sidhu/viz/Book1_16897739973890/Dashboard_Final?publish=yes) for the benefit of key stakeholders seeking to observe competitor attributes.