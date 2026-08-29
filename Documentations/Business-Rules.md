# Business Rules

## 1. Overview

Business rules are used to validate booking information and control the movie ticket booking process.

## 2. Customer Information Validation

Required customer information must be provided before the booking request can proceed.

Required information includes:

- Customer Name
- Mobile Number
- Email

## 3. Show Validation

The selected movie show must have valid:

- Movie
- Show Date
- Show Time
- Show Type

## 4. Ticket Validation

The number of tickets requested must be valid.

The requested number of tickets must not exceed the available seats.

## 5. Seat Availability Rule

Seats must be available before a booking can be confirmed.

```text
Requested Seats <= Available Seats
