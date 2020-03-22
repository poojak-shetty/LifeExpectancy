# Capstone-1
## Life expectancy(WHO)
Life expectancy is a statistical measure of the average time an organism is expected to live, based on the year of its birth, its current age and other demographic factors including gender.This project is based on ML to predict which features affect the life expectancy of a country.
##### The dataset is taken from Kaggle
LINK TO THE DATASET IS 
[LIFE EXPECTANCY(WHO)](https://www.kaggle.com/kumarajarshi/life-expectancy-who)

It has the following features
* Country
* Year
* Status-Developed or Developing status
* Life expectancy-Life Expectancy in age
* Adult Mortality-Adult Mortality Rates of both sexes (probability of dying between 15 and 60 years per 1000 population)
* infant deaths-Number of Infant Deaths per 1000 population
* Alcohol-Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol)
* percentage expenditure-Expenditure on health as a percentage of Gross Domestic Product per capita(%)
* Hepatitis B-Hepatitis B (HepB) immunization coverage among 1-year-olds (%)
* Measles-Measles - number of reported cases per 1000 population
* BMI-Average Body Mass Index of entire population
* under-five deaths-Number of under-five deaths per 1000 population
* Polio-Polio (Pol3) immunization coverage among 1-year-olds (%)
* Total expenditure-General government expenditure on health as a percentage of total government expenditure (%)
* Diphtheria-Diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%)
* HIV/AIDS-Deaths per 1 000 live births HIV/AIDS (0-4 years)
* GDP-Gross Domestic Product per capita (in USD)
* Population-Population of the country
* thinness 1-19 years-Prevalence of thinness among children and adolescents for Age 10 to 19 (% )
* thinness 5-9 years-Prevalence of thinness among children for Age 5 to 9(%)
* Income composition of resources-Human Development Index in terms of income composition of resources (index ranging from 0 to 1)
* Schooling-Number of years of Schooling(years).

We are just taking the key features into consideration.Now lets get to my project.
It has 4 parts,namely
* The description
  * Which gives one proper explanation about what the project is about.What is the aim of this project and all briefly.
    * The link to this page is [BRIEF ABOUT THE PROJECT](https://colab.research.google.com/drive/1JvB8dkzodRVzE1HHm8r9CTv2OZc6zO98)
* Data cleaning
  * This includes importing necessary libraries,loading the dataset as in a csv file over here.
  * Checking if it has any null values,strings and unnecessary columns.Basically called as data preprocessing.
    * The link to this page is [DATA CLEANING AND PROCESSING](https://colab.research.google.com/drive/1HzixfGVbCFoTKbV2aXRbtJGcpmcObx32)
* Data visualization 
  * Here we have visualized the processed data using different plotting techniques.
  * we have also found out the correlation and done our first model ie Linear regression
   * The link to this page is [DATA VISUALIZATION AND LINEAR REGRESSION](https://colab.research.google.com/drive/1wHmO2ilU9qFYV_oj6l0uCREcNMXl3mB1)
* Multivariate polynomial regression
  * Here we have used multivariate polynomial regression with respect to 2 and 3 features and seen the outcome.
   * The link to this page is [MULTIVARIATE POLYNOMIAL REGRESSION](https://colab.research.google.com/drive/1fTHLJbJ08LigXfI-jmeZvBe3uLCxZjmB)
   * A proper conclusion is also given in this page.
   
After all this,I will just highlight the output over here.
MODEL TYPE                        | ACCURACY
--------------------------------- | -------------
LINEAR REGRESSION                 | 91%
MULTIVARIATE POLYNOMIAL REGRESSION| 92%(3 FEATURES),91%(2 FEATURES)
### CONCLUSION
Hence,I would like to conclude that
* Life expectancy is affected by many features.There cannot be only 1 or 2 key features to highlight about.So,we have to experiment and observe various kind of aspects.
* As we have got close accuracy values in both the models,we can say that both linear and multivariate polynomial regression are good.But,multivariate polynomial regression with 3 features is comparitively better as we got 8% error value.
                      
