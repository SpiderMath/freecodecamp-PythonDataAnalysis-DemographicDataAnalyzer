# Demographic Data Analyzer

Hello everyone, this is the FreeCodeCamp project submitted by me for the [*Demography Data Analyser*](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/demographic-data-analyzer) for the certification of [Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/).  

Here are the instructions provided for the project:

<details>
<summary><strong>Instructions</strong></summary>
In this challenge you must analyze demographic data using Pandas. You are given a dataset of demographic data that was extracted from the 1994 Census database. Here is a sample of what the data looks like:  

```
|    |   age | workclass        |   fnlwgt | education   |   education-num | marital-status     | occupation        | relationship   | race   | sex    |   capital-gain |   capital-loss |   hours-per-week | native-country   | salary   |
|---:|------:|:-----------------|---------:|:------------|----------------:|:-------------------|:------------------|:---------------|:-------|:-------|---------------:|---------------:|-----------------:|:-----------------|:---------|
|  0 |    39 | State-gov        |    77516 | Bachelors   |              13 | Never-married      | Adm-clerical      | Not-in-family  | White  | Male   |           2174 |              0 |               40 | United-States    | <=50K    |
|  1 |    50 | Self-emp-not-inc |    83311 | Bachelors   |              13 | Married-civ-spouse | Exec-managerial   | Husband        | White  | Male   |              0 |              0 |               13 | United-States    | <=50K    |
|  2 |    38 | Private          |   215646 | HS-grad     |               9 | Divorced           | Handlers-cleaners | Not-in-family  | White  | Male   |              0 |              0 |               40 | United-States    | <=50K    |
|  3 |    53 | Private          |   234721 | 11th        |               7 | Married-civ-spouse | Handlers-cleaners | Husband        | Black  | Male   |              0 |              0 |               40 | United-States    | <=50K    |
|  4 |    28 | Private          |   338409 | Bachelors   |              13 | Married-civ-spouse | Prof-specialty    | Wife           | Black  | Female |              0 |              0 |               40 | Cuba             | <=50K    |
```

You must use Pandas to answer the following questions:  
<br>

1. How many people of each race are represented in this dataset? This should be a Pandas series with race names as the index labels. (race column)  
1. What is the average age of men?  
1. What is the percentage of people who have a Bachelor's degree?  
1. What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?  
1. What percentage of people without advanced education make more than 50K?  
1. What is the minimum number of hours a person works per week?  
1. What percentage of the people who work the minimum number of hours per week have a salary of more than 50K?  
1. What country has the highest percentage of people that earn >50K and what is that percentage?  
1. Identify the most popular occupation for those who earn >50K in India.  

Use the starter code in the file [`demographic_data_analyzer.py`](./demographic_data_analyzer.py). Update the code so all variables set to None are set to the appropriate calculation or code. Round all decimals to the nearest tenth.  
<br>

**Development**  
Write your code in [`demographic_data_analyzer.py`](./main.py). For development, you can use [`main.py`](./main.py) to test your code.  
<br>

**Testing**  
The unit tests for this project are in [`test_module.py`](./test_module.py). We imported the tests from test_module.py to main.py for your convenience.  
<br>

**Submitting**  
Copy your project's URL and submit it to freeCodeCamp.  
<br>

**Dataset Source**  
Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science.  
</details>
