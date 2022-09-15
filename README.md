# Python Documentation

# Leap Year Checker

This Python script is designed to check if a given year is a leap year or not. 

## Description

The script prompts the user to input a year. It then checks if the year is a leap year or not based on the following rules:

- The year is evenly divisible by 4;
- If the year can be evenly divided by 100, it is NOT a leap year, unless;
- The year is also evenly divisible by 400. Then it is a leap year.

This means that in the Gregorian calendar, the years 2000 and 2400 are leap years, while 1800, 1900, 2100, 2200, 2300, and 2500 are NOT leap years.

## Code Explanation

The script does not import any libraries. It consists of a function `is_leap(year)` and a user input prompt.

The `is_leap(year)` function checks if the input year is a leap year or not based on the rules mentioned above. It uses the modulus operator `%` to check if the year is evenly divisible by 4, 100, and 400.

The user is prompted to input a year with the `input()` function. The input is then converted to an integer with the `int()` function.

The script then calls the `is_leap(year)` function with the user input as the argument. If the function returns `True`, it prints that the year is a leap year. If the function returns `False`, it prints that the year is not a leap year.

## Usage

To use this script, simply run it in a Python environment. When prompted, enter the year you want to check. The script will then print whether the year is a leap year or not.

---

# C# Documentation

# Leap Year Checker in C#

This repository contains a simple C# script that checks if a given year is a leap year or not.

## Script Description

The script prompts the user to input a year. It then checks if the year is a leap year or not based on the following conditions:

- The year is evenly divisible by 4;
- If the year can be evenly divided by 100, it is NOT a leap year, unless;
- The year is also evenly divisible by 400. Then it is a leap year.

This means that in the Gregorian calendar, the years 2000 and 2400 are leap years, while 1800, 1900, 2100, 2200, 2300, and 2500 are NOT leap years.

## Imported Libraries

The script uses the following libraries:

- `System`: This is a built-in C# library that provides fundamental classes and base classes that define commonly-used value and reference data types, events and event handlers, interfaces, attributes, and processing exceptions. In this script, it is used to handle standard I/O operations through the `Console` class.

## Usage

To run the script, you need to have .NET Core installed on your machine. Then, you can use the `dotnet run` command in the terminal from the directory where the script is located.

```bash
dotnet run
```

You will then be prompted to enter a year. After entering a year, the script will output whether the year is a leap year or not.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)

---

# Java Documentation

# Leap Year Checker in Java

This Java program checks if a given year is a leap year or not. A leap year is exactly divisible by 4 except for century years (years ending with 00). The century year is a leap year only if it is perfectly divisible by 400.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

```
Java Development Kit (JDK)
```

## Running the program

To run this program, you need to have Java installed on your computer. Once you have Java installed, you can compile the program using the Java compiler (javac), and then run it using the Java interpreter.

## Code Explanation

The program uses the `java.util.Scanner` class to get the user's input. The `Scanner` class is a simple text scanner which can parse primitive types and strings using regular expressions.

The main logic of the program is in the `if` statement. It checks if the year is divisible by 4 and not divisible by 100, or if it's divisible by 400. If either of these conditions is true, then the year is a leap year.

## Built With

* [Java](https://www.oracle.com/java/)

## Authors

* **Your Name**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

---
