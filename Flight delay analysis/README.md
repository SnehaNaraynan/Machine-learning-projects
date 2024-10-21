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
FL_DATE: Date of the flight.
AIRLINE: Name of the airline.
AIRLINE_DOT: DOT identifier for the airline.
AIRLINE_CODE: Code assigned to the airline.
DOT_CODE: DOT identifier.
FL_NUMBER: Flight number.
ORIGIN: Origin airport code.
ORIGIN_CITY: City of origin airport.
DEST: Destination airport code.
DEST_CITY: City of destination airport.
CRS_DEP_TIME: Scheduled departure time.
DEP_TIME: Actual departure time.
DEP_DELAY: Departure delay.
TAXI_OUT: Time spent taxiing out.
WHEELS_OFF: Time when aircraft's wheels leave the ground.
WHEELS_ON: Time when aircraft's wheels touch the ground.
TAXI_IN: Time spent taxiing in.
CRS_ARR_TIME: Scheduled arrival time.
ARR_TIME: Actual arrival time.
ARR_DELAY: Arrival delay.
CANCELLED: Indicator if the flight was cancelled (1 for cancelled, 0 for not cancelled).
CANCELLATION_CODE: Reason for cancellation (if applicable).
DIVERTED: Indicator if the flight was diverted (1 for diverted, 0 for not diverted).
CRS_ELAPSED_TIME: Scheduled elapsed time.
ELAPSED_TIME: Actual elapsed time.
AIR_TIME: Time spent in the air.
DISTANCE: Distance traveled.
DELAY_DUE_CARRIER: Delay due to carrier.
DELAY_DUE_WEATHER: Delay due to weather.
DELAY_DUE_NAS: Delay due to National Airspace System (NAS).
DELAY_DUE_SECURITY: Delay due to security.
DELAY_DUE_LATE_AIRCRAFT: Delay due to late aircraft arrival.
