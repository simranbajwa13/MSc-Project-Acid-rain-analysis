# MSc-Project-Acid-rain-analysis
Acid rain has been pne of the main hazard to the ecological system. It is a result of  sulfur dioxide (SO2) and nitrogen oxides (NOX)  emitted into the atmosphere and transported by wind and air currents. The SO2 and NOX react with water, oxygen and other chemicals to form sulfuric and nitric acids.  These then mix with water and other materials before falling to the ground. Coal combustion has always been one of the main contributors to sulphur dioxide emission in the environment. 
This study aims towards forecasting, future trends of acid rain emisson in UK based on the past values of it in the time series. 
Along with predicting the future trends, it is necessary to analysis the correlation between various factors responsible for acid rain emission. The study, performs a correlation analysis to test the correlation between so2 emission, which is considered as a prominent source of acid rain and annual coal production in UK since 1990. Besides this the influence of so2 emisson on acid rain and coal production on so2 is forecasted using a multivariate time series model. 

Goals of this project:
* Forecasting Acid rain trend using statistical methods. ( ARIMA)
* Computing the correlation among the three important variables discussed in this project. Coal production rate, Sulphur dioxide emission and acid rain pollution. 
* Forecasting the influence of one time series over the other using multivariate time series analysis methods ( Vector Autoregression)

Resources of Data:
* coal production dataset has been obtained from the Department of Business, Energy and Industrial Strategy UK.
* SO2 emission dataset is obtained from Office of National Statistics UK.
* Acid rain precursor data is obtained from Office of National Statistics UK.

Contents of the Repository:
* acidrain.ipynb :  the main Colab notebook of this project, containing 11 parts:
  * Data collection and cleaning
  * Visualization of the datasets
  * Preprocessing
  * PACF-ACF plots
  * Seasonality analysis  
  * ARIMA model implementation
  * Auto ARIMA implementation 
  * Cointegration analysis and tests 
  *  Granger Causality analysis and explanation -- foundation of multivariates
  *  Vector Auto Regression (VAR) for multivariate time series
  *   Conclusions
* dates.csv: contain the csv file for date values
* acidrain.csv: contains the acid rain precursor values
* coal production.csv: contains the annual coal production values
* SO2.csv: contains the SO2 emission values

The rest of the implementation steps and results are explained inside the ipynb notebook.

