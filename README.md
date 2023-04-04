# Quality Assurance

> I'm learning Automated Quality Assurance, I will be using this repo to document my journey, 
share my notes with others and demonstrate my knowledge to potential employers.

# Software Testing Concepts Table of Contents

1. [What is Software Testing](#what-is-software-testing)
    - [Dynamic vs Static  vs Validation vs Verification Testing](#dynamic-vs-static-vs-validation-vs-verification-testing)
    - [Objectives of Testing](#objectives-of-testing)

2. [Software Development Livecyle](#software-development-livecyle)

    1. [The software development life cycle (SDLC) Processes](#the-software-development-life-cycle-sdlc-processes)

    2. [Sequential Development](#sequential-development)
        - [The Waterfall Model](#the-waterfall-model)
        - [The V-Model](#the-v-model)

    2. [Interactive & Incremental](#interactive--incremental) 
        - [Agile | software development](#agile--software-development)
            - [Agile Frameworks](#agile-frameworks)
        - [Scrum | The Agile Framework](#scrum--the-agile-framework)

3. [Test Processes](#test-processes) 
    - [Test Processes Activities](#test-processes-activities)
    - [Test Levels](#test-levels)

4. [Testing Types](#testing-types)

5. [Technologies used for Quality Assurance and Software Testing](#technologies-used-for-quality-assurance-and-software-testing)

6. [How to write Test Scenario](#how-to-write-test-scenarios)

7. [How to write Test Cases](#how-to-write-test-cases)
    - [Positive vs Negative Test Case](#positive-vs-negative-test-case)
    - [Test Case title](#test-case-title)
    - [Test Case precondition](#test-case-precondition)
    - [The Test Case steps](#the-test-case-steps)
    - [Test Data](#test-data)
    - [High level Test Case & Low level Test Case](#high-level-test-case--low-level-test-case)
    - [Expected Result](#expected-result)
    - [Test Scenarios (Test Suites)](#test-scenarios-test-suites)
    - [Test Environment](#test-environment)
    - [Test Results](#test-results)
    - [Test Status](#test-status)
    - [Test Case Example](#test-case-example)



--- 
# What is Software Testing
> Software testing is a way to assess the quality of a software, system or application and to detect any errors, bugs, defects, or other issues that may affect its functionality, performance, and overall quality. Software testing is a process which includes many different activities, It involves running the software, system or application with the intention of finding faults or defects, and comparing the actual results against the expected results to identify discrepancies.

## Dynamic vs Static  vs Validation vs Verification Testing 
Dynamic testing: involves executing the software system or application and observing its behavior in real-time to identify any defects or issues that may affect its functionality. 

Static testing: This type of testing involves analyzing the software system or application without executing it to identify issues that may affect its quality, such as code errors, syntax errors, or logical errors. 

Validation testing: Ensures that the software system or application meets the specified requirements and functions as intended to satisfy the user's needs. 

Verification testing: The software system or application adheres to the established standards and requirements throughout the development cycle. 

## Objectives of Testing
1. Requirements Fulfillment
2. Preventing & Find Defects
3. Reduce Risk
4. Compliance with Laws
5. Building Confidence
6. Providing Information to Stakeholders

--- 

# Software Development Livecyle
> The software development life cycle (SDLC) is a structured process used by software development teams to design, build, test, and deploy high-quality software. SDLC describes the types of activities performed at each stage in a software development project, and how the activities relate to one another logically and chronologically.

## The software development life cycle (SDLC) Processes
1. Planning: the project scope, requirements, timelines, and resources are defined. This includes identifying the software objectives, user needs, and project constraints.

<!-- Analysis: the software requirements are analyzed and documented. This includes identifying the functional and non-functional requirements of the software. -->

2. Design: the software architecture, system design, and database design are developed. This includes creating a detailed design specification that outlines how the software will be built and how the different components will work together.

3. Implementation | Build: the software code is developed and tested. This includes coding, unit testing, integration testing, and debugging.

4. Testing | Fix: the software is tested to ensure that it meets the specified requirements and quality standards. This includes testing for functionality, performance, usability, security, and compatibility.

5. Deployment | Release: In this stage, the software is released to production and made available to end-users. This includes installation, configuration, and training.


## Sequential Development: 
> A sequential development model describes the software development process as a linear, sequential flow of activities. This means that any phase in the development process should begin when the previous phase is complete. In theory, there is no overlap of phases, but in practice, it is beneficial to have early feedback from the following phase

## The Waterfall Model:
> In the Waterfall model, the development activities are completed one after another. In this model, test activities only occur after all other development activities have been completed.
1. Requirements
2. Design
3. Build
4. Test and fix 
5. Release to customers

## The V-Model
> Unlike the Waterfall model, the V-model integrates the test process throughout the development process, implementing the principle of early testing.

![vmodelimage](vmodel.png)

## Interactive & Incremental 
> Examples of Interactive & Incremental  models. Note: you can have model that’s Interactive & Incremental at the same time, the most famous example is scrum

![interative & Incremental models](in-model.png)

## Agile | software development
> Agile is a project management methodology that emphasizes flexibility, collaboration, and continuous improvement. It involves breaking down a project into small, manageable chunks called sprints, and working on them in short cycles. The goal is to deliver working software quickly and frequently, while continuously adapting to changing requirements and feedback. Agile encourages close collaboration between the development team, the stakeholders, and the customer to ensure that the final product meets the desired outcomes.

### Agile Frameworks 
1. Scrum: A popular framework that focuses on delivering working software incrementally and iteratively, with regular feedback and collaboration.

2. Kanban: A visual framework that focuses on continuous delivery, with a focus on limiting work in progress, and optimizing flow.

3. Lean: A framework that emphasizes continuous improvement, eliminating waste, and creating value for customers.

4. Extreme Programming (XP): A framework that focuses on delivering high-quality software through continuous testing, pair programming, and other practices.

5. Crystal: A family of agile frameworks that emphasizes the importance of communication, collaboration, and simplicity.

6. Dynamic Systems Development Method (DSDM): A framework that emphasizes the importance of active user involvement, frequent delivery, and a focus on business value.

7. Adaptive Software Development (ASD): A framework that emphasizes collaboration, feedback, and continuous learning and improvement.


## Scrum | The Agile Framework
> Scrum is an agile framework for managing and completing complex projects. It involves breaking down a project into short, fixed-length sprints, typically 2-4 weeks long. The development team works on the highest-priority items from the product backlog during each sprint, and holds daily stand-up meetings to coordinate their work. Scrum encourages transparency, inspection, and adaptation throughout the project, and relies on a self-organizing team to deliver high-quality software.

- [Read more](https://www.scrum.org/learning-series/what-is-scrum)
- [The Scrum guide](https://scrumguides.org/) 

--- 
# Test Processes 
>  Test processes refer to the series of activities and tasks that are carried out to ensure that software products and services meet the required standards and specifications.

## Test Processes Activities

1. Test planning: defining the scope of testing, identifying the testing goals and objectives, and determining the resources and timelines required for testing.

2. Test design: developing test cases, test scenarios, and test scripts that will be used to evaluate the software product's functionality, performance, and usability.

3. Test execution: running the tests that were designed in the previous stage, recording the results, and identifying defects and issues.

4. Test reporting: documenting the test results and sharing them with the relevant stakeholders, such as project managers, developers, and customers.

5. Test analysis: analyzing the test results and identifying trends, patterns, and issues that need to be addressed.

6. Test maintenance: updating the test cases and scripts as new features are added to the software product or as requirements change.

## Test Levels
> Test levels are groups of test activities that are organized and managed together. Each test level is an instance of the test process, test levels are related to other activities within the software development lifecycle.

1. Unit: Component testing (also known as unit or module testing) focuses on components that are separately testable (most of the time developer are responsible for it)
2. Integration: Integration testing focuses on interactions between components or systems
    1. There’s 2 type of Integration testing 
        1. Component Integration (also developer is responsible)
        2. System Integration (responsibility by tester)
3. System: System testing focuses on the behavior and capabilities of a whole system or product 
4. Acceptance: like system testing, typically focuses on the behavior and capabilities of a whole system or product. (Mostly done by users os stakeholders)
4. Alpha Testing: is done inside the organization
5. Beta Testing: is done by users at their location

---
# Testing Types
> There are several types of software testing that can be performed to ensure the quality of the software. Some of the most common testing types include: 

1. Functional testing: test a system functionality, e.g a web app login page
2. Non-functional testing: how the sys performs e.g speed, security etc…
3. Black-Box Testing: Testing without knowing the internal structure of the system or code
4. White-Box Testing: Testing while monitoring the internal structure of the system or code
5. Dynamic Testing: Testing that includes executing the software
6. Static Testing: Testing that doesn’t includes executing the software
7. Retesting (Confirmation Testing): Testing that doesn’t includes executing the software
8. Regression Testing: Testing unchanged areas to ensure they are not affected by changes
9. Smoke Testing: Testing main functionalities to ensure that the build is stable enough to continue testing

--- 
# Technologies used for Quality Assurance and Software Testing
> Through my research, I identified the diverse technologies utilized by Quality Assurance experts in software testing.


<details>
<summary>1. Programming languages</summary>

- Python
- SQL
- JavaScript | Typescript
- C#
- Java

</details>

<details>
<summary>2. Test Automation Frameworks</summary>

- Selenium (automates web browsers)
- playwright (End-to-End testing for modern web apps)
- Cypress (Javascript testing framework)
- Appium (open-source framework to automated app testing on Android & iOS)
- Espresso (A native testing framework for android)
- Android Studio Emulator (For manual & automation testing with apks)
- TestComplete
- Protractor
- Cucumber

</details>

<details>
<summary>3. API Testing</summary>

- Postman (API platform for building, testing and using APIs)
- RestAssured (Rest API’s testing in Java)
- SoapUI (Testing tool for SOAP and REST testing)
- Karate Framework (API test-automation, mocks, performance-testing and UI automation)

</details>

<details>
<summary>4. Project | Test management Tools </summary>

- Jira
- Confluence
- Trello
- Asana
- TestRail
- Zephyr
- PractiTest
- TestPad

</details>

<details>
<summary>5. Continuous Integration and Deployment (CI/CD) tools</summary>

- Jenkins
- GitLab CI/CD
- CircleCI
- Travis CI
- Bamboo

</details>

<details>
<summary>6. Performance Testing Tools tools</summary>

- JMeter
- LoadRunner
- Gatling
- BlazeMeter

</details>

<details>
<summary>7. Virtualization and Containerization Tools</summary>

- Docker
- Kubernetes
- Vagrant
- VirtualBox

</details>

<details>
<summary>8. Database Testing</summary>

- PgAdmin
- MySQLworkbench
- DBeaver

</details>

<details>
<summary>9. Version Control</summary>

- Git

</details>


--- 
# How to write Test Scenarios
> A Test Scenario is defined as any functionality that can be tested. It is also called Test Condition or Test Possibility. As a tester, you should put yourself in the end user shoes and figure out the real-world scenarios and use cases of the application under test. e.g: Testing a registration page, what are the scenarios a user is expected to go trough, and test all those scenarios.

> <span style="color: red;" >  Note: there’s a difference between Test Scenario and Test Cases. </span>



1. Carefully study the requirement Document - 
    1. Business Requirement Specification (BRS)
    2. Software Requirement Specification (SRS)
    3. Functional Requirement Specification (FRS)
    4. System Under Test (SUT)
2. Isolate every requirements and identify what possible user actions need to be tested for it. Figure out the technical issues associated with the requirements. Also, remember to analyze and frame possible system abuse scenarios by evaluating the software with the hacker’s eyes
3. Enumerate test scenarios that cover every possible feature of the software. Ensure that these scenarios cover every user flow and business flow involved in the operation of the website or app.
4. After listing the test scenarios, create a traceability Matrix to ensure that every requirement is mapped to a test scenario.
5. Get the scenarios reviewed by a supervisor, and push them to be reviewed by other stakeholders involved in the project.

--- 
# How to write Test Cases
> A Test Case is a set of steps that tests a specific functionality or aspect of an application to verify whether it works as intended or not. It has specific inputs, expected outputs, and actual outputs.

<br>

## Positive vs Negative Test Case
> The 2 types of Test Cases: Positive vs Negative Test Case (Note: not related to Pass or Fail Test Case’s) 

1. Positive Test Case: Is when you test something a normal scenario a user will do.
2. Negative Test Case: testes the invalid scenarios, e.g user made a mistake or suspicious activities

<br>
<br>

## Test Case title
> The title of the test case is a brief summary that describes the purpose or objective of the test. It should be clear, concise, specific and not broad to the test being performed.

- Example: Verify login with a valid username and password.


<br>
<br>


## Test Case precondition
> Preconditions are the conditions that must be met before the test case can be executed. Preconditions help ensure that the test is performed consistently and accurately, and that any dependencies or requirements are met. 

- Example a precondition for a Login Functionality Test: User is already register with valid credentials.

<br>
<br>


## The Test Case steps
> Outline the specific actions that must be performed to execute the test. They should be written in a clear and concise manner, and should be easily reproducible. The steps should also include the expected results or outcomes of each action. 

1. Example for a "Login Functionality Test":
    - Open the login page
    - Enter valid username 
    - Enter valid password
    - Click on the login button
    - Verify that the user is logged in and redirected to the home page
<br>
<br>


## Test Data
> Test data refers to the input values and conditions that are used to validate and verify the behavior, functionality, and performance of software during testing. Test data is designed to represent a range of typical and atypical scenarios that the software may encounter in real-world usage. It may include valid and invalid data

<br>
<br>


## High level Test Case &  Low level Test Case
> High level Test Case: Is about checking functionality from outside(user perspective), the functionality of a software/product is define in a broader way without going into deep functionality. e.g:

1. if we have to write high level test cases for login functionality we'll test that User should be able to login success full with valid credentials.
2. High level test cases are usually written before the software/product is ready for delivery.
3. Testing an E-commerce site: Enter valid login credentials, add  3 valid items to the card.
4. High level test cases are usually most common types of test cases, and leaves so creativity in the hand of the testers.

<br>

> Low level Test Case: is about checking of all components related to a particular functionality, it define the functionality of a software/product in deep way, generally include details like Excepted Result , Test Data, etc...

1. If u are testing a login then under low level test case, use provided credentials to  test user & password box and, login button, forget password option, UI & alignment etc..
2. Testing an E-commerce site: Enter username: abcd, Enter password: 123456, click the login button, add these 3 specific items to the card, if the total is above $45 does user get free shipping options.
3. Low level test case is more complex, takes more time, is typically written by developers, also require advance knowledge of the software/product and everything  is specific from preconditions, test data, expected results and postconditions and detailed description of actions (where applicable).

<br>
<br>


## Expected Result
> A test case expected result is the outcome that a software tester anticipates after executing a particular test case. It is a pre-defined set of conditions, values, or behaviors that the software application under test should exhibit when a specific test is performed. If the actual result differs from the expected one, the difference is documented and called a bug.

- eg: User is login successfully and redirected to home page.
- Actual Vs Expected Result: Actual can be defined as the result received after performing a test case. The actual result may or may not match the expected result. And, if the actual result is not matching with the expected result, then it is called a bug.

<br>
<br>


## Test Scenarios (Test Suites)
> A test suite is a collection of test cases or test scenarios. Test suites are organized into logical groups based on their purpose, and each test case focuses on testing a specific functionality, or application features being tested. 

- Example: Testing login functionality: we can have multiple Test Suites: 1. for login using gmail, 1. for login using apple, 1 for login using facebook etc..

<br>
<br>


## Test Environment
> A test environment is a setup or configuration that is created to facilitate the execution of software tests. It is a replica of the production/user environment. A test environment may include hardware, software, network infrastructure, databases, and other necessary components that are required to execute software tests. The purpose of the test environment is to provide a controlled environment that mimics conditions that are as close to real-world conditions as possible.

## Example:
1. Hardware: e.g: mobile with 4g ram, intel i9 processor, device at least 7 inch screen etc..
2. Software: e.g the operating system android 10, ios 11 or linux (specific distro) 4.xx
3. Network:  e.g: wifi or mobile data, smooth network or drop connection while testing.
4. example: 
    - Windows 10 –Chrome –Wi-Fi
    - Samsung Galaxy Note 10 -Android 10 –4G Network 
    - iPhone 11 –iOS 13.3.1 –5G Network

<br>
<br>


## Test Results
> A Test result is the result you received after performing a test case. Note: Never fill the actual result filed until you execute the test case.

<br>
<br>

## Test Status
| New (Ready to test) | The test case is not executed |
| --- | --- |
| Pass | The test case is executed and the actual result is the same as the expected result. |
| Fail | The test case is executed and the actual result is different from the expected result |
| Blocked/Skipped | The test case can’t be executed  |

<br>
<br>

## Test Case Example
| Title | Testing login with valid credentials |
| --- | --- |
| Precondition  | User is already registered using valid credentials |
| Test Steps | 1. Enter a valid username 2. Enter a valid password 3. Click on sign in |
| Expected Result | User is logged in successfully & User is redirected to Home page |
| Test Suite | Login |
| Test Environment | Iphone 11 - iOS 10 – 4G Mobile Network  |
| Actual Result | Same as expected  |
| Status | Pass |