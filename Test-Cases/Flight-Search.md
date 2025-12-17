# Flight Search – Test Cases

## Valid Scenarios

### TC-FS-001
**Title:** Select return trip with valid dates  

**Steps:**
1. Access the flight search page
2. Select trip type as Return
3. Enter a valid origin and destination
4. Select valid departure and return dates
5. Observe available flights displayed automatically
6. Select one available flight
7. Click on Continue

**Expected Result:**  
Available flights are automatically displayed after filling the search criteria, allowing the user to select a flight and proceed to the next step.

---

### TC-FS-002
**Title:** Select one-way trip with valid date  

**Steps:**
1. Access the flight search page
2. Select trip type as One-way
3. Enter a valid origin and destination
4. Select a valid departure date
5. Observe available flights displayed automatically
6. Select one available flight
7. Click on Continue

**Expected Result:**  
Flights are displayed automatically and the user can proceed with a one-way flight selection.

---

### TC-FS-003
**Title:** Select return trip with same departure and return date  

**Steps:**
1. Access the flight search page
2. Select trip type as Return
3. Enter a valid origin and destination
4. Select the same date for departure and return
5. Observe available flights displayed automatically
6. Select one available flight
7. Click on Continue

**Expected Result:**  
System allows flight selection when departure and return dates are the same.

---

### TC-FS-004
**Title:** Verify default trip type is "Return"  

**Steps:**
1. Access the flight search page

**Expected Result:**  
Return trip option is selected by default.

---

### TC-FS-005
**Title:** Verify Continue button enabled when all required fields are filled  

**Steps:**
1. Access the flight search page
2. Fill all mandatory fields with valid data
3. Observe available flights displayed automatically
4. Select one available flight

**Expected Result:**  
Continue button becomes enabled after selecting a flight.

---

### TC-FS-006
**Title:** Select flight on responsive versions  

**Steps:**
1. Access the flight search page on different screen sizes
2. Fill all mandatory fields
3. Observe available flights displayed automatically
4. Select one available flight

**Expected Result:**  
Flight selection works correctly across responsive layouts.

---

## Invalid Scenarios

### TC-FS-007
**Title:** Attempt to continue without selecting a flight  

**Steps:**
1. Access the flight search page
2. Fill all mandatory fields
3. Do not select any flight
4. Attempt to click on Continue

**Expected Result:**  
System prevents progression and displays a validation message.

---

### TC-FS-008
**Title:** Select flight with required fields not filled  

**Steps:**
1. Access the flight search page
2. Leave one or more required fields empty

**Expected Result:**  
System does not display available flights and shows validation messages for required fields.

---

### TC-FS-009
**Title:** Select flight with same origin and destination  

**Steps:**
1. Access the flight search page
2. Enter the same city for origin and destination
3. Select valid dates

**Expected Result:**  
System prevents flight search and displays a validation message.

---

### TC-FS-010
**Title:** Select return trip with return date earlier than departure date  

**Steps:**
1. Access the flight search page
2. Select trip type as Return
3. Enter valid origin and destination
4. Select a return date earlier than the departure date

**Expected Result:**  
System prevents invalid date selection and displays an error message.

---

### TC-FS-011
**Title:** Select multiple flights at the same time  

**Steps:**
1. Access the flight search page
2. Fill all mandatory fields
3. Observe available flights displayed automatically
4. Attempt to select more than one flight

**Expected Result:**  
System allows selection of only one flight at a time.

---

### TC-FS-012
**Title:** Verify return date field is hidden for one-way trips  

**Steps:**
1. Access the flight search page
2. Select trip type as One-way

**Expected Result:**  
Return date field is not displayed when one-way trip is selected.
