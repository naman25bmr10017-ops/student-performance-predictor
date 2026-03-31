# student-performance-predictor

ML project to predict student marks

# Student Performance Predictor

This project is a simple machine learning application that predicts student marks based on daily habits like study hours, attendance, and sleep.

## Problem Statement

Students often do not understand how their daily routine affects their academic performance. This project helps in predicting marks based on study hours, attendance percentage, and sleep hours.

## Solution

A linear regression model is used to learn patterns from student data and predict marks for new inputs provided by the user.

## Technologies Used

* Python
* Pandas
* Scikit-learn

## Project Structure

student-performance-predictor/
│
├── data/student_data.csv
├── src/model.py
├── requirements.txt
├── README.md

## Installation and Setup

Follow these steps to run the project on your system:

1. Clone the repository
   [git clone](https://github.com/naman25bmr10017-ops/student-performance-predictor)

2. Go to the project folder
   cd student-performance-predictor

3. Install required libraries
   pip install -r requirements.txt

4. Run the program
   cd src
   python model.py

After running, the program will ask you to enter:

* Study hours per day
* Attendance percentage (0 to 100)
* Sleep hours per day

Then it will show the predicted marks.

## How It Works

* The model is trained using sample student data
* The user enters study hours, attendance, and sleep hours
* The model predicts the expected marks

## Example Input

* Study hours: 6
* Attendance: 80
* Sleep hours: 7

## Output

Predicted Marks: around 70

## Learning Outcomes

* Basic understanding of machine learning
* Working with datasets using pandas
* Building a linear regression model
* Taking user input in Python
  
