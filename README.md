# Hotel Booking Analysis Dashboard with Power BI


## Overview

Welcome to the Hotel Booking Analysis Dashboard project! In this project, I have leveraged Power BI and DAX (Data Analysis Expressions) to create an interactive and insightful dashboard for analyzing a hotel booking dataset.

## About Dataset

The dataset used for this analysis contains a wide range of information related to hotel bookings. Here's a brief description of the dataset columns:

1. **hotel**: Type of hotel (H1 = Re Hotel or H2 = City Hotel)
2. **is_canceled**: Value indicating if the booking was canceled (1) or not (0)
3. **lead_time**: Number of days that elapsed between the entering date of the booking and the arrival date
4. **arrival_date_year**: Year of the arrival date
5. **arrival_date_month**: Month of the arrival date
6. **arrival_date_week_number**: Week number of the year for the arrival date
7. **arrival_date_day_of_month**: Day of the arrival date
8. **stays_in_weekend_nights**: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
9. **stays_in_week_nights**: Number of weeknights (Monday to Friday) the guest stayed or booked to stay at the hotel
10. **adults**: Number of adults
11. **children**: Number of children
12. **babies**: Number of babies
13. **meal**: Type of meal booked (e.g., BB – Bed & Breakfast)
14. **country**: Country of origin
15. **market_segment**: Market segment designation
16. **distribution_channel**: Booking distribution channel
17. **is_repeated_guest**: Value indicating if the booking name was from a repeated guest (1) or not (0)
18. **previous_cancellations**: Number of previous bookings that were canceled by the customer prior to the current booking
19. **previous_bookings_not_canceled**: Number of previous bookings not canceled by the customer prior to the current booking
20. **reserved_room_type**: Code of room type reserved
21. **assigned_room_type**: Code for the type of room assigned to the booking
22. **booking_changes**: Number of changes/amendments made to the booking
23. **deposit_type**: Indication if the customer made a deposit to guarantee the booking (No Deposit, Non Refund, Refundable)
24. **agent**: ID of the travel agency that made the booking
25. **company**: ID of the company/entity that made the booking or responsible for paying the booking
26. **days_in_waiting_list**: Number of days the booking was in the waiting list before it was confirmed to the customer
27. **customer_type**: Type of booking (e.g., Contract, Group, Transient)
28. **adr**: Average Daily Rate
29. **required_car_parking_spaces**: Number of car parking spaces required by the customer
30. **total_of_special_requests**: Number of special requests made by the customer
31. **reservation_status**: Reservation last status (Canceled, Check-Out, No-Show)
32. **reservation_status_date**: Date at which the last status was set

