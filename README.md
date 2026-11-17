# Employee ID Validator

A small command-line program written in Python that checks whether an Employee ID is in the correct format.

An ID is valid when it starts with `EMP` and is followed by exactly five digits, for example `EMP12345`. When an ID is rejected, the program says what is wrong with it instead of just printing "Invalid".

## How it works

The input is cleaned first (extra spaces removed, converted to uppercase), then checked in three steps:

1. It must start with `EMP`
2. It must be exactly 8 characters long
3. Everything after `EMP` must be digits

The first check that fails decides which message is shown.

## Run it

You only need Python 3 installed.

```bash
python employee_id_validator.py
```

## Example

```
========================================
          EMPLOYEE ID VALIDATOR
========================================

Enter Employee ID: emp12345

Valid: EMP12345 is a correct Employee ID
```

```
Enter Employee ID: EMP12A45

Invalid: only digits are allowed after 'EMP'
```

## What I practiced

- `startswith()`, `len()` and `isdigit()`
- `strip()` and `upper()` to clean user input
- `if / elif / else` for step-by-step validation
- f-strings and `center()` for tidy output

## Possible improvements

- Ask again until a valid ID is entered
- Check several IDs in one run
- Read IDs from a text file

## About me

**Rammal Ahmed**

**AI & Data Science Enthusiast** | **Microsoft Dynamics 365 CRM Developer** | **Power Platform** | **UI/UX Designer** | **Graphic Designer & Illustrator**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rammal-ahmed-58184b325)
[![GitHub](https://img.shields.io/badge/GitHub-Rammal--Ahmed-181717?style=flat&logo=github)](https://github.com/Rammal-Ahmed)

<div align="center">

If you found this useful, consider giving it a star ⭐

**I truly value your feedback and welcome any suggestions for improvement**

**Always open to fresh perspectives, constructive feedback, and new ideas**


## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details

---

*Developed as part of my Python programming practice*

---

**Project Status:** Completed

</div>
