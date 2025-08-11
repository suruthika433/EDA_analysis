# 📊 Exploratory Data Analysis (EDA) - Titanic Dataset

## **Objective**
The goal of this project is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset to extract meaningful insights using both visual and statistical methods.

---

## **Tools Used**
- **Python**
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization

---

## **Dataset**
- **Source:** Titanic Dataset (CSV format)
- **Description:** Contains details of passengers such as age, gender, ticket class, fare, and survival status.

---

## **Project Steps**
1. **Import Required Libraries**  
   Load Pandas, Matplotlib, and Seaborn.

2. **Load the Dataset**  
   Read the Titanic CSV file into a Pandas DataFrame.

3. **Basic Data Exploration**  
   - Use `.describe()` for summary statistics  
   - Use `.info()` to check data types and missing values  
   - Use `.value_counts()` for categorical variables

4. **Data Visualization**  
   - **Pairplot** to explore relationships  
   - **Heatmap** for correlation matrix  
   - **Boxplots** and **Countplots** for categorical relationships  
   - **Histograms** for distribution analysis  
   - **Scatter plots** for numeric relationships

5. **Observations**  
   Record findings after each visualization.

6. **Summary of Findings**  
   Provide overall insights based on the analysis.

---

## **Key Insights**
- Females had a higher survival rate than males.
- Higher-class passengers (Pclass 1) had better survival chances.
- Younger passengers had slightly better chances of survival.
- Higher fares were generally associated with higher survival rates.

---

## **Deliverables**
- **Jupyter Notebook** containing the complete analysis (`Titanic_EDA.ipynb`)
- **PDF/HTML report** generated from the notebook

---

## **How to Run**
1. Clone the repository or download the project folder.
2. Ensure Python and Jupyter Notebook are installed.
3. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
