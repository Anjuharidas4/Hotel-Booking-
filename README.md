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

##### 1) In which year did the maximum number of bookings occur, considering individual hotels in three years.


<img width="712" alt="Screenshot 2023-10-09 at 9 58 10 PM" src="https://github.com/Anjuharidas4/Hotel-Booking-Analysis/assets/108412331/11932b4d-c46c-427f-be9b-bfa347f12a0f">

#####  - In terms of bookings, 2016 exceeded 2015 with over 55 bookings, marking it as the year with the highest numbers. However, there was a decrease in bookings in 2017, which still outperformed the numbers from 2015.


<img width="588" alt="Screenshot 2023-10-09 at 9 48 22 PM" src="https://github.com/Anjuharidas4/Hotel-Booking-Analysis/assets/108412331/eddaf22e-9763-4ea0-900f-db1bd1c743b9">

#####  - In 2016, city hotels received the highest number of bookings, with a total of 38,140 bookings, surpassing the number of bookings at resorts.

### <ins>Executive Dashboard</ins>

##### Customers booking from India exhibit a booking pattern to various destinations. The maximum bookings occurred in 2016, reaching 36122 bookings, surpassing the numbers in 2015, which were 13,753 bookings, and in 2017, which stood at 24870 bookings.


<img width="524" alt="Screenshot 2023-10-13 at 5 45 52 PM" src="https://github.com/Anjuharidas4/Hotel-Booking-Analysis/assets/108412331/a2559bd9-b1f9-4a30-ad05-2ca54cc5159c">

##### In India, there were a total of 117 bookings over the course of three years. Notably, there is a tendency among people to choose city hotels, with 84 bookings, which is 51 more than resort bookings, which amount to 33, over the same three-year period.


<img width="644" alt="Screenshot 2023-10-13 at 6 12 07 PM" src="https://github.com/Anjuharidas4/Hotel-Booking-Analysis/assets/108412331/0a8a9c29-b194-47bf-8ae7-1d096dfd99f9">

##### On the 23rd of November, the city hotel received its highest number of bookings from India, totaling 9 bookings over a span of three years. Portugal had the highest number of bookings, totaling 21,071, while India contributed only 0.6% of the bookings, indicating that the travel patterns of Indian customers are below the average rate.


<img width="649" alt="Screenshot 2023-10-13 at 5 21 10 PM" src="https://github.com/Anjuharidas4/Hotel-Booking-Analysis/assets/108412331/8d6e08ed-9c29-45ef-ae2b-ac615df28633">

##### - Online bookings accounted for the highest number of reservations made from India.For travelers from India, 
##### - the average minimum lead time to book a city hotel falls within the range of 16 to 59 days, which is approximately two weeks. On the other hand, for resort bookings, the average minimum lead time is in the range of 22 to 58 days, close to two months.


<img width="1227" alt="Screenshot 2023-10-16 at 1 08 03 PM" src="https://github.com/Anjuharidas4/Hotel-Booking-Analysis/assets/108412331/e2f6552b-5f7d-4445-a85f-c0799b4f1336">

##### - The highest booking charges are accrued from Indian tourists who make reservations for Type B rooms at city hotels.
##### - The highest number of bookings, amounting to 72, occurred for weekday stays in the month of November at city hotels, as opposed to 23 bookings for weekend stays in November at city hotels.


<img width="1220" alt="Screenshot 2023-10-16 at 1 19 30 PM" src="https://github.com/Anjuharidas4/Hotel-Booking-Analysis/assets/108412331/ef29a1cd-d738-47dc-a946-f0b842c9d42d">

### <ins>Conclusion</ins>

##### - Based on the data, it's clear that high demand leads to increased costs, as demand and prices exhibit a direct correlation. Therefore, strategically planning your arrival during periods of lower demand can result in significant cost savings and a more serene vacation experience.

##### - It's evident that for obtaining more affordable and reasonable rates, it's advisable to make reservations well in advance, typically within the range of two weeks to two months, or even further ahead. Additionally, selecting an arrival month other than November and scheduling a weekend night stay in resorts can also lead to cost savings. Moreover, it's worth noting that booking charges are generally lower for resort accommodations compared to city hotels.

