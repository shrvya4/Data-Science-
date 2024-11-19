# Job Market Data Analysis

This project analyzes job market trends by scraping job listings from **Google Jobs** using **Selenium**. The scraped data was preprocessed and analyzed to uncover insights about the job market, such as the most in-demand job titles, required skills, job locations, and salary trends. Visualizations were then created to better understand these insights.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Visualization](#visualization)
- [License](#license)

## Overview

In this project, we used **Selenium** to scrape job listings from **Google Jobs** by automating browser interactions. After collecting the job data, we performed data preprocessing to clean and structure it for analysis. Several visualizations were then generated to reveal key trends in the job market, such as:

- Most popular job titles
- Key skills required for different job positions
- Geographical distribution of jobs
- Salary trends and comparisons

## Technologies Used

- **Python**: The primary programming language used in this project.
- **Selenium**: For web scraping and automating interactions with the Google Jobs website.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib** and **Seaborn**: For creating visualizations.
- **Jupyter Notebooks**: For performing interactive analysis and visualizing data.

## Setup and Installation

### Prerequisites

- Python 3.6+
- pip (Python package installer)
- WebDriver for Selenium (e.g., ChromeDriver)

### Steps to Set Up

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/job-market-data-analysis.git
   cd job-market-data-analysis
   ```

2. **Install dependencies:**

   It's recommended to create a virtual environment first

3. **Download WebDriver**:  
   Selenium requires a browser driver to control the browser. For Chrome, you can download **ChromeDriver** from [here](https://sites.google.com/a/chromium.org/chromedriver/). Make sure the version matches your Chrome browser.

4. **Run the script**:  
   After setting up, run the scraping and analysis scripts.

## Usage

1. **Web Scraping**:  
   This script uses **Selenium** to automate browser actions (such as searching for jobs and scrolling through the results) and scrape job listings from Google Jobs. The data includes job titles, companies, locations, descriptions, and other relevant information.

2. **Data Preprocessing**:  
   The `preprocess_data.py` script processes the raw scraped data by:
   - Removing duplicates.
   - Handling missing values.
   - Parsing job titles, companies, and other fields.
   - Extracting key skills mentioned in the job descriptions.

3. **Visualization**:  
   The `visualize_jobs.py` script generates visualizations, such as:
   - **Bar charts** to show the most common job titles.
   - **Word clouds** to represent the most frequently mentioned skills.
   - **Heatmaps** to illustrate job distribution by location.
   - **Boxplots** to visualize salary ranges across different job roles.

## Data Preprocessing

After scraping the job data, several preprocessing steps were applied to clean and structure the data:

- **Data Cleaning**: Removal of incomplete records, handling missing or null values.
- **Feature Extraction**: Extracted relevant features such as job title, company, location, salary (if available), and skills mentioned in job descriptions.
## Visualization

We created several visualizations to analyze job market trends, including:

- **Job Distribution by Title**: A bar chart showing the most frequent job titles in the dataset.
- **Geographic Distribution**: A heatmap displaying job listings based on their geographical locations.
- **Salary Trends**: A boxplot showing the salary distribution for different roles.

These visualizations provide insights into the current job market, such as the most in-demand roles and the skills that employers prioritize.


### Notes:
- Ensure that you have **ChromeDriver** (or another driver based on the browser you use) in the system path or specify its path in the code if necessary.
- Feel free to adjust the details about visualizations or preprocessing steps based on your specific implementation.

Let me know if you'd like to add or modify any part of this!
