# Wind_power_generation_forecasting

The project leverages machine learning techniques to predict power output based on environmental conditions such as temperature, humidity, wind speed, and direction.

# Features
<li>Data Loading: Reads data from multiple CSV files (Location1.csv, Location2.csv, Location3.csv, and Location4.csv), each representing wind-related metrics for different locations.<br>
<li>Data Merging: Combines data from all locations into a single dataset for analysis.<br>
<li>Exploratory Data Analysis (EDA): Displays summary statistics.Identifies missing values and duplicates.<br>
<li>Data Preprocessing: Encodes categorical variables using one-hot encoding.Drops unnecessary columns like Time.<br>
<li>Output: Saves the cleaned and merged dataset to merged_locations.csv.<br></li>

# Dependencies
The following Python libraries are required:
<li>pandas<br>
<li>numpy<br>
<li>matplotlib<br>
<li>seaborn<br>
<li>scikit-learn<br>
<li>Data Description<br></li>

# Meteorological Data:
<li>Temperature at 2m (temperature_2m)<br>
<li>Relative humidity (relativehumidity_2m)<br>
<li>Dewpoint temperature (dewpoint_2m)<br>
<li>Wind speed at 10m and 100m (windspeed_10m, windspeed_100m)<br>
<li>Wind direction at 10m and 100m (winddirection_10m, winddirection_100m)<br>
<li>Wind gusts at 10m (windgusts_10m)<br>
<li>Power Output: Actual wind power generation (Power).<br>
<li>Location: Encoded as categorical variables for four locations.

# Output
The processed dataset is saved as merged_locations.csv for further use in machine learning models or other analyses.
