# 🔐 Random Password Generator

A simple GUI-based Random Password Generator developed using **Python and Tkinter**. This application allows users to generate passwords of different strength levels and copy the generated passwords directly to the clipboard.

## 📌 Project Overview

The Random Password Generator is a Python-based desktop application designed to generate random passwords based on user-selected length and strength.

The application provides three password strength options:
- **Low:** Generates passwords containing lowercase letters.
- **Medium:** Generates passwords containing uppercase and lowercase letters.
- **Strong:** Generates passwords containing uppercase letters, lowercase letters, digits, and special characters.

Users can select the desired password length, generate a password, and copy it to the clipboard using the Copy button.

## ✨ Features

- Generate random passwords instantly.
- Three password strength levels: Low, Medium, and Strong.
- Customizable password length (8–32 characters).
- Copy generated passwords to the clipboard.
- Simple and user-friendly graphical interface.
- Built using Python's Tkinter library.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Tkinter | Graphical User Interface (GUI) |
| Random | Random character selection |
| Pyperclip | Copy passwords to clipboard |

## 📂 Project Structure

```text
Random-Password-Generator/
│
├── codsoft3.py
├── README.md
└── requirements.txt
```

## ⚙️ Installation and Execution

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd Random-Password-Generator
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

Alternatively:

```bash
pip install pyperclip
```

**Note:** Tkinter is included with most standard Python installations. If it is unavailable, install the appropriate Tkinter package for your operating system.

### 4. Run the Application

```bash
python codsoft3.py
```

## 🖥️ How to Use

1. Launch the application.
2. Select the desired password strength (Low, Medium, or Strong).
3. Choose the required password length from the dropdown menu.
4. Click the **Generate** button.
5. Your randomly generated password will appear in the text field.
6. Click **Copy** to copy the password to your clipboard.

## 📚 Concepts Implemented

- Python functions
- Conditional statements
- Loops
- Random module
- GUI development using Tkinter
- Event handling
- Clipboard integration

## 🚀 Future Enhancements

- Use Python's `secrets` module for cryptographically secure password generation.
- Add an option to exclude similar-looking characters.
- Improve password strength validation.
- Add a password visibility toggle.
- Improve the graphical interface with a modern design.

## 👩‍💻 Author

**Swathi Nandiraju**

Developed as a Python programming project to practice GUI development, Python fundamentals, and application development.

---

⭐ If you find this project useful, consider giving the repository a star!
