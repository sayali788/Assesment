This is a Python-based work that aims to analyze the quiz performance data of students using the **NEET Testline** app and provide personalized recommendations to improve their preparation. The recommendations are based on quiz results, accuracy, speed, and the student's historical performance.*Data Analysis:** Analyze quiz performance based on topics, difficulty levels, and accuracy.
Performance Insights:Produce insights that will indicate weak areas and improvement trends.
Personalized recommendations of topics, question types, and difficulty levels to concentrate on.
Student Persona:Define student personas such as "High Performer" and "Low Performer."Required libraries: `pandas`, `requests`, `matplotlib`, `seaborn`, `scikit-learn`, `wordcloud
1. Data Collection:
- The project uses quiz performance data, with two main datasets:
- Current Quiz Data: Data from the most recent quiz attempt by the student.
- Historical Quiz Data: Data from the last 5 quiz attempts.

2. Data Cleaning and Preprocessing:
- The duration data is cleaned to convert it into a usable format (minutes).
- Manage missing values and data inconsistencies, especially in accuracy and score fields.

3. Data Analysis:
Analyze the student's performance in depth to identify trends.
Determine weak and strong topics based on student accuracy.

4. Student Persona Generation:
Generate personas such as "High Performer" and "Low Performer" based on accuracy and performance trends.

5. Personalized Recommendations:
Based on the weaknesses identified for the student, suggest concentrating on specific areas or types of questions.
