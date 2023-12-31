# Automatidata NYC Taxi Fare Prediction Project

## Project Overview
The NYC Taxi & Limousine Commission has partnered with Automatidata to develop a regression model for predicting taxi cab ride fares. This phase of the project focuses on data analysis, exploration, cleaning, and structuring before any modeling can begin.

### Key Insights

**The Problem:** During initial exploratory data analysis (EDA) on a sample of the data provided by the New York City TLC, it became apparent that some data points would pose challenges for accurate fare prediction. Specifically, trips with a total cost entered but a total distance of "0" are identified as anomalies or outliers that must be addressed in the algorithm.

**Proposed Solution:** Following analysis, we recommend removing outliers with a recorded total distance of "0."

**Learnings:** We observed that the majority of trip distances are below 5 miles, but there are outliers with distances up to 35 miles. Fortunately, there are no missing values in the dataset.

**Remaining Questions:** We identified several trips with a trip distance of "0.0." Exploring the nature of these trips and their potential impact on our model is a priority.

### Keys to Success
1. Ensuring that the sample provided by New York City TLC accurately represents their overall data.
2. Developing a plan for addressing other outliers, such as low trip distances coupled with high costs.

## Details

As a result of our exploratory data analysis, the Automatidata data team identified trip distance and total amount as key variables for characterizing a taxi cab ride. The provided scatter plot visually demonstrates the relationship between these two variables, and it was generated using Tableau to enhance the visualization.

### Next Steps
Our next steps include:
- Identifying any additional unusual data points that could pose challenges for future fare prediction analysis, particularly those related to longer trip durations.
- Determining the variables with the most significant impact on trip fares.
- Narrowing down the set of relevant variables for regression, statistical analysis, and parameter tuning.

This README provides an overview of the project's initial analysis and sets the stage for further exploration and model development.
