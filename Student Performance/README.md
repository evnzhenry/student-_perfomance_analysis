 Student Performance Analysis

This project helps you understand and predict student performance using real data from the UCI Student Performance Dataset. 


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
