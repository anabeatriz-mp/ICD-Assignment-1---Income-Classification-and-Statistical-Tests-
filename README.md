# ICD - Assignment 1

## Adult Cencus Income Classification

## 1. General Objective
The goal of this assignment is to consolidate the fundamental concepts of Data Science by performing an exploratory data analysis and classification models to predict whether an individual's annual income is $>50$K or $\leq 50$K.

## 2. Dataset

You will use the Adult Census Income dataset from the UCI Machine Learning Repository:
[https://archive.ics.uci.edu/dataset/2/adult](https://archive.ics.uci.edu/dataset/2/adult).

The dataset contains 48,842 records and 14 socioeconomic attributes, such as age, educational level, weekly working hours, emploument type, and marital status.
The target variable is `income`, with two classes:
* `$\leq 50K$`
* `$> 50K$`

## 3. Exploratory Data Analysis (EDA)
Your EDA should include, at minimum:
* Descriptive statistics for numerical and categorical variables.
* Handling of missing values.
* Distribution analysis of the main features.
* Identification of outliers.
* Exploration of the target variable, including class imbalance.
* Relevant visualisations to support insights.

**Important**
You must interpret all visualisations and statistical outputs.
It is not enough to simply generate plots or descriptive statistics — you must analyse them, explain what they reveal about the dataset, and discuss how these insights might influence preprocessing decisions or model performance.

## 4. Data Preparation
* Encoding of categorical variables.
* Normalisation/standardisation (when appropriate).
* Train/test split.
* A brief justification of your preprocessing decisions.

## 5. Modelling: Test 3 Different Classifiers
You must choose three classification models to explore. For each classifier, you must provide:
* A short explanation of how the classifier work.
* Justification of chosen hyperparameters.
* Comparison of performance on the test set.

## 6. Evaluation Using Classification Metrics
You must evaluate all models using Accuracy and a Confusion Matrix.
In addition, you are required to explore other classification metrics. To do this, research relevant classification metrics and explain how they can be used to assess the performance of your classifiers.

Your analysis should include a discussion of:
* The differences between the metrics.
* The advantages and disadvantages of each model.
* The effect of lass imbalance.
* Which models generate more false positives or false negatives and why.

## Statistical Tests - Comparing proportions and A/B Testing

### Context
Using Adult Census income dataset, perform statistical tests to investigate differences between groups with respect to the variable `income`.

### Question 1 Gender and Income
Investigate whether the proportion of women earning more than 50K is equal to the proportion of men earning more than 50K.

You must:
1. Define the hypotheses.
2. Choose and appropriate statistic.
3. Implement a simulation supporting the test.
4. Report and interpret.

### Question 2 - A/B Test: Weekly Working Hours ($>40$ vs $\leq 40$)
Consider individuals working $>40$ hours per week as Group A and those working $\leq 40$ hours per week as Group B.
Investigate whether the proportion of individuals earning >50K differs between Group A and Group B.

You must:
1. Define the hypotheses.
2. Selecting a testing approach.
3. Implement the simulation.
4. Report and interpret.
