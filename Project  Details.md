FitTrack – Daily Fitness Tracker

---

Project Title

FitTrack – Daily Fitness Tracker

---

Problem Statement

Many people do not regularly track their daily physical activities and workouts. As a result, they may struggle to maintain fitness goals, monitor progress, and stay motivated. A Daily Fitness Tracker helps users record workouts, track calories burned, monitor fitness progress, and maintain a healthier lifestyle.

---

Project Objectives

- Maintain daily workout records efficiently.
- Track exercise duration and calories burned.
- Monitor fitness progress in real time.
- Generate weekly and monthly fitness reports.
- Encourage healthy lifestyle habits.
- Improve motivation and consistency in fitness routines.

---

Technologies Used

Front End

- HTML
- CSS
- JavaScript

Back End

- Python (Flask/Django)

Database

- MySQL

---

Modules

- User Management
- Exercise Management
- Workout Tracking
- Calorie Calculation
- Progress Monitoring
- Goal Management
- Report Generation

---

Database Tables

User

Field Name| Data Type
user_id| INT
username| VARCHAR
password| VARCHAR
age| INT
gender| VARCHAR

---

Exercise

Field Name| Data Type
exercise_id| INT
exercise_name| VARCHAR
category| VARCHAR
calories_per_hour| DECIMAL

---

Workout

Field Name| Data Type
workout_id| INT
user_id| INT
exercise_id| INT
duration| INT
workout_date| DATE

---

Fitness Goal

Field Name| Data Type
goal_id| INT
user_id| INT
goal_type| VARCHAR
target_value| INT
target_date| DATE

---

Progress Report

Field Name| Data Type
report_id| INT
user_id| INT
total_workouts| INT
calories_burned| DECIMAL
report_date| DATE

---

Input Process

1. User registers and logs into the system.
2. User enters workout details.
3. User selects exercise type and duration.
4. User sets fitness goals.
5. System stores the data in the database.

---

Output Process

1. Display daily workout history.
2. Show calories burned for each workout.
3. Track weekly and monthly progress.
4. Generate fitness reports.
5. Display goal achievement status.

---

Features

- User Registration and Login
- Daily Workout Tracking
- Exercise Management
- Calorie Burn Calculation
- Fitness Goal Setting
- Progress Monitoring
- Weekly and Monthly Reports
- User-Friendly Dashboard

---

Expected Outcome

The system will provide an efficient platform for tracking daily fitness activities, monitoring workout progress, calculating calories burned, and helping users achieve their fitness goals through data-driven insights and reports.

---

Conclusion

The FitTrack – Daily Fitness Tracker improves fitness monitoring, encourages regular exercise, and helps users maintain a healthy lifestyle. It provides an organized and reliable solution for tracking workouts, managing fitness goals, and measuring overall progress.

---
