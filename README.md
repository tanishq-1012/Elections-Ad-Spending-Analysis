# Elections-Ad-Spending-Analysis

## Overview

This project analyzes election advertising spending and its potential correlation with voter turnout across different states and constituencies. Using Python 🐍  and Plotly, it visualizes data from various sources to identify trends and insights regarding political ad expenditures and voter participation.
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

## Plot 1

Let's have a look at the total ad spend by state:

<img width="886" alt="Screenshot 2025-03-19 at 2 37 40 PM" src="https://github.com/user-attachments/assets/84f4e00e-b08e-49cd-92a2-9e2ee7b45426" />

The bar graph shows the total ad spend (in INR) by state. Uttar Pardesh leads significantly with the higest ad spend, followed by Maharahstra and Odisha. States like West Bengal, Tamil Nadu, Andhra Pradesh, and Bihar also show substantial ad expenditures. In contrast states such as Lakshadweep, Dadra & Nagar Haveli, Daman and Diu, Andaman & Nicobar Islands, and Arunachal Pardesh have the lowest ad spend. It indicates that larger and more populous states tend to spend more on ads, likely reflecting their greater political significance and larger voter base.

## Plot 2

Let's have a look at the average voter turnout by state:

<img width="886" alt="Screenshot 2025-03-19 at 2 37 56 PM" src="https://github.com/user-attachments/assets/a5787130-94d6-4d00-ace7-51322abd537e" />

Lakshadweep has the highest average voter turnout at nearly 80%, followed closely by Tripura and Assam. States like Andhra Pradesh, Sikkim, and West Bengal also show high voter engagement, with turnouts above 70%. On the other end of the spectrum, states such as Bihar, Uttar Pradesh, and Uttarakhand have the lowest average voter turnout, around 50-55%. It indicates significant regional variations in voter participation, with some smaller states and union territories exhibiting higher engagement compared to larger states with higher ad spend.

## Plot 3

Let's have a look at the top 5 Parties by ad spend:

<img width="1067" alt="Screenshot 2025-03-19 at 2 38 17 PM" src="https://github.com/user-attachments/assets/7147d710-17be-4aec-9414-32ae15147b09" />

The Bharatiya Janata Party (BJP) has the highest ad spend, accounting for 42.3% of the total. This is followed by the Ama Chinha Sankha Chinha party at 24.5% and the Indian National Congress at 23.7%. Ellorum Nammudan and BJP Odisha have significantly lower ad spends, at 5.19% and 4.27%, respectively. It indicates that BJP dominates in terms of ad spending on Facebook and Instagram ads, with nearly half of the total expenditure, suggesting a significant investment in advertising compared to other parties.


## Correlation

Let's have a look at the correlation between ad spend and voter turnout:

<img width="457" alt="Screenshot 2025-03-19 at 2 38 40 PM" src="https://github.com/user-attachments/assets/f322fa0f-979a-4b6b-9c7f-f19451335756" />

The correlation matrix shows that the relationship between the amount spent (INR) and the percentage of votes polled (%) is very weak and slightly negative, with a correlation coefficient of -0.010688. This indicates that there is virtually no linear relationship between ad spend and voter turnout. In other words, increasing the amount spent on advertising does not significantly affect the percentage of voter turnout.

## Plot 4

Let's have a look at the relationship between ad spend and voter turnout by parlimentary constituency:

<img width="868" alt="Screenshot 2025-03-19 at 2 39 06 PM" src="https://github.com/user-attachments/assets/e844efc2-892d-44ec-8369-4037ac1b0131" />

<img width="868" alt="Screenshot 2025-03-19 at 2 39 18 PM" src="https://github.com/user-attachments/assets/fc8fe8c6-0b54-45cf-b579-af4ab6bf5cc2" />

It shows that higher ad spending does not necessarily correlate with higher voter turnout. Voter turnout seems to cluster between 60% and 80% across most constituencies, regardless of the ad spend amount, which ranges from 0 to 150 million INR. This suggests that other factors besides ad spend may play a significant role in influencing voter turnout.

## Plot 5

Let's have a look at the distribution of ad spending:

<img width="868" alt="Screenshot 2025-03-19 at 2 39 39 PM" src="https://github.com/user-attachments/assets/a222729a-671e-441e-9231-7303827625e9" />

The histogram indicates that most constituencies have ad spends clustered around the 50M and 100M INR marks, with fewer constituencies spending less than 10M INR or more than 150M INR. The box plot highlights that the median ad spend is around 70M INR, with the interquartile range (IQR) spanning from approximately 30M to 110M INR. There are a few outliers, particularly a constituency with an exceptionally high ad spend above 150M INR. This distribution suggests that while the majority of ad spends are concentrated within a certain range, there are notable exceptions with significantly higher expenditures.

## Plot 6

Let's analyze ad spending and voter turnout by election phase:

<img width="810" alt="Screenshot 2025-03-19 at 2 40 07 PM" src="https://github.com/user-attachments/assets/7805655e-5aec-4113-ae82-57a2e7071d2b" />

There is no consistent trend between ad spend and voter turnout. Election phases 1 and 4 have the highest ad spends, with phase 4 peaking in voter turnout at around 70%. However, phase 1, despite high ad spend, has a lower voter turnout of about 67%. Phases with moderate ad spend (e.g., 2 and 6) have lower voter turnout, while phase 5 has a notably low turnout despite moderate spending.

## Technologies Used

Python

Pandas (Data manipulation and cleaning)

Plotly (Data visualization)

## Installation

1.**Clone the repository**: git clone https://github.com/tanishq-1012/Elections-Ad-Spending-Analysis.git

2.**Nevigate to the project directory**: cd Elections-Ad-Spending-Analysis

3.**Install dependencies**: pip install pandas plotly
   
## Usage

1. Ensure the dataset files (results.csv, advertisers.csv, locations.csv) are placed in the elections-data/ folder.

2. Run the script: python analysis.py

3. Visualizations will be displayed within Jupyter Notebook, and insights will be printed in the output cells.

## Data Sources

**results.csv**: Election results with voter turnout percentages.

**advertisers.csv**: Political parties and their ad spending data.

**locations.csv**: Mapping of locations and states.

## Insights

Identifies the states with the highest ad spending.

Examines whether higher ad spending translates to increased voter turnout.

Highlights the political parties with the highest advertising budgets.

## Conclusion

Overall, the analyses indicate that higher ad spend does not guarantee higher voter turnout and voter engagement is influenced by various other factors. Larger and more significant states tend to spend more on ads, but this does not necessarily translate to higher voter participation. Political parties, particularly the BJP, invest heavily in advertising, yet the effectiveness of this spending in increasing voter turnout is questionable.

## Future Improvements

Include more granular data on ad categories.

Integrate social media sentiment analysis.

Enhance visualizations with interactive filters.

## Author

Tanishq Sharma
