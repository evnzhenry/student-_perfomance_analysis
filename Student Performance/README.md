Student Performance Analysis

This project helps you understand and predict student performance using real data from the UCI Student Performance Dataset. 


Project Overview

This project performs a complete analysis of student performance data including:

- Part A: Data Loading & Preprocessing
- Part B: First EDA  
- Part C: Feature Engineering 
- Part D: Second EDA & Statistical Inference
- Part E: Simple Machine Learning


Analysis Components

Part A: Data Loading & Preprocessing
- Load dataset and inspect columns
- Encode categorical variables (school, sex, parental education, etc.)
- Scale numeric features (grades, study time, absences)
- Check for missing values and handle them

Part B: First EDA
- Descriptive stats for grades and study time
- Distribution plots (histograms) for grades
- Bar charts: parental education vs average grade
- Correlation heatmap for continuous features
- Discussion of features that might influence final grade

Part C: Feature Engineering
- Compute average of G1 and G2 to predict G3
- Categorize students as pass/fail based on G3 cutoff (10/20)
- Create combined features: study_time × absences, failures × absences
- Discuss rationale for each feature

Part D: Second EDA & Statistical Inference
- ANOVA: Does study time significantly affect final grade?
- Chi-square test: Association between internet access and pass/fail
- Visualize results: boxplots, bar charts with significance annotations

Part E: Simple Machine Learning
- Split data into train/test sets
- Train models: Decision Tree, Logistic Regression
- Evaluate: Confusion matrix, Accuracy, Precision, Recall, ROC curve
- Compute standard deviation of metrics across cross-validation folds
- Report mean ± std format for all metrics


Output Files

The analysis generates several visualization files:

- `part_b_first_eda.png` - Initial exploratory data analysis
- `part_d_statistical_inference.png` - Statistical test results
- `part_e_machine_learning.png` - ML model performance
- `executive_summary.png` - Comprehensive summary visualization

Key Features

Statistical Analysis
- ANOVA testing for study time impact on grades
- Chi-square testing for categorical associations
- Correlation analysis for feature relationships

Machine Learning
- Cross-validation with 5-fold stratified sampling
- Multiple metrics with standard deviations
- Feature importance for analysis
- ROC curve for comparison
  
What Does This Project Do?

- Loads student data (grades, study time, family info, etc.)
- Cleans and prepares the data for analysis
- Shows you patterns in grades and study habits
- Creates new helpful features (like average grades and pass/fail status)
- Tests important questions (like: does study time really matter?)
- Builds prediction models to guess which students might pass or fail
- Summarizes key findings and gives recommendations
- Discusses ethical issues (like fairness and privacy)


How Does It Work?

1. Data Loading:  
   The program reads the student data file and shows you what’s inside.

2. Data Cleaning:  
   It checks for missing info and fixes it, then turns words into numbers so computers can understand.

3. Exploring the Data:  
   You’ll see charts and stats about grades, study time, and family background.  
   Example: Are students with more study time getting better grades?

4. Feature Engineering:  
   The program creates new columns, like:
   - Average of first two grades
   - Pass/fail status (did the student get at least half marks?)
   - Combined effects (like study time × absences)

5. Statistical Testing:  
   It answers questions like:
   - Does study time really affect grades? (Yes!)
   - Is having internet at home linked to passing? (Yes!)

6. Machine Learning:  
   The program builds smart models to predict who will pass or fail, using patterns in the data.

7. Results & Insights:  
   You get easy-to-read tables and colorful charts showing:
   - Which factors matter most
   - How well the models predict
   - What can be done to help students succeed

8. Ethical Reflection:  
   The program reminds you to be careful with student data, avoid unfairness, and respect privacy.


What Will You See?

- Charts showing grade distributions, study habits, and family effects
- Tables comparing prediction models
- Lists of the most important factors for student success
- Recommendations for helping students (like more study support or attendance tracking)
- Warnings about using data responsibly


How To Use

1. Download the dataset:  
   Get `student-mat.csv` or `student-por.csv` from [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance).

2. Run the script:  
   Open the code in VS Code and run:
   analyzer.run_complete_analysis('student-mat.csv')

3. Check the results:
   Look for PNG files with charts and read the printed insights and recommendations.

Why Is This Useful?

- Teachers: Spot students who need help early
- Schools: Design better support programs
- Parents: Understand what helps kids succeed
- Students: Learn what habits matter most


Ethical Reminders

- Don’t use predictions to label or judge students unfairly.
- Protect student privacy and get consent before using data.
- Use these insights to help, not to punish.

