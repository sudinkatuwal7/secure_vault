# 🔐 Python Password Manager

A simple GUI-based Password Manager built using **Python and Tkinter**.

This application allows users to:
- Generate secure random passwords
- Copy passwords automatically to clipboard
- Save login credentials locally in a JSON file
- Search saved credentials by website

---

## ✨ Features

- 🔑 Secure password generator
- 📋 Automatic clipboard copy
- 💾 Save credentials to data.json
- 🖥 Simple and clean Tkinter GUI
- 🧠 Beginner-friendly project
- 🔍 Search saved credentials
- 🧹 Case-insensitive website handling (Facebook = facebook)
  
---

## 🛠 Built With

- Python 3
- Tkinter (GUI)
- Random module
- JSON module
- Pyperclip (clipboard support)

---

## 🚀 How to Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/sudinkatuwal7/secure_vault.git
cd secure_vault
```

### 2️⃣ Install required package
```
pip install pyperclip
```

### 3️⃣ Run the program
```
python main.py
```

---

### 📁 Project Structure
```
secure_vault/
│
├── main.py
├── logo.png
├── data.json        # Created automatically after first save
├── README.md
└── .gitignore
```

---

## 📸 Preview

Here is a preview of the application:

<img width="2560" height="1440" alt="Screenshot (367)" src="https://github.com/user-attachments/assets/3f2c7b35-4fe2-4754-9d4e-d53ef910506c" />

---

<img width="2198" height="1048" alt="Screenshot (369)" src="https://github.com/user-attachments/assets/d31a6d69-e17f-4fcf-842d-5f5511fddbd8" />

---

<img width="2145" height="952" alt="Screenshot (372)" src="https://github.com/user-attachments/assets/3f8ed729-4d20-482b-9af6-ccda8f72a460" />

---

### 📌 How It Works

- Generates a strong random password using letters, numbers, and symbols

- Allows users to enter website and email

- Saves credentials into a local JSON file (data.json)

- Copies generated password automatically to clipboard
  
- Allows searching saved credentials by website


---

### ⚠️ Note

This project stores passwords in a local JSON file for learning purposes.
It is not encrypted and should not be used for real sensitive data.
