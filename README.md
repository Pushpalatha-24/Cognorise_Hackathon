High School Students Exam Score PredictionHackathon Overview 🏆

This project was developed as part of the CognoRise Hackathon. It involves predicting high school students' exam scores using machine learning techniques. The dataset includes features related to students' performance and demographics.Dataset 📂
The dataset is divided into two files:train.csvThis file contains the training data used to build the machine learning model.

 It includes the following columns:
 Roll no: The student's roll number (identifier) 
 🎫test preparation : Whether the student completed a test preparation course (yes/no) 📚
 gender: The gender of the student (male/female) 🚻
 parental level of education: The highest level of education attained by the student's parent(s) or guardian(s) 🎓
 lunch: Whether the student receives free or reduced-price lunch (yes/no) 🍽️
 Section: The student's class section 🏫
 practical score: The student's score on a standardized practical test 📝
 viva score: The student's score on a standardized viva-voce test 🎤
 exam score: The target variable representing the student's score on a standardized exam test 🏆
 ***test.csv
 This file contains the test data for which predictions are to be made. 
 It includes the following columns:
 Roll no: The student's roll number (identifier) 🎫
 test preparation : Whether the student completed a test preparation course (yes/no) 📚
 gender: The gender of the student (male/female) 🚻
 parental level of education: The highest level of education attained by the student's parent(s) or guardian(s) 🎓
 lunch: Whether the student receives free or reduced-price lunch (yes/no) 🍽️
 Section: The student's class section 🏫practical score: The student's score on a standardized practical test 📝
 viva score: The student's score on a standardized viva-voce test 🎤
 exam score: The target variable to be predicted (this column is not present in the test dataset) 🏆
 ***Requirements:
 📋To run this project, you need Python 3.x and the following libraries:
 pandas
 scikit-learn
 
 ##Example Output 📊

The submission.csv file will contain:
- Roll no: The student's roll number.
- exam score: The predicted exam score.

| Roll no | exam score |
|---------|------------|
| 1       | 85         |
| 2       | 78         |
| ...     | ...        |

## Acknowledgements 🙏

- This project was part of the CognoRise Hackathon.
- Special thanks to the organizers and mentors who supported this challenge.
