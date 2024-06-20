<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6295/6295417.png" width="100" />
</p>
<p align="center">
    <h1 align="center">POLITICAL-TWITTER-SENTIMENT-ANALYSIS</h1>
</p>

<p align="center">
	<img src="https://img.shields.io/github/languages/top/Mithesh1/Political-Twitter-Sentiment-Analysis?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/Mithesh1/Political-Twitter-Sentiment-Analysis?style=flat&color=0080ff" alt="repo-language-count">
<p align="center">
	<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=flat&logo=Jupyter&logoColor=white" alt="Jupyter">
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
	<img src="https://img.shields.io/badge/Tweepy-1DA1F2.svg?style=flat&logo=Twitter&logoColor=white" alt="Tweepy">
	<img src="https://img.shields.io/badge/TextBlob-FBBD42.svg?style=flat&logo=Python&logoColor=white" alt="TextBlob">
	<img src="https://img.shields.io/badge/Pandas-150458.svg?style=flat&logo=Pandas&logoColor=white" alt="Pandas">
	<img src="https://img.shields.io/badge/Matplotlib-0769AD.svg?style=flat&logo=Matplotlib&logoColor=white" alt="Matplotlib">
	<img src="https://img.shields.io/badge/Plotly-3F4F75.svg?style=flat&logo=Plotly&logoColor=white" alt="Plotly">
</p>
<hr>

##  Quick Links

> - [ Overview](#-overview)
> - [ Features](#-features)
> - [ Repository Structure](#-repository-structure)
> - [ Modules](#-modules)
> - [ Getting Started](#-getting-started)
>   - [ Installation](#-installation)
>   - [ Running Political-Twitter-Sentiment-Analysis](#-running-Political-Twitter-Sentiment-Analysis)
>   - [ Tests](#-tests)
> - [ Project Roadmap](#-project-roadmap)

---

##  Overview

The Political-Twitter-Sentiment-Analysis project is designed to continuously scrape tweets about political figures and perform live sentiment analysis. The primary goal is to understand public opinion on figures such as Joe Biden and Donald Trump by analyzing the sentiments expressed in real-time tweets mentioning them. Utilizing Tweepy for accessing the Twitter API, TextBlob for sentiment analysis, and various Python libraries for data processing and visualization, this project provides an ongoing, dynamic analysis of political sentiment as it evolves. The system runs indefinitely, periodically fetching new tweets and updating the sentiment analysis, ensuring that the insights remain current and relevant.

---

##  Features

Tweet Scraping: Continuously scrapes tweets mentioning specific political figures using the Twitter API.
Sentiment Analysis: Analyzes the sentiment of tweets to classify them as positive, negative, or neutral.
Data Visualization: Generates visualizations to display the sentiment distribution and trends over time.
Automated Execution: Runs periodically to fetch and analyze new tweets automatically.
CSV Export: Saves the collected tweets and their sentiment analysis results into CSV files for further analysis.


---

##  Repository Structure

```sh
└── Political-Twitter-Sentiment-Analysis/
    ├── Bidenall2.csv CSV file containing tweets mentioning Joe Biden.
    ├── ElectionSentimentAnalysis.ipynb Jupyter notebook for sentiment analysis of political tweets.
    ├── README.md
    ├── Trumpall2.csv CSV file containing tweets mentioning Donald Trump.
    └── webscrapper.ipynb Jupyter notebook for scraping tweets from Twitter.
```

##  Getting Started

***Requirements***

Ensure you have the following dependencies installed on your system:

* **JupyterNotebook**: `version 7.8.1`
* **Python**: `version 3`

###  Installation

1. Clone the Political-Twitter-Sentiment-Analysis repository:

```sh
git clone https://github.com/Mithesh1/Political-Twitter-Sentiment-Analysis
```

2. Change to the project directory:

```sh
cd Political-Twitter-Sentiment-Analysis
```

3. Install the dependencies:

```sh
pip install -r requirements.txt
```

###  Running Political-Twitter-Sentiment-Analysis

Use the following command to run Political-Twitter-Sentiment-Analysis:

```sh
jupyter nbconvert --execute notebook.ipynb
```

###  Tests

To execute tests, run:

```sh
pytest notebook_test.py
```

---

##  Project Roadmap

- [X] `► Implement Real-Time Sentiment Analysis: Develop functionality to provide real-time sentiment analysis of tweets.`
- [X] `► Enhance Data Visualization: Improve the visualizations to provide more detailed insights.`
- [X] `► Expand Data Sources: Integrate additional data sources for a more comprehensive analysis.`
- [X] `► Optimize Tweet Scraper: Enhance the tweet scraper for better performance and accuracy.`



- List any resources, contributors, inspiration, etc. here.

[**Return**](#-quick-links)

---
