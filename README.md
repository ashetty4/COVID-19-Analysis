# COVID-19-Analysis
## About Covid-19:
## Introduction
Coronavirus disease 2019 is an infectious disease caused by severe acute respiratory syndrome coronavirus 2(SARS-CoV-2) that was found in late 2019, however it was not until March 11 that it was declared as a pandemic. Coronaviruses are groups of viruses that cause illness in animals and humans. The symptoms associated with COVID 19 are Shortness of breath or difficulty breathing, Fever, Repeated shaking with chills, Muscle pain, Headache, Sore throat and new loss of taste or smell. However, the most common ones are shortness of breath, fever and cough. As of 11th May there are more than 4.14 million cases across 187 countries and territories with a death count of more than 284,000.
For our project we have decided to perform our analysis on the factors influencing COVID-19, the areas most affected by it, the growth rate of the disease, the age bracket most vulnerable to the disease and we have also compared different diseases and external factors with the respective geographical locations to find correlations between the primitive factors. We have done so by collating datasets ranging from John Hopkins dataset to regional datasets released by officials. Other than these demographic data is also used from sources such as data.gov and cdc.gov
## Objectives:
This project aims to analyze how the spread of coronavirus is related to other parameters.
The questions we tried to answer with our analysis are stated below:</br>
❖ Which region is the most affected by the disease?</br>
❖ What are the Top-N countries affected by the disease?</br>
❖ What are the Top-N states in the USA affected by the disease?</br>
❖ Did the stay-at-home order in the respective states have any positive/ negative effect?</br>
❖ How does the stay-at-home order affect the growth of coronavirus cases across the states in the
 USA?</br>
❖ Out of the Top-N which race has been the most affected?</br>
❖ Out of the different age groups, which of them were the most vulnerable to the disease?</br>
❖ Does gender have any correlation to the disease?</br>
❖ Is there any pattern between Influenza and Covid-19? Any pattern?</br>
❖ What is the difference between the recovery rate and the rate tested positive for Covid-19?</br>
❖ Is there any association with the timestamp? Is it progressing over time?</br>
❖ Does the population density have any correlation with the number of confirmed cases?</br>
❖ Do the total tax collections of the states have any correlation with the number of confirmed cases?</br>
❖ How can the number of confirmed cases be classified by race?</br>
❖ Which states have seen the worst unemployment rates due to COVID-19?</br>
## About the Dataset:-
Our primary dataset is John Hopkins University CSSE COVID-19 Dataset. The link for the same can be found here –
https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data </br>
The repository can be found on GitHub and is updated on a daily basis. This repository consists of various
 datasets ranging from data of all countries to data specific to the United dates of America. </br>

The files used to fetch the confirmed cases, the death count and recovered cases on a global level i.e all countries are:
❖ Confirmed – time_series_covid19_confirmed_global.csv Preview: After pivoting columns to rows </br> 
❖ Deaths – time_series_covid19_deaths_global.csv Preview: After pivoting columns to rows </br>
❖ Recovered - time_series_covid19_recovered_global.csv Preview: After pivoting columns to rows </br>
❖ Analysis on country specific data i.e. about the United States of America can be found below Confirmed cases- time_series_covid19_confirmed_US.csv </br>
❖ Deaths - time_series_covid19_deaths_US.csv </br>
      
Additionally, the following datasets are downloaded to analyze our primary data set from different angles:</br>
• https://worldpopulationreview.com/states/</br>
• https://www.cdc.gov/nchs/nvss/vsrr/covid_weekly/index.htm</br>
• https://www.cdc.gov/nchs/nvss/vsrr/covid19/index.htm </br>
• https://data.census.gov/cedsci/table?g=0100000US.04000.001&tid=GOVSTIMESERIESGS00TC01&hidePreview=true&vintage=2018&layer=VT_2018_040_00_PY_D1&cid=S0102_C01_001E
