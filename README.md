# Prime Numbers From 1-50
## Description
This project is a Python program that demonstrates the use of for loop in Python. A **for loop** is used to execute a block of code repeatedly by iterating over a sequence such as range, list, string or tuple.
## Syntax
```python
for variable in sequence:
    # Code to execute
```
## Concepts Used
- Variables
- range()
- for() loop
## Technologies Used
- Pycharm
- Python 3
## Working
1. The outer for loop starts from 2 and checks every number up to 50.
2. For each number n, a Boolean variable prime is initialized to True.
3. The inner for loop checks whether n is divisible by any number from 2 to n - 1.
4. If n is divisible by any value of i, prime is set to False and the inner loop stops using break.
5. If no divisor is found, the value of prime remains True.
6. After the inner loop finishes, the program checks the value of prime.
7. If prime is True, the current number is a prime number and is printed.
8. The process repeats until all numbers from 2 to 50 have been checked.
## How to run
1. Clone the repository.
2. Open the project in Pycharm.
3. Run the 'main.py' file.
4. View the result.
## Sample Output
```text

2
3
5
7
11
13
17
19
23
29
31
37
41
43
47
```
## Author
- Sadia
- Github: [sadiacode](https://github.com/sadiacode)
