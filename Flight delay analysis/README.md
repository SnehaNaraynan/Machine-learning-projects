## Flight Delay Analysis

## OBJECTIVE:

To predict flight delays and analyze the underlying factors that influence delays across different airlines, airports, and time periods.

## PROBLEM STATEMENT:

Flight delays cause significant inconvenience for passengers and operational inefficiencies for airlines. The goal of this project is to extract, transform, and analyze flight delay data to uncover trends and predict delays. By understanding the key factors that contribute to flight delays, airlines can implement strategies to reduce these occurrences, improving customer satisfaction and operational efficiency.

## Key Questions:
How do delays vary across airlines and airports?
Are there seasonal patterns or trends in delays?
What are the major causes of delays, and how can they be predicted?

## DATASET:
https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023
1. FL_DATE: Date of the flight
2. AIRLINE: Name of the airline
3. AIRLINE_DOT: DOT identifier for the airline.
4. AIRLINE_CODE: Code assigned to the airline.
5. DOT_CODE: DOT identifier.
6. FL_NUMBER: Flight number.
7. ORIGIN: Origin airport code
8. ORIGIN_CITY: City of origin airport.
9. DEST: Destination airport code.
10. DEST_CITY: City of destination airport.
11. CRS_DEP_TIME: Scheduled departure time.
12. DEP_TIME: Actual departure time.
13. DEP_DELAY: Departure delay.
14. TAXI_OUT: Time spent taxiing out.
15. WHEELS_OFF: Time when aircraft's wheels leave the ground.
16. WHEELS_ON: Time when aircraft's wheels touch the ground.
17. TAXI_IN: Time spent taxiing in.
18. CRS_ARR_TIME: Scheduled arrival time.
19. ARR_TIME: Actual arrival time.
20. ARR_DELAY: Arrival delay.
21. CANCELLED: Indicator if the flight was cancelled (1 for cancelled, 0 for not cancelled).
22. CANCELLATION_CODE: Reason for cancellation (if applicable).
23. DIVERTED: Indicator if the flight was diverted (1 for diverted, 0 for not diverted).
24. CRS_ELAPSED_TIME: Scheduled elapsed time.
25. ELAPSED_TIME: Actual elapsed time.
26. AIR_TIME: Time spent in the air.
27. DISTANCE: Distance traveled.
28. DELAY_DUE_CARRIER: Delay due to carrier.
29. DELAY_DUE_WEATHER: Delay due to weather.
30. DELAY_DUE_NAS: Delay due to National Airspace System (NAS).
31. DELAY_DUE_SECURITY: Delay due to security.
32. DELAY_DUE_LATE_AIRCRAFT: Delay due to late aircraft arrival.
