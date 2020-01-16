# Time Series Analysis for Univariate Series: PM2.5 Conditions
I was interested in doing a time series analysis that would try out Tensorflow's long short-term memory (LSTM) and compare that to Auto ARIMA. 
The data comes from the [EPA.gov's API](https://aqs.epa.gov/aqsweb/documents/data_api.html) that tracks various air quality measures. I decided to look at my county's PM2.5 levels. 

### Notebook Sections:
- Data Extraction
- Data Preprocessing and Visualization
- TensorFlow Univariate LSTM 
	- Train vs. Test
	- Future Forecasting 
- Auto ARIMA Univariate
	- Train vs. Test

### The Notebook uses the following technologies:
- API requests
- Parcing JSON
- Pyplot
- TensorFlow
- Auto ARIMA
- Tuning Grid for hyperparameters


*A special shoutout to Ian Felton for his YouTube video [Python - LSTM for Time Series Prediction](https://www.youtube.com/watch?v=h8v9--50mdU&t=4s)*
