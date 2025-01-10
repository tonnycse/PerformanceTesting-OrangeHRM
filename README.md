# OrangeHRM Performance Testing Project

This project focuses on **performance testing** of the OrangeHRM Demo Website. The tests simulate user interactions with the application and validate the system's performance, accuracy, and scalability.

---

## Project Overview

The primary goal of this project is to ensure the stability of the OrangeHRM application by testing critical functionalities. 

## Key Features Tested

- **Login**
- **Validation**
- **My Info**
- **Admin Panel**
- **Dashboard**
- **Logout**

---

## Tools Used

- **JMeter**: For creating and executing performance and load tests.
- **BlazeMeter**: For recording user workflows and generating test scripts.

---

## Test Setup

### 1. **Thread Group Configuration**
- **Number of Threads**: 10.
- **Ramp-Up Period**: 10 seconds.
- **Loop Count**: 1.

### 2. **Recorded Actions**
- Navigate to the Login Page.
- Perform Login Validation.
- Access the My Info and Admin sections.
- Interact with the Dashboard.
- Perform Logout.

### 3. **Assertions**
- **Response Assertion**
- **Duration Assertion**
- **Size Assertion**
- **HTML Assertion**

---

## Results Analysis

### Listeners Added:
- **View Results Tree**
- **View Results in Table**
- **Aggregate Report**
- **Graph Results**

---

## How to Run the Tests

1. **Prerequisites**:
   - Install JAVA on your system.
   - Install JMeter on your system.
   - Install BlazeMeter Plugin.

2. **Setup**:
   - Import the `.jmx` file for the test plan.
   - Configure thread groups and parameters as per your requirement.

3. **Execute the Test**:
   - Open JMeter.
   - Load the test plan.
   - Click **Start** to execute the test.

4. **Analyze Results**:
   - View test results using listeners like **Aggregate Report**, **Graph Results**, etc.

---

## How to make Reports

- Save the .jmx file in bin foulder
- Create a report folder
- Open with JMeter
- Run Command:
jmeter -n -t filename.jmx -l report\filename.jtl
- Run Command for Report:
jmeter -g report\filename.jtl -o report\filename.html













