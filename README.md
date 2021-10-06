# Data Scientist Survey: Asian vs. European
This project will follow a standard industry practice of utilizing CRISP-DM with the data from Stack Overflow Developer Survey Results:

**Survey Database:**
You can find the official published results here:

https://insights.stackoverflow.com/survey/2017

This database - The Public 2017 Stack Overflow Developer Survey Results - is made available under the Open Database License (ODbL): http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/

## Technologies
Project is created with:
* Python version: 3.8
* Jupyter Notebooks

## Installation
You need to be able to work in a Jupyter Notebook on your computer. The following packages (libraries) need to be installed. You can install these packages via conda or pip.
* Numpy
* Pandas
* Matplotlib
* Seaborn
	
## Setup
This project requires file:
* survey_results_public.csv = for the survey results
* survey_results_schema.csv = the full text of each question
* Data Scientist Blog Post.ipynb = my coding analysis

# CRISP-DM Cross-industry standard process for data mining  
* **1. Business Understanding** : The objective is to understand the developers salaries for two areas and the factor that impact them based on the Stackoverflow developer 2017 survey that could be found in : Stack Overflow data from 2017

* **2. Data Understanding** : Will utilize Stack Overflow Developer Survey Results, primarly survey_results_public.csv. I have propsed 3 questions that will be asked below to better understand the data.

* **3. Prepare Data**: Only need to keep and condense necessry columns for a dataframe plus handle use of NaN values.

* **4. Data Modeling**: Will utlize tables and graphs.

* **5. Evaluate the Results**: Results will be noted in this notebook but also in the blog post.


## 1. Business Understanding
For this project we will try to find out the below observations:

* Salary comparison between Asian and European.
* Salary comparison with respect to education level.
* Finally find out salary growth with respect to job experience.

## 2. Data Understanding
First of all we we import all of necessary libraries.
We read the data as it will be a general view with necessary information.

## 3. Prepare Data 
Only need to keep and condense necessry columns for a dataframe plus handle use of NaN values.

## 4. Data Modeling
Will utlize tables and graphs.

## 5. Evaluate the Results
Results will be noted in this notebook but also in the blog [post](https://medium.com/@albokhitan/data-scientist-analysis-on-stack-overflow-survey-us-vs-europe-fc1d02cf70b9).

