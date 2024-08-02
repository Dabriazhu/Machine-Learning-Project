# Machine-Learning-Project
New York City Taxi Tip Prediction
-BLUF
-Our project is making great progress in developing a predictive model to boost taxi drivers' tip earnings.The model effectively predicts generous tips but tends to generate more false positives. Despite this, its high precision and recall indicate reliability. VendorID_2 is the most important predictors, indicating that different suppliers have a significant impact on tipping behavior. Possible reasons include differences in the quality of service provided by different providers, the service attitudes of drivers, or the impact of different providers' billing and payment systems on passenger behavior. The time characteristics of night, rushinevening and morning indicate that tipping behavior is significantly different in different time periods of the day. Night time and rush hour affect passengers' mood and willingness to pay. passenger_count is also an important predictors, indicating that tipping behavior will differ when multiple people ride. Further analysis is needed to understand VendorID's impact. Adjusting the model's threshold could enhance performance and driver experience.

-Business Problem
-The objective is to develop a predictive model that can effectively increase revenue for taxi cab drivers by identifying optimal strategies for maximizing tips. The model will leverage historical data to predict whether a passenger is likely to be a generous tipper based on various trip attributes and customer behavior.

-The successful implementation of this predictive model can be utilized to:

-Guide drivers in prioritizing routes and passengers that are more likely to result in higher tips, thereby maximizing their earnings. -Provide real-time insights to drivers, enabling them to adapt their service approach during the ride to potentially increase tip amounts. -Assist taxi cab companies in optimizing driver incentives and reward programs to incentivize behaviors that lead to higher tips.

-Project Goal
The challenge is to leverage the available dataset to construct a robust predictive model using appropriate machine learning techniques. The model should accurately predict whether a passenger will be a generous tipper based on trip characteristics and other relevant factors.

-Metrics
We used precision, recall, F1 score, accuracy, and AUC (Area Under the ROC Curve), which are vital for evaluating classification models. Precision measures positive prediction accuracy, recall captures all positives, F1 balances precision and recall, accuracy indicates overall correctness, and AUC assesses model discrimination ability. These metrics collectively provide insights into the model's performance, crucial for assessing its effectiveness in practical applications.

-About the Data
The New York City Taxi and Limousine Commission (TLC) oversees the licensing and regulation of taxi cabs and for-hire vehicles in the city. With data sourced from over 200,000 licensees, it represents a vast network facilitating roughly one million trips daily. However, it's important to note that while this dataset serves educational purposes, it may not fully reflect the actual behaviors of taxi cab riders in New York City.

-Feature explanations
-MatchID: Identification number for the league match
-VendorID: Code indicating the TPEP provider that provided the record. (1= Creative Mobile Technologies, LLC; 2= VeriFone Inc.)
-TPEP_pickup_datetime: Date and time when the meter was engaged.
-TPEP_dropoff_datetime: Date and time when the meter was disengaged.
-Passenger_count: Number of passengers in the vehicle. (Driver-entered value)
-Trip_distance: Elapsed trip distance in miles reported by the taximeter.
-PULocationID: TLC Taxi Zone in which the taximeter was engaged.
-DOLocationID: TLC Taxi Zone in which the taximeter was disengaged.
-RateCodeID: Final rate code in effect at the end of the trip. (1= Standard rate, 2=JFK, 3=Newark, 4=Nassau or Westchester, 5=Negotiated fare, 6=Group ride)
-Store_and_fwd_flag: Flag indicating whether the trip record was held in vehicle memory before being sent to the vendor. (Y= store and forward trip, N= not a store and forward trip)
-Payment_type: Numeric code signifying how the passenger paid for the trip. (1= Credit card, 2= Cash, 3= No charge, 4= Dispute, 5= Unknown, 6= Voided trip)
-Fare_amount: Time-and-distance fare calculated by the meter.
-Extra: Miscellaneous extras and surcharges. (Includes the 0.50 and 1 dollar rush hour and overnight charges)
-MTA_tax: 0.50 dollar MTA tax that is automatically triggered based on the metered rate in use.
-Improvement_surcharge: 0.30 dollar improvement surcharge assessed trips at the flag drop. (Began being levied in 2015)
-Tip_amount: Tip amount automatically populated for credit card tips. (Cash tips are not included)
-Tolls_amount: Total amount of all tolls paid in the trip.
-Total_amount: Total amount charged to passengers. (Does not include cash tips)
