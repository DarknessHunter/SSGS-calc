# **SSGS Calculator**
# **LB403CREW**
## **✨ Project Overview**
The **SSGS Calculator** is a simple yet powerful Node.js-based application designed to perform basic arithmetic operations: **addition**, **subtraction**, **multiplication**, and **division**.

This project includes:
- A **core module** (`calculator.js`) implementing the arithmetic operations.
- A **command-line interface (CLI)** (`start.js`) for seamless user interaction.
- **Unit tests** written using Jest to ensure the correctness of the core logic.
- A **Continuous Integration (CI) pipeline** using GitHub Actions to automate testing and code coverage reporting.

This project was developed as part of a lab assignment to practice software development principles such as **modular design**, **unit testing**, **version control**, and **CI/CD integration**.

---

## **🎯 Scope of the Project**
The scope of this project includes:

### **Core Functionality**
- Implementing basic arithmetic operations:
  - Addition
  - Subtraction
  - Multiplication
  - Division
- Handling edge cases like **division by zero** and **negative numbers**.

### **Testing**
- Writing **unit tests** for all functions using Jest.
- Achieving **100% code coverage** for the core module.

### **Version Control**
- Managing the project under **Git version control** and hosting it on GitHub.

### **CI/CD Pipeline**
- Setting up a **GitHub Actions pipeline** to:
  - Automatically run tests on every push or pull request.
  - Generate and upload a **code coverage report** as an artifact.

### **Documentation**
- Providing clear instructions for **installation**, **usage**, and **testing** in this `README.md` file.

---

## **📋 Prerequisites**
Before you begin, make sure you have the following installed:
- **Node.js** (version >= 20.0.0)
- **npm** (comes with Node.js)

To check your Node.js version, run:
```bash
node -v
```

---

## **⚙️ Installation**
Follow these steps to set up the project:

1. Clone this repository:
   ```bash
   git clone https://github.com/DarknessHunter/SSGS-calc.git
   ```
2. Navigate to the project directory:
   ```bash
   cd SSGS-calc
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

---

## **🚀 Usage**
You can use the **SSGS Calculator** via the command-line interface (CLI). 

### Start the CLI:
Run this command to start the interactive CLI:
```bash
npm start
```

### Example Interaction:
1. Select an operation (e.g., addition).
2. Enter two numbers.
3. View the result.

---

## **🧪 Testing**
To run the unit tests, use the following command:
```bash
npm test
```

### Coverage Report:
The tests aim for 100% code coverage. After running the tests, you can view the coverage report in the terminal or as an HTML file in the `coverage/` directory.

---

## **📂 Project Structure**
```
SSGS-calc/
├── start.js           # Command-line interface (CLI)
├── package.json       # Project metadata and dependencies
├── calculator.test.js # Jest test file
├── jest.config.js     # Jest configuration
└── .github/          # GitHub Actions workflow directory
```

---

## **🛠️ Issues and Contributions**
### Found a Bug?
Report it in the [Issues section](https://github.com/DarknessHunter/SSGS-calc/issues).

### Want to Contribute?
Feel free to fork the repository, make your changes, and submit a pull request. Check out our [contributing guidelines](CONTRIBUTING.md) for details.

---

## **📜 License**
This project is licensed under the [ISC License](LICENSE).

---

## **🌐 Links**
- **Repository**: [SSGS Calculator GitHub Repo](https://github.com/DarknessHunter/SSGS-calc)
- **Bug Tracker**: [Report Issues](https://github.com/DarknessHunter/SSGS-calc/issues)
- **Homepage**: [SSGS Calculator Readme](https://github.com/DarknessHunter/SSGS-calc#readme)
