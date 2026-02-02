<div align="center">

# Uber India Rides Analysis

</div>

*Studying Uber India ride data to find ways to improve business operations and customer ride experience.*
<hr style="height:2px; border:none; color:#333; background-color:#333;">

## 📌 Table of Contents
- [Overview](#overview)
- [Datasets](#datasets)
- [Tools & Technologies](#tools--technologies)
- [Project Structure](#project-structure)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Research Questions](#research-questions)
- [Analysis and Findings](#analysis-and-findings)
- [Dashboard](#dashboard)
<hr style="height:2px; border:none; color:#333; background-color:#333;">

## Overview
This project explores a real-world ride booking dataset to uncover patterns in trip outcomes, cancellations, and customer satisfaction. It involves data preprocessing, exploratory data analysis, and visualization to derive actionable insights. The analysis was implemented in Python using Pandas, Scipy, Matplotlib, and Seaborn, and the final dashboard was prepared using Power BI.
<hr style="height:2px; border:none; color:#333; background-color:#333;">

## Datasets
- The Ride Bookings dataset of size around 16 MB was downloaded from Kaggle, and it has around 1,03,000 records and 13 features.
- This dataset contains booking information for the month of July 2024, capturing the interaction between customers and drivers.
- The data set was cleaned and preprocessed to prepare a dataset that was then used for the final analysis.
<hr style="height:2px; border:none; color:#333; background-color:#333;">

## Tools & Technologies
- Python (Pandas, NumPy, Scipy, Matplotlib, Seaborn)
- PowerBI (DAX, Interactive Visualizations)
- GitHub
<hr style="height:2px; border:none; color:#333; background-color:#333;">

## Project Structure
```text
uber_india_rides_analysis/
│
├── README.md
├── .gitignore
│
├── analysis_notebook/                  # Jupyter notebook
|   ├── data_analysis.ipynb
│
├── final_dashboard_powerbi/                  # Power BI dashboard file
|   ├── rides_analysis_powerbi_dashboard.pdf
|   └── rides_powerbi_dashboard.pbix
```
<hr style="height:2px">

## Data Cleaning & Preparation
- Corrected data types and created new columns from the original columns.
- Handled Missing and Null values and sorted categorical columns.
<hr style="height:2px">

## Research Questions
1. Which vehicle type (Auto vs. Prime Sedan) has the highest cancellation rate?
2. Can we predict if a ride is likely to be cancelled based on the Pickup Location and Time of Day?
3. When are bookings highest? When are cancellations highest?
4. What is the most common reason for drivers to cancel a ride?
5. Do drivers significantly cancel "Low Value" rides more often than high-value ones?
6. Which specific Pickup-Dropoff routes result in the highest Opportunity Loss (Revenue Lost due to Cancellations/Incomplete rides)?
7. Is there a correlation between Driver_Ratings and Customer_Rating for the same trip?
8. How does the vehicle wait time (V_TAT) impact the Driver's Rating, and at what specific duration does customer satisfaction drop the most?
<hr "height:2px">

## Analysis and Findings
Click here to view the Analysis and Findings - [Analysis and Findings](https://github.com/mjameel9/uber_india_rides_analysis/blob/main/data_analysis.ipynb)
<hr "height:2px">

## Dashboard
The Power BI Dashboard shows:
* Hourly Successful Bookings vs Cancellation Rates
* Top 10 Routes with the Highest Opportunity Loss
* Total Booking Value of different types of rides
* Impact of Wait Time on Driver Ratings
<img width="1323" height="756" alt="Screenshot 2026-02-02 130757" src="https://github.com/user-attachments/assets/ae8182b6-4944-4815-a5d5-5fa341682955" />
<hr "height:2px">

## Author & Contact
#### Mohammed Jameel
🔗 [Portfolio](https://github.com/mjameel9?tab=repositories)



