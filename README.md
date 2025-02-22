# Selenium E2E Project

## Introduction
This Test Automation Framework is created using Java + Selenium Web Driver + TestNG + Cucumber + Maven Page Object Model(POM). 
Which can be used across different web based applications.It is used to make the code more readable, maintainable and reusable.

## Technologies/Tools used in building the framework
- IntelliJ IDEA - IDE
- Selenium - Browser Automation library
- Maven - Build automation tool
- Java - Programming language
- TestNG - Test Management library
- BDD - Cucumber
- Extent Reports - Reporting framework
- GitHub - Version control
- Jenkins - CI/CD

## Steps to clone execute the tests
`git clone https://github.com/kaushalkartik/CucumberE2ECICD.git`<br/>
 `cd SeleniumE2EProject`<br/>
 `mvn clean install`<br/>
 `mvn test`

## Screenshot:
- Take Screenshots On test failures Method will automatically capture & store the screenshots under /reports directory. 
  The screenshot files will be named of the test method name.

## Reporting:
- The framework produce index.html report. It resides in the reports folder.This reports gives the link to all the different component of the TestNG reports like Groups & Reporter Output. On clicking these will display detailed descriptions of execution.


## About Project
This is the sample cucumber project use to trigger from bamboo