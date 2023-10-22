# La Más Draga Data Science Project

## Table of Contents
+ [Project Overview](#Project-overview)
+ [Technologies Used](#Technologies-Used)
+ [Project Problem](#Project-Problem)
+ [Project Walkthrough](#Project-Walkthrough)
+ [Project Insights](#Project-Insights)
+ [Screenshots](#Screenshots)
+ [Source](#Source)


## Project Overview
An exciting data science project focused on "La Más Draga," a Mexican version of RuPaul's Drag Race. This project involves web scraping, data extraction, preprocessing, and the creation of machine learning models to predict if contestants could win the competition.

## Technologies Used
+ Python - The programming language used for data analysis.
+ libraries installed
   + NumPy - For numerical operations and array manipulation.
   + Pandas - For data manipulation and analysis.
   + Seaborn - For creating informative and attractive visualizations.
   + Matplotlib.pyplot - For additional visualization capabilities.
   + Sklearn - For machine learning
   + BeautifulSoup - For data extraction.


## Usage
1. Clone this repository:
   ```python
   git clone https://github.com/your-username/la-mas-draga-ds.git 

## Project Problem
The problem addressed in this project is creation of a model to predict the success of contestants in "La Más Draga" based on their performance and characteristics.

## Project Walkthrough
1. Import the necessary libraries
2. Data Extraction: Web scraping was used to gather information and tables from two different websites.
3. Data Transformation: Data transformation steps included converting data types, cleaning, and merging tables to create both datasets.
4. Database Integration: The cleaned datasets were loaded into a MySQL database for efficient storage and retrieval.
5. Data Preprocessing: Preparing the data for machine learning.
6. Machine Learning Models: Three machine learning models were created to predict if contestants could win the competition based on the available information:
   - Logistic Regression Model
   - Random Forest Classification Model
   - Decision Tree Classification Model


## Project Insights
Model Evaluation: The models were evaluated using classification reports to determine the most suitable model for shows like "La Más Draga." According to the evaluation, the Decision Tree Classification model was found to be the most suitable for predicting contestant success.

## Screenshots
<div style="display: flex; flex-direction: row;">
  <img  style="margin-bottom: 10px;" src="https://github.com/NilArj/drag_show/blob/f8cb2353aba40be2d3ff2d79770da9acd264027e/images/Captura%20de%20pantalla%202023-10-14%20115158.png" alt="project index" width="600" height="280">
  <img  style="margin-bottom: 10px;" src="https://github.com/NilArj/drag_show/blob/f8cb2353aba40be2d3ff2d79770da9acd264027e/images/Captura%20de%20pantalla%202023-10-14%20115744.png" alt="project index" width="500" height="450">

</div>


## Source
- Dataset_contestant: [Data from wikipedia](https://es.wikipedia.org/wiki/La_M%C3%A1s_Draga_(M%C3%A9xico))
- Dataset_progress: [Data from drag race wiki](https://rupaulsdragrace.fandom.com/wiki/La_M%C3%A1s_Draga_(Season_3)#Scores_Overall)


