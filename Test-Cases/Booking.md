# Booking – Passenger Details

## Valid Scenarios

### TC-BK-001
**Title:** Enter valid passenger first and last name  

**Steps:**
1. Access the passenger details page after selecting a flight
2. Enter a valid first name
3. Enter a valid last name
4. Click on Continue

**Expected Result:**  
Passenger details are accepted and user is redirected to the payment page.

---

## Invalid Scenarios

### TC-BK-002
**Title:** Enter invalid characters in passenger name fields  

**Steps:**
1. Access the passenger details page
2. Enter invalid characters in the first name and/or last name fields
3. Click on Continue

**Expected Result:**  
System displays validation message and prevents progression.

---

### TC-BK-003
**Title:** Attempt to proceed with empty required fields  

**Steps:**
1. Access the passenger details page
2. Leave first name and/or last name empty
3. Click on Continue

**Expected Result:**  
System displays validation message for required fields and does not allow progression.
