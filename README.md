# 🕸️ Cyber Shujaa - Exploratory Data Analysis 🚀

This is my updated solution to the week 3 assignment in the Cyber Shujaa program 
for the **Data and AI Specialist** track.

## 🧭 Table of contents

- [🌟 Overview](#🌟-overview)
  - [The assignment 🎯](#the-assignment-🎯)
  - [Links 🔗](#links-🔗)
- [🛠️ My process](#🛠️-my-process)
  - [Built with 🧱](#built-with-🧱)
  - [What I learned 🧠](#what-i-learned-🧠)
  - [Continued development 🌱](#continued-development-🌱)
  - [Useful resources 📚](#useful-resources-📚)
- [👩🏽‍💻 Author](#👩🏽‍💻-author)

## 🌟 Overview

### The assignment 🎯

The purpose of this assignment was to develop hands-on experience on Exploratory 
Data Analysis using a Kaggle dataset and publishing our work on [Kaggle]().

We were to practice the Exploratory Data Analysis steps:

1. Initial Data Exploration
2. Handling Missing Values and Outliers
3. Univariate Analysis
4. Bivariate Analysis
5. Multivariate Analysis
6. Target Variable Analysis

We were to personalize our Exploratory Data Analysis of the dataset, ensuring that we:

1. **Profile and analyze the list of features:** via data types, missing values, 
duplicates, errors, and plots we could explore per feature. Here are some essential 
`Pandas` functions used for initial exploration:

    - `df.head()`: Displays the first few rows of the dataset to give you a quick 
    preview.
    - `df.shape`: Returns the number of rows and columns in the dataset.
    - `df.info()`: Provides details about the columns, their data types, and the 
    number of non-null (non-missing) values.
    - `df.describe()`: Provides summary statistics (mean, median, min, max, etc.) 
    for numerical columns.
    - `df.columns`: Lists the names of all columns in the dataset.
    - `df.nunique()`: Returns the number of unique values in each column.
    - `df.duplicated()`: Checks for duplicate rows.

2. **Univariate Analysis:** Examine each feature at a time to understand its 
distribution and seek to answer questions like:

    - What is the age distribution of passengers?
    - How many passengers embarked from each location?
    - Are ticket prices evenly distributed, or are they skewed?

3. **Bivariate Analysis:** Examine pairs of features of interest. Justify which 
features you would like to pair in the analysis and seek to answer questions like:

    - Does the Fare change depending on the Pclass?
    - Are younger passengers more likely to survive on the Titanic?
    - Does the Embarked location affect survival rate?

4. **Multivariate analysis:** Explore more complex relationships between three or 
more variables simultaneously. Detect interactions, combined effects, and hidden 
patterns that may not be visible in bivariate analysis. This can help answer complex 
questions, such as:

    - How do Pclass, Age, and Fare jointly affect survival?
    - Are survival rates different for Embarked locations when considering Pclass?

5. **Outlier detection and handling:** There are different ways to handle outliers, 
which include removing, capping, imputing, or leaving them as is. Argue and justify 
your selected method of handling outliers for each feature, e.g.

    - Removing outliers in Fare may help for predictive models, but could hide 
    important insights for understanding passenger wealth.

6. **Target Variable Exploration:** Analyze the Target/Dependent Variable Survived 
and explore:

    - The distribution of the target variable (Survived) using countplots and bar 
    plots.
    - How balanced or imbalanced the dataset is.
    - What factors (like age, gender, class, or embarkation point) may influence 
    survival?
    - Use combined plots to detect interaction effects.

### Links 🔗

- [Kaggle dataset]()

## 🛠️ My process

### Built with 🧱

### What I learned 🧠

### Continued development 🌱

### Useful resources 📚

## 👩🏽‍💻 Author

- LinkedIn - [Grace Sampao](https://www.linkedin.com/in/grace-sampao)
- GitHub - [@nadupoy](https://github.com/nadupoy)
- X - [@grace_sampao](https://x.com/grace_sampao)
- [Blog](https://nadupoy.github.io/)