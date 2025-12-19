# Bug Reports – Flight Search

## BUG-FS-001
**Title:** User can proceed without selecting a flight  

**Precondition:**  
User is on the Flight Search page.

**Steps to Reproduce:**
1. Fill all mandatory fields (trip type, origin, destination, dates)
2. Do not select any available flight
3. Click on Continue

**Expected Result:**  
System should prevent progression and require the user to select a flight.

**Actual Result:**  
User is able to proceed to the next step without selecting a flight.

---

## BUG-FS-002
**Title:** Return trip allows return date earlier than departure date  

**Precondition:**  
User is on the Flight Search page.

**Steps to Reproduce:**
1. Select trip type as Return
2. Enter valid origin and destination
3. Select a departure date
4. Select a return date earlier than the departure date

**Expected Result:**  
System should block invalid date selection and display an error message.

**Actual Result:**  
System allows the user to proceed with invalid date configuration.

---

## BUG-FS-003
**Title:** Same origin and destination with same dates allows flight search  

**Precondition:**  
User is on the Flight Search page.

**Steps to Reproduce:**
1. Enter the same city for origin and destination
2. Select the same date for departure and return

**Expected Result:**  
System should prevent flight search due to invalid route configuration.

**Actual Result:**  
System displays available flights for an invalid route.

