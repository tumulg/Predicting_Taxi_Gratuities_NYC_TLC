# NYC Taxi Gratuity Prediction  

This project aims to predict taxi gratuities for the New York City Taxi & Limousine Commission (NYC TLC) using the 2017 Yellow Taxi Trip Data. The dataset contains detailed information about various taxi trips, including trip distance, payment methods, fare amounts, and tip amounts.  

The project involves **data analysis** to uncover patterns and relationships between variables and **machine learning** to predict tipping behavior. These insights can help taxi drivers optimize their services and increase gratuities.  

---

## Project Overview  

The project is divided into five Jupyter notebooks, each focusing on a specific aspect of the analysis and modeling:

1. **Data Inspection and Analysis:** Initial exploration of the dataset to understand its structure, handle missing values, and inspect data distributions. This step provides a foundation for subsequent analysis.  
2. **EDA and DataViz:** Exploratory Data Analysis (EDA) and visualization of key variables to uncover patterns, relationships, and trends that influence tipping behavior.  
3. **Stats and Hypothesis Testing:** Analyzing the relationship between fare amount and payment type using statistical methods to gain insights into tipping patterns.  
4. **Multiple Linear Regression:** Building a regression model to predict taxi fares based on various trip attributes collected over the year.  
5. **Random Forest Model:** Creating a machine learning model to predict whether a customer will not leave a tip, helping drivers identify potential tipping behavior.  

---

## Machine Learning  

- **Purpose:** To identify factors that influence tipping behavior and generate insights for taxi drivers to increase their revenue.  
- **Goal:** To predict whether a customer is likely to leave a generous tip based on trip details.  

---

## Technologies Used  

- **Programming Language:** Python  
- **Libraries:**  
  - Data Manipulation: Pandas, NumPy  
  - Visualization: Matplotlib, Seaborn  
  - Machine Learning: Scikit-learn  
- **Development Environment:** Jupyter Notebooks  

---

## Dataset Description  

The dataset used for this project is the **2017 Yellow Taxi Trip Data**, collected by the NYC Taxi & Limousine Commission (NYC TLC). It contains the following columns:

- **ID:** Trip identification number.  
- **VendorID:** A code indicating the TPEP provider that recorded the trip.  
  - 1 = Creative Mobile Technologies, LLC  
  - 2 = VeriFone Inc  
- **tpep_pickup_datetime:** The date and time when the meter was engaged.  
- **tpep_dropoff_datetime:** The date and time when the meter was disengaged.  
- **Passenger_count:** The number of passengers in the vehicle. This is a driver-entered value.  
- **Trip_distance:** The distance of the trip in miles, as reported by the taximeter.  
- **PULocationID:** The TLC Taxi Zone where the meter was engaged (Pickup location).  
- **DOLocationID:** The TLC Taxi Zone where the meter was disengaged (Drop-off location).  
- **RateCodeID:** The final rate code in effect at the end of the trip.  
  - 1 = Standard rate  
  - 2 = JFK  
  - 3 = Newark  
  - 4 = Nassau or Westchester  
  - 5 = Negotiated fare  
  - 6 = Group ride  
- **Store_and_fwd_flag:** Indicates whether the trip record was stored in vehicle memory before being sent to the vendor.  
  - Y = Store and forward trip  
  - N = Not a store and forward trip  
- **Payment_type:** A numeric code indicating how the passenger paid for the trip.  
  - 1 = Credit card  
  - 2 = Cash  
  - 3 = No charge  
  - 4 = Dispute  
  - 5 = Unknown  
  - 6 = Voided trip  
- **Fare_amount:** The time-and-distance fare calculated by the meter.  
- **Extra:** Miscellaneous extras and surcharges, including the $0.50 and $1 rush hour and overnight charges.  
- **MTA_tax:** A $0.50 MTA tax that is automatically triggered based on the metered rate in use.  
- **Improvement_surcharge:** A $0.30 improvement surcharge assessed on trips at the flag drop, implemented starting in 2015.  
- **Tip_amount:** The tip amount, automatically populated for credit card payments. Cash tips are not included.  
- **Tolls_amount:** The total amount of tolls paid during the trip.  
- **Total_amount:** The total amount charged to passengers, excluding cash tips.  

---

## Usage  

To run the notebooks, open them in Jupyter Notebook or Jupyter Lab:  
```bash
jupyter notebook
```

Then, execute the notebooks in the following order:

1. **Data Inspection and Analysis**
2. **EDA and DataViz**
3. **Stats and Hypothesis Testing**
4. **Multiple Linear Regression**
5. **Random Forest Model**

---

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

## Acknowledgments

- NYC Taxi & Limousine Commission (TLC) for providing the dataset.
- The Python and data science community for valuable resources and tools.

