# DonorsChoose
DonorsChoose.org is an online charity that makes it easy to help students in need through school donations. At any time, thousands of teachers in K-12 schools propose projects requesting materials to enhance the education of their students. When a project reaches its funding goal, they ship the materials to the school. the goal is to identify projects that are exceptionally exciting to the business, at the time of posting. While all projects on the site fulfill some kind of need, certain projects have a quality above and beyond what is typical. By identifying and recommending such projects early, Donor’s Choose will improve funding outcomes, better the user experience, and help more students receive the materials they need to learn. The data for this case study is provided in the form of csv files. There are in total 3 files:

1.essays.csv: contains project text posted by teachers.
2.projects.csv: contains information about each project
3.outcomes.csv: contains information about the outcomes of projects

Any project posted before 2014-01-01 is in the training set (along with its funding outcomes). Any project posted after that is in the test set.

Following are the requirements for this case study:
1.Data Audit report and code used to create the data audit report. 
2.Feature engineering on text 
3.the model should be built to predict if a project is exciting.
4.AUC reported on five-fold CV and The AUC should be reported in the following format in a csv file: 
Fold, AUC 1,Value 2, Value 3,Value 4,Value 5,Value

