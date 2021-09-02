# Repo for 33n's open-ended question

*Author: Yewshen Lim*
*Created: 02/09/2021*

This repository contains my attempt at the open-ended question in the 33n's technical assessment.
The question asked for a new column to be created in the events dataframe to show the most recent diagnosis.

## Table of Contents
1. diagnoses.csv
2. events.csv
3. script.ipynb

script.ipynb is a jupyter notebook does the following:
1. reads the two csv files
2. creates a dictionary of the most recent diagnosis for each EventID
3. maps the most recent diagnosis for each EventID onto the events dataframe