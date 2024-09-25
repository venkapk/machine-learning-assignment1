# Project Overview
The project involves **Exploratory Data Analysis (EDA)** and **Feature Engineering** on Airbnb's Listings and Reviews datasets for five major Tech Hubs in the United States: **Boston, Chicago, Los Angeles, Dallas and San Francisco**. Key tasks include descriptive statistics, correlation analysis, price trends, neighborhood comparisons, outlier detection, and review text analysis.

# Contents
- [Data Source](https://github.com/venkapk/machine-learning/edit/master/README.md#data-source)
- [Folder Structure](https://github.com/venkapk/machine-learning/edit/master/README.md#folder-structure)
- [Objectives](https://github.com/venkapk/machine-learning/edit/master/README.md#objectives)
- [Tasks](https://github.com/venkapk/machine-learning/edit/master/README.md#tasks)
- [Contributors](https://github.com/venkapk/machine-learning/edit/master/README.md#contributors)
- [License](https://github.com/venkapk/machine-learning/edit/master/README.md#license)

# Data Source
Data is sourced from Inside Airbnb. The datasets used are:
- **Detailed Lisitings Dataset**: This dataset contains contains detailed information about each property, such as the `location`, `neighbourhood`, `price`, `minimum_nights`, `maximum_nights`, `availability`, `features` etc.
- **Detailed Reviews Dataset**: This dataset includes guest comments on various properties, reflecting their experiences and attributes such as the `listing_id` and `review_comments` .

🔗Source: [https://insideairbnb.com/get-the-data/](https://insideairbnb.com/get-the-data/)

# Folder Structure

    ├── data/
    │   ├── Listings
    |       ├──listingsBoston       # Listings data for Boston
    |       ├──listingsChicago      # Listings data for Boston
    |       ├──listingsSF           # Listings data for Boston
    |       ├──listingsDallas       # Listings data for Boston
    │   ├── README.md               # Describes the data sources
    ├── tasks/
    │   ├── Boston/                 # Directory for tasks for Boston
    |   |   ├──BostonListings       # Tasks such as EDA, feature engineering, and results on listing dataset for Boston
    │   │   ├──BostonReviews        # Tasks such as EDA, feature engineering, and results on reviews dataset for Boston
    │   ├── Chicago/                # Directory for tasks for Boston
    |   |   ├──ChicagoListings      # Tasks such as EDA, feature engineering, and results on listing dataset for Chicago
    │   │   ├──ChicagoReviews       # Tasks such as EDA, feature engineering, and results on reviews dataset for Chicago
    │   ├── Los Angeles/            # Directory for tasks for Los Angeles
    |   |   ├──LosAngelesListings   # Tasks such as EDA, feature engineering, and results on listing dataset for Los Angeles
    │   │   ├──LosAngelesReviews    # Tasks such as EDA, feature engineering, and results on reviews dataset for Los Angeles
    │   ├── Dallas/                 # Directory for tasks for DAllas
    |   |   ├──DallasListings       # Tasks such as EDA, feature engineering, and results on listing dataset for Dallas
    │   │   ├──DallasReviews        # Tasks such as EDA, feature engineering, and results on reviews dataset for Dallas
    │   ├── SF/                     # Directory for tasks for San Francisco
    |   |   ├──SanFranListings      # Tasks such as EDA, feature engineering, and results on listing dataset for SF
    │   │   ├──SanFranReviews       # Tasks such as EDA, feature engineering, and results on reviews dataset for SF
    └── README.md                   # This README file

# Objectives:
1. Perform EDA on Listings data (e.g., price, review scores).
2. Engineer features from Reviews data to predict guest satisfaction.
3. Identify correlations and trends across neighborhoods using the listings data.

# Tasks
* Descriptive Statistics: Summary stats for key features like price and review scores.
* Distribution Analysis: Visualize distributions and detect outliers.
* Correlation & Price Analysis: Identify correlations and trends in pricing across neighborhoods.
* Review Feature Engineering: Extract keywords and analyze review text length.

# Contributors
* Milad Ghavami
* Pravinkumar Yadav
* Reena Sajad Hyder
* Venkateshprasad Pradeeprao Kulkarni

# License
This project is licensed under the MIT License. Feel free to use, modify, and distribute as needed.
