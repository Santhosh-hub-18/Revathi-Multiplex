# Test Cases

## 1. Overview

Testing is performed to verify that the Revathi Multiplex application works correctly for different movie ticket booking scenarios.

## 2. Test Case 1 – Valid Booking Request

**Objective:** Verify that a customer can submit a valid booking request.

### Input

- Valid customer information
- Valid movie
- Valid show
- Valid number of tickets
- Available seats

### Expected Result

The booking request should be accepted and proceed to the next stage.

---

## 3. Test Case 2 – Invalid Customer Information

**Objective:** Verify that required customer information is validated.

### Input

Missing or invalid customer information.

### Expected Result

The system should prevent the booking from proceeding until the required information is corrected.

---

## 4. Test Case 3 – Show Availability

**Objective:** Verify that the selected movie show is available.

### Input

A valid movie and available show.

### Expected Result

The booking should proceed to seat availability checking.

---

## 5. Test Case 4 – Insufficient Seats

**Objective:** Verify that a booking cannot be completed when sufficient seats are unavailable.

### Input

The requested number of tickets is greater than the available seats.

### Expected Result

The booking should not be confirmed.

---

## 6. Test Case 5 – Ticket Cost Calculation

**Objective:** Verify automatic calculation of the total ticket cost.

### Example

```text
Ticket Price = ₹200
Number of Tickets = 3

Total Cost = ₹200 × 3
           = ₹600
