# Flight-Price-Prediction

The dataset's exploratory data analysis, which included visualizing the correlation between different attributes and flight costs. A few machine learning algorithms are assessed, and measures like mean absolute error and mean squared error is used to compare the effectiveness of the models. The machine learning model includes Linear Regression, Decision Tree, Random Forest, and Artificial Neural Network (ANN). The outcomes demonstrate that the ANN algorithm delivers the greatest results followed by Random Forest Algorithm.

The dataset consists of information about flight booking options from the Easemytrip website for flight travel between India's top 6 metro cities. There are 300,159 data points and 13 features in the cleaned dataset (seperately created). Features:

1. Airline: The airline column contains the name of the airline provider. There are six different airlines, making it a category trait.
2. Source City: The location where the flight departs. It is a classification feature with 6 distinctive cities.
3. Departure Time: By organising periods into bins, we build this derived categorical feature. It has six different time labels and stores information about the departure time.
4. Number of Stops: The number of stops between the source and destination cities is stored in a categorical feature with three separate values.
5. Destination City: The location of the aircraft's landing. It is a classification feature with 6 cities.
6. Arrival Time: By dividing periods into bins, this derived categorical feature was produced. It maintains information regarding the arrival time and has six different time labels.
7. Trip Duration: A running feature that shows the total number of hours needed to travel between two cities.
8. Date of Journey: Journey date of the flight.
9. Days Left: To calculate this derived characteristic, divide the trip date by the booking date.
10. Day of Week: It is derived from the Date of the Journey.
11. Flight Code: Information about the flight of the aircraft is kept in the flight code.
12. Journey Class: This is a categorised characteristic with two unique values: Business and Economy, and it contains information on seat class.
13. Ticket Price: This column keeps track of the ticket price information.
