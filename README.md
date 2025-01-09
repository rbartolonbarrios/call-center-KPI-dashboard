# Call Center Performance Dashboard

## Overview
This project utilizes a dataset containing three months of daily call records from a call center with eight employees. The dataset provides insights into call resolution, call duration, customer satisfaction, speed of answering calls, and the time of day calls occurred. The goal is to provide a user-friendly dashboard to help managers monitor and evaluate employee performance effectively.

## Dataset
The dataset includes the following columns:
- **Employee ID**: Identifier for the call center employee.
- **Call Resolved**: Boolean indicator of whether the call was resolved (True/False).
- **Call Duration (minutes)**: Total duration of the call.
- **Satisfaction Rating**: Customer rating of the call (1-5 scale).
- **Speed of Answer (seconds)**: Time taken to answer the incoming call.
- **Time of Day**: Timestamp indicating when the call occurred.

The dataset is saved in an Excel file named **"Call Center Data (raw)"**, which is included in the repository.

## Dashboard Features
The dashboard is designed to provide actionable insights through the following components:

### 1. Individual Employee Performance Tracking
- **Monthly Speed of Answer**: Displays the average time employees take to answer calls each month.
- **Resolution Rates**: Tracks the percentage of calls resolved monthly for each employee.
- **Total Resolved Calls**: Shows the cumulative count of calls resolved by each employee.

### 2. Monthly Satisfaction Rating Visualization
- **Bar Chart**: Illustrates the distribution of customer satisfaction ratings (1-5 scale) for the month.

### 3. Key Performance Metrics
- **Overall Monthly Resolution Rate**: Title card displaying the resolution rate for the most recent month.
- **Inbound Calls Today**: Title card showing the total number of inbound calls received on the current day.
- **Average Call Length Today**: Title card presenting the average call duration for today (in minutes).

### 4. Call Volume by Day of the Week
- **Bar Chart**: Visualizes the number of calls received during the most recent month, segmented by day of the week.

## Tools and Technologies
- **Data Cleaning**: Performed directly in Tableau.
- **Visualization and Dashboard Creation**: Tableau
- **Version Control**: Git and GitHub
