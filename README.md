# Crowdfunding ETL Project

![ETL Process](https://github.com/SakinaJaffri/-Crowdfunding_ETL_Project/assets/146900226/1031497d-d4b5-446c-8ca1-87c64ab68117)

## Project Overview

This project focuses on building an ETL (Extract, Transform, Load) pipeline for crowdfunding data. Using Python, Pandas, and PostgreSQL, the data is extracted from Excel files, transformed, and loaded into a relational database.

## Background

The goal of this project is to practice ETL processes by extracting crowdfunding data from Excel files, transforming it into a suitable format, and then loading the transformed data into a PostgreSQL database. The data is first processed into four CSV files, and an Entity Relationship Diagram (ERD) and database schema are created to map the database structure.

## Features

- Extract crowdfunding and contact data from Excel files.
- Transform and export data into four CSV files for **Category**, **Subcategory**, **Campaign**, and **Contact**.
- Create an Entity Relationship Diagram (ERD) and a database schema.
- Load the transformed data into PostgreSQL tables.

## Steps to Run

1. **Extract & Transform:** Run the Jupyter Notebook to extract data from Excel, transform it, and export it into CSV files.
2. **Database Setup:** Use the provided `crowdfunding_db_schema.sql` to create the PostgreSQL tables.
3. **Load Data:** Load the CSV files into the corresponding PostgreSQL tables.
4. **Verify Data:** Query the PostgreSQL database to ensure the data has been correctly loaded.

## Tools Used

- **Python**: For data extraction and transformation.
- **Pandas**: For data manipulation and transformation.
- **PostgreSQL**: To create and manage the database.
- **Jupyter Notebook**: To write and run the ETL process.
- **Excel**: For the original crowdfunding dataset.

## Usage

1. Clone the repository.
2. Run the Jupyter Notebook to perform the ETL operations.
3. Set up the PostgreSQL database using the provided schema file.
4. Load the CSV files into the PostgreSQL database.
5. Use SQL queries to interact with and analyze the loaded data.

## Contributors

- **Sakina Jaffri** - Developed the ETL pipeline and database schema.
