---
title: "Exercise 3 -- Work Plan"
author: Backé Julian, Russo Dominik, Salzer Tobias, Singh Ajayvir
geometry: "left=18mm,right=18mm,top=6mm,bottom=21mm"
output: pdf_document
---


<!-- compile with: pandoc -o plan.pdf plan.md -->

\vspace{-13mm}
### Questions
\vspace{-3mm}
1. How do university rankings change over time?
	
	The goal is to compare and visualize rank(s) over time. It will be interesting to find out the methodology and the criteria of the rank calculation (focus on research or on teaching).

2. Which characteristics of universities contribute most to good rankings, or to large changes in the ranking position?

	Analyse individual criteria in datasets and what characteristics contribute most to good ranking. Following attributes could be interesting for this question:

	\begin{minipage}[t]{0.45\textwidth}
	\begin{itemize}
		\item   Budget for conducting research
		\item	Tuition fee
		\item   Presence of faculties in a certain field
			(research focus of the university)
		\item   Age of university
		\item   Sector (public/private)
		\item   Research output (published papers per annum)
		
	\end{itemize}
	\end{minipage}
	\hspace{5mm}
	\begin{minipage}[t]{0.45\textwidth}
	\begin{itemize}

		\item   Eesearch impact (citations per paper)
		\item   Male to female ratio (students, staff,...)
		\item   Number of students (total or in certain fields)
		\item   Number of notable alumni to total number of\\
			students ratio
		\item   Students to resource ratio (labs, computers, ...)
		\item   Students to professors ratio
	
	\end{itemize}
	\end{minipage}



	For this, an extensive data-exploration and effective visualisations will be necessary.


3. How do these characteristics correlate with characteristics of cities or countries in which the university is located?

	Following location related attributes could be considered:
	\begin{minipage}[t]{0.45\textwidth}
	\begin{itemize}
		\item   GDP
		\item	HDI
		\item   Corruptions perception index per country
		\item   City size (number of inhabitants)
		\item   Average ranking grouped by continent, country or city over time
		
	\end{itemize}
	\end{minipage}
	\hspace{5mm}
	\begin{minipage}[t]{0.45\textwidth}
	\begin{itemize}


		\item   Public expenditure on education
		\item   Rain days per year
		\item   Absolute number of universities per continent, country or city
		\item   Relative (per capita) number of universities per continent, country or city
	
	\end{itemize}
	\end{minipage}


4. Are there predictors for increases or decreases in the rankings?

	The above attributes should be analysed and prediction models for the rank trend of a university should be built.

\vspace{-2mm}
### Datasets
\vspace{-3mm}
\begin{minipage}[t]{0.45\textwidth}
\begin{itemize}

	\item   Corruption in public sector: (\hyperlink{https://data.worldbank.org/indicator/IQ.CPA.TRAN.XQ}{click here})
	\item	GDP Growth: (\hyperlink{https://data.worldbank.org/indicator/NY.GDP.MKTP.KD.ZG}{click here})
	\item   HDI: (\hyperlink{https://databank.worldbank.org/reports.aspx?source=1147\&series=UNDP.HDI.XD}{click here})
	\item   Top 2000 universities 2019/2020: (\hyperlink{https://cwur.org/2019-2020.php}{click here})
	
\end{itemize}
\end{minipage}
\hspace{5mm}
\begin{minipage}[t]{0.45\textwidth}
\begin{itemize}

	\item   University rankings: (\hyperlink{https://www.kaggle.com/mylesoneill/world-university-rankings}{click here})
	\item   Weather data: (\hyperlink{https://earthdata.nasa.gov/}{click here})
	\item   World population metrics: (\hyperlink{https://sedac.ciesin.columbia.edu/data/collection/gpw-v3>}{click here})

\end{itemize}
\end{minipage}

\vspace{-2mm}
### Plan
\vspace{-3mm}
Step 1: Get the data. Some further data source research has to be done. The data will be loaded into a Jupyter Notebook (in Pandas Dataframes) and cleaned up if necessary. Each group member will have his own information to search for and his own datasets to clean and load in.

Step 2: Explore the data. As already noted, the data exploration represents an essential part of this work. This includes in particular finding out about (cor)relations between variables and the ranking by calculating correlation coefficients as well as plotting the data in an appropriate manner. Each group member will explore his datasets, which will be linked to the dataset containing the ranking.

Step 3: Model the data. Once possible predictors for increases or decreases of rankings were identified, we would like to find out how the predictors interact with the rankings. For this, we aim to to build up simple machine learning models in the beginning. In a next step, these could be improved by more complex approaches identified during the work progress. This work will be split up when the outcomes of the data exploration are manifest.

