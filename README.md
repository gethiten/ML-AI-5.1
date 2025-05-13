# ML-AI-5.1
This repository contains ML-AI Practical assignment 5.1

# Coupon Acceptance Prediction

## Project Overview

This project analyzes a dataset of driver coupon acceptance behavior to understand the factors influencing whether a driver would accept a coupon offered to them while driving. The dataset includes various driver demographics, contextual information like time of day, weather, and passenger, and coupon details like type and expiration.

The goal is to identify patterns and characteristics associated with higher coupon acceptance rates for different coupon types, focusing specifically on **bar coupons** and **coffee house coupons**.

## Data Source

The data used in this project is from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. It contains information about driving scenarios and coupon acceptance decisions made by drivers.

## Analysis and Findings

The analysis involves exploring the data through visualizations, statistical summaries, and correlation analysis. Key findings include:

### Bar Coupons

*   **Frequent bar-goers** are more likely to accept bar coupons.
*   Drivers **over 25 with non-kid passengers** and specific occupations exhibit higher acceptance rates.
*   Drivers **under 30 who frequent bars** show a higher likelihood of accepting bar coupons.
*   A moderate correlation is observed between drivers visiting **cheap restaurants** frequently and income levels with acceptance of bar coupons.

### Coffee House Coupons (Further Exploration)

The project also explores the characteristics of passengers who accept coffee house coupons, considering factors like:

*   Frequency of coffee house visits
*   Time of day
*   Passenger type
*   Direction of travel

## Key Insights

The analysis reveals potential profiles of drivers who are more likely to accept specific types of coupons. This information can be used to target coupon promotions more effectively and improve the overall acceptance rates.

## Repository Contents

*   `data/`: Contains the dataset used in the analysis (coupons.csv).
*   `notebook.ipynb`: Jupyter Notebook containing the code for data exploration, analysis, and visualization.
*   `images/`: Folder containing generated visualizations.
*   `README.md`: This file, providing an overview of the project.
