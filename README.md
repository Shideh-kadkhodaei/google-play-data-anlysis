# Google Play Store Data Analysis

## 📌 Project Overview

This project explores the Google Play Store dataset using Python, focusing on app ratings, installations, reviews, pricing, app size, and categories. The goal is to clean the data, perform exploratory data analysis (EDA), and visualize patterns and relationships between different app attributes.

## 🎯 Objectives

- Explore and understand the Google Play Store dataset.
- Handle missing values and clean inconsistent data.
- Analyze app ratings, prices, reviews, and installations.
- Compare free and paid applications.
- Investigate relationships between app size, ratings, and installations.
- Create visualizations to identify trends and patterns.
- Export the cleaned dataset for further analysis.

## 📂 Dataset

The project uses the following input file:

- `googleplaystore.csv`

The dataset contains information about Google Play Store applications, including:

| Column | Description |
|---|---|
| `App` | Application name |
| `Category` | Application category |
| `Rating` | User rating |
| `Reviews` | Number of reviews |
| `Size` | Application size |
| `Installs` | Number of installations |
| `Type` | Free or paid |
| `Price` | Application price |
| `Content Rating` | Target audience classification |
| `Genres` | Application genre |
| `Last Updated` | Last update date |
| `Current Ver` | Current application version |
| `Android Ver` | Required Android version |

## 🛠️ Technologies Used

- **Python**
- **Pandas** — data manipulation and cleaning
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization
- **Jupyter Notebook** — interactive analysis

## 🔍 Project Workflow

### 1. Exploratory Data Analysis (EDA)

- Inspect dataset structure and data types.
- Review descriptive statistics.
- Identify missing values and potential data quality issues.
- Examine the distribution of app ratings and other numerical features.

### 2. Data Cleaning and Preprocessing

- Filter out ratings above the valid maximum of 5.
- Convert installation counts into numerical values.
- Convert prices into numerical values.
- Convert review counts into numerical values.
- Standardize app sizes into megabytes where possible.
- Remove rows missing essential values such as rating, installs, price, or reviews.

### 3. Data Visualization

The notebook includes visualizations to investigate:

- Distribution of app ratings.
- Relationship between price and rating for paid apps.
- Ratings across the top 10 app categories.
- Relationship between reviews and ratings.
- App categories with the highest total installations.
- Proportion of free versus paid apps.
- Relationship between app size and installations.
- Distribution of content ratings.
- Correlations among numerical features.
- Rating distributions for free and paid applications.

### 4. Export Cleaned Data

The cleaned dataset is saved as:

`googleplaystore_cleaned.csv`

This file can be reused for additional analysis or future machine learning projects.

## 📊 Key Analysis Areas

This project investigates several questions:

- How are app ratings distributed?
- Which categories have the highest total installations?
- Do paid apps have different rating patterns from free apps?
- Is there a relationship between the number of reviews and app ratings?
- How does app size relate to installations?
- What correlations exist among ratings, reviews, installs, price, and size?

The notebook is designed to explore these questions through data analysis and visualization rather than to establish causal relationships.

## 🚀 Getting Started

### Prerequisites

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Run the Project

1. Clone or download this repository.
2. Place `googleplaystore.csv` in the appropriate project directory.
3. Open the Jupyter Notebook.
4. Run the notebook cells in order.

```bash
jupyter notebook
```

## 📁 Project Structure

```text
Google-Play-Store-Analysis/
│
├── googleplaystore.csv
├── Machine Learning in Python Mini Project1.ipynb
├── googleplaystore_cleaned.csv
└── README.md
```

*The cleaned CSV is generated when the notebook is executed.*

## 🔮 Future Improvements

- Perform deeper statistical analysis.
- Investigate rating differences across categories.
- Analyze app update dates and version information.
- Build a machine learning model to predict app ratings or installation levels.
- Develop an interactive dashboard for exploring app data.


