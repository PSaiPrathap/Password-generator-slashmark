# Password-generator-slashmark

**README.md** file for your password generator script with a detailed guide on how to run and use it.

---

## 🔐 Random Password Generator

This is a **Python-based password generator** that creates random passwords based on the desired length specified by the user. The generated passwords include:

✅ Random lowercase letters  
✅ Random digits replacing some characters  
✅ Random uppercase letters replacing some characters  

---

## 📂 File Structure

```
/password-generator
├── password_generator.py  # Main script for password generation
└── README.md              # Project documentation
```

---

## 🚀 Features

- 🛡️ **Multiple Password Generation:** Generate multiple passwords in one go.
  
- 🔢 **Digit Replacement:** Replaces some characters with random numbers.
  
- 🔠 **Uppercase Character Replacement:** Replaces some characters with uppercase letters.
  
- 📏 **Custom Lengths:** Choose different lengths for each password.
  
- 🛑 **Minimum Length Enforcement:** Ensures a minimum password length of 3 characters.

---

## ⚡️ Prerequisites

Before running the application, ensure you have the following:

- Python 3.x installed on your system.  
To check if Python is installed, run:
```bash
python --version
```
If not installed, download and install it from [Python Official Website](https://www.python.org/downloads/).

---

## 📖 How to Run

Follow these steps to execute the `password_generator.py` file:

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repository-name.git
```
Replace `your-username` and `your-repository-name` with your GitHub username and repository name.

### 2. Navigate to the Project Directory
```bash
cd your-repository-name
```

### 3. Run the Application
Run the `password_generator.py` script using Python:
```bash
python password_generator.py
```

---

## 📝 Usage Instructions

1. **Run the Script:** Launch the script by running `password_generator.py`.
2. **Enter Number of Passwords:** Specify how many passwords you want to generate.
3. **Set Length for Each Password:** Input the length of each password (minimum length is enforced as 3).
4. **Receive Generated Passwords:** The generated passwords will be displayed.

---

## 📌 Example Usage

```
How many passwords do you want to generate? 3
Generating 3 passwords
Minimum length of password should be 3
Enter the length of Password #1 8
Enter the length of Password #2 12
Enter the length of Password #3 5
Password #1 = a4kjPqdv
Password #2 = shd7sWk9xnNp
Password #3 = j6Rkv
```

---

## ⚙️ Code Overview

- `generatePassword(pwlength)` – Generates passwords of specified lengths.
- `replaceWithNumber(pword)` – Replaces random positions with numbers.
- `replaceWithUppercaseLetter(pword)` – Replaces random positions with uppercase letters.
- `main()` – Handles user input and password generation logic.

---

## ⚠️ Important Notes

- Passwords have a **minimum length of 3** to ensure complexity.
- Passwords will contain a mix of:
    - Lowercase letters
    - Digits
    - Uppercase letters

