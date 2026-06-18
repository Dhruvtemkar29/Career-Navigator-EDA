# Machine Learning Lab 02 - Dataset Normalization Techniques

## Program

M.Sc Artificial Intelligence & Machine Learning (AIM)

## Lab Exercise 2

Preprocessing the Dataset Using Normalization Techniques

---

## Objective

To apply different normalization techniques on an Education and Career Success dataset and analyze their impact on numerical attributes. The objective is to prepare the dataset for machine learning algorithms by transforming features into comparable scales.

---

## Dataset Information

### Domain

Education Analytics and Career Success Analysis

### Dataset

Education and Career Success Dataset

### Records

400

### Attributes

19

### Numerical Features

* Age
* High_School_GPA
* SAT_Score
* University_GPA
* Internships_Completed
* Projects_Completed
* Certifications
* Soft_Skills_Score
* Networking_Score
* Job_Offers
* Starting_Salary
* Career_Satisfaction
* Years_to_Promotion
* Work_Life_Balance

### Categorical Features

* Student_ID
* Gender
* Field_of_Study
* Current_Job_Level
* Entrepreneurship

---

## Tasks Performed

### Data Understanding

* Dataset Inspection
* Feature Identification
* Data Type Analysis

### Data Quality Assessment

* Missing Value Detection
* Duplicate Record Detection
* Data Consistency Verification

### Normalization Techniques

#### Min-Max Normalization

Scaled numerical attributes between 0 and 1 using MinMaxScaler.

#### Z-Score Normalization

Standardized numerical attributes using StandardScaler to achieve:

* Mean ≈ 0
* Standard Deviation ≈ 1

---

## Visualizations

### Before and After Normalization

* Histogram Comparison
* Box Plot Comparison
* Line Plot Comparison
* Bar Plot Comparison
* Correlation Heatmap Comparison

---

## Key Findings

* Feature scale imbalance was successfully removed.
* Min-Max Normalization transformed values into the range [0,1].
* Z-Score Standardization standardized feature distributions.
* Correlation relationships remained unchanged after normalization.
* Normalization improved dataset suitability for machine learning models.
* Z-Score Normalization was found to be more suitable due to varying feature ranges.

---

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

---

## Future Scope

The normalized dataset can be used for:

* Career Success Prediction
* Employability Analysis
* Salary Prediction
* Job Offer Prediction
* Workforce Readiness Analytics
* Career Navigator Platform Development

---

## Author

Dhruv
M.Sc AIM
Machine Learning Laboratory
