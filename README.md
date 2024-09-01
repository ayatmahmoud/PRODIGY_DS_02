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

![Figure_19](https://github.com/user-attachments/assets/04c0d2c3-b15f-40aa-ba8f-f101b1b8430f)
![Figure_18](https://github.com/user-attachments/assets/fdaa4a1d-9a74-474b-a57a-3276e47c990e)
![Figure_17](https://github.com/user-attachments/assets/a6561ee7-885f-4cfc-89be-d6f5a3cd66bb)
![Figure_16](https://github.com/user-attachments/assets/ab9d87da-06d0-4acf-9701-14ec46ca11b9)
![Figure_15](https://github.com/user-attachments/assets/6b431317-f8cd-4226-a593-2291d030eb70)
![Figure_14](https://github.com/user-attachments/assets/79d2cd67-c6dd-441c-b3b1-be707700adcb)
![Figure_13](https://github.com/user-attachments/assets/d0811b03-82f4-461c-b1fe-cbc1349a9efa)
![Figure_12](https://github.com/user-attachments/assets/2bf37b7c-824e-405a-9134-960586169a70)
![Figure_11](https://github.com/user-attachments/assets/0c670d99-032d-4b2c-bd7c-abb22ced1cee)
![Figure_10](https://github.com/user-attachments/assets/a5c9ebae-6240-42de-8930-ee94a7fbbd95)
![Figure_9](https://github.com/user-attachments/assets/ba978c88-7225-47d3-b945-582c4054d2a9)
![Figure_8](https://github.com/user-attachments/assets/a9cad707-9cfd-4c4e-8891-4291a11590d0)
![Figure_7](https://github.com/user-attachments/assets/addcb453-177a-4ac9-9d38-5111d16ea158)
![Figure_6](https://github.com/user-attachments/assets/b077dba8-397e-4fb2-9e4f-d35e278dcdce)
![Figure_5](https://github.com/user-attachments/assets/17e8d014-fcfb-4d0a-a9d8-7a1e957a5ae4)
![Figure_4](https://github.com/user-attachments/assets/e1d2e65e-df6b-410d-8b5a-28eddefcee01)
![Figure_3](https://github.com/user-attachments/assets/7610703d-ec7e-47f1-b7cc-ae433bb52cf5)
![Figure_2](https://github.com/user-attachments/assets/e6800338-417e-4792-b313-c9df866a977e)
![Figure_1](https://github.com/user-attachments/assets/d0f0f9e3-9383-4473-bd36-e556d205ddf4)

 

 
These insights can serve as the basis for developing predictive models to estimate the likelihood of survival based on the features provided.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- **Kaggle**: For providing the Titanic dataset.
- **Open-source Community**: For contributing to the libraries and tools that make projects like this possible.

 
