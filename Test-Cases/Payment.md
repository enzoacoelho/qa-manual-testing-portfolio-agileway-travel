# Payment – Test Cases

## Valid Scenarios

### TC-PAY-001
**Title:** Complete payment with valid credit card details  

**Steps:**
1. Access the payment page after completing passenger details
2. Select a credit card type
3. Enter valid credit card number
4. Enter valid expiry date
5. Enter valid cardholder name
6. Click on Pay Now

**Expected Result:**  
Payment is successfully processed and user is redirected to the confirmation or home page.

---

## Invalid Scenarios

### TC-PAY-002
**Title:** Attempt payment with all required fields empty  

**Steps:**
1. Access the payment page
2. Click on Pay Now without filling any fields

**Expected Result:**  
System displays validation messages and prevents payment submission.

---

### TC-PAY-003
**Title:** Attempt payment with partially filled required fields  

**Steps:**
1. Access the payment page
2. Fill only some of the required fields
3. Click on Pay Now

**Expected Result:**  
System displays validation messages for missing fields and prevents payment.

---

### TC-PAY-004
**Title:** Attempt payment without selecting credit card type  

**Steps:**
1. Access the payment page
2. Fill all required card details
3. Do not select a credit card type
4. Click on Pay Now

**Expected Result:**  
System prevents payment and displays a validation message for card type selection.

---

### TC-PAY-005
**Title:** Enter credit card details that do not match selected card type  

**Steps:**
1. Access the payment page
2. Select a credit card type
3. Enter a credit card number that does not correspond to the selected type
4. Fill remaining required fields
5. Click on Pay Now

**Expected Result:**  
System detects card type mismatch and prevents payment submission.

---

### TC-PAY-006
**Title:** Attempt payment with invalid credit card number format  

**Steps:**
1. Access the payment page
2. Select a credit card type
3. Enter an invalid credit card number format
4. Fill remaining required fields
5. Click on Pay Now

**Expected Result:**  
System displays an error message for invalid card number and prevents payment.

---

### TC-PAY-007
**Title:** Attempt payment with expired credit card  

**Steps:**
1. Access the payment page
2. Select a credit card type
3. Enter a credit card number
4. Enter an expired expiry date
5. Fill remaining required fields
6. Click on Pay Now

**Expected Result:**  
System displays an error message indicating the card is expired and prevents payment.

---

### TC-PAY-008
**Title:** Attempt payment with invalid or empty cardholder name  

**Steps:**
1. Access the payment page
2. Select a credit card type
3. Enter valid card number and expiry date
4. Leave cardholder name empty or enter invalid characters
5. Click on Pay Now

**Expected Result:**  
System displays validation message for cardholder name and prevents payment.

---

### TC-PAY-009
**Title:** Multiple clicks on Pay Now button  

**Steps:**
1. Access the payment page
2. Fill all required fields with valid data
3. Click on Pay Now multiple times quickly

**Expected Result:**  
System processes the payment only once and prevents duplicate submissions.

