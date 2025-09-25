# US Medical Healthcare Cost Drivers: SQL + Tableau Case Study
This project explores the drivers of individual healthcare costs using a U.S. insurance dataset. SQL is used to perform in-depth analytics with Common Table Expressions (CTEs) and Key Performance Indicators (KPIs), while Tableau brings the findings to life with an interactive dashboard.

The analysis highlights how lifestyle choices (smoking, BMI), demographics (age, dependents, sex), and geography (region) influence medical costs. This mirrors the type of work done in healthcare analytics, insurance risk assessment, and policy planning.
## ❓ Key Questions Answered:
What lifestyle factors are the biggest cost drivers in healthcare?

* Do smokers pay significantly more than non-smokers?

* How does obesity (BMI ≥ 30) affect medical spending?

* Is there a “healthy baseline” for BMI groups?

How do healthcare costs evolve with age?

* Which age groups contribute most to total healthcare costs?

* Do costs rise steadily or accelerate at certain life stages?

Do family dynamics play a role in medical charges?

* Are larger families (more dependents) associated with higher average spending?

* Is there a cost efficiency or burden spread across families?

Are there geographic disparities in U.S. healthcare costs?

* Which regions face higher average charges?

* Do certain regions have lower or more stable costs?

How do population-level KPIs help summarize overall risk?

* What is the average cost per patient?

* What are the extremes (min & max charges)?

* How much variation (std. dev) exists in patient costs?

## 🛠️ Tools Used:
SQL (aggregation, grouping, CTEs, KPIs, CASE statements)

Tableau (interactive dashboarding, KPI cards, maps, bar/line/scatter plots)


## 📈 Results:
Population Overview (KPIs)

* The average medical cost per person is $X,XXX, with charges ranging from $MIN to $MAX.

* The standard deviation of ~$Y,YYY indicates wide variability in patient expenses, suggesting high-risk outliers.

Lifestyle Factors

* Smokers pay Z% more on average than non-smokers, making smoking the strongest individual cost driver.

* Obese patients (BMI ≥ 30) spend $X,XXX more on average compared to those with a healthy BMI range (18.5–24.9).

Age & Life Stage

* Costs increase gradually in early adulthood but accelerate after age 50, peaking in the senior group (60+).

* The middle-age group (45–59) shows the steepest rise in average charges, signaling the onset of chronic conditions.

Family Burden

* Families with children tend to spend more, though the increase is not linear — e.g., costs plateau beyond 3+ children, suggesting risk-sharing within households.

Regional Disparities

* The Southeast records the highest average charges, likely due to higher prevalence of obesity and smoking.

* The Northeast shows comparatively lower charges, reflecting possible differences in healthcare access or lifestyle factors.
