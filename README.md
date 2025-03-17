**Title**

The following is the title of the machine learning project: “Predicting Coupon Acceptance on E-commerce Platforms”.

**Problem Statement and Understanding**

- The goal of this project is to leverage machine learning techniques to analyse driving scenarios and user attributes collected from an e-commerce website.
- By accurately predicting whether users will accept coupons during their journeys, the aim is to optimise coupon distribution strategies and enhance user engagement with the platform's offerings.
- The survey describes different driving scenarios including the user’s destination, current time, weather, passenger, coupon attributes, user attributes, and contextual attributes, and then asks the user whether he/she will accept the coupon or not.

**Data Dictionary**

- Gender: Female, Male.
- Age: 21, 46, 26, 31, 41, 50plus, 36, below21.
- Marital Status: Unmarried partner, Single, Married partner, Divorced, Widowed.
has_Children: Whether the person has children or not, where — 1: has children, 0: No children.
- Education: Some colleges — no degree, bachelor’s degree, Associates degree, High School Graduate, Graduate degree (Master or Doctorate), Some High School.
- Occupation: Traveller’s occupation.
- Income: Income of the traveler.
- Car: Description of vehicle driven by the traveller.
- Bar: How many times does the traveler go to a bar every month?
- Coffee House: How many times does the user go to a coffeehouse every month?
- Carry Away: How many times does the user get takeaway food every month?
- RestaurantLessThan20: How many times does the user go to a restaurant with an average expense per person of less than $20 every month?
- Restaurant20To50: How many times does the user go to a restaurant with an average expense per person of $20 — $50 every month.
- Destination: Destination of traveler.
- Passenger: Who are the passengers in the car.
- Weather: Weather when the user is driving (Sunny, Rainy, Snowy).
- Temperature: Temperature in Fahrenheit when the user is driving.
- Coupon: Type of Coupon.
- Expiration: Validity of Coupon.
- toCoupon_GEQ5min: Driving distance to the restaurant/cafe/bar for using the coupon is greater than 5 minutes (0,1).
- toCoupon_GEQ15min: Driving distance to the restaurant/cafe/bar for using the coupon is greater than 15 minutes (0,1).
- toCoupon_GEQ25min: Driving distance to the restaurant/cafe/bar for using the coupon is greater than 25 minutes (0,1).
- direction_same: Whether the restaurant/cafe/bar is in the same direction as the traveler’s current destination (0,1).
- direction_opp: Whether the restaurant/cafe/bar is in the opposite direction as the user’s current destination (0,1).
- Accept(Y/N?): Target column( whether user will accept the coupon or not? ).

**Models Used**

- Logistic Regression
- Decision Tree
- Random Forest Classifier
- XGBoost Classifier

**Challenges and Project Limitations**

- The primary challenge in feature selection is to identify which features can be dropped from the dataset without introducing significant data leakage.
- The choice of data visualisations is inherently subjective, and influenced by cognitive and contextual considerations. This variability makes selecting the optimal data visualisation tool a complex task.
- The visualisation, similar to coding the program, takes quite a bit of hit-and-trial methods to find the best plot to display.
- Tuning hyper-parameters is essential for achieving optimal model performance. However, it is often computationally intensive.

**Model Performance**

- The XGBoost model delivered the highest scores in all the performance criteria.
- Hyperparameter tuning helped increase the performance ( from 72.57% to 75.64% ) of the model by 4.23%.
- The performance can further be improved. However, due to computational cost, the user is not able to test out further parameters.

**Disclaimer**

- This project utilizes a dataset provided by **Learnbay**, an institute where I am currently studying Data Science. The dataset is being used purely for educational purposes as part of my learning journey.
- **I do not own the dataset**; it was provided to me for academic use.
- I would like to acknowledge **Learnbay** for providing this dataset and supporting my learning in the field of data science.
