SSGS Calculator
Project Overview
The SSGS Calculator is a simple Node.js-based application designed to perform basic arithmetic operations: addition, subtraction, multiplication, and division. The project includes:

A core module (calculator.js) implementing the arithmetic operations.
A command-line interface (CLI) (app.js) for user interaction.
Unit tests written using Jest to ensure the correctness of the core logic.
A Continuous Integration (CI) pipeline using GitHub Actions to automate testing and code coverage reporting.
This project was developed as part of a lab assignment to practice software development principles such as modular design, unit testing, version control, and CI/CD integration.

Scope of the Project
The scope of this project includes:

Core Functionality :
Implementing basic arithmetic operations (addition, subtraction, multiplication, division).
Handling edge cases like division by zero and negative numbers.
Testing :
Writing unit tests for all functions using Jest.
Achieving 100% code coverage for the core module.
Version Control :
Managing the project under Git version control and hosting it on GitHub.
CI/CD Pipeline :
Setting up a GitHub Actions pipeline to automatically run tests and generate coverage reports on every push or pull request.
Documentation :
Providing clear instructions for installation, usage, and testing in this README.md file.
What We Did
1. Core Module Development
We implemented a calculator.js module with the following functions:

addizione(a, b): Adds two numbers.
sottrazione(a, b): Subtracts two numbers.
moltiplicazione(a, b): Multiplies two numbers.
divisione(a, b): Divides two numbers, with error handling for division by zero.
Example:

javascript
Copy
1
2
3
const calculator = require('./calculator');
console.log(calculator.addizione(2, 3)); // Output: 5
console.log(calculator.divisione(10, 0)); // Throws an error: "Impossibile dividere per zero."
2. Command-Line Interface (CLI)
We created a CLI application (app.js) that allows users to interact with the calculator module via the terminal. Users can select an operation and input parameters to see the result.

3. Unit Testing
We wrote unit tests for all functions in the calculator.js module using Jest. The tests cover:

Normal cases (e.g., 2 + 3 = 5).
Edge cases (e.g., 0 + 0, -1 + 1, division by zero).
Error handling (e.g., throwing an error when dividing by zero).
4. Code Coverage
We achieved 100% code coverage for the calculator.js module by writing comprehensive tests for all functions and edge cases. The coverage report is generated using Jest’s --coverage flag.

5. GitHub Repository
The project is hosted on GitHub under version control. All files, including the source code, tests, and pipeline configuration, are committed and pushed to the repository.

6. GitHub Actions Pipeline
We set up a GitHub Actions pipeline to:

Automatically run tests on every push or pull request.
Generate and upload a code coverage report as an artifact.
Ensure the project remains stable and free of regressions.
What Should Be Done
To further improve the project, consider the following enhancements:

Extend Functionality :
Add more operations (e.g., exponentiation, square root, modulus).
Allow multiple operations in a single session.
Improve User Experience :
Add input validation to handle invalid user inputs gracefully.
Display random greetings or messages at the end of the program.
Enhance Testing :
Write integration tests for the CLI application (app.js).
Use tools like jest-github-actions-reporter to format test results for GitHub Actions.
Deployment :
Package the application as an executable or Docker container for easier distribution.
Documentation :
Add diagrams (e.g., flowcharts) to explain the program’s structure and workflow.
Include screenshots of the CLI application in action.
Installation
To install and run the project locally, follow these steps:

Clone the repository:
bash
Copy
1
git clone https://github.com/DarknessHunter/SSGS-calc.git
Navigate to the project directory:
bash
Copy
1
cd SSGS-calc
Install dependencies:
bash
Copy
1
npm install
Usage
Run the CLI application:

bash
Copy
1
node app.js
Follow the prompts to select an operation and input parameters.
The program will display the result and exit.
Testing
Run the unit tests:

bash
Copy
1
npm test
To check code coverage:

bash
Copy
1
npm test -- --coverage
CI Pipeline
The project uses GitHub Actions to automate testing and code coverage reporting. The pipeline runs on every push or pull request to the main branch.

Pipeline Workflow
Checkout Code : Fetches the latest code from the repository.
Set Up Node.js : Installs Node.js (version 20) on the runner.
Install Dependencies : Runs npm install to install required packages.
Run Tests : Executes npm test -- --coverage to run tests and generate a coverage report.
Upload Coverage Report : Uploads the coverage report as an artifact for review.
Coverage
Code coverage is visible in the GitHub Actions logs and uploaded as an artifact after each pipeline run. To achieve 100% coverage , we ensured all functions and edge cases are tested.

