# STAT540 Final Project Repository

## Project Overview

This repository contains a completed statistical analysis project developed in R and RStudio for STAT540.

The purpose of the project was to analyze data, apply statistical methods, and generate findings using reproducible workflows and data visualization techniques.

# Data Description

This project uses data from the National Health and Nutrition Examination Survey (NHANES), a large-scale health survey conducted by the National Center for Health Statistics (NCHS) in the United States. The NHANES dataset contains health, demographic, and physical examination information collected from thousands of participants across the country. :contentReference[oaicite:0]{index=0}

The objective of this project was to study the diabetes status of individuals recorded in the NHANES dataset using supervised machine learning algorithms. The target variable for prediction was the `Diabetes` variable, which indicates whether a participant had been told by a doctor or health professional that they had diabetes. :contentReference[oaicite:1]{index=1}

Several health and demographic variables were explored as potential predictors, including:
- Age
- Gender
- Body Mass Index (BMI)
- Blood pressure measurements
- Cholesterol levels
- Income and education levels
- General health indicators

The dataset was analyzed and preprocessed in R using statistical and machine learning techniques. Missing values were reviewed, variables were cleaned and formatted appropriately, and relevant features were selected for model development.

A Decision Tree classifier was implemented as the baseline machine learning model and compared against at least two additional classification algorithms to evaluate predictive performance. The project focused on understanding how different machine learning methods can be applied to healthcare-related datasets and how health indicators may contribute to diabetes prediction.

## Motivation

The motivation for this project was to gain experience with:
- Data analysis in R
- Statistical modeling
- Data visualization
- Reproducible research practices
- Version control using Git and GitHub

## Project Structure

- `code/` contains scripts used during analysis
- `data/original/` contains raw datasets
- `data/derived/` contains processed datasets
- `report/` contains project reports and findings

## Tools Used

- R
- RStudio
- Git
- GitHub
