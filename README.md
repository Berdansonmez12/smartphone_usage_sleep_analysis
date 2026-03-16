# Smartphone Usage and Sleep Analysis

## Project Overview

This project analyzes the relationship between late-night smartphone usage and sleep patterns using personal screen time data collected from an Android device.

The goal of this project is to investigate whether smartphone usage during late evening hours delays sleep time and affects wake-up time and total sleep duration.

---

## Motivation

Smartphone usage has become a significant part of daily life, especially during late evening hours. Several studies suggest that late-night screen exposure can negatively affect sleep quality and sleep schedules.

This project aims to explore this relationship using real personal smartphone usage data and sleep tracking data.

---

## Research Questions

This project focuses on answering the following questions:

- Does smartphone usage after 22:00 delay sleep time?
- Does late-night screen time lead to later wake-up times?
- Does increased evening screen time reduce total sleep duration?
- Are there differences in smartphone usage patterns between weekdays and weekends?

---

## Dataset

The dataset is collected manually using Android Digital Wellbeing and sleep tracking data.

Features included in the dataset:

- date
- total_screen_time
- screen_after_22
- screen_after_23
- unlocks
- notifications
- sleep_time
- wake_time
- sleep_duration

Dataset file:
data/screen_time_dataset.csv

## Methods

The project will follow a typical data science pipeline:

1. Data Collection  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Hypothesis Testing  
5. Machine Learning Models  

---

## Tools and Technologies

Python will be used for data analysis.

Libraries planned to be used:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
