# Exploratory Data Analysis on Terrorism Dataset

## Overview

As a security/defense analyst, this project focuses on conducting Exploratory Data Analysis (EDA) on the Terrorism dataset to identify hot zones of terrorism. The analysis utilizes Jupyter Lab for data exploration and visualization.

## Dataset

The dataset used for this analysis contains information about terrorist attacks worldwide, including details such as location, date, casualties, and terrorist group responsible.

## Tools Used

- **Tool:** Jupyter Lab
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, WordCloud

## Project Structure

1. **Importing Libraries:**
   - Import necessary libraries such as Pandas, NumPy, Matplotlib, Seaborn, and WordCloud.

2. **Seaborn Style Setting:**
   - Set Seaborn style for better visualization aesthetics.

3. **Loading Dataset:**
   - Load the terrorism dataset into Jupyter Lab for analysis.

4. **Data Cleaning and Preparation:**
   - Printing different details about the dataset like data columns, renaming columns, and selecting only certain columns.
   - Information on the selected columns.
   - Checking columns for missing values.

5. **Deriving New Columns:**
   - Create a new column for casualties.

6. **WordCloud Visualization:**
   - Generate a word cloud for the countries affected by terrorism.

7. **Mode Calculation:**
   - Print the mode of different columns.

8. **Data Visualization:**

### Temporal Analysis:
   - Plot the number of terrorist attacks through the years.
   - Plot the number of terrorist attacks throughout each year by region using crosstabs.
   - Plot the number of attacks in the top N countries over the years.
   - Plot the number of attacks in the top N cities over the years.

### Attack Characteristics:
   - Plot the types of attacks and their frequencies.
   - Create a pie chart for the number of casualties for each attack type.

### Top Entities Analysis:
   - Plot the top 10 groups with the most terrorist attacks.
   - Plot the top 20 countries with the most casualties.
   - Plot the top 20 countries with the most wounded.
   - Plot the top 20 countries with the most killed.

### Casualty Analysis:
   - Analyze casualties, wounded, and killed by region.
   - Create a pie chart for the type of attack most deadly by each attack type.

### Year-Specific Analysis:
   - Distribution of attacks in 2007 and comparison with global distribution.

## How to Run

1. Clone the repository:
   ```sh
   git clone https://github.com/AnuragSuni1/Terrorism-EDA.git
