# PROJECT SUMMARY - Big Data Mining and Analytics

**Student:** Seth Mbasha  
**Student ID:** S22B23/010, A99501  
**Course:** DSC3108 - Data Mining and Analytics  
**Program:** BSCS (Bachelor of Science in Computer Science)

---

## Overview

This repository contains coursework for a Big Data Mining and Analytics course, including assignments, practical exercises, tests, and exploratory data analysis projects. The work demonstrates proficiency in data preprocessing, exploratory data analysis (EDA), statistical analysis, classification mining, and text mining.

---

## ASSIGNMENTS

### Assignment 1: Data Transformation and Analysis
- **File:** `Assignment1/assignment.ipynb`
- **Dataset:** CellPhone_Data.csv
- **Topics Covered:**
  - Data transformation to exclude inconsistencies
  - Relationship analysis between continuous variables (front camera vs primary camera megapixels)
  - Statistical correlation analysis (correlation coefficient: 0.645716)
  - Visual representation of data relationships
  - Export of transformed dataset

**Key Finding:** Medium positive relationship between front camera and primary camera megapixels, suggesting phones with higher primary camera megapixels tend to have higher front camera megapixels.

---

### Assignment 2: Heart Disease Analysis
- **File:** `Assignment2.ipynb`
- **Dataset:** Assignment2.csv (Ass2Data.csv)
- **Student ID Submissions:** S22B23/010, A99501
- **Topics Covered:**
  - Statistical hypothesis testing
  - ANOVA testing for continuous variables
  - Chi-square testing for categorical variables
  - Outlier analysis (outliers constitute >30% of data, retained for analysis)
  - Association testing between health indicators

**Research Questions:**
1. Are BMI, DiffWalking, AgeCategory, PhysicalActivity, and GenHealth key indicators for HeartDisease?
   - **Result:** Yes, all variables showed significant associations (p-value ≈ 0)
   
2. Is there an association between AgeCategory and GenHealth?
   - **Result:** Yes, statistically significant association confirmed

3. What is the association between GenHealth across different age categories?
   - **Result:** Significant variation identified through statistical testing

---

### Assignment 3: Advanced Statistical Analysis
- **File:** `assignment3.ipynb`
- **Student:** Seth Mbasha, S22B23/010 A99501 BSCS
- **Topics Covered:**
  - Outlier analysis and retention decisions
  - ANOVA testing methodology
  - Chi-square tests for categorical values
  - Statistical reasoning for data quality decisions

**Key Decision:** Retained outliers due to dataset size constraints and potential analytical value

---

## PRACTICAL EXERCISES

### Practical 1: Data Pre-processing
- **File:** `Practical1_Pre-processing.ipynb`
- **Topics Covered:**
  - Importing Excel datasets using Pandas
  - Handling missing information
  - Data cleaning strategies:
    - Mode replacement for categorical data
    - Mean/median replacement for quantitative data (based on distribution)

---

### Practical 2: Data Pre-transformation
- **Files:** `Practical2_Pre-transformation.ipynb`, `Practical2_Pre-transformation2.ipynb`
- **Topics Covered:**
  - Advanced data transformation techniques
  - Data normalization and standardization
  - Feature engineering

---

### Practical 5: Classification Mining
- **File:** `Practical5_Classification_Mining.ipynb`
- **Dataset:** Bike_Sales.xlsx
- **Topics Covered:**
  - Supervised machine learning algorithms
  - Decision Tree Classifier
  - Train-test split (70-80% training, 20-30% testing)
  - Model evaluation metrics (target accuracy >75%)
  - Gini index for split quality evaluation

**Objective:** Create a classifier model to predict Age_Group from Bike Sales data

**Models Saved:**
- `DecisionTreeModel.pkl`
- `DecisionTreeModel.joblib`
- `GaussianNBModel.joblib`

---

### Practical 7/8: Text Mining and Exploratory Data Analysis
- **File:** `Practical 8_Text Mining.ipynb`
- **Topics Covered:**
  - Text data cleaning
  - Removing anomalies (stop words, punctuation, special characters)
  - Natural language processing techniques
  - Text mining for insights extraction

---

## TESTS

### Test 1: Student Performance Analysis
- **File:** `Test1/Test1.ipynb`
- **Datasets:** 
  - Students.csv
  - healthcare_dataset.csv
  - World Largest Cities by Population 2024.csv
  - democracy-eiu.csv

**Research Question:** Understanding factors that statistically affect a student's "Target" in the education system

**Methodology:**
- Dython library for Cramer's V association analysis
- ANOVA testing for continuous variables
- Comprehensive correlation analysis

**Key Findings:** 24+ variables significantly correlated with student Target, including:
- Academic factors: Application mode/order, admission grade, previous qualifications
- Family background: Mother's/Father's qualification and occupation
- Performance metrics: Curricular units (enrolled, approved, grades) for both semesters
- Economic factors: Unemployment rate, GDP

