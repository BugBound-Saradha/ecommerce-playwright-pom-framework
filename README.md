# 🛒 Ecommerce Playwright POM Framework

## 📌 Overview

This project is a **test automation framework** built using **Playwright** and follows the **Page Object Model (POM)** design pattern. It is designed for automating end-to-end testing of an e-commerce web application with a focus on **scalability, maintainability, and reusability**.

The framework organizes UI interactions into reusable page classes, making test scripts cleaner and easier to manage.

---

## 🚀 Key Features

* ✅ Built with **Playwright**
* ✅ Implements **Page Object Model (POM)**
* ✅ Structured and modular test architecture
* ✅ Supports **UI automation for e-commerce workflows**
* ✅ Reusable components for pages and actions
* ✅ Easy to extend and maintain

---

## 🧱 Framework Architecture

Typical structure includes:

```
project-root/
│
├── pages/          # Page Object classes (UI elements + actions)
├── tests/          # Test cases
├── utils/          # Helper functions/utilities
├── fixtures/       # Custom fixtures (if implemented)
├── config files    # Playwright config, env setup
└── package.json
```

### 🔹 Page Object Model (POM)

* Each page (Login, Product, Cart, etc.) is represented as a class
* Encapsulates:

  * Locators
  * Actions (methods)
* Improves:

  * Maintainability
  * Reusability
  * Readability ([GitHub][1])

---

## ⚙️ Prerequisites

Before running the project, ensure you have:

* Node.js installed
* npm or npx available
* Playwright installed

---

## 📥 Installation

```bash
# Clone the repository
git clone https://github.com/BugBound-Saradha/ecommerce-playwright-pom-framework.git

# Navigate to project folder
cd ecommerce-playwright-pom-framework

# Install dependencies
npm install

# Install Playwright browsers
npx playwright install
```

---

## ▶️ Running Tests

```bash
# Run all tests
npx playwright test

# Run specific test file
npx playwright test tests/<file-name>.spec.ts

# Run in headed mode
npx playwright test --headed
```

---

## 🧪 Test Scenarios (E-commerce Examples)

Typical automated flows include:

* 🔐 User login
* 🛍️ Product selection
* ➕ Add to cart
* 🧾 Checkout validation

Example flow:

1. Login to application
2. Add product to cart
3. Navigate to cart
4. Validate cart contents ([Medium][2])

---

## 🔧 Best Practices Used

* Separation of test logic and UI interactions (via POM)
* Reusable page methods
* Clean folder structure
* Minimal code duplication
* Scalable design for large test suites

---

## 📈 Benefits of This Framework

* Easier maintenance when UI changes
* Faster test development
* Improved readability of test cases
* Better scalability for large projects

---

## 🤝 Contributing

* Fork the repo
* Create a feature branch
* Submit a pull request

---

## 📌 Summary

This repository is a solid **starter framework for Playwright automation** using POM, especially suited for:

* QA engineers learning automation
* Building scalable test suites
* E-commerce application testing

---
