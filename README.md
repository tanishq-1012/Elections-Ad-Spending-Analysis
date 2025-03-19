# Elections-Ad-Spending-Analysis

## Overview

This project analyzes election advertising spending and its potential correlation with voter turnout across different states and constituencies. Using Python and Plotly, it visualizes data from various sources to identify trends and insights regarding political ad expenditures and voter participation.
If you are highly active on Facebook and Instagram, you must have seen ads based on elections by any of the political parties, especially **BJP** and **INC**. All the parties in India usually spend a lot of money on election campaigns. I recently collected data from Meta ads about how much money was spent on Instagram and Facebook ads by each political party during the Indian election 2024 in each state.

## Features

1.**Data Cleaning & Merging**: Cleans and merges election results, advertiser data, and location data.

2.**Total Ad Spend by State**: Bar chart visualization of total advertising expenditure per state.

3.**Average Voter Turnout by State**: Bar chart representation of voter turnout percentages per state.

4.**Top 5 Parties by Ad Spend**: Pie chart visualization of the highest spending political parties.

5.**Correlation Analysis**: Computes the correlation between ad spending and voter turnout.

6.**Ad Spend vs. Voter Turnout (Scatter Plot)**: Examines the relationship between spending and turnout across constituencies.

7.**Ad Spend Distribution**: Histogram and box plot depicting ad spending distribution.

8.**Ad Spend and Voter Turnout by Election Phase**: Dual-axis bar and line chart analyzing trends by election phases.

## Dataset

1. The **Advertisers Dataset** provides insights into which pages (parties or organizations) spend money on election ads and the volume of ads they run.

2. The **Location Dataset** shows how much money was spent on ads in different locations, indicating where the campaigns were focusing their efforts.

3. The **Result Dataset** provides actual voting data, showing how many people voted in each area and the percentage of voter turnout.

## Dataset

**Result**

<img width="872" alt="Screenshot 2025-03-19 at 2 35 38 PM" src="https://github.com/user-attachments/assets/99c94a87-0830-4485-9554-5d40170c8ec5" />

<img width="845" alt="Screenshot 2025-03-19 at 2 36 06 PM" src="https://github.com/user-attachments/assets/59063d0e-9908-4f70-9f4e-1bcb1b82c236" />

**Advertisers**

<img width="1039" alt="Screenshot 2025-03-19 at 2 36 28 PM" src="https://github.com/user-attachments/assets/734de895-99f7-4217-9e4a-1736edee9e1d" />

<img width="1007" alt="Screenshot 2025-03-19 at 2 36 45 PM" src="https://github.com/user-attachments/assets/b92bfc01-611c-4e77-ac2e-cb6eb5da20df" />

**Location**

<img width="386" alt="Screenshot 2025-03-19 at 2 37 06 PM" src="https://github.com/user-attachments/assets/d62847af-8bcd-412a-9e6e-1245435dc4bc" />

The results data has a column named state, and the location data has a column named location name. We will merge these data sets using these columns.

<img width="1064" alt="Screenshot 2025-03-19 at 2 37 22 PM" src="https://github.com/user-attachments/assets/a535c9be-3611-4588-83de-d82fa52245bc" />
