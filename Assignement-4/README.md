# Python Fundamentals – Assignment 4
## Survey Feedback Analyzer

### Project Overview
The Survey Feedback Analyzer is a Python-based project designed to collect, clean, and analyze customer feedback. It demonstrates the application of fundamental Python programming concepts to organize textual feedback and extract meaningful insights from survey responses.

The project uses a dictionary of lists to store customer information, written feedback, and ratings. It also performs basic text cleaning and analyzes feedback to identify frequently used words and calculate rating statistics.

### Objectives
- Store survey feedback using a dictionary of lists.
- Collect additional feedback dynamically from users.
- Validate user ratings to ensure they are between 1 and 5.
- Automatically generate serial numbers for new entries.
- Clean textual feedback by removing punctuation, extra spaces, and converting text to lowercase.
- Analyze feedback using loops, conditional statements, and functions.
- Extract meaningful insights from customer feedback.

### Project Steps

**Step 1: Preloaded Feedbacks**
- Initialize a dictionary containing 10 predefined customer feedback records.
- Store serial numbers, names, feedback comments, and ratings.

**Step 2: Add More Feedbacks**
- Ask users how many additional feedback records they want to enter.
- Collect customer name, written feedback, and rating.
- Validate ratings to accept only values between 1 and 5.
- Automatically generate serial numbers starting from 11.
- Append new records to the existing dictionary.

**Step 3: Text Cleaning**
- Remove punctuation marks such as periods, commas, exclamation marks, and question marks.
- Remove unnecessary leading and trailing spaces.
- Replace multiple spaces with a single space.
- Convert all feedback text into lowercase.

**Step 4: Word Count Insights**
- Create a user-defined function to count feedback entries containing a particular word.
- Analyze the occurrence of the following words:
  - Good
  - Poor
  - Excellent

**Step 5: Final Summary and Insights**
- Display the final cleaned feedback dictionary.
- Calculate the average customer rating.
- Identify the feedback with the longest comment based on word count.
- Extract unique words used across all feedback entries.
- Optionally sort feedback entries based on ratings in descending order.

### Python Concepts Used
- Variables and Data Types
- Lists and Dictionaries
- User Input (`input()`)
- Type Conversion
- For Loops and While Loops
- Conditional Statements (`if`, `elif`, `else`)
- Logical Operators
- String Manipulation and String Methods
- List Methods (`append()`)
- User-Defined Functions
- `range()` and `len()`
- `split()` and `join()`
- `replace()` and `lower()`
- `set()` for identifying unique words
- `zip()` and `sorted()` for optional sorting
- Input Validation

### Tools and Technologies
- **Programming Language:** Python
- **Development Environment:** Jupyter Notebook
- **Version Control:** GitHub

### Key Learning Outcomes
Through this assignment, I gained practical experience in:
- Managing structured data using Python dictionaries and lists.
- Implementing input validation to maintain data accuracy.
- Applying loops to process multiple records.
- Cleaning unstructured textual feedback.
- Developing reusable functions for text analysis.
- Extracting basic insights from customer feedback.
- Understanding how Python can support data preparation and analysis tasks.

### Repository Structure

```text
Python-Fundamentals/
│
└── Assignment-4/
    ├── Survey_Feedback_Analyzer.ipynb
    └── README.md
```

### Conclusion
This project demonstrates how fundamental Python programming concepts can be applied to a practical feedback analysis scenario. It provides a foundation for understanding data collection, data cleaning, and basic text analysis, which are important skills for aspiring Data Analysts.

---

**Author:** Mohamed Fahad  
**Focus Area:** Python Programming | Data Analytics
