
# Coupon Acceptance Survey

## Project Overview

This project analyzes a dataset of driver coupon acceptance behavior to understand the factors influencing whether a driver would accept a coupon offered to them while driving. The dataset includes various driver demographics, contextual information like time of day, weather, and passenger, and coupon details like type and expiration.

The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not focusing specifically on **bar coupons** and **coffee house coupons**.

## Data Source

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).

## Analysis and Findings

The analysis involves exploring the data through visualizations, statistical summaries, and correlation analysis. Key findings include:

### Bar Coupons

*   **Frequent bar-goers** are more likely to accept bar coupons.
*   Drivers **over 25 with non-kid passengers** and specific occupations exhibit higher acceptance rates.
*   Drivers **under 30 who frequent bars** show a higher likelihood of accepting bar coupons.
*   A moderate correlation is observed between drivers visiting **cheap restaurants** frequently and income levels with acceptance of bar coupons.

### Carry out & Take away Coupons 

The project also explores the characteristics of passengers who accept Carry out & Take away coupons, considering factors like:

*   Frequency of accepting Carry out & Take away coupons
*   Weather and Temperature
*   Education
*   Passenger type
*   Direction of travel

  
  Based on the bar plots generated for various attributes, here's a hypothesis about the characteristics of drivers more likely to accept "Carry out & Take away" coupons:

*  Young or unemployed/student
*  Traveling with a partner or friends
*  Heading home or having no urgent destination
*  Going out in sunny weather or at a comfortable temperature
*  Having more time to travel to their destination
*  A few occupation categories like Unemployed, Healthcare Support, Building & Grounds show slightly higher acceptance rates. However, the occupation category generally doesn't show a consistent trend with acceptance.
*  Educational attainment seems to have little or no influence on acceptance rates.

## Key Insights

The analysis reveals potential profiles of drivers who are more likely to accept specific types of coupons. This information can be used to target coupon promotions more effectively and improve the overall acceptance rates.

## Repository Contents

*   `data/`: Contains the dataset used in the analysis [(coupons.csv)](https://github.com/gethiten/ML-AI-5.1/blob/main/data/coupons.csv).
*   `coupons.ipynb`: Jupyter Notebook containing the code for data exploration, analysis, and visualization.
                     [Link: coupons.ipynb](https://github.com/gethiten/ML-AI-5.1/blob/main/coupons.ipynb)
*   `images/`: Folder containing generated visualizations. [Images Link](https://github.com/gethiten/ML-AI-5.1/tree/main/images)
*   `README.md`: This file, providing an overview of the project. [README.md Link]

## Tech Stacks

*   `Python`: pandas, NumPy, scikit-learn, OS
*   `Data Visualization:`: Matplotlib, Seaborn.
*   `Tools`: Google Colab, Jupyter

