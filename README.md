# Crime Data Analysis (2020 - Present)

This project focuses on the cleaning and analysis of real-world crime data from 2020 to the present, with a goal to uncover patterns and trends in California. The dataset underwent a thorough cleaning process to ensure its readiness for analysis. Exploratory Data Analysis (EDA) was conducted to reveal crime trends, seasonal patterns, high-crime areas, and other key insights.

---

## 1. Data Cleaning and Preparation

### 1.1 Data Acquisition
- The dataset was loaded using Python’s `pandas` library.
- It contains over **980,000 records** across **28 columns**, including crime type, dates, times, locations, victim details, and more.

### 1.2 Data Inspection
- Initial inspection included reviewing the structure and data types.
- Columns were categorized into categorical, numerical, and date fields.

### 1.3 Data Cleaning Process
1. **Handling Missing Data**  
   - Replaced invalid or unknown values in categorical columns.  
   - Removed rows where all values were missing.  

2. **Removing Duplicates**  
   - Verified no duplicate rows existed in the dataset.

3. **Converting Data Types**  
   - Converted `Date Rptd` and `DATE OCC` to `datetime` objects.  
   - Formatted `TIME OCC` into the `HH` format.

4. **Handling Outliers**  
   - Outliers in columns like `Vict Age` (e.g., values ≤ 0) were replaced with `NaN`.

5. **Normalization and Standardization**  
   - Standardized and normalized numerical fields like `Rpt Dist No` and `Premis Cd`.

---

## 2. Exploratory Data Analysis (EDA)

### 2.1 Crime Trends Over Time
- Analyzed yearly fluctuations in crime rates from 2020 to the present.

### 2.2 Seasonal Crime Patterns
- Identified that **January** experiences peak crime rates.

### 2.3 Most Common Types of Crimes
- **Top Crime Types:**  
  - `Vehicle - Stolen` (highest frequency).  
  - Followed by **Simple Assaults** and **Burglaries**.  
- Vehicle theft trends showed consistent patterns over the years.

### 2.4 Crime Rates by Region
- Areas like **Wilshire** and **Central** reported the highest crime rates.

### 2.5 Crime Rates by Location
- Streets showed higher concentrations of crimes compared to other locations.

### 2.6 Crime by Days of the Week
- Crimes occur more frequently on **weekends** (Friday and Saturday).  
- Vehicle thefts and simple assaults are most common on these days.

---

## 3. Advanced Analysis

### 3.1 Predictive Modeling
- Predictive models were used to forecast future crime trends.  
- **Insight:** Crime rates are predicted to significantly decrease, even showing negative values by 2025–2026.

---

## 4. Key Insights
- **Vehicle-related crimes** are the most prevalent, requiring targeted interventions.  
- **Geographic focus:** Areas like Wilshire and Central report consistently high crime rates.  
- **Weekly patterns:** Crimes peak on weekends, especially vehicle-related offenses.  
- Predictive analysis indicates a **downward trend** in crime rates in the near future.

---

## 5. Conclusion
The analysis highlights actionable insights for law enforcement and policymakers. By focusing on high-crime areas, addressing seasonal fluctuations, and targeting specific offenses (e.g., vehicle theft), more effective crime prevention strategies can be implemented.

---

## Technologies Used
- **Python Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Tools:** Jupyter Notebook, predictive modeling techniques.

---

## Future Enhancements
- Include more granular economic and demographic data for deeper analysis.
- Develop interactive dashboards for real-time crime monitoring and reporting.
