# 💥 FizzBuzz

A Python implementation of the classic FizzBuzz programming challenge, printing numbers from 1 to 100 according to specific divisibility rules.

This project is part of **Angela Yu's 100 Days of Code: The Complete Python Pro Bootcamp**.

## 📌 About the Project

FizzBuzz is a programming exercise that tests basic logical thinking and the use of conditional statements.

The program iterates through numbers from 1 to 100 and checks whether each number is divisible by 3, 5 or both.

Depending on the result, it prints:

- **FizzBuzz** if the number is divisible by both 3 and 5.
- **Fizz** if the number is divisible by 3.
- **Buzz** if the number is divisible by 5.
- The number itself if none of the conditions are met.

## 🛠️ Technologies & Concepts Used

- **Python 3** – the programming language used.
- `range()` – generates numbers from 1 to 100.
- `for` loops – iterates through the sequence.
- `if`, `elif` and `else` – evaluates different conditions.
- Modulo operator (`%`) – checks the remainder after division.
- Logical operator (`and`) – combines multiple conditions.

## 📚 What I Learnt

Through this project, I practised several fundamental Python concepts:

1. **Ranges** – using `range(1, 101)` to generate integers from 1 to 100.
2. **For Loops** – iterating through a sequence of numbers.
3. **Conditional Statements** – using `if`, `elif` and `else` to control program flow.
4. **Modulo Operator (`%`)** – checking divisibility by determining whether a number has a remainder.
5. **Logical Operators** – using `and` to check whether two conditions are true simultaneously.
6. **Condition Ordering** – checking the combined condition first so that numbers divisible by both 3 and 5 print `FizzBuzz` instead of only `Fizz` or `Buzz`.

## ▶️ How to Run

1. Make sure Python 3 is installed.
2. Clone this repository or download the Python file.
3. Open the project in your preferred code editor or terminal.
4. Run the following command:

```bash
python main.py
```

The program will print the FizzBuzz sequence from 1 to 100 in the terminal.

## 💻 Example Output

```text
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
...
```

## 💡 Possible Improvements

As I continue learning Python, I could extend this project by:

- Allowing users to choose the range of numbers.
- Creating a reusable function for the FizzBuzz logic.
- Exploring alternative approaches using list comprehensions.
- Customising the words printed for different divisibility rules.

## 🌱 Learning Journey

This exercise is part of Angela Yu's **100 Days of Code** bootcamp.

FizzBuzz helped me combine several Python fundamentals into one program and practise writing logical conditions that work together.

I'm documenting even the smaller exercises to create a record of my progress as I develop my programming skills.

*Learning one concept at a time!* 🐍
