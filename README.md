# Professional Survey Data Analysis using Power BI

This project focuses on analyzing survey data collected from professionals using Power BI. The primary goals are to extract and transform the given data from an Excel worksheet, and create insightful visualizations.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Data Transformation](#data-transformation)
- [Visualizations](#visualizations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Cloning the Repository](#cloning-the-repository)

## Introduction

This project involves the analysis of survey data collected from professionals regarding their roles, salaries, job satisfaction, and other demographics. The key tasks are to clean the data, automate the cleaning process, and create new measures to derive useful insights using Power BI.

## Dataset

The dataset contains survey responses from professionals with the following information:

- Individual ID
- Profession
- Salary
- Place of residence
- Responses to survey questions (Q1 to Q12)

### Survey Questions:

1. **Q1**: Which Title Best Fits your Current Role?
2. **Q2**: Did you switch careers into Data?
3. **Q3**: Current Yearly Salary (in USD)
4. **Q4**: What Industry do you work in?
5. **Q5**: Favorite Programming Language
6. **Q6**: How Happy are you in your Current Position with the following? 
   - Salary
   - Work/Life Balance
   - Coworkers
   - Management
   - Upward Mobility
   - Learning New Things
7. **Q7**: How difficult was it for you to break into Data?
8. **Q8**: If you were to look for a new job today, what would be the most important thing to you?
9. **Q9**: Male/Female?
10. **Q10**: Current Age
11. **Q11**: Which Country do you live in?
12. **Q12**: Ethnicity

## Requirements

- Power BI Desktop
- Excel data files (provided in the repository)

## Data Transformation

1. **Load Data**: Load the survey data from the provided Excel files into Power BI.
2. **Remove Duplicates**: Identify and remove duplicate entries in the dataset using Power BI's data transformation tools.
3. **Clean Data**: Remove unwanted data entries based on specific criteria (e.g., erroneous entries).
4. **Automate Transformation**: Use Power BI to automate the data cleaning process by applying the same transformation steps.

## Visualizations

We will create the following visualizations using Power BI:

1. **Number of Workers in Specific Country**: A bar chart showing the number of survey respondents in each country.
2. **Average Salary by Job Title**: A bar chart displaying the average salary for each job title.
3. **Count of Survey Takers**: A card visualization showing the total number of survey respondents.
4. **Average Age of Survey Takers**: A card visualization showing the average age of the survey respondents.
5. **Average Salary Based on Sex**: A bar chart comparing the average salary based on gender.
6. **Favorite Programming Languages**: A pie chart or bar chart showing the distribution of favorite programming languages among respondents.

## Usage

1. **Clone the repository**.

2. **Open Power BI Desktop**.

3. **Load the Excel data files** into Power BI.

4. **Apply the data transformation steps** as described.

5. **Create visualizations** to analyze the data and derive insights.

## Cloning the Repository

To clone this repository, follow these steps:

1. **Install Git**: If you don't have Git installed, download it from [Git's official website](https://git-scm.com/downloads) and install it.

2. **Open Terminal/Command Prompt**:
   - On Windows, you can use Command Prompt or PowerShell.
   - On macOS and Linux, you can use Terminal.

3. **Navigate to the directory** where you want to clone the repository. For example:
   ```sh
   cd path/to/your/directory
   ```

4. **Clone the repository** using the following command:
   ```sh
   git clone https://github.com/AishwaryaS-srk/Professional-survey-analysis
   ```

5. **Navigate into the cloned repository**:
   ```sh
   cd Professional-survey-analysis
   ```

Now you have a local copy of the repository on your machine, and you can start working on the project.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.



This README now includes detailed instructions for the project, covering everything from the dataset to data transformation, visualizations, usage, and cloning the repository.
