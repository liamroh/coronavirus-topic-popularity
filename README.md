# Coronavirus Topic Popularity

This is a Jupyter Notebook workflow that focuses on the analysis and processing of tweets during the COVID-19 outbreak. This project includes text preprocessing, keyword analysis, topic modeling, statistical analysis, and various transformations on a pre-collected dataset. The ultimate goal is to gain insights into public sentiment, engagement, and the most discussed topics related to COVID-19 on Twitter.

## Table of Contents

- [Methodology](#methodology)
- [Packages Included](#packages-included)
- [Getting Started](#getting-started)
- [Cloning](#cloning)
- [Usage](#usage)
- [LDA Model Screenshot](#lda-model-screenshot)

---

## Methodology

**Methodology**:

1. **Data Preprocessing**:
   - Tokenization, stop word removal, lemmatization, and stemming

2. **Keyword Analysis**:
   - Created a bag of words from the preprocessed data
   - Filtered out tokens, keeping the 20 most frequent tokens

3. **Topic Modeling**:
   - Utilized Latent Dirichlet Allocation (LDA) to discover topics within the data
   - Identified dominant topics for each tweet

4. **Statistical Analysis + Modeling**:
   - Conducted regression analysis to examine relationships between dominant topics and other variables, such as favorites and retweets
   - Applied various mathematical transformations to further process the data

5. **Alternate Regressions and Transforms**:
   - Explored power transformation of data

---

## Packages Included

This project leverages several Python packages for data analysis and visualization, including:

- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [Gensim](https://radimrehurek.com/gensim/)
- [NLTK](https://www.nltk.org/)
- [scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [scikit-learn](https://scikit-learn.org/)
- [Statsmodels](https://www.statsmodels.org/stable/index.html)
- [pyLDAvis](https://github.com/bmabey/pyLDAvis)
- [openpyxl](https://openpyxl.readthedocs.io/en/stable/)

---

## Getting Started

**Prerequisites**:

Before getting started with this project, ensure you have the following prerequisites:

- [Python](https://www.python.org/) 3.8 or higher
- Jupyter Notebook

## Cloning

**Cloning**:

1. Clone the GitHub repository and navigate to the project directory:

   ```bash
   git clone https://github.com/YOUR-USERNAME/coronavirus-topic-popularity.git
   cd coronavirus-topic-popularity

 ## Start the Jupyter Notebook

   To run the Jupyter Notebook for this project, open your terminal and execute the following command:
   
    jupyter notebook
   
 ## Usage
   
   To use this project, follow these steps:
   
   1. Open the Jupyter Notebook "Coronavirus_Topic_Popularity.ipynb" using Jupyter Notebook
   2. Execute the cells in a sequential order to analyze and process coronavirus-related tweets
   3. Explore the provided visualizations and insights

   Note: The tweet dataset is not provided as part of this workflow, you will need to import your own tweets

## LDA Model Screenshot

**LDA Model Screenshot**:

![pyLDAvis Output](./LDAmodel.png)
