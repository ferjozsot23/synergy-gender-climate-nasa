# synergy-gender-climate-nasa
---

# README

## Project Title: Gender Inequality and Climate Change Correlation Analysis

### Overview

This project consists of two Jupyter Notebooks that analyze the relationship between the **Gender Inequality Index (GII)** and the **Climate Change Index (CCI)**. The goal is to explore the correlations between gender inequality and climate change across different countries from LatinAmerica, identifying patterns and insights that can inform policy decisions. The project uses the following datasets:

- **Dataset 1**: Gender Inequality Index (GII)
- **Dataset 2**: Climate Change Index (CCI) - Created by ourselfs
- **Dataset 3**: Socioeconomics dataset

Each notebook contains a thorough analysis of the respective dataset and evaluates correlations between the indicators.

---

### Notebooks

#### 1. **Notebook 1: Correlations Analysis**

This notebook focuses on exploring the Gender Inequality Index, Climate change index and socioeconomics dataset, which contains indicators related to gender disparities in health, education, and economic status across Latam countries.

**Key Steps:**
- **Data Loading**: Load and preprocess the GII dataset, including handling missing values and normalization.
- **Exploratory Data Analysis (EDA)**: Visualize and summarize the distribution of gender inequality indicators.
- **Statistical Correlation**: Calculate the correlations between gender inequality metrics to identify which factors are most strongly associated with gender disparities.
- **Key Results**: Highlight the countries with the highest and lowest levels of gender inequality and climate change.

RESULTS:

![image](https://github.com/user-attachments/assets/9766c6fb-11e4-47d8-b147-9033da76f6c0)

![image](https://github.com/user-attachments/assets/c2de0a50-abde-4f83-9c75-5fd1413360ff)

![image](https://github.com/user-attachments/assets/020ceb38-5761-4c90-9a47-9bacc04c95ed)


#### 2. **Notebook 2: Climate Change Index (CCI) creation**

This notebook creates the Climate Change Index, which includes metrics like CO2 emissions, energy consumption, and climate-related displacement. The goal is to understand how climate factors vary across Latam countries and creating and index from this.

**Key Steps:**
- **Data Loading**: Load and preprocess the CCI dataset, performing necessary data cleaning and normalization.
- **Exploratory Data Analysis (EDA)**: Explore the key climate-related indicators through visualizations and summary statistics.
- **Key Results**: Get a climate change index

---


### How to Run

1. Clone or download the project repository to your local machine.
2. Ensure you have Python and Jupyter installed.
3. Install the necessary dependencies by running:

   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook and open each notebook.

5. Follow the analysis in each notebook step by step. Both notebooks contain inline comments explaining each step.
6. Ensure you upload the following datasets like:
   df_cci.xlsx for Climate_change_index notebook
   gender-development index.csv and nasa_1.xlsx for Correlations notebook

---

### Dependencies

The following Python libraries are used in the notebooks:

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.
- **matplotlib**: For data visualization.
- **seaborn**: For creating advanced visualizations and correlation heatmaps.

You can install all dependencies via `pip` using the provided `requirements.txt` file.

---

### Results and Insights

The final section of the analysis combines the two datasets and demonstrates that:
- Countries with higher levels of gender inequality tend to have lower climate resilience, particularly in areas such as access to resources and environmental degradation.
- Specific climate factors like water scarcity and deforestation are more strongly correlated with gender disparities in education and economic participation.

The project concludes with recommendations for integrating gender-sensitive approaches into climate policies, particularly in Latin America, to address both social and environmental challenges.

---

### Future Work

This project can be extended by:
- Incorporating additional datasets, such as economic inequality or health vulnerability indices.
- Developing machine learning models to predict future trends in gender inequality and climate vulnerability.
- Integrating real-time data from NASA's Earthdata for dynamic analysis.

---

