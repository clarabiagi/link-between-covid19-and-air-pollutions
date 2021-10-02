# Link between covid19 and air pollutions in England
The aim of this project is to replicate the result of the paper _Link between covid19 and air pollution in England_ written by Marco Travaglio, Yizhou Yu, Rebeka Popovic, Liza Selley, Nuno Santos Leal, Luis Miguel Martins. The original analysis was manly performed in R while my project is entirely proposed in Python. 
The paper studied the relationshipe between level of certain pollutants and mortality and infectivity of covid-19. The project is structured as follws:

First I analysed the regional level data. After visualizing the data through maps and plots I fitted linear, Poisson and negative binomial regression model with NO, NO2, O3 as regressors and both cases and deaths as dependent variable. I also controlled for the population density. The covid19 data include all covid cases and deaths up to April 8, 2020. All other information are referred to the 2018.

Then I used subregional data. Again I fitted negative binomial regression model both to cases and deaths. Here more pollutants were included as regressors (pm10, pm25, nox, no2, o3) and I controlled for population density and also for age and earnings.

Again at subregional level I expanded the analysis including pollutants data from 2014 to 2018. I fitted also in this case a negative binomial regression both for cases and deaths, controlling for the same variables as before.
