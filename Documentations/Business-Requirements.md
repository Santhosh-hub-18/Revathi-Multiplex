# Business Requirements

## 1. Business Problem

Traditional movie ticket booking processes may involve manual communication and inefficient handling of booking requests.

The Revathi Multiplex application aims to provide a structured case management solution for handling movie ticket bookings.

## 2. Business Objectives

The application should:

1. Allow customers to submit movie ticket booking requests.
2. Capture required customer and booking information.
3. Validate booking information.
4. Check show availability.
5. Check seat availability.
6. Calculate the total booking cost.
7. Allow the customer to confirm or cancel the booking.
8. Route booking requests to the appropriate team.
9. Allocate seats for confirmed bookings.
10. Generate a unique Ticket ID.
11. Track booking status.
12. Send confirmation notifications.
13. Monitor case processing using SLA rules.

## 3. Functional Requirements

### Customer Booking

The system should allow customers to provide:

- Customer name
- Contact information
- Movie selection
- Show date
- Show time
- Show type
- Number of tickets
- Seat requirements

### Availability

The system should verify:

- Selected movie/show availability
- Required number of seats
- Availability before completing the booking

### Cost Calculation

The application should calculate the total cost based on:

```text
Total Cost = Ticket Price × Number of Tickets
