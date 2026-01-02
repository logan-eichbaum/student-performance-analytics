# Student Performance Analytics: What Drives High School Success?

## Project Summary
This project analyzes **which factors most strongly influence high school student performance**, moving beyond effort alone to examine the role of demographics, family background, behavior, and study habits.

Using student data from two Portuguese public schools, I built a **logistic regression model** and an **interactive dashboard** to identify and explore the strongest predictors of academic success.

---

## Business Question
Educators often assume academic success is primarily driven by effort.  
This project asks:

- Which factors most strongly influence student performance?
- How much control do students actually have over their outcomes?
- Which variables should educators focus on to improve success rates?

---

## Data
**Source:** UCI Machine Learning Repository  
**Scope:** 650 students, 30 features, 2014  

Key feature categories:
- Demographics (age, sex)
- Family background (parental education, family support)
- Behavioral factors (study time, absences, alcohol consumption)
- Academic outcomes (three grading periods)

A composite **Average Grade** metric was created from period grades to represent overall performance.

---

## Data Preparation
- Verified data completeness (no missing values)
- Converted categorical variables to factors
- Engineered success metric using average grades
- Structured data for modeling and visualization

---

## Modeling Approach
- **Logistic Regression** used to classify academic success levels
- Feature importance extracted to rank influencing factors
- Results used to guide dashboard navigation and interpretation

The model enables both **predictive insight** and **explanatory analysis**.

---

## Key Findings
- **Intent to pursue higher education** is the strongest predictor of success
- **Parental education** has a measurable impact on grades
- **Study time increases performance**, but with diminishing returns beyond moderate levels
- **Absences and behavioral patterns** negatively affect outcomes
- Demographic factors (age, gender) influence performance but are secondary to academic intent and support

---

## Interactive Dashboard
The dashboard enables exploratory analysis by allowing users to:
- Compare any variable against average grades
- Apply filters (e.g., gender, travel time) to add analytical depth
- View ranked factor importance from the regression model

Design emphasizes clarity, minimalism, and interpretability based on established data visualization principles.

---

## Use Case
Designed for:
- Educators
- School administrators
- Education policy analysts

The tool supports **data-informed decisions** around curriculum design, student support strategies, and intervention planning.

---

## Tools & Technologies
- Logistic Regression
- Data Visualization (Interactive Dashboard)
- Feature Engineering
- Statistical Analysis
