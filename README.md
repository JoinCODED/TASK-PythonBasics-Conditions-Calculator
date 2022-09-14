## Setup

1. Go to the [following link](https://replit.com/team/coded-instructor).
2. Open the task **3. Conditions - Basic Calculator**.
3. Open `main.py` and solve the task.
4. Once you're done click on the submit button.

---

## Task

In this task you'll be creating a calculator. You'll ask the user for one input: the mathematical operation (+, =, /, \*). Then you will print the result of the operation to the user.

Example:

```bash
Choose the operation (+, -, /, *): *
5 * 10 = 50
```

In this example, we set the numbers to `5` and `10`, and the operation `*`.

## Steps

1. Ask the user for one input: `operation`.
2. Write an if condition that checks the operation, if it's `+` add the two numbers, if it's `-` subtract the two numbers, etc.
3. Print the result to the user.
4. Validate the user input:
   - If the operation the user entered was not any of the options (`+`, `-`, `*`, or `/`), print to the user that the operation is not valid.

## Bonus

1. Instead of hard-coding the numbers, ask the user to enter the numbers. Keep in mind the inputs will be strings, you need to convert them to integers or floats first.
2. Validate user input: If the user's inputs were not numbers, print to the user that the numbers were invalid. For example if the user enters letters instead of numbers.

**Hint:** The [String methods](https://www.w3schools.com/python/python_ref_string.asp) here will help.
