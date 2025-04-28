# Titanic Dataset Survival Analysis
This project analyzes the survival patterns of Titanic passengers by creating visualizations with Seaborn and Matplotlib.
The aim is to uncover the factors that impacted survival rates across various passenger characteristics.

## Visualizations and Key Findings

### 1. Age Distribution by Survival Status
- Younger passengers, particularly children, had a higher survival rate.

### 2. Survival by Gender
- Females survived at much higher rates than males.

### 3. Age Distribution by Passenger Class
- First-class passengers included older individuals.
- Third-class passengers were generally younger.

### 4. Survival by Embarked (Port of Embarkation)
- Passengers embarking from Cherbourg had the highest survival rates.
- Southampton passengers had comparatively lower chances of survival.

### 5. Fare by Survival Status
- Survivors tended to have paid higher ticket fares.
- Fare was positively correlated with survival.

### 6. Survival by Age Group
- Children had the highest survival rate.
- Seniors had the lowest chance of survival.

### 7. Family Size vs Survival (SibSp + Parch)
- Smaller family sizes (1-3) showed better survival outcomes.
- Very large family groups had lower survival rates.

### 8. Survival by Deck (First Letter of Cabin)
- Higher decks (A, B, C) had greater survival rates.
- Lower decks were associated with lower survival chances.

## Technologies Used
- Python
- Pandas
- Seaborn
- Matplotlib

## How to Run
1. Install required libraries:
    bash
    pip install pandas seaborn matplotlib
    
2. Load the Titanic dataset from Seaborn.
3. Execute each analysis cell to visualize survival patterns.

---
## Conclusion
Exploratory analysis and visualizations clearly show that factors like age, gender, passenger class, fare amount, family size, and deck location played a major role in determining survival on the Titanic.
