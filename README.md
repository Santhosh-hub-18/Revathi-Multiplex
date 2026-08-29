# Revathi Multiplex – Movie Ticket Booking Management

## 📌 Project Overview

Revathi Multiplex is a **Pega-based movie ticket booking management application** designed to automate and manage the complete movie ticket booking lifecycle.

The application allows customers to submit movie ticket booking requests while the system manages show availability, seat availability, ticket cost calculation, customer confirmation, seat allocation, ticket generation, SLA management, and booking notifications.

The application is developed using **Pega App Studio** and follows a **case-based workflow**.

---

## 🎯 Objectives

The main objectives of the application are:

- Automate the movie ticket booking process
- Manage customer booking requests
- Check movie and show availability
- Validate seat availability
- Calculate ticket costs
- Allow customers to confirm or cancel bookings
- Allocate seats for confirmed bookings
- Generate a unique Ticket ID
- Route cases using work queues
- Apply SLA management
- Send booking confirmation notifications

---

## 🔄 Case Lifecycle

The primary case type is:

**Movie Ticket Request**

The main stages are:

```text
Booking Request
       ↓
Availability
       ↓
Approval
       ↓
Booking Execution
       ↓
Booking Confirmation
       ↓
Case Resolution
