# SLA and Notifications

## 1. Overview

The Revathi Multiplex application uses SLA (Service Level Agreement) management to monitor the time taken to process movie ticket booking requests.

SLA helps ensure that booking cases are processed within the expected time.

## 2. SLA Management

SLA rules help the booking team to:

- Monitor case processing time
- Identify delayed cases
- Prioritize cases that require attention
- Ensure timely processing of booking requests

## 3. SLA Processing

The general SLA flow is:

```text
Booking Request
      ↓
SLA Timer Starts
      ↓
Case Processing
      ↓
Booking Completed
      ↓
SLA Timer Stops
