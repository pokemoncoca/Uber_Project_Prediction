# Uber_Project_Prediction
Predicting Uber booking outcomes (Completed vs Not Completed) using ML models (Decision Tree, Random Forest, XGBoost) with EDA, cross-validation, and business insights.

##Key Results
- **Decision Tree & XGBoost**: ~95% accuracy, with near-perfect recall for bookings  
- **Random Forest**: ~93% accuracy, more balanced precision/recall  
- **Business takeaway**: High recall ensures Uber rarely misses true bookings, even if a few false alarms occur


##Exploratory Data Analysis
- Booking success varies by **vehicle type** (e.g., Bikes/eBikes more prone to failures)  
- Failures are more frequent during **rush hours (8–10 AM, 5–8 PM)**  
- **Ride distance** influences outcomes: shorter rides fail more often

## Tech Stack
- Python, Pandas, NumPy  
- scikit-learn, XGBoost  
- Matplotlib, Seaborn

## Business Impact
By predicting failed bookings in advance, Uber could reallocate drivers, reduce lost revenue during peak hours, and improve customer trust.
