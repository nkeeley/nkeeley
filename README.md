## Description

This portfolio provides a snapshot of data science-related work I've done professionally, personally, and academically. 

Last updated: 22 AUG 2023. 

Language types: SQL, R, Python, HTML. 

![](https://komarev.com/ghpvc/?username=nkeeley&color=blue)

## Table of Contents

### Professional

[Project: Shopper Marketing ROI Optimization (MSDS Capstone Project)](https://github.com/nkeeley/nkeeley/edit/main/README.md#capstone-project-measuring-shopper-marketing-effectiveness)

### Personal



### Academic

[Project: "Cash, Credibility, and Conversion: The Influence of Synthetic Media on Investment Behavior" 现金、信念、和转化：合成媒体对投资行为的影响]

[Project: Exploring Company Earnings Calls Before & After COVID-19 (Exploratory Text Analytics)](https://github.com/nkeeley/nkeeley/edit/main/README.md#text-analytics-project-exploring-company-earnings-calls-before--after-covid-19)

[Programming and Systems for Data Analysis (CS5010)](https://github.com/nkeeley/nkeeley/edit/main/README.md#cs5010---programming-and-systems-for-data-analysis)

[Foundations of Computer Science (CS5012)](https://github.com/nkeeley/nkeeley/edit/main/README.md#cs5012---foundations-of-computer-science)

[Linear Models for Data Science (STAT6012)](https://github.com/nkeeley/nkeeley/edit/main/README.md#stat6012---linear-models-for-data-science)

[Practice and Application of Data Science (DS6001)](https://github.com/nkeeley/nkeeley/edit/main/README.md#ds6001---practice-and-application-of-data-science)

[Data Visualization and Analytics (DVA)](https://github.com/nkeeley/nkeeley/edit/main/README.md#dva---data-visualization-and-analytics)

[Data Science in Business (DSB)](https://github.com/nkeeley/nkeeley/edit/main/README.md#dsb---data-science-in-business)

[Statistical Learning / Data Mining (DS6030)](https://github.com/nkeeley/nkeeley/edit/main/README.md#ds6030---statistical-learning)

[Bayesian Machine Learning (DS6014)](https://github.com/nkeeley/nkeeley/edit/main/README.md#ds6014---bayesian-machine-learning)

[Deep Learning (DS6050)](https://github.com/nkeeley/nkeeley/edit/main/README.md#ds6050---deep-learning)

[Exploratory Text Analytics (DS5001)](https://github.com/nkeeley/nkeeley/edit/main/README.md#ds5001---exploratory-text-analytics)
## 

## Professional

### Project: Shopper Marketing ROI Optimization (MSDS Capstone)

[Repository](https://github.com/nkeeley/capstone-project-measuring-shopper-marketing-tactic-effectiveness/blob/main/README.md)

Language types: SQL, Python

A leading international consumer packaged goods (CPG) company asked our team (capstone project) to help with assessing the ROI of their shopper marketing strategies. They provided us access to their database, which totaled over 30M customer transactions and product marketing efforts. Our team extracted, cleaned, and aggregated this data prior to analysis. Based on pre-existing literature on retail sales forecasting, I chose to build a random forest model using walk-forward validation. My model ultimately outperformed our baseline/other competing models, and was accepted by our client for further development. We were able to use this model to determine effective vs. ineffective marketing strategies. Due to the proprietary nature of the data involved, this project notebook is selectively available by request - please message me at https://www.linkedin.com/in/nicholas-g-keeley/. 

![image](https://github.com/nkeeley/capstone-project-measuring-shopper-marketing-tactic-effectiveness/blob/main/CapstoneScreenshot2.jpg)

## Personal

## Academic

### Project: "Cash, Credibility, and Conversion: The Influence of Synthetic Media on Investment Behavior" 
### 现金、信念、和转化：合成媒体对投资行为的影响 

Repository: In progress

Language types: Python

For the capstone project of the Schwarzman Scholars program, I empirically evaluated the influence of synthetic text on investment behavior (inspired by deepfakes and other forms of synthetic disinformation). I created two different survey versions in Chinese, embedding each with either a real earnings call transcript sample or a ChatGPT-generated one. Respondents were randomly exposed to either survey version and asked a series of questions. Data was compiled from the surveys, aggregated, and then analyzed via Welch t-tests. Semantic analysis (using a Chinese parser!) was conducted on qualitative responses. Results indicated that AI-generated financial text can significantly alter investor behavior, and even introduce more extreme "conversions" in opionion than their genuine counterparts. 
Full paper (Arxiv) here: https://arxiv.org/abs/2306.05033.

![image](https://github.com/nkeeley/schwarzman_capstone/blob/main/thesis_pic.jpg)

### Project: Exploring Company Earnings Calls Before & After COVID-19 (Exploratory Text Analytics)

[Repository](https://github.com/nkeeley/Exploring-Company-Earnings-Calls)

Language types: Python

For the capstone project of my Exploratory Text Analytics class, I chose to investigate how company earnings call language changed before/after the onset of the COVID-19 pandemic. I produced my own raw text dataset by scraping over 35K earnings calls publicly available on the Motley Fool's website, ultimately refining the corpus into a digital analytical edition that contained topic modeling, semantic algebra, PCA, agglomerative clustering, and more.

![image](https://github.com/nkeeley/Exploring-Company-Earnings-Calls/blob/main/ClusteringTickers.jpg)

### Programming and Systems for Data Analysis (CS5010)

[Repository](https://github.com/nkeeley/CS5010-Programming_and_Systems_for_Data_Analysis)

Language types: Python

This repository contains key assignments and projects for an introductory programming course in Python. Topics include object oriented programming, webscraping, data visualization, and pandas dataframe querying.

###  Foundations of Computer Science (CS5012)

[Repository](https://github.com/nkeeley/CS5012-Foundations_of_Computer_Science)

Language types: Python

This repository contains assignments and projects related to the fundamentals of relational database design, data structures, and algorithmic programminig. Topics include entity-relationship diagrams, graph networks, search algorithms, regular expressions, hash tables, database transactions, propositional logic, Big-O complexity, and the solutions for Nearest-Neighbor/Closest-Pair problems.

![Sample ER Diagram](https://github.com/nkeeley/CS5012-Foundations_of_Computer_Science/blob/main/Screen%20Shot%202022-05-24%20at%2010.17.54%20PM.png)

### Linear Models for Data Science (STAT6012)

[Repository](https://github.com/nkeeley/STAT6021-Linear_Models_for_Data_Science)

Language types: R

This repository contains assignments and projects for a course on basic statistics for data science. Course topics included single linear regression, multiple linear regression, logistic regression, transformation, ANOVA F-tests, stepwise/backwards/forwards model creation, and linearity assumptions.

![Sample Visualization](https://github.com/nkeeley/STAT6021-Linear_Models_for_Data_Science/blob/main/STAT6021_DiamondVisual%20copy.jpg)

### Practice and Application of Data Science (DS6001)

[Repository](https://github.com/nkeeley/DS6001-Practice_and_Application_of_Data_Science)

Language types: Python, SQL

This repository contains assignments that involve loading, processing, and querying data along the "data pipeline." Data was accessed via tabular files, relational/NoDBMS databases, and APIs.

```
## Cursor query

pitch_cursor = winedb.cursor()
pitch_cursor.execute("SELECT title, artist, score FROM reviews WHERE score = 10")
response1 = pitch_cursor.fetchall()
df1=pd.DataFrame(response1)
df1

## Alt query

df2 = pd.read_sql_query("SELECT title, artist, score FROM reviews WHERE score = 10", winedb)
df2

## commit and close

winedb.commit()
winedb.close()
```

###  Data Visualization and Analytics (DVA)

[Repository](https://github.com/nkeeley/DVA-Data_Visualization_and_Analytics)

Language types: SQL

This repository contains assignments involving data visualizations via Tableau, as well as big data querying/predictive model generation using GoogleBigQuery.

![BigQuery](https://github.com/nkeeley/DVA-Data_Visualization_and_Analytics/blob/main/GoogleBigQuery.jpg)

### Data Science in Business (DSB)

[Repository](https://github.com/nkeeley/DSB---Data-Science-in-Business)

Language types: Python

This repository contains several assignments and projects related to predictive modeling (using machine learning tecniques), data munging, and data visualization. For the final project, my team and I submitted a model to an expired Kaggle competition: the Microsoft Malware Classification Challenge.

![image](https://github.com/nkeeley/DSB---Data-Science-in-Business/blob/main/TreeImage.jpg)

###  Statistical Learning (DS6030)

[Repository](https://github.com/nkeeley/DS6030-Statistical-Learning/blob/main/README.md)

Language types: R

This repository contains exams and assignments primarily involving hyperparameter tuning of statistical models. Additional topics include KNN models, model-based clustering/Kernel Density Estimation, association analysis, and validation techniques (e.g. OOB, k-fold, etc.). Note: each .Rmd file has an associated HTML file with a similar name.

![image](https://github.com/nkeeley/DS6030-Statistical-Learning/blob/main/TreeTuning.jpg)

### Bayesian Machine Learning (DS6014)

[Repository](https://github.com/nkeeley/DS6014---Bayesian-Machine-Learning)

Language types: Python

This repository contains assignments and projects relevant to Bayesian Machine Learning. Topics include practical applications of Bayes Theorem and conjugate analysis, Naive Bayes Classifiers and LDA/QDA Bayes Optimal Classifiers, Bayesian regression models, sampling methods (e.g. Gibbs Sampling, MCMC sampling, etc.), variational inference, Hidden Markov Models, pooled vs unpooled vs. hiearchical models, and an implementation of autoencoder variational Bayes to topic modeling. Note: many of these notebooks were produced on a remote operating system with pymc3 pre-installed. This package is required to run many of the sampling methods used, and is challenging to install on many computers.

![image](https://github.com/nkeeley/DS6014---Bayesian-Machine-Learning/blob/main/BayesSampleImage.jpg)

### Deep Learning (DS6050)

[Repository](https://github.com/nkeeley/DS6050---Deep-Learning)

Language types: Python

This repository contains the assignments and projects related to a Deep Learning course. Topics included the architectures of Convolutional Neural Networks (CNNs), construction of CNNs from scratch and via Tensorflow Keras, the creation of recurrent neural networks, the application of transfer learning, and the detection of GAN-generated satellite images. Also, all assignment were run in GoogleCollabPro to reduce runtime duration/RAM maxout.

![image](https://github.com/nkeeley/DS6050---Deep-Learning/blob/main/FiltersImage.jpg)

### Exploratory Text Analytics (DS5001)

[Repository](https://github.com/nkeeley/DS5001---Exploratory-Text-Analytics)

Language types: Python

This repository contains assignments and projects associated with exploratory text analytics. Topics include manual text cleansing/OHCO chunking using regex, parts of speech annotation, term-frequency analysis, n-gram analysis, agglomerative clustering, principal components analysis, topic modeling, and semantic algebra through word embeddings. For sentiment analysis-related content covered in class, please see https://github.com/nkeeley/Exploring-Company-Earnings-Calls.

![sample](https://github.com/nkeeley/DS5001---Exploratory-Text-Analytics/blob/main/TopicModel.jpg)

<!--
**nkeeley/nkeeley** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
