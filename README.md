# 🧑‍💻 Personal Data Collector

> An interactive Python CLI tool for collecting and displaying user data with type introspection

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Level](https://img.shields.io/badge/Level-Beginner%20Friendly-green?style=flat)
![Status](https://img.shields.io/badge/Status-Active-yellow?style=flat)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat)

---

## 📖 About

**Personal Data Collector** is a beginner-level Python CLI project that demonstrates how Python handles different data types. It collects personal information like name, age, height, and favourite number, then displays each value alongside its data type and memory address — making it a practical tool for understanding Python's type system and the built-in `type()` and `id()` functions. It also computes the user's approximate birth year using the `datetime` module.

---

## ✨ Features

- 🖥️ **Interactive CLI** — Guided prompts to collect user input in real time
- 🔍 **Type Introspection** — Shows the Python data type for each collected value
- 🧬 **Memory Addresses** — Displays the memory `id()` of each variable
- 📅 **Birth Year Calculator** — Estimates birth year using Python's `datetime` module

---

## ✅ Requirements

- Python 3.x (no third-party libraries needed)
- Standard library: `datetime` (built-in)
- A terminal or command prompt

---

## 🚀 Installation & Usage

```bash
# 1. Clone the repository
git clone https://github.com/raj-jivani/fundamental-booster.git

# 2. Navigate into the project folder
cd fundamental-booster

# 3. Run the script
python fundamental-booster.py
```

---

## ⚙️ How It Works

1. **Greets the user** — Prints a welcome message to the console
2. **Collects input** — Prompts for name (`str`), age (`int`), height (`float`), and favourite number (`int`)
3. **Displays type info** — Prints each value with its Python type and memory address via `type()` and `id()`
4. **Calculates birth year** — Uses `datetime.datetime.now().year` minus age to estimate the user's birth year

---

## 📊 Data Collected

| Variable           | Input Example | Python Type | Description              |
|--------------------|---------------|-------------|--------------------------|
| `name`             | Alice         | `str`       | User's full name         |
| `age`              | 21            | `int`       | User's age in years      |
| `height`           | 1.72          | `float`     | Height in metres         |
| `favourite_number` | 7             | `int`       | User's favourite integer |

---

## 🖥️ Sample Output

```
Welcome to the Interactive Personal Data Collector!
Enter your name: Alice
Enter your age: 21
Enter your height in meters: 1.72
Enter your favourite number: 7

Thank you! Here is the information we collected:
Name: Alice <class 'str'> 140234567890
Age: 21 <class 'int'> 9781234
Height: 1.72 <class 'float'> 140234000123
Favourite Number: 7 <class 'int'> 9781246

Your birth year is approximately: 2005 (based on your age of 21)
Thank you for using the Personal Data collector.
Goodbye!!!
```

---

## 📚 Concepts Covered

- Variables & data types
- User input via `input()`
- Type casting (`int()`, `float()`)
- `print()` & f-strings
- `type()` & `id()` built-in functions
- `datetime` module
- Arithmetic operations

---

## 📁 Project Structure

```
fundamental-booster/
│
├── fundamental-booster.py    # Main script
└── README.md                 # Project documentation
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ as a Python fundamentals project · © 2026</p>
