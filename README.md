# 🧮 Python GUI Calculator with History

A simple yet powerful **Python desktop calculator** with a **history feature**, built using **Tkinter**. This project demonstrates basic **full-stack logic** for local file storage combined with an intuitive **graphical user interface**.

---

## 📌 Overview

This calculator lets you:
- Perform **basic arithmetic operations** (+, −, ×, ÷)
- View a **calculation history** (saved in a local `history.txt` file)
- Clear the history with one click

Every calculation you perform is **automatically saved**, so you can track your previous results anytime!

---

## 🚀 Key Features

✅ **User-Friendly GUI**  
- Clean layout using **Tkinter** widgets  
- Large input display and responsive buttons

✅ **Real-Time Evaluation**  
- Supports addition, subtraction, multiplication, and division  
- Handles simple syntax errors gracefully

✅ **Persistent History**  
- Each result is stored in `history.txt`  
- View your past calculations with the **📜 View History** button  
- Clear the saved history with the **🗑 Clear History** button

✅ **Easy to Extend**  
- Cleanly structured Python code  
- Easy to upgrade with new features like advanced operators, keyboard shortcuts, or a dark theme!

---

## ⚙️ How It Works

- When you press `=`, the calculator **evaluates** the input expression using Python’s `eval()`.
- The expression and its result are **appended** to a local `history.txt` file.
- The **View History** button reads this file and displays the contents in a pop-up.
- The **Clear History** button wipes the file clean for a fresh start.

---

## 🧰 Tech Stack

- **Python 3**
- **Tkinter** — Python’s standard GUI library
- **messagebox** — for pop-up dialogs

---

## 🗂️ Project Screenshots

### 🖥️ Main Calculator Window
<img width="335" height="505" alt="Calculator Main Window" src="https://github.com/user-attachments/assets/0384762f-f6bd-4a50-a89d-30c0e5909962" />

### 📜 View Calculation History
<img width="663" height="501" alt="View History Popup" src="https://github.com/user-attachments/assets/0405a515-8907-4519-a9a1-b9c3ddc65ee3" />

### 🗑 Clear Calculation History
<img width="650" height="504" alt="Clear History Confirmation" src="https://github.com/user-attachments/assets/5bd845a9-23bc-4654-98f8-2788367daaa3" />

---

## 🚀 Run It Locally

```bash
# Clone this repository
git clone https://github.com/Salman-Dev262/python-gui-calculator.git

# Navigate to the project folder
cd python-gui-calculator

# Run the app
python calculator.py

```

## 🙌 Author

**Created by Salman Ali**  
📌 *“A simple tool to practice Python GUI skills & file handling!”*

Feel free to ⭐️ star, fork, and share!
