# Project Proposal

## Project Title
Analyzing the Impact of Late-Night Smartphone Usage on Sleep Patterns

## Motivation

Smartphones are a big part of daily life, especially during the late evening hours. Most people, including myself, tend to use their phones before going to sleep. This habit may affect when we fall asleep and how well we rest.

The main motivation of this project is to better understand how late-night smartphone usage impacts sleep behavior using real personal data. Since the data comes from my own daily usage, the project also reflects realistic behavioral patterns.

---

## Data Source

The dataset will be collected manually from:

- Android Digital Wellbeing (for screen time, unlocks, and notifications)
- Personal sleep tracking (sleep time and wake-up time)

The data will be recorded daily and updated regularly throughout the project.

---

## Dataset Description

Each row in the dataset represents one day. The dataset includes the following variables:

- date  
- total_screen_time (minutes)  
- screen_after_22 (minutes)  
- screen_after_23 (minutes)  
- unlocks (count)  
- notifications (count)  
- sleep_time (HH:MM)  
- wake_time (HH:MM)  
- sleep_duration (hours)  

The dataset will grow over time as more observations are collected.

---

## Research Questions

This project aims to explore the following questions:

- Does using a smartphone after 22:00 delay sleep time?
- Does late-night screen usage lead to waking up later?
- Does increased evening screen time reduce total sleep duration?
- Is usage after 23:00 more strongly associated with negative effects on sleep?

---

## Methodology

The project will follow a standard data science workflow:

1. Collecting and organizing the data  
2. Performing exploratory data analysis (EDA)  
3. Analyzing correlations between variables  
4. Conducting basic hypothesis testing  
5. Applying simple machine learning models to predict sleep duration  

---

## Expected Outcome

It is expected that higher smartphone usage, especially after 23:00, will be associated with later sleep times and shorter sleep duration. The project aims to quantify this relationship and identify patterns that can help better understand the impact of late-night phone usage.
