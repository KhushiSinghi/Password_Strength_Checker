# Password Strength Checker

## Overview

This project is a Python-based Password Strength Checker built using **Tkinter** for the graphical user interface and **Regular Expressions (Regex)** for password validation. It provides instant feedback on the strength of a password and helps users improve their password security.

---

## Features

* Simple and user-friendly GUI
* Instant password strength evaluation
* Regex-based validation for accuracy
* Scoring system based on multiple password criteria
* Secure masked password input
* Lightweight and beginner-friendly code

---

## Technologies Used

* **Python 3.x**
* **Tkinter** (GUI)
* **Regex** module (`re`)

---

## Project Structure

```
Password-Strength-Checker/
│
├── main.py
├── README.md
└── requirements.txt (optional)
```

---

## Setup Instructions

### **1. Install Python**

Make sure Python 3.x is installed on your system.
Check by running:

```
python --version
```

### **2. Install Required Libraries**

This project mainly uses built-in libraries, so no external installations are required.
If you want to create a requirements file, include:

```
tk
re
```

### **3. Run the Project**

Navigate to the project folder and run:

```
python main.py
```

The GUI window will open immediately.

---

## Code Details

### **check_strength(password)**

This function evaluates the strength of the password by checking:

* Minimum length (>= 8)
* Uppercase letters
* Lowercase letters
* Digits
* Special characters

Based on these checks, it returns:

* **Weak**
* **Medium**
* **Strong**

### **on_check()**

* Reads the password from the input field
* Calls the strength checking function
* Updates the label in the GUI with the result

### **Tkinter GUI Components**

* `Tk()` → Creates main window
* `Label` → Displays text
* `Entry` → Password input (masked)
* `Button` → Triggers strength check

---

## How It Works

1. User enters a password in the masked field.
2. User clicks "Check Strength".
3. The program analyzes the password.
4. The result is displayed on screen.

---

## Future Enhancements

* Color-coded strength indicator
* Real-time checking without button click
* Suggestions for improving weak passwords
* Progress bar for visual strength display

---

## Conclusion

This Password Strength Checker is a simple and effective tool demonstrating GUI development and regex-based input validation in Python. It helps users create safer passwords while providing a clean, interactive experience.
