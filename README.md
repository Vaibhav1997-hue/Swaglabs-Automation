# Swaglabs-Automation
Automated Functional Testing of SauceDemo (Swag Labs)
Website: [https://www.saucedemo.com/v1/]

Automate the testing of key functionalities on the SauceDemo / Swag Labs e-commerce site using Selenium WebDriver, TestNG and generate automated test reports using Extent reports.

Tools & Technologies Used

Language | Java
| Automation Tool | Selenium WebDriver
| Testing Framework | TestNG
| Data Source | JSON
| Reporting Tool | Extent Reports
| Build Tool | Maven
| IDE | IntelliJ IDEA / Eclipse
| Browser | Chrome (via ChromeDriver)

Test Scenarios Covered

Homepage Load Verification after Login
Login with valid credentials
Assert homepage loads successfully
Data-driven: multiple credential sets from JSON
✅ 2. Product Filtering
Apply sort: Price (Low to High)
Extract and print product names post-filtering
✅ 3. Cart Operations
Select and add a product to the cart
Verify cart contains selected product
✅ 4. Checkout Process
Proceed to checkout
Fill in required details
Complete purchase
Assert confirmation message
Reports generated using Extent Reports

Shows test name, status (Pass/Fail), and failure screenshots
Report output: test-report.html
Test Data- { "standard_user", "secret_sauce" }, { "problem_user", "secret_sauce" }, { "performance_glitch_user", "secret_sauce" },

How to Run the Project Prerequisites Java 8+

Maven installed

Chrome browser

ChromeDriver in system PATH

Assignment Info Course: Software Testing / Automation

Submitted By: Vaibhav Khondekar

Date: 4/18/2025
