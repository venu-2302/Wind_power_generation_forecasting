# Wind_power_generation_forecasting

# Features
<li>Data Loading: Reads data from multiple CSV files (Location1.csv, Location2.csv, Location3.csv, and Location4.csv), each representing wind-related metrics for different locations.
<li></li>Data Merging: Combines data from all locations into a single dataset for analysis.
<li></li>Exploratory Data Analysis (EDA): Displays summary statistics.Identifies missing values and duplicates.
<li></li>Data Preprocessing: Encodes categorical variables using one-hot encoding.Drops unnecessary columns like Time.
<li></li>Output: Saves the cleaned and merged dataset to merged_locations.csv.

# Dependencies
The following Python libraries are required:
<li>pandas
numpy
matplotlib
seaborn
scikit-learn
Data Description</li>

The dataset includes the following features:

Meteorological Data:

Temperature at 2m (temperature_2m)

Relative humidity (relativehumidity_2m)

Dewpoint temperature (dewpoint_2m)

Wind speed at 10m and 100m (windspeed_10m, windspeed_100m)

Wind direction at 10m and 100m (winddirection_10m, winddirection_100m)

Wind gusts at 10m (windgusts_10m)

Power Output: Actual wind power generation (Power).

Location: Encoded as categorical variables for four locations.

Output
The processed dataset is saved as merged_locations.csv for further use in machine learning models or other analyses.
