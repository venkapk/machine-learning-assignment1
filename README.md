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
    │   ├── Boston                  # Tasks such as EDA, feature engineering, and results  for Boston
    │   ├── Chicago                 # Tasks such as EDA, feature engineering, and results  for Chicago
    │   ├── LosAngeles              # Tasks such as EDA, feature engineering, and results  for LA
    │   ├── Dallas                  # Tasks such as EDA, feature engineering, and results  for Dallas
    │   ├── SanFrancisco            # Tasks such as EDA, feature engineering, and results  for San Francisco
    └── README.md                   # This README file

# Objectives:
1. Perform EDA on Listings data (e.g., price, review scores).
2. Engineer features from Reviews data to predict guest satisfaction.
3. Identify correlations and trends across neighborhoods using the listings data.

# Tasks
* **Descriptive Statistics**: Calculate summary statistics for numerical features such as `price`, `minimum_nights`, `maximum_nights`, `number_of_reviews`, and
`review_scores_rating`. Understand the central tendency, dispersion, and distribution of these variables.
* **Distribution Analysis**: Plot histograms or density plots for key numerical features like `price`, `minimum_nights`, and `review_scores_rating`. Analyze the
distribution of these features to identify any skewness or outliers.
* **Correlation Analysis**: Create a correlation matrix to explore relationships between numerical variables such as `price`, `number_of_reviews`, `availability_365`,
and `review_scores_rating`. Identify any strong correlations that might be useful for predictive modeling or further investigation.
* **Price Analysis**: Analyze the distribution of prices across different neighborhoods (`host_neighbourhood`) or room types (if available). Understand which
neighborhoods have higher or lower average prices and whether certain neighborhoods are more popular for shortterm or longterm stays.
* **Neighborhood Comparison**: Compare the average `review_scores_rating` across different neighborhoods. Determine if certain neighborhoods have consistently higher
ratings, which could indicate better or worse guest experiences.
* **Outlier Detection**: Identify outliers in the dataset, particularly in `price`, `minimum_nights`, and `review_scores_rating`.
* **Text Length**: Create a new feature that measures the length of each review (number of words or characters). Determine if the length of a review
correlates with its sentiment or the review scores.
* **Keyword Extraction**: Identify and count the occurrence of specific keywords (e.g., "clean," "comfortable," "noisy") in the reviews. Generate new features based on the
presence of these keywords, which might influence guest satisfaction.

# Contributors
* Milad Ghavami
* Pravinkumar Yadav
* Reena Sajad Hyder
* Venkateshprasad Pradeeprao Kulkarni

# License
This project is licensed under the MIT License. Feel free to use, modify, and distribute as needed.
