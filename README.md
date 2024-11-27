# Grafana-Dashboard-on-Hotel-Bookings-Streaming-Data-

https://github.com/user-attachments/assets/59cb72d1-b43e-4965-a7c2-b1328a285967

# About Dataset
# *Context*

Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests?

This hotel booking dataset can help explore those questions!

# *Content*
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.

The dataset contains information about hotel reservations with the following columns:

•	hotel: Type of hotel (e.g., ResortHotel or CityHotel).

•	iscanceled: Indicates if the reservation was canceled.

•	leadtime: Number of days between booking and check-in.

•	arrivaldateyear, arrivaldatemonth: Check-in year and month.

•	staysinweekendnights, staysinweeknights: Nights spent during weekends and weekdays.

•	adults, children, babies: Number of adults, children, and babies in the reservation.

•	country: Guest's country of origin.

•	marketsegment, distributionchannel: Booking source (e.g., Direct, Online TA).

•	reservedroomtype, assignedroomtype: Room types reserved and assigned.

•	deposittype: Type of deposit made for the reservation.

•	agent, company: IDs for the booking agent and company.

•	customertype: Type of customer (e.g., transient).

•	reservationstatus: Final status (e.g., CheckOut, Canceled).

# Acknowledgements
The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.

# Objective of the Dashboard

The primary objective of this dashboard is to provide actionable insights into reservation trends, customer behavior, and market segment performance to aid managerial decision-making. Specifically, it aims to:

1. Monitor Key Metrics: Visualize and track essential metrics like lead time, cancellations, check-outs, and market segment performance to assess operational efficiency and revenue opportunities.

2. Understand Customer Segments: Analyze the behavior and preferences of various customer segments (e.g., groups, corporate clients, OTA customers) to identify growth opportunities and tailor marketing strategies.

3. Improve Occupancy and Revenue: Leverage insights to optimize pricing strategies, reduce cancellations, and enhance customer satisfaction through targeted offers and services.

4. Forecast Demand and Optimize Operations: Use data-driven patterns (e.g., lead time, reservation status) to forecast demand, allocate resources effectively, and minimize losses due to no-shows or last-minute cancellations.

5. Support Strategic Planning: Provide a consolidated view of performance across multiple dimensions (e.g., average stay duration, reservation sources) to inform long-term strategies for customer acquisition and retention.

# Insights of the Dashboard

Chart 1: Average Lead Time by Market Segment

•	Complementary Segment: The lowest lead time (11.5 days) indicates that bookings in this segment are made close to the check-in date, likely because these bookings are spontaneous or last-minute.

•	Corporate Segment: A lead time of 31.4 days shows moderate planning. Corporate clients plan ahead but not too far in advance.

•	Groups and Offline TA/TO: These segments have the longest lead times, with Groups at 121 days and Offline TA/TO at 89.2 days.

•	Online TA (62.6 days): Lead time is relatively long, reflecting the preference for pre-planned online bookings.

Chart 2: Reservation Status Breakdown

•	Key Observations:

o	There is a high cancellation rate in certain time slots, which correlates with factors like lead time, market segment, or guest type.

o	The majority of the "Canceled" reservations include multiple adults, indicating cancellations may occur in group bookings or couples.

Chart 3: Children vs. Adults in Reservations

•	Observation:

o	The pie chart indicates that 96% of reservations include adults, while only a small percentage includes children.

o	This suggests that the majority of bookings are made by adult-only groups, such as couples or solo travelers.

Chart 4: Reservation Patterns by Lead Time

•	Observation:

o	The chart shows fluctuations in reservations (cancellations, check-outs, and no-shows) based on lead time.

o	A significant portion of reservations is made within certain lead time intervals, with a notable number of cancellations closer to check-in dates.

Chart5: Average Number of Adults per Reservation by Market Segment

Observations:

1.	The chart shows an even distribution across market segments such as Direct, Online Travel Agents (OTA), Groups, Offline TA/TO, Complementary, and Corporate.

2.	Each segment (except for Complementary and Corporate, which are smaller at 10% each) accounts for approximately 20% of the total average number of adults per reservation.

Chart 6 Lead Time Analysis

Observation:

•	 Lead time fluctuates significantly, peaking at certain times.

•	Some customers book well in advance, while others prefer last-minute bookings. Peaks indicate periods of high demand.

Chart 7 Total Number of Adults

Observation: 

•	Over 4.29K adults were part of reservations.

•	High adult participation suggests families and business travelers are primary demographics.

Chart 8  Total Weekday Nights Booked

Observation:

•	 14.8K weekday nights were booked.

•	Weekdays are popular for business or extended stay customers.

Chart 9  Weekly vs Weekend Stay Trends

Observation:

•	 More stays are recorded on weekdays (198) compared to weekends (87).

•	Business-related travel dominates, while weekends may attract leisure travelers.

Chart 10  Children vs Adults in Reservations

Observation:

•	 Meal preferences are distributed across adults and children. The most popular meal types are Full Board (FB) and Bed & Breakfast (BB).

•	Families with children may prefer meal-inclusive plans, especially breakfast.

Chart 11  Average Lead Time per Distribution Channel

Observation:

•	 Corporate bookings have the shortest lead time (6.5 days), while Direct (134 days) and TA/TO (98.9 days) have longer lead times.

•	Corporate guests often book closer to their travel dates, while leisure or tourist bookings via agents or direct channels plan further ahead.

Chart 12  Total Reservations by Countries

Observation: 

•	Portugal (PRT) and a few other countries contribute the most to reservations.

•	The hotel attracts mostly local or regional guests, with fewer international visitors.

