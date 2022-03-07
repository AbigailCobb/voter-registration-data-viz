## Table of Contents
* [Introduction](#introduction)
* [Data](#data)
* [Technologies](#technologies)

## Introduction
Welcome! The purpose of this project is to use Python to analyze and visualize new voter registration in early 2020 versus early 2016 in 11 states and Washington, D.C. The analysis and visualizations seek to answer the following questions: 
*  How many new voters registered in each state by year?
*  What state had the most new voters register in each year?
*  How did the number of new voters compare to the total population of the state?
*  How many new voters registered in each state by year as a percentage of the total population of that state?
*  What state had the most new voters register in each year compared to their total population?
*  What month had the highest number of new voters register in each state? Did this vary by year?

## Data
The data shows how many people registered to vote in early 2020 versus early 2016 in 11 states and Washington, D.C. Data is available from January through April for all 12 of the jurisdictions, and data is available through May for four states and Washington D.C. This data is from the Center for Innovation and Research and was used in [this report](https://electioninnovation.org/wp-content/uploads/2020/06/New_Voter_Registrations.pdf). In addition, the data in [Florida](https://dos.myflorida.com/elections/data-statistics/voter-registration-statistics/voter-registration-reportsxlsx/), [Maryland](https://elections.maryland.gov/voter_registration/stats.html), [North Carolina](https://dl.ncsbe.gov/?prefix=data/voterstats/), [Virginia](https://www.elections.virginia.gov/resultsreports/registration-statistics/) and [Washington, D.C.](https://www.dcboe.org/Data-Resources-Forms/Request-Data) is publicly available.

Population data was sourced from the United States Census Bureau and is publicly available. 2016 population data is from [State Population Totals: 2010-2019](https://www.census.gov/data/datasets/time-series/demo/popest/2010s-state-total.html#par_textimage_1873399417), and 2020 data is from [State Population Totals and Components of Change: 2020-2021](https://www.census.gov/data/tables/time-series/demo/popest/2020s-state-total.html#par_textimage).

## Technologies
This project is created with Python 3 within a Jupyter Notebook, using the following packages:
*  plotly
*  matplotlib
