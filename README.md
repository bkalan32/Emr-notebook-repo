# EMR Notebook Repo

This repository contains a collection of Amazon EMR (Elastic MapReduce) Notebooks that demonstrate how to process, analyze, and derive insights from the [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## Dataset

The dataset used in this project is provided by [Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), containing information about 100k orders from a Brazilian e-commerce platform. It includes details such as:

- Orders
- Products
- Customers
- Sellers
- Payments
- Reviews
- Geolocation
- Shipping data

## Project Objective

The main objective of this project is to:

- Demonstrate how to use EMR Notebooks with Spark to process real-world datasets
- Perform data cleaning, transformation, and exploratory data analysis (EDA)
- Explore how EMR can be leveraged for scalable and cost-efficient big data processing
- Showcase potential downstream ML use cases (if applicable)


## Technologies Used

- Amazon EMR
- EMR Notebooks
- Apache Spark (PySpark)
- Amazon S3
- AWS Glue (optional, for Data Catalog integration)
- Python 3.x
- Pandas, Matplotlib, Seaborn (optional for local EDA or visualizations)

## Setup Instructions

1. **Upload the Dataset**  
   Download the dataset from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) and upload the CSV files to an S3 bucket.

2. **Launch EMR Notebook**  
   - Create an EMR cluster (or use EMR Serverless)
   - Open EMR Studio or EMR Notebooks in the AWS Console
   - Clone this repository in your notebook environment

3. **Run the Notebooks**  
   - Open each notebook in the `notebooks/` folder in sequence
   - Update any required S3 paths or configuration settings
   - Run each notebook cell to process and analyze the data

## Example Analyses

- Top-selling products and product categories
- Average customer review score by seller or product
- Shipping delay trends and delivery time analysis
- Revenue insights by location and payment type

## Possible Extensions

- Create Apache Iceberg or Delta Lake tables for versioned data lake support
- Integrate with AWS Glue Data Catalog for schema management