---

## EXPLORATORY DATA ANALYSIS PROJECTS

### EDA 1: Bicycle Sales Analysis
- **File:** `EDA_bicycle.ipynb`
- **Dataset:** Bike_Sales.xlsx
- Focus on sales patterns and customer demographics

### EDA 2: General Exploratory Analysis
- **Files:** 
  - `Exploratory Data Analysis.ipynb`
  - `Exploratory_Data_Analysis.ipynb`
  - `Second_EDA.ipynb`
  - `secondEDA.ipynb`
  - `Week4- Exploratory Data Analysis.ipynb`
  - `Lecture3_EDA.ipynb`
- Various datasets analyzed for patterns and insights

### SolPaper: Gender Pay Gap Analysis
- **File:** `SolPaper.ipynb`
- **Topics Covered:**
  - Gender pay gap analysis using suitable visuals
  - Anomaly detection (missing values, duplicates)
  - Outlier analysis (27.5% of samples identified as outliers)
  - Comparative analysis with and without outliers
  - Data transformation strategies

**Data Quality Issues Addressed:**
- 33 missing samples in Grade variable
- 617 duplicate records
- Outlier retention for analytical insights

---

## OTHER PROJECTS

### In-Class Assignment
- **File:** `In_class assignment.ipynb`
- Quick exercises and problem-solving during lectures

### NotGraded Assignment
- **File:** `NotGraded S22B23010.ipynb`
- Practice exercises for skill development

### Web Scraping
- **File:** `webscrapping.ipynb`
- Introduction to web data extraction techniques

### Big Data Processing
- **File:** `bigData.ipynb`
- Large-scale data processing techniques

---

## DATASETS USED

### Main Datasets:
- CellPhone_Data.csv (Assignment 1)
- Ass2Data.csv / Assignment2.csv (Heart Disease data)
- Bike_Sales.xlsx (Classification Mining)
- Students.csv (Education analysis)
- healthcare_dataset.csv
- Traffic_Data.csv
- Train.csv
- Iris.csv
- Female_Mps.csv
- DiamondPricesData.csv
- academic_food_data.csv/xlsx
- Student_performance.xlsx / studentperfomance.xlsx
- Cassava_Yield_Data.xlsx
- Data_Mining_Sample_data_generated.xlsx
- ida_credits.csv
- Dec11.sav
- DataForML.pkl

---

## SKILLS DEMONSTRATED

### Statistical Analysis:
- ANOVA testing
- Chi-square tests
- Correlation analysis
- Hypothesis testing
- Cramer's V association

### Data Processing:
- Data cleaning and preprocessing
- Missing value imputation
- Outlier detection and handling
- Data transformation
- Feature engineering

### Machine Learning:
- Supervised learning (Classification)
- Decision Trees
- Gaussian Naive Bayes
- Model evaluation
- Train-test splitting

### Visualization:
- Exploratory data visualization
- Statistical graphics
- Comparative analysis charts

### Programming & Tools:
- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebooks
- Statistical libraries (Dython)
- Machine learning frameworks

---

## LEARNING OUTCOMES

1. **Data Preprocessing:** Mastered techniques for cleaning, transforming, and preparing data for analysis
2. **Statistical Testing:** Applied various statistical tests to validate hypotheses and find associations
3. **Machine Learning:** Developed and evaluated classification models with appropriate metrics
4. **Critical Thinking:** Made informed decisions about outlier retention and data quality
5. **Text Mining:** Learned natural language processing and text data cleaning
6. **Exploratory Analysis:** Conducted comprehensive EDA to derive insights from multiple datasets
7. **Research Skills:** Formulated and tested research questions using appropriate methodologies

---

## REPOSITORY STRUCTURE

```
Big-Data-Mining-and-analytics/
├── Assignment1/                 # Assignment 1 files
├── Test1/                       # Test 1 files
├── Practical5_Classification_Mining/  # Practical 5 files
├── *.ipynb                      # Various Jupyter notebooks
├── *.csv, *.xlsx, *.sav        # Multiple datasets
├── *.pkl, *.joblib             # Saved machine learning models
└── *.zip                        # Submission archives
```

---

## CONCLUSION

This repository represents comprehensive coursework in Big Data Mining and Analytics, covering the full data science pipeline from data collection and preprocessing through analysis, modeling, and interpretation. The work demonstrates strong analytical skills, statistical reasoning, and practical application of machine learning techniques to real-world datasets.

**Total Projects:** 15+ individual assignments, practicals, and tests  
**Primary Focus Areas:** Statistical Analysis, Machine Learning, Data Preprocessing, Exploratory Data Analysis  
**Academic Performance:** Completed assignments with detailed analysis and justification of methodological choices
