% DOPP Exercise 3 Work Plan
% Backé Julian, Russo Dominik, Salzer Tobias, Singh Ajayvir

<!-- compile with: pandoc -o plan.pdf plan.md -->


## 1. How do university rankings change over time?

*    Compare and visualize rank(s) over time


## 2. Which characteristics of universities contribute most to good rankings, or to large changes in the ranking position?

Analyse individual criteria in dataset and what characteristics contribute most to good ranking:

*   Budget for conducting research
*   Correlate age of university with ranking
*   Eesearch impact (citations per paper)
*   Male to female ratio
*   Number of notable alumni relative to total number of students
*   Research output (published papers per annum)
*   Sector (public/private)
*   Student to resource ratio (labs, computers, ...)
*   Students to professors ratio
*   Tuition fee


## 3. How do these characteristics correlate with characteristics of cities or countries in which the university is located?
*   GDP
*   HDI
*   average ranking grouped by continent/country/city over time
*   corruptions perception index per country
*   public expenditure on education
*   rain days per year
*   universities per continent/country/city (absolute)
*   universities per continent/country/city (relative per capita)


## 4. Are there predictors for increases or decreases in the rankings?

*   analyse criteria mentioned above


## Plan

Step 1: get the data

*   Budget for academic education and research of location (per capita)
*   Number of students per study field
*   Ranking data of universities
*   Salaries of professors
*   Size of city where university lies
*   Tuition fees
*   Which faculties does a university have


Step 2: explore the data

*   find out about (cor)relations between a variable and the ranking by calculating correlation coefficients, and plotting the data in an appropriate manner


Step 3: model the data

*   once possible predictors for increases or decreases of rankings were identified, we should check how the predictors interact with the rankings (start to build up simple machine learning models)


## Datasets:

*   Corruption in public sector: data.worldbank.org/indicator/IQ.CPA.TRAN.XQ
*   GDP Growth: data.worldbank.org/indicator/NY.GDP.MKTP.KD.ZG
*   HDI: databank.worldbank.org/reports.aspx?source=1147&series=UNDP.HDI.XD
*   Top 2000 universities 2019/2020 cwur.org/2019-2020.php
*   University rankings: www.kaggle.com/mylesoneill/world-university-rankings
*   Weather data: earthdata.nasa.gov/
*   World population metrics: sedac.ciesin.columbia.edu/data/collection/gpw-v3
