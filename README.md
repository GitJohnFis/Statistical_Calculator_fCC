# Statistics Calculator

Welcome to the **Statistics Calculator** project! This project is designed to help you learn advanced JavaScript array methods like `map()`, `reduce()`, and `filter()` by building a functional statistics calculator. You'll gain experience with handling user input, DOM manipulation, and method chaining, all while performing statistical calculations such as mean, median, mode, variance, and standard deviation.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Getting Started](#getting-started)
4. Usage
5. Contributing
6. License

## Introduction

The Statistics Calculator is a fun and interactive way to learn JavaScript by creating real programs. This project will help you understand how to manipulate arrays and perform complex calculations, making your learning experience enjoyable and practical.

## Features

- **Mean Calculation**: Compute the average of a set of numbers.
- **Median Calculation**: Find the middle value in a set of numbers.
- **Mode Calculation**: Identify the most frequently occurring number(s) in a set.
- **Variance Calculation**: Measure the spread of numbers in a set.
- **Standard Deviation Calculation**: Determine the amount of variation in a set of numbers.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/statistics-calculator.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd statistics-calculator
    ```

3. **Open the project in your favorite code editor**.

## Usage

Here's a brief overview of how to use the Statistics Calculator:

1. **Input your data**: Enter a set of numbers into the input field.
2. **Select the calculation**: Choose the statistical calculation you want to perform.
3. **View the results**: The calculator will display the results on the screen.

### Example Code

Here's an example of how the variance calculation ist getVariance = (array) => {
  const mean = getMean(array);
  const variance = array.reduce(+ (el - mean) ** 2, 0);
  return variance / array.length;
};

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please feel free to submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

In this statistics calculator project, I gained experience with handling user input, DOM manipulation, and method chaining. I got practice by performing statistical calculations like mean, median, mode, variance, and standard deviation. Practicing in https://www.freecodecamp.org.
