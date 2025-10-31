# 🧠 Demoblaze Automated Testing Project (Katalon Studio)

## 📋 Overview
This project automates end-to-end testing for the [Demoblaze e-commerce website](https://www.demoblaze.com/) using **Katalon Studio**.  
It covers key user workflows to ensure functionality, performance, and user experience consistency across modules.

### 🧩 Modules Covered
- 🧍‍♂️ User Signup  
- 🔐 Login  
- 🛍️ Product Browsing & Details  
- 🛒 Cart Management  
- 💳 Checkout  
- 💬 Contact Form  
- 🎥 About Us (video verification)

---

## 🧪 Test Summary
| Metric | Result |
|--------|---------|
| **Total Test Cases** | 32 |
| **Passed** | 24 |
| **Failed** | 8 |
| **Execution Time** | 12m 55s |

---

## 🧰 Tools & Technologies
- **Katalon Studio** (Groovy-based test automation)
- **Selenium WebDriver**
- **Test Suite Collections**
- **HTML Reports & Screenshots**
- **GitHub** for version control

---

## 🧱 Project Structure
```
DemoBlaze/
├── Test Cases/
│   ├── Signup_TCs/
│   ├── ProductBrowsingAndDetails_TCs/
│   ├── Checkout_TCs/
│   ├── AboutUs_TCs/
│   ├── ContactForm_TCs/
│   ├── CartManagement_TCs/
│   └── LogIn_TCs/

├── Test Suites/
│   ├── Signup_TS/
│   ├── ProductBrowsingAndDetails_TS/
│   ├── Checkout_TS/
│   ├── AboutUs_TS/
│   ├── ContactForm_TS/
│   ├── DemoBlaze_FULLTEST
│   ├── CartManagement_TS/
│   └── LogIn_TS/

├── Object Repository/
├── Profiles/
├── Reports/
└── Keywords/
```

---

## 🚀 How to Run
1. Open the project in **Katalon Studio**.  
2. Configure your preferred browser (Chrome recommended).  
3. Run individual test suites or execute all via **Test Suite Collection**.  
4. View results and screenshots in the **Reports** folder.

---

## 📸 Reporting
- Detailed **HTML reports** and **execution logs** generated per suite.  
- Optional **email or CI/CD integration** for reporting (can be added).

---

## 📁 Example Test Case
```groovy
WebUI.openBrowser('')
WebUI.navigateToUrl('https://www.demoblaze.com/')
WebUI.click(findTestObject('Object Repository/LoginPage/Login_Button'))
WebUI.setText(findTestObject('Object Repository/LoginPage/Username_Field'), 'testuser')
WebUI.setEncryptedText(findTestObject('Object Repository/LoginPage/Password_Field'), 'encrypted_password')
WebUI.click(findTestObject('Object Repository/LoginPage/Login_Submit'))
WebUI.verifyElementPresent(findTestObject('Object Repository/HomePage/Welcome_Message'), 10)
WebUI.closeBrowser()
```

---

## 👤 Author
**Omar Hazem**  
🎓 *QA Engineer | Automation Tester*  
📅 *Created: October 2025*  
🌐 *Part of my Automation Testing Portfolio*

---

✅ *This project demonstrates professional web automation using Katalon Studio, emphasizing clean structure, modularity, and reliable reporting.*
