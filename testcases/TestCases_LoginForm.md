#  Test Cases for Login Form

| Test Case ID | Scenario / Description | Pre-condition | Steps to Execute | Expected Result | Actual Result | Status |
|--------------|------------------------|----------------|------------------|-----------------|----------------|---------|
| TC001 | Verify login with valid credentials | Application is open | 1. Enter username `admin`<br>2. Enter password `1234`<br>3. Click **Login** | “Login Successful!” message appears in green | (To fill after test) | Pass/Fail |
| TC002 | Verify login with invalid password | Application is open | 1. Enter username `admin`<br>2. Enter password `wrong`<br>3. Click **Login** | “Invalid Username or Password!” message appears in red | (To fill after test) | Pass/Fail |
| TC003 | Verify login with empty fields | Application is open | 1. Leave fields blank<br>2. Click **Login** | Browser should show “Please fill out this field.” | (To fill after test) | Pass/Fail |
| TC004 | Verify message color for valid login | Application is open | 1. Login with valid credentials | Success message color = green | (To fill after test) | Pass/Fail |
| TC005 | Verify message color for invalid login | Application is open | 1. Login with invalid credentials | Error message color = red | (To fill after test) | Pass/Fail |
