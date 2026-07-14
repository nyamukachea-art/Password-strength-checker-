# Password-strength-checker-🔐 Python Password Strength Checker

A simple cybersecurity-focused Python project that evaluates the strength of a password based on security best practices. The program analyzes password characteristics and provides feedback on how to improve password security.

📌 Features

- Checks password length
- Detects uppercase letters
- Detects lowercase letters
- Checks for numbers
- Checks for special characters
- Identifies commonly used weak passwords
- Provides password strength rating:
  - Weak
  - Medium
  - Strong
- Gives suggestions for improving password security

🛠️ Technologies Used

- Python 3
- Regular Expressions ("re" module)

📂 Project Structure

python-password-strength-checker/
│
├── password_checker.py
└── README.md

🚀 How to Run the Project

1. Clone the repository

git clone https://github.com/yourusername/python-password-strength-checker.git

2. Navigate to the project folder

cd python-password-strength-checker

3. Run the program

python password_checker.py

💻 Example Usage

=== Password Strength Checker ===

Enter your password: Hello123

Password Strength: Medium

Suggestions:
- Add special characters (!@#$%^&*)

🔎 How It Works

The program assigns points based on password security features:

Feature| Points
12+ characters| 2
8+ characters| 1
Uppercase letters| 1
Lowercase letters| 1
Numbers| 1
Special characters| 1

The final score determines the password strength level.

🎯 Learning Objectives

This project demonstrates:

- Python programming fundamentals
- Use of conditional statements
- Regular expressions
- User input handling
- Basic cybersecurity concepts
- Password security principles

🔮 Future Improvements

Possible upgrades:

- Add a password generator
- Add a graphical user interface (GUI)
- Calculate password entropy
- Add password breach checking
- Create a web version using Flask

👨‍💻 Author

Arthur Nyamukache

Cybersecurity student building practical security projects with Python.

📜 License

This project is open-source and available for educational purposes.
