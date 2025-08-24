# StandAloneTest - Selenium Automation Script

This project demonstrates an **end-to-end Selenium automation** in Java using **Selenium WebDriver** and **TestNG-style waits**.

## 🚀 What this script does
The script automates the following workflow on [Rahul Shetty Academy Client](https://rahulshettyacademy.com/client):

1. Launches Chrome browser using **ChromeDriver**
2. Logs in with test credentials
3. Locates a product and **adds it to the cart**
4. Waits for the loading animation to disappear
5. Opens the shopping cart and **proceeds to checkout**
6. Selects a country dynamically from a dropdown
7. Completes the purchase

---

## 🛠️ Features and Methods Used
- **Implicit Waits**: Global synchronization for locating elements  
- **Explicit Waits** (`WebDriverWait`, `ExpectedConditions`): Handle dynamic UI elements  
- **Element Locators**: `By.id`, `By.cssSelector`, `By.xpath`  
- **WebElement interactions**: `sendKeys`, `click`, `getText`  
- **Nested element handling**: Locating buttons inside a product card  
- **Loops**: Iterating through options to select "Nigeria"  
- **Navigation**: `driver.get()` to open the site

---

## 📂 Project Structure
```
src/
 └── kene/
     └── StandAloneTest.java
```

---

## ▶️ How to Run
1. Install **Java 8+** and **Maven**
2. Download **ChromeDriver** and ensure it matches your Chrome version
3. Clone this repository
4. Run the Java file:

```bash
javac StandAloneTest.java
java StandAloneTest
```

---

## ✅ Dependencies
- **Selenium WebDriver**
- **ChromeDriver**
- **Java 8+**
- (Optional) TestNG for structured test management

---

## 📌 Notes
- Make sure to replace login credentials with valid ones.
- Update `ChromeDriver` path if it’s not added to system PATH.
