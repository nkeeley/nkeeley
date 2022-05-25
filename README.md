## Nicholas Keeley's Portfolio


### Description

This portfolio provides an overview of data science-related work I've done since 2020, when I began a Masters in Data Science at the University of Virginia. Last updated: 24 MAY 2022.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nkeeley)](https://github.com/nkeeley/github-readme-stats)

[![Nick's github stats](https://github-readme-stats.vercel.app/api?username=nkeeley&count_private=true&show_icons=true&theme=radical&hide_rank=false)](https://github.com/nkeeley/github-readme-stats)


### Table of Contents

[CS5010 - Programming and Systems for Data Analysis](https://github.com/nkeeley/nkeeley/edit/main/README.md#cs5010---programming-and-systems-for-data-analysis)

[CS5012 - Foundations of Computer Science](https://github.com/nkeeley/nkeeley/edit/main/README.md#cs5012---foundations-of-computer-science)

[STAT6012 - Linear Models for Data Science](https://github.com/nkeeley/nkeeley/edit/main/README.md#stat6012---linear-models-for-data-science)

[DS6001 - Practice and Application of Data Science](https://github.com/nkeeley/nkeeley/edit/main/README.md#ds6001---practice-and-application-of-data-science)


### CS5010 - Programming and Systems for Data Analysis

[Repository](https://github.com/nkeeley/CS5010-Programming_and_Systems_for_Data_Analysis)

This repository contains key assignments and projects for an introductory programming course in Python. Topics include object oriented programming, webscraping, data visualization, and pandas dataframe querying.

### CS5012 - Foundations of Computer Science

[Repository](https://github.com/nkeeley/CS5012-Foundations_of_Computer_Science)

This repository contains entity-relationship diagrams, alongwith a series of notebooks on the following topics: graph networks, search algorithms, regular expressions, hash tables, database transactions, propositional logic, Big-O complexity, and the solutions for Nearest-Neighbor/Closest-Pair problems.

![Sample ER Diagram](https://github.com/nkeeley/CS5012-Foundations_of_Computer_Science/blob/main/Screen%20Shot%202022-05-24%20at%2010.17.54%20PM.png)

### STAT6012 - Linear Models for Data Science

[Repository](https://github.com/nkeeley/STAT6021-Linear_Models_for_Data_Science)

This repository contains assignments and projects for a course on basic statistics for data science. Course topics included single linear regression, multiple linear regression, logistic regression, transformation, ANOVA F-tests, stepwise/backwards/forwards model creation, and linearity assumptions.

![Sample Visualization](https://github.com/nkeeley/STAT6021-Linear_Models_for_Data_Science/blob/main/STAT6021_DiamondVisual%20copy.jpg)

### DS6001 - Practice and Application of Data Science

[Repository](https://github.com/nkeeley/DS6001-Practice_and_Application_of_Data_Science)

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
