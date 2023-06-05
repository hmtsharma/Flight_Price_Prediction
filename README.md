# Flight_Price_Prediction
The project "EDA for Airline Price Prediction" aims to perform Exploratory Data Analysis (EDA) on a dataset with the goal of understanding the data and preparing it for building a predictive model to estimate airline ticket prices. Here's how you can conduct EDA for this project based on the provided information:

1. Airline: Explore the distribution of airlines in the dataset. Analyze the frequency of each airline and determine if there are any dominant airlines or if the distribution is relatively balanced.

2. Flight: Analyze the flight codes to understand if there are any patterns or correlations between flight codes and ticket prices. Check for any missing or inconsistent values.

3. Source City and Destination City: Examine the source and destination cities to identify the most common routes and determine if certain city pairs have higher or lower ticket prices.

4. Departure Time: Investigate the departure time bins and their relationship with ticket prices. Analyze if there are any time periods during the day or week that tend to have higher or lower prices.

5. Stops: Explore the distribution of the number of stops and its impact on ticket prices. Determine if flights with more stops have higher or lower prices compared to non-stop or single-stop flights.

6. Arrival Time: Analyze the arrival time bins to identify any patterns or correlations with ticket prices. Determine if certain arrival time periods are associated with higher or lower prices.

7. Class: Investigate the distribution of seat classes (Business and Economy) and their relationship with ticket prices. Determine if there are significant price differences between the two classes.

8. Duration: Examine the distribution of flight durations and its relationship with ticket prices. Determine if longer or shorter flights tend to have higher prices.

9. Days Left: Analyze the derived feature of days left between the booking and trip dates. Determine if there is any correlation between the number of days left and ticket prices.

10. Price: Explore the distribution of ticket prices. Analyze the statistical properties such as mean, median, and range. Check for outliers and determine if there are any significant price variations based on the other features.

During the EDA process, The project involves conducting Exploratory Data Analysis (EDA) on a dataset to gain insights and prepare the data for building a predictive model to estimate airline ticket prices. Here's utilize various techniques such as

1. Data Understanding: Begin by understanding the dataset and its structure. Review the column names, data types, and the overall layout of the data. Identify the target variable, which in this case is the "Price" column, as this is what we want to predict.

2. Data Cleaning: Clean the data to ensure its quality and usability. Handle missing values, outliers, and inconsistencies in the dataset. This step is crucial for accurate analysis and modeling.

3. Descriptive Statistics: Compute descriptive statistics such as mean, median, standard deviation, and quartiles for numerical columns like "Duration" and "Price". This provides a summary of the data distribution and helps identify any unusual patterns.

4. Data Visualization: Create visual representations of the data to uncover patterns, trends, and relationships. Use techniques like histograms, scatter plots, box plots, and bar charts to explore the distribution of variables, identify outliers, and analyze correlations between variables.

5. Feature Engineering: Create new features or modify existing ones to enhance the predictive power of the data. For example, you could extract additional information from the "Departure Time" and "Arrival Time" columns to capture patterns or create new derived features such as day of the week or time of the day.

6. Feature Selection: Select the most relevant features that have a strong correlation with the target variable. This step helps reduce noise and improve the efficiency of the predictive model.

7. Data Preprocessing: Preprocess the data by encoding categorical variables using techniques like one-hot encoding or label encoding. Scale numerical features if necessary to ensure all variables are on a similar scale.

8. Data Split: Split the dataset into training and testing sets. The training set is used to build the predictive model, while the testing set is used to evaluate its performance.

By performing these steps, I gain a comprehensive understanding of the dataset, identify important patterns and relationships, and prepare the data for the subsequent stages of building a predictive model for airline price prediction.
