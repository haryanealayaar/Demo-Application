Student Performance Analysis:-

This data set consists of the marks secured by the students in various subjects. Here we will try to understand the influence of the parents background, test preparation etc on students performance. Also we will try to analyze is there are any socio-economic pattern that could affect students to perform better on the exam.

Kaggle Dataset Link: https://www.kaggle.com/spscientist/students-performance-in-exams


Student Performance Indicator Project
This project explores how different factors affect student test scores. I look at things like:

Gender: Are there differences in scores between male and female students?

Race/Ethnicity: Does a student's racial or ethnic background play a role?

Parental Education: Does the level of education of a student's parents matter?

Lunch: Does having a standard lunch or a free/reduced lunch affect scores?

Test Preparation: Does taking a test preparation course make a difference?

Scores: I analyze math, reading, and writing scores.


* What I did:-

1. Loaded the data: I started by loading the student data from a CSV file.

2. Checked the data: I looked for missing information and duplicates to make sure the data was clean. We also checked the types of data (like numbers or text) and how many unique values were in each column.

3. Calculated scores: I added up the math, reading, and writing scores to get a total score and then calculated the average score for each student.

4. Visualized the data: I created charts to see how the average scores were distributed and how they related to different factors like gender, lunch type, and parental education.

5. Built a model: I used the data to build a machine learning model that can predict student performance based on the other factors.

6. Evaluated the model: We checked how well our model made predictions.


* Key Findings:

1. Female students tended to perform better than male students on average.

2. Students who had a standard lunch generally performed better on exams.

3. Parental education seemed to have less impact on female students' performance, but male students with parents who had associate's or master's degrees tended to perform better.

4.  Math, reading, and writing scores are highly correlated with each other.
   

* How to use this project:-
  
You can run the code in this notebook to see how we performed the analysis and built the model. The code includes steps for data loading, cleaning, visualization, and model training.
