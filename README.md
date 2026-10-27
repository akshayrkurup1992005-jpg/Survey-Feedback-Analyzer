# 📊 Survey Feedback Analyzer

### Python Fundamentals — Module End Assignment 4

A Python-based project to analyze customer survey feedback, clean text data, and generate useful insights from customer ratings and comments.

## 📌 Project Overview

The **Survey Feedback Analyzer** is designed to manage and analyze customer feedback using Python. It allows users to add new feedback entries, clean text responses, count frequently mentioned words, and generate a summary of customer satisfaction.

This project demonstrates fundamental Python programming concepts along with data analysis using Pandas.

## 🎯 Objectives

- Store and manage survey feedback data.
- Allow users to add additional feedback entries.
- Validate customer ratings between 1 and 5.
- Clean feedback text by removing punctuation and extra spaces.
- Convert feedback text to lowercase.
- Count the number of feedback entries containing specific words.
- Calculate the average customer rating.
- Identify the longest feedback comment.
- Extract unique words from all feedback entries.
- Sort feedback records by rating.

## 🛠️ Technologies Used

- **Python** — Core programming language
- **Pandas** — Data organization and tabular display
- **Regular Expressions (re)** — Text cleaning
- **Jupyter Notebook** — Development environment

## ✨ Key Features

### 1. Preloaded Feedback Data
Starts with 10 sample customer feedback entries, including customer names, written comments, and ratings.

### 2. Add New Feedback
Allows users to enter additional customer feedback interactively. Ratings are validated to ensure they fall between 1 and 5.

### 3. Text Cleaning
Standardizes feedback text by:
- Removing punctuation marks.
- Removing unnecessary spaces.
- Converting text to lowercase.

### 4. Word Count Analysis
Counts how many feedback entries contain selected words, such as:
- `good`
- `poor`
- `excellent`

Each feedback entry is counted only once per searched word.

### 5. Summary and Insights
Generates useful information, including:
- Total number of feedback entries.
- Average customer rating.
- Longest feedback comment.
- Word count of the longest comment.
- Unique words used across all feedback entries.

### 6. Sort Feedback by Rating
Displays feedback records from the highest rating to the lowest rating.

## 📂 Project Structure

```text
Survey-Feedback-Analyzer/
│
├── Module End Assignment.ipynb
└── README.md
```

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open the project in Jupyter Notebook.
3. Install the required library if it is not already installed:

   ```bash
   pip install pandas
   ```

4. Open `Survey_Feedback_Analyzer.ipynb`.
5. Run the notebook cells sequentially, starting from Step 1.
6. Enter additional feedback when prompted.
7. View the results in table format.

## 📊 Expected Output

The notebook displays:

- Preloaded and updated feedback tables.
- Cleaned customer feedback.
- Word count analysis.
- Average rating summary.
- Longest feedback comment.
- A list of unique words.
- Feedback sorted by rating.

## 📚 Concepts Practiced

- Python dictionaries and lists
- Loops and conditional statements
- Functions
- String manipulation
- Input validation
- Sets and list comprehensions
- Lambda functions
- Pandas DataFrames
- Data sorting and basic analysis

## 🎓 Learning Outcomes

This project provides practical experience in collecting, cleaning, organizing, and analyzing textual feedback. It also demonstrates how Python can transform raw customer comments into structured data and meaningful summaries.

## 👩‍💻 Project Information

**Project:** Survey Feedback Analyzer  
**Course:** Python Fundamentals  
**Assignment:** Module End Assignment 4  
**Environment:** Jupyter Notebook

---

⭐ If you find this project useful, feel free to explore the notebook and learn from the implementation.
