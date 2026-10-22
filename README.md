# Simple-Chat-Bot-With-Python
A console-based interactive chatbot developed in Python as part of the JetBrains Academy / Hyperskill course.

## Overview
This program runs through a structured interactive conversational sequence:
1.  **Greeting (`greet`):** Introduces the chatbot named **Sabrina** (created in 2026).
2.  **Name Prompt (`remind_name`):** Prompts the user to enter their name and responds with a personalized greeting.
3.  **Age Prediction (`guess_age`):** Guesses the user's age based on user -provided remainders from dividing their age by 3, 5, and 7 using modular arithmetic.
4.  **Interactive Counter (`count`):** Prompts the user for a number and counts from `0` up to that number using a `while` loop.
5.  **Knowledge Quiz (`test`):** Tests the user on basic programming knowledge ("What is Python?") with a multiple-choice prompt, looping until the user inputs option `2`.
6.  **Completion (`end`):** Outputs a friendly farewell message upon successful test completion.

## How to Run
1. Ensure you have Python installed.
2. Run the script from your terminal or IDE:
```bash
python bot.py

