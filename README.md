# Powerball Lottery Analysis
Using: <img src="https://github.com/microsoft/PowerBI-Icons/blob/main/SVG/Power-BI.svg" alt="Power BI" width="40" height="40"/> Power BI

## Overview

Welcome to the Powerball Lottery Analysis project! In this repository, I've conducted an analysis of Powerball lottery winning combinations since 2010 using open-source data from data.gov. The project showcases my analytical skills and provides insights into the frequency of numbers and combinations drawn in the Powerball lottery.

## Data Source

The data used for this analysis was sourced from the data.gov website, providing open-source data on Powerball lottery winning combinations since 2010.

## Data Modeling and Analysis in Power BI

1. Data Cleaning and Preparation:
- Uploaded the dataset into Power BI.
- Utilized Power BI's Query Editor to clean and trim the data, ensuring consistency and accuracy.


2. Identifying lucky numbers by creating a separate table from existing data to analyze the frequency of individual numbers being drawn.


3. Identifying Lucky Combinations:
- Recognized that lottery wins begin with a combination of at least 2 numbers.
- Analyzed and identified the luckiest combination of 2 numbers.
- Merged the first number of each 6-number combination with the second, third, fourth, and so on. For example, from combination "01 02 03 04 05 06", I have "01 02", "01 03", and so on.
- Ensured removal of duplicates to avoid redundancy, using unique IDs for each line combination of 2 numbers.

## Dashboard Creation and Overview

Developed a dashboard using various visuals to present the following insights:
- Total number of games played
- Top 10 lucky numbers, filterable by draw position (1st to 6th).
- Top 3 most winning combinations of 2 numbers.
- Multiplier trend by month.
- Frequency of various multipliers being drawn.

### Screenshot
![](https://github.com/IlziraC/Powerball/blob/6c05d1c0ded22c621e27c01fb1f5412bf7ba0211/Dashboard%20snip%20.png)


## Repository Structure

- `Lottery_Powerball_Winning_Numbers__Beginning_2010.csv`: Contains the dataset used for analysis.
- `Lottery.pbix`: Power BI file containing the data model and dashboard.

## Usage

Feel free to explore the project and reach out with any questions or feedback! Contributions and suggestions are always welcome.
