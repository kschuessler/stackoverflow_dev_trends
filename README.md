## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

To run the notebook and scripts, Jupyter notebook, Python 3.7 and the following libraries are neccessary:

* numpy
* pandas
* matplotlib

To run the application, it is necessary to download the Stackoverflow Developer Survey data for 2016, 2017, 2018, 2019 and 2020.
The datasets are available via the [stackoverflow website](https://insights.stackoverflow.com/survey).

To run the functions without issues, you need to create a folder named 'developer_survey' in the same directory as this repo and add a subfolder named 'developer_survey_$year' for each year with the respective files inside or adjust the paths in the notebook.

## Project Motivation<a name="motivation"></a>

For this project, I was interested in using Stack Overflow data from 2016 to 2020 to better understand the prevalence of different programming languages among Data Scientists.
More specifically, I answer the following questions for the subset of respondents who are Data Scientists:

1. Which programming languages are currently being used?
2. How has this changed over the past years?
3. Which programming languages are the respondents aspiring to use in the future?

## File Descriptions <a name="files"></a>

The main analysis is contained in the [Stackoverflow_Survey_Technology_Radar_2020](Stackoverflow_Survey_Technology_Radar_2020.ipynb) Jupyter notebook. The notebook includes all functions and code used to answer the project questions as well as the rationale behind the analyses in Markdown cells.

## Results<a name="results"></a>

The main findings of the code can be found at the Medium post available [here](https://medium.com/@schuessler.katharina/).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit must be given to Stack Overflow for the data. 
