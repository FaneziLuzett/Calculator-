
# 🧮 Calculator

A **simple UI Calculator program written in Java** that performs basic arithmetic operations. Built with modular structure and test coverage to ensure correctness and ease of maintenance.

---

## 📌 Description

This project demonstrates a basic calculator with a user interface (UI), designed to perform essential arithmetic operations. Ideal for beginners to understand Java programming structure and how to set up a Maven-based Java application.

---

## 🚀 Features

- ➕ Addition  
- ➖ Subtraction  
- ✖️ Multiplication  
- ❌ Deleting (Clear Input/Reset)

---

## 🛠 Technologies Used

- Java
- Maven (for build automation)
- JUnit (for unit testing)

---

## 💻 Installation Instructions

### ✅ Prerequisites

Ensure you have the following installed:

- Java Development Kit (JDK 8 or higher)  
- Maven  
- Git (optional, for cloning)

### 📥 Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/Lilita-Xelelo/Calculator-.git
   cd Calculator-
   ```

2. **Build the project using Maven**

   ```bash
   mvn clean install
   ```

3. **Run the application**

   If the project uses a GUI, you can run it using:

   ```bash
   mvn exec:java -Dexec.mainClass="com.lilita.calculator.Calculator"
   ```

   *(Make sure to update the main class path if it's different.)*

---

## 🔧 Project Structure

```
Calculator-/
├── src/
│   ├── main/java/com/lilita/calculator/
│   │   └── Calculator.java        # Main calculator logic
│   └── test/java/com/lilita/calculator/
│       └── CalculatorTest.java    # Unit tests
├── pom.xml                        # Maven build configuration
├── README.md                      # Project documentation
├── target/                        # Compiled output
└── .vscode/                       # VS Code settings (optional)
```

---

## 🧪 Basic Usage Example

Once the calculator UI launches:

- Enter numbers in the input fields.
- Click on the operation button (`+`, `-`, `*`) to get the result.
- Use the delete or reset function to clear inputs.

Example:

```
Input: 7 * 4  
Output: 28
```

---

## ⚙️ Configuration Options

No special configuration is needed for basic operation. However, you can customize:

- **Calculator.java** — Modify or extend arithmetic logic.
- **pom.xml** — Add libraries or plugins as needed.

---

## 🛠 Troubleshooting

| Problem                           | Solution                                                                 |
|----------------------------------|--------------------------------------------------------------------------|
| `mvn: command not found`         | Make sure Maven is installed and added to your system's PATH.           |
| Compilation errors               | Ensure your Java version is compatible with the project (JDK 8+).       |
| `Main class not found` error     | Double-check the `exec.mainClass` in the Maven command.                 |
| GUI doesn't appear               | Ensure you are running in an environment that supports GUI (e.g. not WSL).|

---

## 🤝 Contributing

We welcome contributions!

1. Fork the repository  
2. Create a new branch: `git checkout -b feature/YourFeatureName`  
3. Commit your changes: `git commit -m "Add your feature"`  
4. Push the branch: `git push origin feature/YourFeatureName`  
5. Open a pull request

Please follow clean code practices and test your changes.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Created by **Lilita Xelelo**  
For any queries or suggestions, feel free to reach out via GitHub.

---
