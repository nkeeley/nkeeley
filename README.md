## Nick's Portfolio


### Description

This portfolio provides an overview of data science-related work I've done since 2020, when I began a Masters in Data Science at the University of Virginia. Last updated: 24 MAY 2022.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nkeeley)](https://github.com/nkeeley/github-readme-stats)

[![Nick's github stats](https://github-readme-stats.vercel.app/api?username=nkeeley&count_private=true&show_icons=true&theme=radical&hide_rank=false)](https://github.com/nkeeley/github-readme-stats)


### Table of Contents

[CS5010 - Programming and Systems for Data Analysis](https://github.com/nkeeley/nkeeley/edit/main/README.md#cs5010---programming-and-systems-for-data-analysis)

[CS5012 - Foundations of Computer Science](https://github.com/nkeeley/nkeeley/edit/main/README.md#cs5012---foundations-of-computer-science)

[STAT6012 - Linear Models for Data Science](https://github.com/nkeeley/nkeeley/edit/main/README.md#stat6012---linear-models-for-data-science)

[DS6001 - Practice and Application of Data Science](https://github.com/nkeeley/nkeeley/edit/main/README.md#ds6001---practice-and-application-of-data-science)

[DVA - Data Visualization and Analytics](https://github.com/nkeeley/nkeeley/edit/main/README.md#dva---data-visualization-and-analytics)

[DSB - Data Science in Business](https://github.com/nkeeley/nkeeley/edit/main/README.md#dsb---data-science-in-business)

[Text Analytics Project: Exploring Company Earnings Calls Before & After COVID-19](https://github.com/nkeeley/nkeeley/edit/main/README.md#text-analytics-project-exploring-company-earnings-calls-before--after-covid-19)

[DS6030 - Statistical Learning](https://github.com/nkeeley/nkeeley/edit/main/README.md#ds6030---statistical-learning)

[Capstone Project: Measuring Shopper Marketing Effectiveness](https://github.com/nkeeley/nkeeley/edit/main/README.md#capstone-project-measuring-shopper-marketing-effectiveness)

[DS6014 - Bayesian Machine Learning](https://github.com/nkeeley/nkeeley/edit/main/README.md#ds6014---bayesian-machine-learning)

[DS6050 - Deep Learning](https://github.com/nkeeley/nkeeley/edit/main/README.md#ds6050---deep-learning)

[DS5001 - Exploratory Text Analytics](https://github.com/nkeeley/nkeeley/edit/main/README.md#ds5001---exploratory-text-analytics)


### CS5010 - Programming and Systems for Data Analysis

[Repository](https://github.com/nkeeley/CS5010-Programming_and_Systems_for_Data_Analysis)

Language types: Python

This repository contains key assignments and projects for an introductory programming course in Python. Topics include object oriented programming, webscraping, data visualization, and pandas dataframe querying.

### CS5012 - Foundations of Computer Science

[Repository](https://github.com/nkeeley/CS5012-Foundations_of_Computer_Science)

Language types: Python

This repository contains assignments and projects related to the fundamentals of relational database design, data structures, and algorithmic programminig. Topics include entity-relationship diagrams, graph networks, search algorithms, regular expressions, hash tables, database transactions, propositional logic, Big-O complexity, and the solutions for Nearest-Neighbor/Closest-Pair problems.

![Sample ER Diagram](https://github.com/nkeeley/CS5012-Foundations_of_Computer_Science/blob/main/Screen%20Shot%202022-05-24%20at%2010.17.54%20PM.png)

### STAT6012 - Linear Models for Data Science

[Repository](https://github.com/nkeeley/STAT6021-Linear_Models_for_Data_Science)

Language types: R

This repository contains assignments and projects for a course on basic statistics for data science. Course topics included single linear regression, multiple linear regression, logistic regression, transformation, ANOVA F-tests, stepwise/backwards/forwards model creation, and linearity assumptions.

![Sample Visualization](https://github.com/nkeeley/STAT6021-Linear_Models_for_Data_Science/blob/main/STAT6021_DiamondVisual%20copy.jpg)

### DS6001 - Practice and Application of Data Science

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

### DVA - Data Visualization and Analytics

[Repository](https://github.com/nkeeley/DVA-Data_Visualization_and_Analytics)

Language types: SQL

This repository contains assignments involving data visualizations via Tableau, as well as big data querying/predictive model generation using GoogleBigQuery.

![BigQuery](https://github.com/nkeeley/DVA-Data_Visualization_and_Analytics/blob/main/GoogleBigQuery.jpg)

### DSB - Data Science in Business

[Repository](https://github.com/nkeeley/DSB---Data-Science-in-Business)

Language types: Python

This repository contains several assignments and projects related to predictive modeling (using machine learning tecniques), data munging, and data visualization. For the capstone project, my team and I submitted a model to an expired Kaggle competition: the Microsoft Malware Classification Challenge.

![image](https://github.com/nkeeley/DSB---Data-Science-in-Business/blob/main/TreeImage.jpg)

### Text Analytics Project: Exploring Company Earnings Calls Before & After COVID-19

[Repository](https://github.com/nkeeley/Exploring-Company-Earnings-Calls)

Language types: Python

For the capstone project of my Exploratory Text Analytics class, I chose to investigate how company earnings call language changed before/after the onset of the COVID-19 pandemic. I produced my own raw text dataset by scraping over 35K earnings calls publicly available on the Motley Fool's website, ultimately refining the corpus into a digital analytical edition and conducting text analytics.

![image](https://github.com/nkeeley/Exploring-Company-Earnings-Calls/blob/main/ClusteringTickers.jpg)

### DS6030 - Statistical Learning

[Repository](https://github.com/nkeeley/DS6030-Statistical-Learning/blob/main/README.md)

Language types: R

This repository contains exams and assignments primarily involving hyperparameter tuning of statistical models. Additional topics include KNN models, model-based clustering/Kernel Density Estimation, association analysis, and validation techniques (e.g. OOB, k-fold, etc.). Note: each .Rmd file has an associated HTML file with a similar name.

![image](https://github.com/nkeeley/DS6030-Statistical-Learning/blob/main/TreeTuning.jpg)

### Capstone Project: Measuring Shopper Marketing Effectiveness

[Repository](https://github.com/nkeeley/capstone-project-measuring-shopper-marketing-tactic-effectiveness/blob/main/README.md)

Language types: SQL, Python

For the capstone project of our Master in Data Science program, my project team was assigned to help a leading international consumer packaged goods (CPG) firm with assessing the effectiveness of their shopper marketing tactics using "big data" (~30M rows) that they provided. Based on pre-existing literature on retail sales forecasting, I decided to develop a random forest model using walk-forward validation. My model ultimately outperformed our baseline/other competing models, and was accepted by our client for further development. Due to the proprietary nature of the data involved, this project notebook is selectively available by request - please message me at https://www.linkedin.com/in/nicholas-g-keeley/. 

![image](https://github.com/nkeeley/capstone-project-measuring-shopper-marketing-tactic-effectiveness/blob/main/CapstoneScreenshot2.jpg)

### DS6014 - Bayesian Machine Learning

[Repository](https://github.com/nkeeley/DS6014---Bayesian-Machine-Learning)

Language types: Python

This repository contains assignments and projects relevant to Bayesian Machine Learning. Topics include practical applications of Bayes Theorem and conjugate analysis, Naive Bayes Classifiers and LDA/QDA Bayes Optimal Classifiers, Bayesian regression models, sampling methods (e.g. Gibbs Sampling, MCMC sampling, etc.), variational inference, Hidden Markov Models, pooled vs unpooled vs. hiearchical models, and an implementation of autoencoder variational Bayes to topic modeling. Note: many of these notebooks were produced on a remote operating system with pymc3 pre-installed. This package is required to run many of the sampling methods used, and is challenging to install on many computers.

![image](https://github.com/nkeeley/DS6014---Bayesian-Machine-Learning/blob/main/BayesSampleImage.jpg)

### DS6050 - Deep Learning

[Repository](https://github.com/nkeeley/DS6050---Deep-Learning)

Language types: Python

This repository contains the assignments and projects related to a Deep Learning course. Topics included the architectures of Convolutional Neural Networks (CNNs), construction of CNNs from scratch and via Tensorflow Keras, the creation of recurrent neural networks, the application of transfer learning, and the detection of GAN-generated satellite images. Note: To facilitate efficiency, all assignments contained varying degrees of templated material provided by the professor. Also, all assignment were run in GoogleCollabPro to reduce runtime duration/RAM maxout.

![image](https://github.com/nkeeley/DS6050---Deep-Learning/blob/main/FiltersImage.jpg)

### DS5001 - Exploratory Text Analytics

[Repository](https://github.com/nkeeley/DS5001---Exploratory-Text-Analytics)

Language types: Python

This repository contains assignments and projects associated with exploratory text analytics. Topics include manual text cleansing/OHCO chunking using regex, parts of speech annotation, term-frequency analysis, n-gram analysis, agglomerative clustering, principal components analysis, topic modeling, and semantic algebra through word embeddings. For sentiment analysis-related content covered in class, please see https://github.com/nkeeley/Exploring-Company-Earnings-Calls. Note: All assignments were based off of templates provided by the professor, and adapted to meet the needs of assigned problem solutions and different corpora.

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
