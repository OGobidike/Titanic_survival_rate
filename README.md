# Titanic Survival Rate Analysis  
*A Tableau Visualization Project*

## Abstract
This project leverages the Titanic dataset to explore factors that may have influenced survival rates during the infamous maritime disaster. Through a series of interactive visualizations created in Tableau, the project examines whether passenger class, family relationships (measured by the number of siblings/spouses aboard), and age had significant impacts on survival outcomes. By following the scientific method—posing hypotheses, conducting exploratory data analysis, and drawing conclusions—the project provides insights into historical survival trends and demonstrates effective data storytelling techniques.

## Table of Contents
- [Introduction](#introduction)
- [Hypotheses](#hypotheses)
- [Methodology](#methodology)
- [Results and Discussion](#results-and-discussion)
- [Visualizations](#visualizations)
- [Accessing the Interactive Dashboard](#accessing-the-interactive-dashboard)
- [Conclusion](#conclusion)
- [Project Structure](#project-structure)
- [License](#license)

## Introduction
The sinking of the Titanic remains one of the most well-known tragedies in history. The Titanic dataset contains records for passengers, including variables such as survival status, passenger class, age, and the number of siblings/spouses aboard. This project aims to dissect the factors influencing survival, moving beyond raw numbers to provide a narrative of discovery through interactive visualization.

## Hypotheses
Based on historical context and preliminary research, the following hypotheses were explored:
- **Passenger Class:** Passengers in first class had a higher survival rate compared to those in third class.
- **Family Connections:** A higher number of siblings/spouses onboard correlated with lower survival chances, possibly due to complications during evacuation.
- **Age Factor:** Passengers in the age group of 20-30 experienced a higher chance of survival, suggesting age-related differences in vulnerability or mobility during the disaster.

## Methodology
1. **Data Acquisition & Preparation:**  
   The Titanic dataset was cleaned and preprocessed to ensure accuracy and consistency in variables of interest (survival status, passenger class, number of siblings/spouses, and age).

2. **Visualization Design:**  
   Using Tableau Desktop, multiple charts were created:
   - **Survival by Passenger Class:** A bar chart comparing survival rates across the different classes, highlighting the significantly higher survival rate in first class.
   - **Impact of Siblings/Spouses:** A visualization that plotted the number of siblings/spouses against survival outcomes, revealing that an increased count often led to a decreased survival rate.
   - **Age Distribution and Survival:** A chart illustrating survival rates across age groups, with a notable peak in survival for passengers aged between 20-30.

3. **Scientific Analysis:**  
   Each visualization was analyzed to test the initial hypotheses, drawing on patterns observed in the charts to support or refute the expected trends.

## Results and Discussion
The visual analysis provided clear evidence supporting the initial hypotheses:
- **Passenger Class Impact:** The charts clearly demonstrated that first-class passengers had a markedly higher chance of survival compared to third-class passengers.
- **Family Influence:** An inverse relationship was observed between the number of siblings/spouses and survival rate, indicating that having more family members onboard was linked to a lower likelihood of survival.
- **Age Influence:** The data suggested that younger adults, particularly those between 20-30 years, had better survival outcomes, a trend that could be linked to physical resilience or quicker response times during the emergency.

These findings not only underscore historical accounts but also demonstrate how interactive visualizations can transform raw data into an engaging narrative.

## Visualizations
### 🚢 Survival Rate by Passenger Class
![Survival by Class](images/survival_by_class.png)

### 🏠 Impact of Siblings/Spouses on Survival
![Siblings/Spouses vs. Survival](images/siblings_vs_survival.png)

### 📊 Age and Survival Rate
![Age vs. Survival](images/age_vs_survival.png)

These visualizations highlight the key patterns observed in the dataset and reinforce the conclusions drawn from the analysis.

## Accessing the Interactive Dashboard
To experience the interactive visualizations and explore the data further, please visit the Tableau Public dashboard:

[View the Titanic Survival Rate Dashboard](https://public.tableau.com/app/profile/oguguamakwa.og.obidike/viz/titanic_survival_rate/Dashboard1)

Alternatively, you can embed this dashboard in your browser or share it with others to facilitate discussion and further exploration.

## Conclusion
This project illustrates a structured approach to data analysis using the scientific method—from hypothesizing and data cleaning to visualization and interpretation. The insights gained from the Titanic dataset offer a compelling historical perspective and exemplify how data visualization can be used to communicate complex findings effectively.

## Project Structure
```
├── README.md
├── data
│   └── titanic_dataset.csv   # The source data file
└── tableau_files
    └── titanic_workbook.twbx # Tableau workbook file
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
