 # Titanic Survival Data Science Project

Welcome to the Titanic Survival Analysis and Prediction project. This repository contains a comprehensive analysis of the Titanic passenger data, aiming to uncover patterns that contributed to survival during the tragic sinking. Through meticulous data cleaning, exploratory data analysis (EDA), and visualization, this project offers valuable insights and sets the foundation for predictive modeling.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Getting Started](#getting-started)
- [Data Cleaning and Exploration](#data-cleaning-and-exploration)
- [Visualizations](#visualizations)
- [Results and Insights](#results-and-insights)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

The Titanic dataset is a classic case study used in data science for both learning and competition. This project focuses on:

1. **Data Acquisition**: Loading the Titanic dataset for analysis.
2. **Data Cleaning**: Handling missing values, outliers, and irrelevant features.
3. **Exploratory Data Analysis (EDA)**: Understanding the data through statistical analysis and visual representation.
4. **Visualization**: Creating meaningful plots to illustrate survival rates and their correlation with various factors.

## Dataset Description

The dataset consists of 891 records of passengers who were aboard the Titanic. Each record contains 12 features:

- **PassengerId**: A unique identifier for each passenger.
- **Survived**: Survival status (0 = No, 1 = Yes).
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- **Name**: Full name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Fare paid by the passenger.
- **Cabin**: Cabin number (if assigned).
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Getting Started

### Prerequisites

Before running the project, ensure you have the following Python libraries installed:

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.
- **matplotlib**: For basic plotting and visualizations.
- **seaborn**: For advanced visualizations based on Matplotlib.

## Data Cleaning and Exploration

- **Missing Data**: The dataset contains missing values in columns such as `Age`, `Cabin`, and `Embarked`. The script addresses these issues by either filling in missing data or removing unnecessary columns.
- **Feature Engineering**: Relevant features are engineered to improve the analysis, such as creating new features or transforming existing ones.
- **Outlier Detection**: Outliers in features like `Fare` are identified and managed.

## Visualizations

The project produces several insightful visualizations, including but not limited to:

- **Survival Distribution**: A count plot that visualizes the distribution of survivors and non-survivors.
- **Survival by Class**: A bar plot showing survival rates across different passenger classes.
- **Age Distribution**: A histogram representing the age distribution of passengers.
- **Fare vs. Survival**: A scatter plot analyzing the relationship between fare amount and survival status.
- **Correlation Heatmap**: A heatmap to identify correlations between different features.

## Results and Insights


The visualizations and analysis reveal significant patterns, such as:
 

 ![Figure_1](https://github.com/user-attachments/assets/90a5a584-7d6f-4b59-b950-fc91f938b0f3)
  
 ![Figure_2](https://github.com/user-attachments/assets/35e50d9a-f01a-4bb1-bebd-f4fac173fa67)
 
 ![Figure_3](https://github.com/user-attachments/assets/0bb2a4c3-7b27-4327-a1af-1598bf6b7732)
 
 ![Figure_4](https://github.com/user-attachments/assets/c6b9f468-4b69-4599-80f6-16641154dd9e)
 
 ![Figure_5](https://github.com/user-attachments/assets/e1d8ec80-d650-403f-93bd-be9775b06afa)

 ![Figure_6](https://github.com/user-attachments/assets/99d4a26e-d98f-4068-9241-35ee3e789e15)
 
 ![Figure_7](https://github.com/user-attachments/assets/43782579-30d1-475e-932f-e0ec42579173)
 
 ![Figure_8](https://github.com/user-attachments/assets/1800a291-35e5-48ce-9380-2b1877cdc557)
  
 ![Figure_9](https://github.com/user-attachments/assets/22c6a6b5-2f4c-46b2-ada8-d51eaaa34b53)
 
 ![Figure_10](https://github.com/user-attachments/assets/7cbb07d0-97e2-471c-86d2-ffd9f3be83f1)
  
 ![Figure_11](https://github.com/user-attachments/assets/c8151cfa-abba-4cbc-960f-f89a53324f7c)
  
 ![Figure_12](https://github.com/user-attachments/assets/845a9866-2a0f-4d86-99d4-955f17be4b54)
  
 ![Figure_13](https://github.com/user-attachments/assets/67507c44-52ad-401a-873c-5b90251fb957)
 
 ![Figure_14](https://github.com/user-attachments/assets/a23c5ffd-bf55-41d6-b21b-73ad813ba5f2)
  
 ![Figure_15](https://github.com/user-attachments/assets/ace9938b-3964-4429-9540-4a4f06755353)
  
 ![Figure_16](https://github.com/user-attachments/assets/768db153-3330-48c7-b568-845622e46b3c)
 
 ![Figure_17](https://github.com/user-attachments/assets/4a0ddb0b-b2fb-41f8-9ee0-22aaa071d90e)
 
 ![Figure_18](https://github.com/user-attachments/assets/470637c7-c812-4fd9-9537-ab3192cbe5c5)
 
 ![Figure_19](https://github.com/user-attachments/assets/5011f8d4-ea27-4f2a-b62a-0f0d7c044a2f)


 
These insights can serve as the basis for developing predictive models to estimate the likelihood of survival based on the features provided.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- **Kaggle**: For providing the Titanic dataset.
- **Open-source Community**: For contributing to the libraries and tools that make projects like this possible.

 
