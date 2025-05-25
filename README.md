
# 🧪 TDD / BDD Final Project

Welcome to the **Test-Driven Development (TDD) & Behavior-Driven Development (BDD) Final Project**! 🎉 This project helps you master writing tests first and describing software behavior clearly with BDD to ensure high-quality, maintainable software.

---

## 🚀 Project Overview

This project guides you through:

* Creating **fake products** and testing your data model 🛍️
* Building a **REST API** with full test coverage 🔗
* Designing a **minimalist Product Admin UI** and writing UI tests 🖥️
* Loading test data and implementing **BDD scenarios** with Behave ⚙️
* Automating UI actions via Selenium WebDriver for real browser testing 🕵️‍♂️

---

## 📋 Features Tested

* **Create a Product** 🆕
* **Read a Product** 🔍
* **Update a Product** ✏️
* **Delete a Product** ❌
* **List All Products** 📜
* **Search Products by Category** 🗂️
* **Search Products by Availability** ✅ / ❌
* **Search Products by Name** 🏷️

---

## 🛠️ Technologies & Tools

* **Python 3**
* **Flask** (REST API backend)
* **Behave** (BDD testing framework)
* **Selenium WebDriver** (UI automation)
* **requests** (HTTP client for API testing)
* **honcho** (process manager)
* **Git** (version control)

---

## 📁 Project Structure

```
/features
    /steps
        load_steps.py       # Load background data into the system
        web_steps.py        # Step definitions for UI tests
    products.feature        # BDD feature file describing scenarios
/app
    models.py               # Product data model
    routes.py               # REST API endpoints
/tests
    test_models.py          # Unit tests for models
    test_routes.py          # API endpoint tests
```

---

## 📝 How to Run

1. **Start the service**

```bash
honcho start
```

2. **Run unit tests**

```bash
nosetests --with-coverage
```

3. **Run BDD tests**

```bash
behave
```

---

## ✍️ Writing Tests

* Use **TDD** to write tests first, then implement the feature.
* Use **BDD** to write user-focused scenarios in `products.feature`.
* Step definitions in `web_steps.py` automate UI actions and assertions.
* Background data loaded in `load_steps.py` ensures consistent test setup.

---

## ✅ Acceptance Criteria

* All unit tests pass with **95%+ coverage**.
* All 7 BDD scenarios pass:

  * Read, Update, Delete a product
  * List all products
  * Search by Category, Availability, and Name

---

## 📚 Learning Outcomes

* Understand TDD and BDD principles and workflows
* Write clear, reusable test scenarios using Gherkin syntax
* Automate web UI testing using Selenium WebDriver
* Manage test data effectively for reliable test runs
* Use Git for version control and collaboration

---

## 🤝 Contributing

Feel free to open issues or submit pull requests to improve tests, add features, or enhance documentation!

---

