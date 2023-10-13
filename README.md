# Hotel-Booking using Tableau

### <ins>Data Description</ins>

 - ***hotel***: Hotel type 

 - ***is_canceled***: Value indicates if the booking is canceled or not.

 - ***lead_time***: How long in advance the booking was made.

 - ***arrival_date_year***: Customer arrival year.

 - ***arrival_date_month***: In which month of the year does the customer visit the hotel?

 - ***arrival_date_week_number***: In which week of the year the customer arrived.

 - ***arrival_date_day_of_month***: The date of the month the customer visited the hotel.

 - ***stays_in_weekend_nights***: Customer stayed or booked to stay in a hotel during weekend nights.

 - ***stays_in_week_nights***: Customer stayed in the hotel during weeknights.

 - ***adults***: Number of adults

 - ***children***: Number of children.

 - ***babies***: Number of babies.

 - ***meal***: Type of meal booked. 

 - ***country***: Country of origin of customer.

 - ***market_segment***: where the bookings came from.

 - ***distribution_channel***: Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”.

 - ***is_repeated_guest***: Value indicating if the booking name was from a repeated guest (1) or not (0).

 - ***previous_cancellations***: Number of previous bookings that were cancelled by the customer prior to the current booking.

 - ***previous_bookings_not_canceled***: Number of previous bookings that were cancelled by the customer prior to the current booking.

 - ***reserved_room_type***: Code of room type reserved. Code is presented instead of designation for anonymity reasons.

 - ***assigned_room_type***: Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due. booking_changes : Number of changes/amendments made to the booking from the moment the booking was entered on the PMS.

 - ***deposit_type***: Indication if the customer made a deposit to guarantee the booking.

 - ***agent***: ID of the travel agency that made the booking.

 - ***company***: ID of the company/entity that made the booking or is responsible for paying the booking.

 - ***days_in_waiting_list***: Number of days the booking was in the waiting list before it was confirmed to the customer.

 - ***customer_type***: Type of booking, assuming one of four categories.

 - ***ADR***: Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights.

 - ***required_car_parking_spaces***: Number of car parking spaces required by the customer.

 - ***total_of_special_requests***: Number of special requests made by the customer (e.g. twin bed or high floor).

 - ***reservation_status***: Reservation last status, assuming one of three categories: Canceled – booking was canceled by the customer; Check-Out: customer check out from hotel,No show: Customer did not check-in hotel and informed hotel with reason.

 - ***reservation_status_date***: Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking cancelled or when did the customer checked out of the hotel.

### <ins>Dashboard Tableau Public</ins>

https://public.tableau.com/app/profile/anju.haridas/viz/HotelBookingAnalysis_16971090037870/OverviewofHotelBookinganalysis?publish=yes

### <ins> Data Manupulation </ins>

##### 1) In which year did the maximum number of bookings occur, considering individual hotels in three years. Also which month and ?

<img width="712" alt="Screenshot 2023-10-09 at 9 58 10 PM" src="https://github.com/Anjuharidas4/Hotel-Booking-Analysis/assets/108412331/11932b4d-c46c-427f-be9b-bfa347f12a0f">

#####  - In terms of bookings, 2016 exceeded 2015 with over 55 bookings, marking it as the year with the highest numbers. However, there was a decrease in bookings in 2017, which still outperformed the numbers from 2015.

<img width="588" alt="Screenshot 2023-10-09 at 9 48 22 PM" src="https://github.com/Anjuharidas4/Hotel-Booking-Analysis/assets/108412331/eddaf22e-9763-4ea0-900f-db1bd1c743b9">

#####  - In 2016, city hotels received the highest number of bookings, with a total of 38,140 bookings, surpassing the number of bookings at resorts.

### <ins>Executive Dashboard</ins>

<img width="1232" alt="Screenshot 2023-10-13 at 4 10 02 PM" src="https://github.com/Anjuharidas4/Hotel-Booking-Analysis/assets/108412331/b8886b85-eb02-4595-91c1-ad0d7b8246ff">
