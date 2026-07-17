# BMI Calculator

A simple Python-based Body Mass Index (BMI) Calculator that calculates a user's BMI using their weight and height and classifies it according to standard BMI categories.

## Features

- Calculate Body Mass Index (BMI)
- Height input in centimeters (cm)
- Automatic conversion from centimeters to meters
- Categorize BMI as:
  - Underweight
  - Normal Weight
  - Overweight
  - Obese
- Positive input validation
- Realistic weight validation (10–500 kg)
- Realistic height validation (50–300 cm)
- Handles invalid (non-numeric) input using exception handling

## Technologies Used

- Python 3

## Project Structure

```text
BMI-Calculator/
│
├── BMI_Calculator.py
├── test_BMI_Calculator.py
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

1. Go to the project folder:

```bash
cd BMI-Calculator
```

2. Run the program:

```bash
python BMI_Calculator.py
```

## Sample Output

```text
===== BMI Calculator =====
Enter your weight (kg): 60
Enter your height (cm): 165

Your BMI is: 22.04
Category: Normal weight
```

## Input Validation

The program validates user input by checking:

- Weight and height must be greater than zero.
- Weight must be between **10 kg and 500 kg**.
- Height must be between **50 cm and 300 cm**.
- Only numeric values are accepted.

## BMI Categories

| BMI | Category |
|------|----------|
| Below 18.5 | Underweight |
| 18.5 - 24.9 | Normal Weight |
| 25.0 - 29.9 | Overweight |
| 30.0 and above | Obese |

## Author

**Ayela Ahsan**

---
If you found this project helpful, feel free to ⭐ star the repository.