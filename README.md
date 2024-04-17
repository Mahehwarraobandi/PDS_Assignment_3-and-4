# PDS_Assignment_3-and-4

For the Question 1 -
I have used the Fixer Currency API as an example, since it provides a straightforward API for accessing currency exchange rates, which are commonly used and easy to understand.

These are the steps included - 

API Registration: First, you would need to sign up at Fixer.io to get an API key.
Fetch Data: Use the requests library to make an API call and fetch data.
Parse JSON: Parse the JSON response to get the desired data.
Display Data: Use a Python library to display the data. We'll use pandas here for simplicity, but for a more interactive or user-friendly interface, you might consider using Dash.

For this approach i have visualized, interactive way to represent the data fetched from the API, which can be particularly useful for presentations, dashboards, or public displays.


For the Question 2 -
These are the steps included for the question 2

Step A: Random Sample and Comparison of Glucose Levels

1. Load the Data
Import necessary libraries (e.g., pandas).
Load the data from the CSV file into a pandas DataFrame.

2. Set Seed and Sample Data
Set a random seed to ensure reproducibility.
Randomly select 25 observations from the dataset.

3. Calculate Sample Statistics
Compute the mean and maximum Glucose levels from the sample.

4. Calculate Population Statistics
Compute the mean and maximum Glucose levels from the entire dataset.

5. Visualization
Create bar charts to compare these statistics between the sample and the entire dataset.


Step B: 98th Percentile of BMI

1. Calculate Percentiles
Find the 98th percentile of BMI for both the sample and the entire dataset.

2. Visualization
Plot the results to visually compare the 98th percentiles of BMI from the sample and the population.

Step C: Bootstrap Analysis for Blood Pressure

1. Bootstrap Sampling
Perform a bootstrap sampling 500 times, each with 150 observations.
For each sample, calculate the mean, standard deviation, and the 50th percentile of Blood Pressure.

2. Calculate Bootstrap Statistics
Find the average of the means, standard deviations, and percentiles across all bootstrap samples.

3. Calculate Population Statistics
Compute the mean, standard deviation, and 50th percentile of Blood Pressure from the entire dataset.

4. Visualization
Create bar charts to compare the bootstrap statistics to the actual population statistics.

5. Interpret Results
Analyze the visualizations to determine the accuracy and reliability of bootstrap sampling as a method for estimating population parameters.



