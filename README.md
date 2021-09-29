# link-between-covid19-and-air-pollutions
The aim of this project is to replicate the result of the paper _Link between covid19 and air pollution in England_ written by Marco Travaglio, Yizhou Yu, Rebeka Popovic, Liza Selley, Nuno Santos Leal, Luis Miguel Martins. The original analysis was manly performed in R while my project is entirely proposed in Python. 
The paper studied the relationshipe between level of certain pollutants and mortality and infectivity of covid-19. The project is structured as follws:

First I analised the regional level data. After visualizing the data through maps and plots I fitted linear, Poisson and negative binomial regression model with NO, NO2, O3 as regressors and both cases and deaths as dependent variable. I also controlled for the population density. 

Then I used subregional data. 
