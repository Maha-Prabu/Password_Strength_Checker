# 🔐 Password Strength Checker

A simple Python-based tool to evaluate the strength of a password using standard security rules.

---

## 📌 Features

- Checks password length
- Validates uppercase and lowercase characters
- Ensures inclusion of numbers
- Detects special characters
- Provides feedback for improvement

---

## 🛠️ Tech Stack

- Python
- Regular Expressions (re module)

---

## 🚀 How It Works

The program analyzes the password based on the following criteria:

| Criteria              | Requirement                  |
|----------------------|------------------------------|
| Length               | Minimum 8 characters         |
| Uppercase Letter     | At least one                |
| Lowercase Letter     | At least one                |
| Number               | At least one                |
| Special Character    | At least one                |

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/Maha-Prabu/password-strength-checker.git

2.Navigate to the project folder:
cd password-strength-checker

3.Run the script:
python main.py

Example Output

Enter your password: Test123

Result: Moderate Password ⚠️
Suggestions:
- Include at least one special character