# My Data Science project
From the SkillFactory Data Science course

## Projects

* [Project 0 - "Game: guess the number"](https://github.com/mLiverinova/sf_data_science/blob/main/Project%200)
* [Project 1 - "Datas Visualization"](https://github.com/mLiverinova/sf_data_science/blob/main/Project%201.ipynb)
* [Project 2 - "HH Project"]()

## Сontents

[__Project 0__](https://github.com/mLiverinova/sf_data_science/blob/main/Project%200)
-    [1 Projects description](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#project_description)
-    [2 What case is solving](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#what-case-is-solving)
-    [3 Data information](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#data-information)
-    [4 Stages of the project](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#stages-of-the-project)
-    [5 Result](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#result)
-    [6 Conclusions](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#conclusions)

[__Project 1__](https://github.com/mLiverinova/sf_data_science/blob/main/Project%201.ipynb)
-    [1 Projects description](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#project_description-1)
-    [2 What case is solving](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#what-case-is-solving-1)
-    [3 Data information](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#data-information-1)
-    [4 Stages of the project](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#stages-of-the-project-1)
-    [5 Result](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#result-1)
-    [6 Conclusions](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#conclusions-1)

[__Project 2__]()
-    [1 Projects description]()
-    [2 What case is solving]()
-    [3 Data information]()
-    [4 Stages of the project]()
-    [5 Result]()

### Project_0

#### Project_description
The program guesses an integer from 1 to 100 in less than a 20 attempts on average out of 1000 times. The guessed number is guessed by the computer.

:yellow_circle:[To contents](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#сontents)

#### What case is solving
Need to write a program that guesses a number in less than 20 attempts out of 1000 repetitions on average

#### Data information 
...

#### Stages of the project
1. Writing a function that determines the number guessed by the computer. The method of dividing the interval of numbers in half is used, while taking into account more or less than the hidden number of the middle value of the interval.
2. Writing a function that runs the number guessing function a specified number of times and determines the average number of guesses.

#### Result
Functions that satisfy the conditions of the case are obtained.

#### Conclusions
The problem uses the method of dividing the interval in half. This method allows you to solve the problem with an average number of guesses 5 (out of 1000 repetitions)

:yellow_circle:[To contents](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#сontents)

### Project_1

#### Project_description
This program is designed to analyze bank data and identify the main causes of customer churn.

:yellow_circle:[To contents](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#сontents)

#### What case is solving
It is necessary with the help of graphs to analyze the influence of various factors on the outflow of customers. Libraries used: matplotlib, seaborn, plotly.

#### Data information 
- The source table contains the following data.
- RowNumber - table row number (this is redundant information, so you can get rid of it right away)
- CustomerId - customer identifier
- Surname - customer's last name
- CreditScore - the client's credit rating (the higher it is, the more the client took loans and returned them)
- Geography — client's country (international bank)
- Gender - gender of the client
- Age - the age of the client
- RowNumber - table row number (this is redundant information, so you can get rid of it right away)
- CustomerId - customer identifier
- Surname - customer's last name
- CreditScore - the client's credit rating (the higher it is, the more the client took loans and returned them)
- Geography — client's country (international bank)
- Gender - gender of the client
- Age - the age of the client
- Tenure - how many years the client has been using the services of the bank
- Balance - balance on the client's bank accounts
- NumOfProducts - the number of bank services purchased by the client
- HasCrCard - does the client have a credit card (1 - yes, 0 - no)
- IsActiveMember - whether the client has the status of an active client of the bank (1 - yes, 0 - no)
- EstimatedSalary - estimated salary of the client
- Exited — loyalty status (1 — departed client, 0 — loyal client)

#### Stages of the project
1. Choosing the type of chart, writing code to build it.
2. Analysis of the results

#### Result
The influence of age, estimated salary, gender on the outflow of customers was assessed

#### Conclusions
...

:yellow_circle:[To contents](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#сontents)

### Project_2

#### Project_description
This project contains the preparation, processing and analysis of the HeadHunter database

:yellow_circle:[To contents](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#сontents)

#### What case is solving
It is necessary to explore the data structure, process the data and transform it into a form accessible for analysis. You also need to analyze applicants on various grounds (age, work experience, city, and so on)

#### Data information 
The source database contains the following columns: "Пол, возраст", "ЗП", "Ищет работу на должность:", "Город, переезд, командировки", "Занятость", "График", "Опыт работы", "Последнее/нынешнее место работы", "Последняя/нынешняя должность", "Образование и ВУЗ", "Обновление резюме", "Авто".

#### Stages of the project
1. Data transformation: extracting key information about education, separating the "Пол, возраст" column into "Пол" and "Возваст", bringing work experience to a single unit of measure (month), determining readiness for business trips and relocations in a boolean format, categorizing the city of residence, creating columns , signaling the applicant's readiness to work on various schedules, the conversion of the requested salary to rubles.
2. Data dependency analysis.
3. Emission cleaning, pass processing.

#### Result
The result is a processed table suitable for data analysis, as well as dependency graphs and their analysis.


:yellow_circle:[To contents](https://github.com/mLiverinova/sf_data_science/blob/main/README.md#сontents)


