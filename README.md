## 📊 Data Analysis 2 – Twitter Data Wrangling and Visualization Project

This project focuses on data wrangling, analysis, and visualization using multiple data sources.
It demonstrates the complete data analytics workflow — from gathering and cleaning real-world data to extracting insights through analysis and visualization.
The dataset centers around the popular WeRateDogs Twitter account, which humorously rates people’s dogs.

## 🧠 Overview

The goal of this project is to perform data gathering, assessment, cleaning, and analysis using Python.
It applies the data wrangling process to combine and refine datasets from different formats (CSV, TSV, and JSON).

Key features include:

📥 Data gathering from multiple sources

🧹 Data assessment and cleaning using Pandas

📊 Data visualization using Matplotlib and Seaborn

🐕 Exploratory analysis of WeRateDogs tweet data

🧩 Integration of image predictions and tweet metadata

## ⚙️ Datasets Used
| Dataset                        | Format | Description                                     |
| ------------------------------ | ------ | ----------------------------------------------- |
| `twitter_archive_enhanced.csv` | CSV    | Base dataset of WeRateDogs tweets               |
| `image_predictions.tsv`        | TSV    | Contains breed predictions for each tweet image |
| `tweet_json-copy.txt`          | JSON   | Twitter API data (retweet and favorite counts)  |
| `twitter_archive_master.csv`   | CSV    | Final cleaned and merged dataset                |

## 🔌 Project Files
| File                           | Description                                               |
| ------------------------------ | --------------------------------------------------------- |
| `wrangle_act.ipynb`            | Main notebook performing data wrangling and visualization |
| `twitter_archive_enhanced.csv` | Original dataset from WeRateDogs                          |
| `image_predictions.tsv`        | Model predictions for image content                       |
| `tweet_json-copy.txt`          | JSON file with tweet metadata                             |
| `twitter_archive_master.csv`   | Cleaned dataset used for final analysis                   |
| `wrangle_report.pdf`           | PDF summary of the wrangling and cleaning steps           |
| `act_report.pdf`               | Analytical report with insights and visualizations        |

## 💻 Software & Libraries

This project is written in Python and uses the following libraries:
vpip install pandas numpy matplotlib seaborn requests tweepy

To run Jupyter notebooks:

pip install jupyterlab

## 🪛 How to Run

**1- Open Jupyter Notebook**:

  - jupyter notebook wrangle_act.ipynb

**2- Run cells step-by-step**:

- Data Gathering: Import all three datasets.

- Data Assessment: Identify quality and tidiness issues.

- Data Cleaning: Use Pandas to clean, fix, and merge datasets.

- Data Analysis: Explore trends in ratings, retweets, and engagement.

- Visualization: Plot charts and insights.

## 📈 Key Features

✅ Automated data gathering from different file formats

✅ Systematic data assessment and cleaning workflow

✅ Integration of multiple data sources into one master dataset

✅ Clear data visualizations for insights and storytelling

✅ Professional reports (wrangle_report.pdf, act_report.pdf) summarizing process and findings

## 🔬 Example Insights

🐾 Most WeRateDogs tweets rate dogs above 10/10, reflecting the account’s humorous tone.

💬 Tweets with images tend to get higher engagement (favorites and retweets).

📅 Posting times and dog “stages” (puppo, doggo, etc.) correlate with popularity.

🧠 Certain dog breeds, predicted via image classification, consistently appear in high-rated tweets.

## 🌟 Future Improvements

🔗 Integrate real-time Twitter API streaming for live data updates.

📊 Add interactive dashboards using Plotly or Power BI.

🤖 Apply sentiment analysis or NLP models for tweet text.

🧠 Incorporate machine learning for predicting tweet popularity.

## 👨‍💻 Author

Omar Mohamed
Data Analysis 2 – Twitter Data Wrangling and Visualization Project (2025)
