# World Happiness Analysis

**Overview:**  
Analyzed global happiness data to identify socio-economic factors impacting national happiness scores and built ML models to predict happiness categories.

**Highlights:**
- Conducted exploratory data analysis (EDA) and visualized trends using Python & MS Excel.
- Built classification models with R:
  - Logistic Regression (80% accuracy)
  - Neural Network (84% accuracy)
  - Decision Tree
  - kNN (up to 83.9% accuracy)
- Normalized multi-factor datasets and validated insights with 95% confidence intervals.

**Achievements:**
- Identified GDP, social support, and healthy life expectancy as the top 3 factors most correlated with happiness.
- Produced actionable insights that could inform policy decisions and global well-being initiatives.
- Improved prediction accuracy of country happiness categories by 15% compared to baseline models.

**Tools:** Python, MS Excel, Pandas, NumPy, Seaborn

# Key Findings

## Happiness Rankings
- **Finland** ranks as the happiest country.  
- The top 20 happiest countries are concentrated in **Western Europe (13)**, with others in:  
  - Australia & New Zealand (2)  
  - North America (2)  
  - Latin America & Caribbean (1)  
  - Middle East & North Africa (1)  
  - Central & Eastern Europe (1)  
- **South Sudan** ranks as the unhappiest country.  
- The top 20 unhappiest countries are largely from **Sub-Saharan Africa (14)**, with others in:  
  - Middle East & North Africa (1)  
  - South Asia (1)  
  - Latin America & Caribbean (1)  

## Correlated Factors
- Strong correlations observed between:  
  - Class & healthy life expectancy  
  - GDP per capita & healthy life expectancy  
- Regression analysis highlights **GDP per capita, healthy life expectancy, and social support** as the top 3 predictors of happiness score.  
- Linear regression of GDP per capita vs. happiness score yields **R² = 0.632**, indicating a moderate-to-strong relationship.  

## Modeling Insights
- Logistic regression & confusion matrix analysis: **≈80% accuracy** in predicting happiness level from GDP per capita.  
- Neural network model predicting life expectancy (classified into 3 levels: *55–65, 65–75, 75–85*) achieved **84% accuracy**.  
- K-Nearest Neighbors (**K=16**) classified happiness rank categories with **83.9% accuracy**.  
- Random Forest classifier reached **93.5% accuracy**, outperforming SVM (**74.1% accuracy**) in predicting happiness levels.  

## Generosity Factor
- Generosity shows notable relationships with:  
  - **Perception of Corruption (34%)**  
  - **Freedom to make life choices (27%)**  
- The most generous regions are:  
  - Australia & New Zealand (**33%**)  
  - Southeast Asia (**30%**)  
  - North America (**28%**)  

---

# Strategic Insights & Recommendations

### Policy Priorities
Countries aiming to improve happiness should prioritize **GDP growth, healthcare (life expectancy), and social support systems**, as these are the strongest predictors of happiness scores.  

### Targeted Regional Development
Regions with lowest rankings:  
- **Sub-Saharan Africa**  
- **South Asia**  

Policies that improve **healthcare access, governance quality, and economic stability** may significantly improve happiness outcomes.  

### Generosity & Governance
The link between **generosity, corruption perception, and freedom** suggests that improving **transparency and civic freedoms** could indirectly boost well-being.  

### Modeling Applications
- **Random Forest** and **Neural Network** models demonstrate strong predictive power (**84–93%**), offering valuable tools for **policy simulation and forecasting**.  
- Governments and NGOs can leverage these models to **evaluate potential interventions before large-scale implementation**.  

### Benchmarking Engagement
- With **R² = 0.632** between GDP and happiness score, GDP growth **alone is insufficient**.  
- **Social and health investments are equally critical** for long-term improvements.  

