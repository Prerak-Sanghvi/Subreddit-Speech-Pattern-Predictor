## Project Overview

This project focuses on the classification of Reddit comments to their respective subreddits, aiming to identify unique linguistic patterns associated with different online communities. By analyzing textual data, the project seeks to develop a predictive model that can accurately assign comments to their source subreddits.

## Motivation

Reddit, as a large and diverse online forum, presents a valuable dataset for studying online subcultures and their language use. This project explores the potential of machine learning to understand and categorize these linguistic differences, with potential applications in areas like hate speech detection, mental health analysis, and political discourse analysis.

## Data

The dataset used in this project was aggregated from four distinct subreddits:

* `funny`
* `philosophy`
* `The_Donald`
* `SandersForPresident`

The data was collected using a Python script and stored in a CSV format, including fields such as subreddit (`sub`), username, and comment text.

## Methodology

The project employed the following methodologies:

* Data preprocessing and feature extraction, including word counts, stop word analysis, and contextual word searches.
* Text vectorization using TF-IDF.
* Machine learning model development and evaluation using decision trees and Multinomial Naive Bayes.
* Analysis of the average words, and stop word count, and vocabulary size of each subreddit.

## Key Findings

* TF-IDF vectorization proved significantly more effective than simple bag-of-words approaches.
* Contextual features, such as the presence of specific keywords, improved model accuracy for certain subreddits.
* The vocabulary size, average words, and stop word count differed between subreddits.

## Libraries Used

* pandas
* nltk
* scikit-learn (sklearn)
* seaborn
* matplotlib


## Potential Applications

* Hate speech detection
* Analysis of language patterns related to mental health
* Political affiliation analysis
* Identifying echo chambers.

