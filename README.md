## Code-501-Data-Analysis-with-Python
Assignments for Code 501 at Code Fellows

## 1. Code 501 Final Project
### Data analysis and visualization of 2016 New Coder Survey
* A survey of 15,000+ people who are actively learning to code, 48 questions
* Surveyed by Free Code Camp and CodeNewbie.org
* Data source: kaggle.com/freecodecamp/2016-new-coder-survey-

* Utilyzed NumPy and Pandas to explore demographics of the survey participants: income, age, gender, country of residence, 
  bootcamp attendance and programming experience
* Performed t-Test to assess the difference in age and income between male and female survey participants
* Utilized Scikit-Learn (k - nearest neighbors algorithm) to create a prediction model for gender of participants based on columns such as
  'Income', 'Age', and 'CountryLive'. Compared accuracy of prediction for 4 created models.

### To contribute to the project:
* create a virtual environment in your working directory and activate it
```
$python3 -m venv .
$source bin/activate
```
* fork the repo and clone it to your working directory
* install the requirements
```
$pip install requirements.txt
```
* download the dataset from kaggle.com/freecodecamp/2016-new-coder-survey-
* make sure '2016-FCC-New-Coders-Survey-Data.csv' is in the same folder as 'Code_501_final_project.ipynb'

