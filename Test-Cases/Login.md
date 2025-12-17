# Login – Test Cases

## Valid Scenarios

### TC-LOGIN-001
**Title:** Login with valid credentials  

**Steps:**
1. Access the login page
2. Enter valid username and password
3. Click on Login button

**Expected Result:**  
User is successfully authenticated and redirected to the home page.

**Status:** Pass

---

## Invalid Scenarios

### TC-LOGIN-002
**Title:** Login with empty required fields  

**Steps:**
1. Access the login page
2. Leave username and password empty
3. Click on Login button

**Expected Result:**  
System displays validation message indicating required fields.

**Status:** Pass

---

### TC-LOGIN-003
**Title:** Login with invalid credentials  

**Steps:**
1. Access the login page
2. Enter invalid username or password
3. Click on Login button

**Expected Result:**  
System displays error message and denies access.

**Status:** Pass

---

### TC-LOGIN-004
**Title:** Login with empty username and valid password  

**Steps:**
1. Access the login page
2. Leave username empty
3. Enter a valid password
4. Click on Login button

**Expected Result:**  
System displays validation message for username field.

**Status:** Pass

---

### TC-LOGIN-005
**Title:** Login with valid username and empty password  

**Steps:**
1. Access the login page
2. Enter a valid username
3. Leave password empty
4. Click on Login button

**Expected Result:**  
System displays validation message for password field.

**Status:** Pass
