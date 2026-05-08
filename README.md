# Pandas_notes
🐼 Pandas Notes Repository
Welcome to the Pandas Notes Repository 🚀
This repository contains beginner to advanced notes, examples, and practice snippets for learning the powerful Python library Pandas used in Data Analysis and Data Science.
📌 About Pandas
Pandas is an open-source Python library used for:
Data Cleaning
Data Analysis
Data Manipulation
Handling CSV/Excel Files
Working with Tables & DataFrames
It is widely used in:
Data Science
Machine Learning
AI Projects
Business Analytics
📚 Topics Covered
🔹 Basics
Introduction to Pandas
Installing Pandas
Importing Pandas
Python
import pandas as pd
🔹 Series
Creating Series
Accessing Elements
Indexing
Operations on Series
Python
s = pd.Series([10, 20, 30])
print(s)
🔹 DataFrames
Creating DataFrames
Selecting Rows & Columns
Adding/Deleting Columns
Updating Data
Python
data = {
    "Name": ["Ram", "Sam"],
    "Marks": [90, 85]
}

df = pd.DataFrame(data)
print(df)
🔹 Reading Files
Python
df = pd.read_csv("data.csv")
Supported files:
CSV
Excel
JSON
🔹 Data Cleaning
Handling Missing Values
Removing Duplicates
Filling Null Values
Python
df.dropna()
df.fillna(0)
🔹 Filtering Data
Python
df[df["Marks"] > 80]
🔹 Sorting Data
Python
df.sort_values("Marks")
🔹 GroupBy Operations
Python
df.groupby("Department").sum()
🔹 Useful Functions
Function
Purpose
head()
First 5 rows
tail()
Last 5 rows
info()
Dataset information
describe()
Statistics summary
shape
Rows & columns count
🛠 Requirements
Install Pandas using:
Bash
pip install pandas
▶️ Run the Program
Bash
python filename.py
🎯 Who Can Use This?
✅ Beginners
✅ Students
✅ Python Learners
✅ Data Science Aspirants
✅ ML Enthusiasts
📸 Repository Highlights
Easy Notes
Beginner Friendly
Practical Examples
Interview Questions
Real-Time Practice
🤝 Contributing
Feel free to contribute by:
Adding examples
Improving notes
Fixing errors
Sharing interview questions
⭐ Support
If you found this repository useful:
⭐ Star the repository
🍴 Fork the repo
📢 Share with friends
👨‍💻 Author
XMASTER PYHUB
📷 Instagram: @xmaster_pyhub
🐍 Happy Learning Pandas! 🚀