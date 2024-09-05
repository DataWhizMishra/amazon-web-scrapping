# **Amazon Bestsellers Tech Data Analysis**

## **Project Overview**

This repository contains a data analysis project where I scraped data from Amazon's Bestsellers Tech page. The project involved collecting, preprocessing, and analyzing data to gain insights into the pricing and rating patterns of top tech products.

## **Role**

As a **Data Analyst**, my responsibilities included:

- Scraping data from Amazon's Bestsellers Tech webpage.
- Preprocessing and cleaning the collected data.
- Performing exploratory data analysis (EDA) to extract meaningful insights.

## **Technologies Used**

- **Python**: The primary programming language used for data scraping and analysis.
- **Beautiful Soup**: Utilized for web scraping to extract data from the Amazon webpage.
- **Matplotlib**: Employed for creating visualizations and plotting data.
- **Seaborn**: Used for advanced statistical data visualization.

## **Project Details**

### **Data Collection**

The data was scraped from the Amazon Bestsellers Tech page using Beautiful Soup. The collected data includes:

- Product Name
- Price
- Rating
- Number of Ratings

### **Data Preprocessing**

The data was cleaned and preprocessed to handle missing values and inconsistencies. Key preprocessing steps included:

- Removing duplicates
- Converting data types
- Handling missing values

### **Data Analysis**

The analysis focused on understanding the relationship between product ratings and price ranges. Key findings include:

- Most products with higher ratings fall within the **$0-$2500** price range.

### **Visualization**

The project includes visualizations created using Matplotlib and Seaborn to illustrate the distribution of ratings across different price ranges.

## **Conclusion**

This project demonstrates the ability to scrape and analyze e-commerce data to uncover pricing and rating trends. The findings highlight that a significant number of highly-rated tech products are priced between **$0 and $2500**.

## **Repository Structure**

- `data_scraper.py`: Script for scraping data from Amazon's Bestsellers Tech page.
- `data_preprocessing.py`: Script for cleaning and preprocessing the data.
- `data_analysis.py`: Script for performing exploratory data analysis and generating insights.
- `visualizations.py`: Script for creating visualizations using Matplotlib and Seaborn.
- `README.md`: This file.

## **How to Run**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-bestsellers-tech-analysis.git
