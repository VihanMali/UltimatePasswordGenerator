# Ultimate Password Generator 🔐

Ultimate Password Generator is a Java-based console application that creates passwords based on user input and selected difficulty levels. The program balances **memorability** and **security** by combining words, random symbols, reversals, and character case variations.

---

## 🚀 Features

- Three password difficulty levels:
  - **Mid** – Simple and readable
  - **Hard but Rememberable** – Reversed words with symbols
  - **Strong** – Reversals + random uppercase letters
- Randomly selected special characters
- Randomized password structure for stronger security
- Easy-to-use command-line interface

---

## 🧠 How It Works

1. User selects a difficulty level.
2. User enters words that form the base of the password.
3. The program:
   - Inserts random special characters
   - Reverses selected words
   - Randomly capitalizes characters (for strong passwords)
4. A final password is generated and displayed.

---

## 🧪 Difficulty Levels Explained
### 1️⃣ Mid
- Combines two words
- Adds random special characters
- Easy to remember

**Example:**
hello@world!

---

### 2️⃣ Hard but Rememberable
- Uses four words
- Reverses selected words
- Adds multiple special characters

**Example:**
olleh@dlrow#java$edoC

---

### 3️⃣ Strong
- Uses four words
- Randomly reverses word positions
- Random uppercase letters added
- Multiple special characters

**Example:**
OlLeH@dLrOw#AvAj$EdOc

## Strengths
- Mid (hello@world!) --> Very Weak (31 secs to crack) 
- Hard (olleh@dlrow#java$edoC) --> Very Strong (300 Trillion years to crack)
- Strongest (OlLeH@dLrOw#AvAj$EdOc) --> Very Strong (13000000 Trillion years to crack)

**Remember that these Strengths may change according to the words you have given**
**All these Passwords' Strengths are checked from - https://www.passwordmonster.com/ **
---

## 🛠 Technologies Used

- Java
- Java Standard Library (`Random`, `Scanner`, `StringBuilder`)

---

## ▶️ How to Run

1. Clone the repository:
   git clone https://github.com/your-username/UltimatePasswordGenerator.git
   
2.Navigate to the project directory:
cd UltimatePasswordGenerator

3.Compile the program:
javac UltimatePasswordGenerator.java

4.Run the program:
java UltimatePasswordGenerator
