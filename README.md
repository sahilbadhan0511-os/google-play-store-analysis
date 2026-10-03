# Google Play Store Analysis 📱

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on Google Play Store applications and user reviews using Python. The goal is to understand app popularity, ratings, installations, pricing, categories, and user sentiment.

The project uses data cleaning, statistical analysis, data visualization, and sentiment analysis to discover patterns and generate useful business insights.

## 🎯 Objectives

* Analyze Google Play Store app categories.
* Study app ratings and review counts.
* Identify popular and highly installed applications.
* Compare free and paid applications.
* Analyze app pricing and size.
* Examine user review sentiment.
* Compare positive, negative, and neutral reviews.
* Identify category-wise sentiment patterns.
* Generate key insights using visualizations.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📂 Project Structure

```text
google-play-store-analysis/
│
├── Google_Play_Store_Analysis.ipynb
├── googleplaystore.csv
├── googleplaystore_user_reviews.csv
├── requirements.txt
├── README.md
└── .gitignore
```

## 📊 Datasets

The project uses two datasets:

1. **Google Play Store Apps:** Contains app names, categories, ratings, reviews, installs, size, price, content rating, and other application details.
2. **Google Play Store User Reviews:** Contains app names, translated reviews, sentiment labels, sentiment polarity, and sentiment subjectivity.

Place both CSV files in the project directory before running the notebook.

## 🔍 Project Workflow

1. Import Python libraries.
2. Load the application and user review datasets.
3. Explore dataset structure, columns, and data types.
4. Check missing values and duplicate records.
5. Clean ratings, reviews, installations, prices, and app sizes.
6. Perform descriptive statistical analysis.
7. Analyze app categories and ratings.
8. Identify the most reviewed and installed apps.
9. Compare free and paid applications.
10. Analyze pricing distributions.
11. Examine user sentiment and sentiment polarity.
12. Merge application data with review data.
13. Generate business insights and dashboard-style visualizations.

## 📈 Key Analysis Areas

### App Category Analysis

* Number of apps in each category.
* Top 10 categories by app count.
* Average ratings by category.

### Rating and Popularity Analysis

* Distribution of app ratings.
* Most reviewed applications.
* Most installed applications.
* Relationship between reviews and installations.

### Pricing Analysis

* Free versus paid app distribution.
* Average ratings for free and paid apps.
* Pricing distribution among paid applications.
* Most expensive applications.

### User Sentiment Analysis

* Positive, negative, and neutral review distribution.
* Sentiment polarity distribution.
* Apps with the most positive and negative reviews.
* Sentiment analysis by category.
* Relationship between app ratings and review sentiment.

## 💡 Business Applications

This analysis can help developers and business teams understand:

* Which app categories have a large number of applications.
* How ratings and review counts vary across apps.
* Differences between free and paid apps.
* Common patterns in user feedback.
* Categories that receive positive or negative feedback.
* Opportunities to improve app quality and user satisfaction.

## ⚙️ Installation and Setup

### Step 1: Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/google-play-store-analysis.git
```

### Step 2: Open the project folder

```bash
cd google-play-store-analysis
```

### Step 3: Install the required libraries

```bash
pip install -r requirements.txt
```

### Step 4: Run Jupyter Notebook

```bash
jupyter notebook
```

Open `Google_Play_Store_Analysis.ipynb` and execute the cells in order.

## 📦 Requirements

The project requires Python and the following libraries:

* pandas
* numpy
* matplotlib
* seaborn
* jupyter

## 📝 Conclusion

This project demonstrates how Python can be used to clean, explore, analyze, and visualize real-world app store data. It examines application popularity, ratings, installations, pricing, and user sentiment to identify useful patterns and business insights.

The project provides practical experience in data analytics, data preprocessing, exploratory data analysis, statistical analysis, and data visualization.

## 👨‍💻 Author

**Sahil Pankaj Badhan**

* GitHub: [@sahilbadhan0511-os](https://github.com/sahilbadhan0511-os)
* LinkedIn: [Sahil Badhan](https://www.linkedin.com/in/sahil-badhan/)

## 🏷️ Topics

`python` `data-analysis` `exploratory-data-analysis` `pandas` `numpy` `matplotlib` `seaborn` `sentiment-analysis` `google-play-store` `data-visualization`
