# Leap Year Assessment Challenge

We're pleased to introduce a new coding challenge that will allow you to demonstrate your coding proficiency, understanding of control flow, and ability to write maintainable code. This task involves evaluating leap years from year 1 to the current year.

## Challenge Details

**Objective:** Create a .Net 8 application written in C# that determines whether each year from 1 to the present year is a leap year. The application should generate two files, one in CSV format and the other in JSON format, listing each year and its leap year status.

**Your Task:**

- Loop through every year from 1 up to the current year.
- Manually write the logic to determine if the year is a leap year, no libraries are allowed for the calculation. You also cannot use the built in DateTime.IsLeapYear function.
- Output the results to new two files for each execution of the application: one CSV file and one JSON file.
- Output the total number of leap years found to the console.

### CSV Output Example

```csv
Year,LeapYear
1,No
2,No
3,No
4,Yes
...
```

### Json Output Example

```json
[
  {
    "Year": 1,
    "LeapYear": "No"
  },
  {
    "Year": 2,
    "LeapYear": "No"
  },
  {
    "Year": 3,
    "LeapYear": "No"
  },
  {
    "Year": 4,
    "LeapYear": "Yes"
  },
  ...
]
```

### Console Output Example

```terminal
Total Leap Years: X
```

**Technical Requirements:**

- **Unit Tests:** Include comprehensive unit tests for the solution.
- **File Output:** Ensure the application correctly writes the results to both a CSV file and a JSON file. New files should be created for each application execution.
- **Console Output:** Display the total number of leap years found in the console.
- **Clean Code:** Your code should be clean and easy to read.
- **SOLID Principles:** Apply SOLID principles to ensure that the code is well-architected and maintainable.

**Submission Instructions:**

- Please submit your code through a Git repository (e.g. GitHub) with accessible commit history.
- Your commit history should clearly illustrate your development process, including initial tests, core functionality implementation, and output file generation.
- Make sure all tests pass before finalizing your submission.

## Assessment Criteria

- **Correctness:** The application must accurately determine leap years based on the given rules.
- **Testing:** Your submission should include robust unit tests that cover various edge cases and typical scenarios.
- **Code Quality:** We expect high-quality, production-ready code that adheres to industry standards.
- **File Handling:** Proper file creation and formatting in both CSV and JSON formats will be key.
- **Understanding of SOLID Principles:** Your code should reflect a solid understanding of SOLID design principles.
- **Version Control Proficiency:** The submission must be through a Git repository (e.g., GitHub) with a clear, accessible commit history. Commit messages should be concise, yet descriptive, explaining why changes were made rather than what was changed.
- **README File:** Include a well-structured README file in the Git repository. It should explain the purpose of the application, how to setup and run it, and any dependencies or configuration required. This demonstrates the candidate's ability to communicate effectively and ensure that their codebase is accessible to other developers.

## Conclusion

This challenge will test your ability to handle a basic algorithm, work with file I/O, and apply best practices in software development. It offers a chance to showcase your technical skills and your approach to problem-solving in a structured and professional manner.

We look forward to reviewing your innovative solutions and discussing your approach.
