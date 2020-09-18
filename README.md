![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Project: Depression / Suicide rates

## Overview

The goal of this project was to collect data from suicides rates and interpreting different types of visualizations as well as statistical analysis. Throughout the project, our aim was to try to find a potential correlation between several variables and the suicide rates,which will be explained in the next points. 


## Initial Hypotheses

As a starting point, we put together several hypotheses that we would like to tackle. The main questions analysed were:

- "Does depression and suicide rate correlate with each other?"
- "Does GDP correlate with depression/suicide rates?"
- "Does Human Development Index (HDI) correlate with depression/suicide rates?"
- "Does unemployment have an effect on suicide rates/depression?"
- "Does urbanization affects suicide/depression rates?"
- "Does Life ladder as an effect on suicide/depression rates?"
- 'Does age have an influence on suicide/depression?"
- "Does gender gap between male/female have any correlation with depression?"
- "Does unemployment gap have any correlation with male suicide rates?"
- "Does education level has any correlation with depression/suicide rates?" 


## Datasets

In order to explain the suicide rates and analyse our hypotheses, we search different datasets on different sources. The main dataset had global data on suicides by country, age and gender from 1985 to 2016 (the data had some gaps as expected). We used different datasets for different different goals, all CSV files:

- rural_excel.xls
- alcohol-1980-1999.csv
- alcohol-2000-2009.csv
- suicide_rate.csv
- suicide-death-rates-by-sex.csv
- suicide-rates-by-age-detailed.csv
- suicide-rates-vs-prevalence-of-depression.csv
- depression-by-level-of-education-employment.csv
- prevalence-of-depression-by-age.csv
- prevalence-of-depression-males-vs-females.csv
- female_unemployment.csv
- male_unemployment.csv
- human-development-index.csv
- number-with-depression-by-country.csv
- unemployment_rate.csv
- world_happiness_index.csv



## Data Workflow

Our workflow organisation was set on Trello (link at the bottom of the file). The main steps were:

* Choose a topic of interest
* Research for possible data sources
* Create Trello board
* Create a new repo on GitHub
* Think on the file structure
* Merge and clean the data from the the different datasets
* Ploting results globally, having year and country common to the datasets
* Do some statistic analysis
* Create a model that can support some findings - in our case, model based on a case study
* Make a presentation on Tableau
* Organise repository and read me file

## Analysis

For our analysis, we tried to match different variables with suicide rates taking into consideration a time series from 1985 to 2016 on a global scale (by country) as starting point. We tried to explain suicidade through depression, gender, age group, GDP, HDI, unemployment, urbanization (rural areas percentage), life ladder effect and education. We add several variables to try to explain  the suicide numbers which made more difficult reaching a global model. We could see considerable trends with depression, gender, age group but overall we didn´t have enough support from data to correlate other variables on a global scale (although some trends were visible and would need deeper long-term analysis). Looking at our results, we spotted a clear trend on former Union of Soviet Socialist Republics (USSR) countries, which led us to a case study on USSR. After checking some legislation, besides the obvious effect of the country split, we found some potential connection to alcohol consumption, which we added to our initial hypotheses. Related to it, it is relevant to point out Gorbachev partial ban on alcohol in 1985, which lead to a economic crisis in the following years (less official drinkers, more home brewers, same social issues, less state revenue on alcohol taxes etc - link at the bottom og the page), that we also tried to correlate. Our model for USSR was a clear improvement on accurary to the general model and takes into consideration years, age , gender, and depression to explain suicide. All our in-deepth analysis can be found on the repository.


## Problems encountered

Due to our large amount of data and general topic set up, we found some problems throughout the project,especially:

* finding clean data
* large and complex datasets and topic
* merging data
* data containing a lot of missing values, that limits our possible regression models
* finding correlation for any of initial hypotheses 
* dataset with a lot categorical data, hard two make sense of all the variables
* making sense of the data and finding an acceptabel regression
* topic that can be influenced by various socio/political/economic etc factors, which would mean months of analysis


## Repository organisation

The repository is organised as:

- data folder: containing all the datasets on dataset bullet point
- data-wrangling folder: containing new merged datasets and jupyter notebooks with some analysis
- Analysis folder: jupyter notebooks with statistic analysis
- Ploting folder: plots from jupyter notebook
- Tableau Presentation folder: tableau file  




## Links

Repository:https://github.com/Brunadiasmiguel/depression

Trello: https://trello.com/b/n7YiMQcK/depressionproject

Alcohol explanation: https://www.vice.com/en_uk/article/vv53q9/the-soviet-posters-meant-to-keep-russians-from-drinking

Tableau Public: https://public.tableau.com/profile/joao4789#!/vizhome/Project_suicide_16004355393650/Story1?publish=yes



## Main datasources: 

<a href='https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016'>suicide-rates-overview-1985-to-2016</a>

<a href='https://ourworldindata.org/'>Our world data</a>

<a href='http://hdr.undp.org/en/data'>Human Development Data (1990-2018)</a>

Alcohol data: https://apps.who.int/gho/data/node.main.A1029SDG3?lang=en

Rural area data: https://data.worldbank.org/
