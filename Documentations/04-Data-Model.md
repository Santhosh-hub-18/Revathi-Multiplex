# Data Model

## 1. Overview

The Revathi Multiplex application uses data objects to store and manage information required for movie ticket booking.

## 2. Customer

The Customer data object stores information about the customer.

### Customer Information

- Customer Name
- Email
- Mobile Number
- Customer ID
- Booking Details

## 3. Movie

The Movie data object stores movie-related information.

### Movie Information

- Movie Name
- Genre
- Language
- Duration
- Movie Status

## 4. Show

The Show data object stores information about a particular movie show.

### Show Information

- Movie
- Show Date
- Show Time
- Show Type
- Ticket Price
- Available Seats

## 5. Ticket

The Ticket data object stores information about a confirmed booking.

### Ticket Information

- Ticket ID
- Customer
- Movie
- Show
- Seat Numbers
- Number of Tickets
- Total Cost
- Booking Status

## 6. Seat Allocation

The Seat Allocation data object stores information about seats assigned to a customer.

### Seat Allocation Information

- Show
- Seat Number
- Customer
- Ticket ID
- Allocation Status

## 7. Work Queue

The Work Queue is used to route booking requests to the appropriate booking team.

## 8. Data Relationship

```text
Customer
    ↓
Movie Ticket Request
    ↓
 ┌───────────────┬───────────────┬───────────────┐
 ↓               ↓               ↓
Movie           Show       Seat Allocation
                                  ↓
                                Ticket
