# preptrack-jakeer
PrepTrack - Placement Preparation Performance Analyzer
## Project Features

- Student information validation
- Attendance validation
- Project and profile verification
- Seven-day practice score processing
- Average score calculation
- Placement eligibility evaluation
- Final report generation

## ✨ Features Implemented

- Student profile input collection
- Student name validation
- Attendance percentage validation
- Project completion validation
- Profile verification validation
- Seven-day coding practice processing
- Practice score validation
- Absent day handling using `continue`
- Score classification (Strong, Satisfactory, Needs Improvement, Critical)
- Passed and failed practice counting
- Highest score detection
- Lowest score detection
- First critical score identification
- Total score calculation
- Average score calculation
- Placement readiness evaluation
- Final status and next action generation
- Complete performance report generation
  
## 🛠 Python Concepts Used

The project is implemented using the following Python concepts:

- Variables and meaningful variable names
- Input using `input()`
- Type conversion using `int()` and `float()`
- Arithmetic operators
- Assignment operators
- Relational operators
- Logical operators
- Boolean variables and Boolean expressions
- Formatted output using f-strings
- `if`, `elif`, and `else` statements
- Nested and compound conditions
- `while` loops
- `for` loops with `range()`
- `break` statement
- `continue` statement
- Counters and accumulator variables
- Input validation
- Performance classification
- Highest and lowest score tracking
- Average score calculation
- Placement readiness evaluation
  
## ▶️ How to Run

1. Clone this repository.
2. Open the project in AntiGravity IDE or any Python IDE.
3. Open the terminal in the project folder.
4. Run the following command:

```bash
python main.py
```

If your system uses Python 3:

```bash
python3 main.py
```

5. Enter the required student details and coding practice scores.
6. The application will generate the complete PrepTrack performance report.

## 📋 Test Result Summary

| Test ID | Scenario | Expected Result | Actual Result | Status |
|---------|----------|-----------------|---------------|--------|
| TC-01 | All requirements satisfied | Ready for Mock Interview | Ready for Mock Interview | ✅ Passed  |
| TC-02 | Critical score present | Critical Support Required | Not Eligible (Critical score found) | ✅ Passed |
| TC-03 | Fewer than six attempts | Practice Incomplete | Not Eligible (Less than 6 attempts) | ✅ Passed |
| TC-04 | Fewer than four passed days | Insufficient Passed Practices | Not Eligible (Less than 4 passed days) | ✅ Passed  |
| TC-05 | Average below 70 | Practice Improvement Required | Not Eligible (Average below 70) | ✅ Passed |
| TC-06 | Attendance below 75 | Attendance Improvement Required | Not Eligible (Attendance below 75%) | ✅ Passed |
| TC-07 | Graduation year not eligible | Graduation Criteria Not Met | Not Applicable (Input validation prevents invalid graduation year) | ✅ Passed |
| TC-08 | Project incomplete | Application On Hold | Not Eligible (Project incomplete) | ✅ Passed |
| TC-09 | Profile not verified | Application On Hold | Not Eligible (Profile not verified) | ✅ Passed |
| TC-10 | All practice days absent | Practice Not Evaluated | Not Eligible (No practice attempted) | ✅ Passed |
| TC-11 | Invalid score below -1 | Input Rejected | Invalid input message displayed | ✅ Passed |
| TC-12 | Invalid score above 100 | Input Rejected | Invalid input message displayed | ✅ Passed |
| TC-13 | Boundary value testing | Correct Classification | Boundary values classified correctly | ✅ Passed |
| TC-14 | Multiple blockers | First Major Blocker Displayed | Not Eligible (Critical score found) | ✅ Passed |

## 👨‍💻 Individual Contribution

**Name:** Mohammed Jakeer F Maniyar

**Role:** Team Lead

**Repository URL:**  
https://github.com/maniyarjakeer0209-source/preptrack-jakeer

**My Main Contribution:**
- Coordinated the team throughout the project.
- Maintained the team repository directory.
- Tracked repository creation and submission status.
- Guided team members in understanding the project requirements.
- Developed my own version of the PrepTrack application.

**Features I Implemented:**
- Student input collection
- Input validation
- Practice score processing
- Placement readiness evaluation
- Final report generation

**Python Concepts Used:**
- Variables
- Loops
- Conditional Statements
- Boolean Expressions
- Counters and Accumulators

**Most Difficult Logic:**
- Placement readiness evaluation and final status priority.

**Problem Faced:**
- Understanding the complete project flow and organizing the program logic.

**How I Solved It:**
- Carefully studied the PRD, followed the project flow step by step, and tested the application with different scenarios.

## Team Lead

Mohammed Jakeer F Maniyar

## Team Members

| Member | GitHub Repository | Status |
|--------|-------------------|--------|
| Jakeer | https://github.com/maniyarjakeer0209-source/preptrack-jakeer | ✅ Completed |
| Sai Shivangi T | https://github.com/saishivangi/preptrack-saishivangi | ✅ Completed |
| M.Aravind | https://github.com/Aravind118-D/preptrack-Aravind | ✅ Completed |
| Yaparla Usharani | https://github.com/usharani-9391/preptrack-usha | ✅ Completed |
| Pardhu | https://github.com/pardhueemana/preptrack-pardhu | ✅ Completed |
| Vaishnavi Cp |https://github.com/gombea/Preptrackvaish | ✅ Completed |
| Bogala Murali Krishna Reddy | https://github.com/MURALIKRISHNA2004/preptrack-murali | ✅ Completed |
|V Neha Likhita |https://github.com/nehalikhitav/preptrack-NehaLikhita/tree/main | ✅ Completed |
| Ambati Sankarsai |https://github.com/sankar-a7/preptrack-sankarsai | ✅ Completed |
| Lohitha  |https://github.com/nlohitha97/preptrack-lohitha | ✅ Completed |


