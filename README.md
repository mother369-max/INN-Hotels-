# INN Hotels Supervised Learning

INN Hotels is a Portugal-based organization that faced heavy revenue losses due to last-minute booking cancellations.  
This project implements machine learning classification models to predict whether a customer will **cancel** or **confirm** a booking.

## Objective
- Build classification models to identify customers likely to cancel their bookings, enabling management to take proactive actions and reduce revenue loss.

## Techniques
- Logistic Regression with VIF treatment to address multicollinearity
- Decision Trees (CART):
  - Basic model
  - Pre-pruned model
  - Post-pruned model

## Results
- The choice of metric was recall to catch as many positives as possible.
- High lead times, simple meal plans, higher prices, and presence of children increase the likelihood of cancellations
- Bookings are more likely to be confirmed when:
  - Lead time is low
  - Prices are affordable
  - Car parking space is reserved
