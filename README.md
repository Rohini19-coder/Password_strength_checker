# Password Strength Checker

This is a simple Python script to check the strength of a password based on several security rules.

## Features

✅ Counts:
- Capital letters
- Small letters
- Symbols
- Numbers
- Length of password

✅ Classifies password strength into:
- **Low**
- **Medium**
- **High**

## Password Strength Rules

| Strength | Capital Letters | Small Letters | Symbols | Numbers | Min Length |
|----------|-----------------|---------------|---------|---------|------------|
| Low      | 0               | ≤ 6           | 0       | 0       | ≥ 6        |
| Medium   | ≥ 1             | ≥ 8           | 0       | ≥ 1     | ≥ 8        |
| High     | ≥ 2             | ≥ 10          | ≥ 1     | ≥ 4     | ≥ 14       |

## How to Run

1. Make sure Python is installed on your system.
2. Save the script as `password_checker.py`.
3. Open a terminal and run:

