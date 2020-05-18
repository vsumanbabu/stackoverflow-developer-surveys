# Stack Overflow Annual Developer Survey Insights

## Overview
Get Insights from Stack Overflow Annual Developer Survey Data

Process Used - Cross Industry Process for Data Mining (CRISP-DM)
1. Business Understanding
2. Data Understanding
3. Prepare Data
4. Data Modeling
5. Evaluate the Results
6. Deploy

Data Source - https://insights.stackoverflow.com/survey

## Setup
1. Install Miniconda - https://docs.conda.io/en/latest/miniconda.html
2. conda env remove -n stackoverflow-developer-survey-env
3. conda env create -f stackoverflow-developer-survey-env.yaml
4. conda info --envs
5. conda env list
6. conda activate stackoverflow-developer-survey-env
7. jupyter notebook
8. conda deactivate

## Business Questions (How Data could be used)
1.) What are the most desired Platforms next year (2020)?
2.) What are the most desired Databases next year (2020)?
3.) What are the most desired Programming Languages next year (2020)?
4.) What are the most desired Web Frameworks next year (2020)?
5.) What are the most used Dev environments currently (2019)?

## Run the Notebook
MostDesiredSoftwares.ipynb ( https://github.com/vsumanbabu/stackoverflow-developer-surveys/blob/master/main/MostDesiredSoftwares.ipynb )
