# orangehrm# Selenium Automation on Open Source OrangeHRM 

## Technologies Used:
  - Java
  - Selenium (4.6)
  - TestNG
  - Allure
  - Faker Library


## Flow Of Automation
  1. Visit the site: [Open Source OrangeHRM](https://opensource-demo.orangehrmlive.com/) .
  2. Assert the dashboard.
  3. Create 2 new employees.
  4. Search the employees with their Id and assert that 2 employees are found.
  5. Then login with the last employee credential.
  6. Update some employee info (e.g Nationality, Blood Group, License Expiry Date).
  7. Now go to my info page and assert the edited info.
  8. Finally logout.

## Test Cases For Automation
 - [Google Drive](https://docs.google.com/spreadsheets/d/1rV5zmZRtifpRC2xvnloNuAk0ri_6O85yqIyaYjh6kY0/edit?usp=sharing)

 ## Requirements
  - Java needs to be installed in device

 ## Video of Result
  - [Youtube](https://youtu.be/ZwJmDiy8qUg)

## Allure Report

![Allure Report Overview](https://github.com/Rakshit023/orangehrm/blob/main/overview.png)
![Allure Report Suites](https://github.com/Rakshit023/orangehrm/blob/main/suites.png)
![Allure Report Overview](/images/graphs.png "Allure Report Graph")

# Selenium Test case with PageObject Model Pattern.
Page Object Pattern Test Cases in Selenium-Java with Advance Reports


Page Object model is an object design pattern in Selenium, where web pages are represented as classes, and the various elements
on the page are defined as variables on the class. All possible user interactions can then be implemented as methods on the class


![Alt text](https://solutionscafe.files.wordpress.com/2014/01/untitled10.png "Page Object Model Example")
Code
