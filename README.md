# temperature-anomaly-detection

This is an end-to-end machine learning project for detecting temperature anomalies in HVAC systems. Here are some details:

What is it?

It is a predictive model to identify unexpected variations in temperatures of an HVAC system using historical sensor data.
Why is it needed?

Temperature anomalies can indicate issues like faulty equipment, degraded performance, etc. Early detection allows preventive maintenance.
How does it work?

Sensor data including temperatures, setpoints etc. is collected from the HVAC system over time.
A RandomForestRegressor model is trained to predict expected temperature range.
The model forecasts are compared to actual temperatures.
Significant deviations are flagged as anomalies for investigation.
What technology is used?

The pipeline uses Python for data preparation, modeling, and deployment.
Pandas is used for loading and preprocessing data.
Scikit-learn provides the RandomForestRegressor algorithm for prediction.
Matplotlib visualizes actual vs predicted temperatures.
What algorithms are implemented?

A RandomForestRegressor model captures patterns between variables to forecast temperatures.
StandardScaling normalizes input data for effective modeling.
Anomaly detection uses a simple thresholding approach on prediction errors.
The key strengths are:

ContinuousTemperature monitoring to detect issues early
Few manual rules required compared to traditional methods
Retraining improves accuracy over time
Easy integration into existing HVAC management systems
