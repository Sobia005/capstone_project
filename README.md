# Hamrfull Chemicals in Cosmetics

## PowerBI Dashboard

Link: 



## Table of Contents
* [PowerBI Dashboard](#PowerBI-dashboard)
* [Motivation](#motivation)
* [Questions](#questions)
* [Data Preparation](#data-preparation)
* [Challenges](#Challenges)
* [Technologies Used](#technologies-used)
* [Sources](#sources)
* [Conclusion](#conclusion)

## Motivation:
Beauty and cosmetic products are a big part of women everyday life. I have always seen my sister being careful about choosing safe, organic products. She spends a lot of time researching ingredients andreading reviews before buying anything. She often advises me on what to use and what to avoid. Seeing
her dedication made me curious. Are these products really as safe as they seem? I wanted to explore the presence of harmful chemicals in cosmetics.


## Questions:
1) What are the most common harmful chemicals in cosmetics?
2) Which companies and brands have discontinued their products due to chemical concerns?
3) What are the most frequently continued and discontinued chemicals?
4) How do these chemicals vary across different product categories (e.g., skincare, makeup, hair care)?

## Data Preparation
The dataset I selected includes information on harmfull chemicals in cosmetics, discountinued products, affected brand and the product cetagories. I cleaned and normalized the data using Python, removing duplicates, and making sure chemical names were consistent throghout the dataset. After cleaning, I converted each dataframe into a CSV file to easily import the data into Power BI for visualization and analysis.

## Challenges:
Cleaning the data was difficult because there were many missing values (NaNs), making it hard to organized the information in a meaningfull way. Another confusing part was understanding the different date columns in the dataset. InitialDateReported is the date when the manufacturer first reported the product to the California Department of Public Health (CDPH). ChemicalCreatedAt is the date when a specific chemical in the product was first reported. It took a lot of careful reading of the data guide to understand the difference between these dates and how to use them correctly.

## Technologies Used
1) Python / Pandas - for exploration, normalizing and aggregation of the dataset
2) PowerBI - for creating interactive dashboard
3) Canva - for introduction of Project
4) Git - for version control

## Sources
To answer the above questions I used the following sources to collect datasets for my analysis

1) Chemicals in Cosmetics: https://data.chhs.ca.gov/dataset/chemicals-in-cosmetics/resource/57da6c9a-41a7-44b0-ab8d-815ff2cd5913


2) Campaign for Safe Cosmetics: https://www.safecosmetics.org/

3) The Good Trade: https://www.thegoodtrade.com/features/clean-organic-makeup-brands/

4) Clean Beauty Awards: https://www.cleanbeautyawards.com/blog/42-clean-beauty-brands-in-the-usa-you-should-try

## Conclusion
This analysis shows that many cosmetics contain harmful chemicals, and some companies have discontinued products that contain them. While some chemicals are linked to health risks, more research is needed to confirm direct effects. Future studies could expand on this by including more health data and studying consumer awareness of harmful ingredients in beauty products.
 