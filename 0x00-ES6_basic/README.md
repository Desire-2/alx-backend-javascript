# 0x00. ES6 Basics

Welcome to the `0x00-ES6_basic` project repository! This project focuses on mastering the basics of ES6 (ECMAScript 2015) in JavaScript. By completing the tasks outlined below, you'll gain a solid understanding of ES6 features and their applications.

## Project Overview

This project covers various ES6 topics, including:

- Constants and Variables (`const` and `let`)
- Block Scope
- Arrow Functions
- Default Parameters
- Rest Parameter Syntax
- Spread Syntax
- Template Literals
- Object Property Value Shorthand
- Computed Property Names
- ES6 Method Properties
- Iterators and `for...of` Loops

## Learning Objectives

By the end of this project, you should be able to:

- Explain what ES6 is and its significance.
- Identify and utilize new features introduced in ES6.
- Understand the difference between constants and variables (`const` and `let`).
- Work with block-scoped variables.
- Utilize arrow functions and function parameters defaulting to them.
- Handle rest and spread function parameters effectively.
- Implement string templating in ES6.
- Create objects and manipulate their properties using ES6 syntax.
- Iterate over collections using iterators and `for...of` loops.

## Requirements

### General
- All files must be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x.
- Allowed editors: vi, vim, emacs, Visual Studio Code.
- All files should end with a new line.
- A `README.md` file, at the root of the project folder, is mandatory.
- Your code should use the `.js` extension.
- Testing will be conducted using the Jest Testing Framework.
- Code analysis will be performed using ESLint with specific rules provided.

### Setup
1. Install NodeJS 12.11.x:
    ```bash
    curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
    sudo bash nodesource_setup.sh
    sudo apt install nodejs -y
    nodejs -v
    npm -v
    ```

2. Install Jest, Babel, and ESLint:
    Navigate to your project directory and run:
    ```bash
    npm install
    ```

## Project Structure

The project directory is organized as follows:

- **Tasks:** Contains JavaScript files for each task.
- **Tests:** Includes test files for Jest testing.
- **Documentation:** Instructions for each task.
- **Configuration Files:** Contains necessary configuration files (package.json, babel.config.js, .eslintrc.js).

## Tasks

1. **Const or let?**: Modify functions to use `const` and `let`.
2. **Block Scope**: Adjust variables inside functions to prevent overwriting within conditional blocks.
3. **Arrow Functions**: Rewrite functions using ES6 arrow syntax.
4. **Parameter Defaults**: Condense function internals to one line using default parameter values.
5. **Rest Parameter Syntax**: Modify a function to return the number of arguments passed using rest parameter syntax.
6. **The Wonders of Spread Syntax**: Concatenate arrays and a string using spread syntax.
7. **Take Advantage of Template Literals**: Rewrite a return statement using template literals.
8. **Object Property Value Shorthand Syntax**: Simplify object creation by using key names.
9. **No Need to Create Empty Objects**: Rewrite a function using ES6 computed property names.
10. **ES6 Method Properties**: Rewrite a function to use ES6 method properties.
11. **For...of Loops**: Rewrite a function to use ES6's `for...of` operator.
12. **Iterator**: Write a function to return an iterator to go through every employee in every department.
13. **Iterating Through Report Objects**: Write a function to iterate through every employee in every department and return their names.
14. **Iterate Through Object**: Write a function to iterate through objects and return employee names separated by `|`.

## Getting Started

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Complete each task following the instructions provided in the task files.
4. Test your solutions using Jest.
5. Ensure your code passes ESLint checks.
6. Modify the `README.md` file to include any additional instructions or clarifications.

## Support

If you encounter any issues or have questions regarding the project, feel free to open an issue in the GitHub repository or reach out to the project maintainers for assistance.

Let's dive into ES6 and enhance our JavaScript skills together! 🚀
