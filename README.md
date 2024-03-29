# Write a Data Science blog post
Udacity Data Scientist Nanodegree Project.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Description](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This code runs with Python version 3.* and requires some libraries, to install theses libraries you will need to execute: </br>
` pip install -r requirements.txt `

You will need to download Stackoverflow’s 2017 and 2018 Annual Developer Survey and put in specific folders. You can find the data to download [here](https://insights.stackoverflow.com/survey). </br>

To move the downloaded files to the specific folder, you can execute. </br>

1. Stackoverflow’s 2017 data </br>
` mv survey_results_public.csv Write-a-Data-Science-Blog-Post/data/2017/survey_results_public.csv `</br>

2. Stackoverflow’s 2018 data </br>
` mv survey_results_public.csv Write-a-Data-Science-Blog-Post/data/2018/survey_results_public.csv `</br>

## Project Motivation <a name="motivation"></a>

This is an Udacity Nanodegree project.I was interested in using Stackoverflow Developer Survey Data to better understand:</br>
1. What are the most used programming languages in Brazil? </br>
2. What are the most wanted programming languages in Brazil? </br>
3. How does programming languages used at work relates with programming languages people want to learn? </br>

## File Description <a name="files"></a>

**exploratory_analysis.ipynb**: Notebook containing the data analysis. </br>
**data/2017/survey_results_public.csv**: Stackoverflow's 2017 Annual Developer Survey data. </br>
**data/2018/survey_results_public.csv**: Stackoverflow's 2018 Annual Developer Survey data. </br>

## Results <a name="results"></a>
The main findings of the code can be found at the post available [here](http://pfahad.com/a-data-analysis-using-stackoverflows-2017-and-2018-annual-developer-survey/)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Stackoverflow for the data. You can find the Licensing for the data and other descriptive information at the Stackoverflow link available [here](https://insights.stackoverflow.com/survey).
