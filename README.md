# Predict-The-Flight-Ticket-Price-Hackathon
![Capture](https://user-images.githubusercontent.com/37707687/56852600-e3a87b00-693a-11e9-805c-adc9cf311465.JPG)

Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travellers saying that flight ticket prices are so unpredictable. Huh! Here we take on the challenge! As data scientists, we are gonna prove that given the right data anything can be predicted. Here you will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities.

Size of training set: 10683 records

Size of test set: 2671 records

# Features 
- Airline: The name of the airline.
- Date_of_Journey: The date of the journey
- Source: The source from which the service begins.
- Destination: The destination where the service ends.
- Route: The route taken by the flight to reach the destination.
- Dep_Time: The time when the journey starts from the source.
- Arrival_Time: Time of arrival at the destination.
- Duration: Total duration of the flight.
- Total_Stops: Total stops between the source and destination.
- Additional_Info: Additional information about the flight
- Price: The price of the ticket

# Evaluation Metric
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the predicted value and observed score values. The final score calculation is done in the following way:

Submissions are evaluated on Root-Mean-Squared-Log-Error (RMSLE) error = RMSLE (error)

Score = 1 – error

# Leaderboard
2nd Rank - 0.9558244

Featured in Analytics India Magazine:

https://www.analyticsindiamag.com/see-how-a-sr-analyst-a-tech-lead-business-analyst-solved-machinehacks-predict-the-flight-ticket-price-hackathon/
