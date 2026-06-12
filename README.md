# Hacker News Data Mining Pipeline

## Overview

This project demonstrates an end-to-end data mining workflow using data collected from the Hacker News API. The project retrieves top stories, processes the collected data, performs exploratory data analysis, extracts trends and insights, and builds simple recommendation and search functionalities.

The objective of this project is to understand how real-world data mining pipelines are designed, implemented, and analyzed using Python.

---

## Author

**Prantika Biswas**

---

## Project Features

### Data Collection

* Fetch top stories from the Hacker News API
* Build structured datasets from raw JSON data
* Store processed datasets as CSV files

### Data Processing

* Convert Unix timestamps into readable datetime format
* Extract posting hour and day information
* Handle missing values
* Create derived analytical features

### Exploratory Data Analysis

* Dataset statistics
* Average score analysis
* Comment analysis
* Story popularity analysis
* Top authors analysis

### Text Mining

* Most common words in story titles
* Keyword frequency analysis
* Technology mention analysis
* AI-related story detection

### Trend Analysis

* Story category classification
* Category performance analysis
* Category-wise engagement comparison
* Time-based trend analysis

### Recommendation System

* Recommend highly engaging stories
* Search stories by keyword
* Analyze keyword impact on engagement

### Reporting

* Automated dataset reports
* AI story reports
* Summary analytics

---

## Technologies Used

* Python
* Requests
* Pandas
* Jupyter Notebook
* Hacker News API

---

## Project Structure

```text
hacker-news-data-mining-pipeline/
│
├── main.ipynb
├── top_stories.csv
├── README.md
└── requirements.txt
```

---

## Sample Analyses Performed

* Highest scoring stories
* Most discussed stories
* Correlation between score and comments
* Author performance analysis
* Hour-wise story analysis
* Day-wise story analysis
* Category trend analysis
* AI keyword impact analysis

---

## Future Improvements

* Interactive visualizations using Matplotlib
* Dashboard creation using Streamlit
* Sentiment analysis
* Machine learning-based popularity prediction
* Real-time data collection pipeline

---

## Learning Outcomes

This project demonstrates practical experience with:

* API-based data collection
* Data cleaning and preprocessing
* Feature engineering
* Exploratory data analysis
* Text mining
* Trend analysis
* Recommendation systems
* Modular Python programming
