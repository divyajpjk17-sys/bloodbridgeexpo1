BloodBridge

Overview

BloodBridge is a frontend-focused healthcare coordination system designed to efficiently manage and route blood requests between hospitals, blood banks, and donors in real time.
The system ensures faster response during emergencies by intelligently forwarding requests based on availability and eligibility.

Goal

To demonstrate a realistic emergency blood coordination flow that minimizes delay and improves response efficiency through structured request routing.

ystem Workflow

1. Hospital Request Flow
   
A hospital raises a blood request with required blood group and details
The request is first sent to the nearest connected blood bank

3. Blood Bank Response
   
If required blood is available
Blood bank accepts the request
Blood is dispatched to the hospital
If not available
Blood bank declines the request
Request is forwarded back to the hospital system

5. Donor Notification Flow
   
Hospital system filters eligible donors based on:
Blood group match
Availability
Pre-shorted donor list
Only matching donors receive notifications

7. Donor Response Flow
   
Donors can accept or ignore the request
Once a donor accepts:
The request is immediately removed from other eligible donors
Hospital is notified about confirmed donor

Key Idea

The system ensures that:

Requests follow a structured routing flow (Hospital → Blood Bank → Donors)
Only eligible donors are notified
Once a match is found, redundancy is removed instantly
Real-time response handling is prioritized

Summary 

BloodBridge is a frontend-based system that streamlines emergency blood requests. Hospitals send requests first to nearby blood banks; if unavailable, it is forwarded to eligible matched donors. Only suitable donors receive notifications, and once a donor accepts, the request is closed for others to ensure fast, efficient coordination.
