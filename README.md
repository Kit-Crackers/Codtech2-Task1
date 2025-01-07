# Flight Delay Analysis with PySpark

## Objectives
- Analyze flight delay data to identify patterns.
- Calculate and compare delay percentages for different airlines.
- Visualize results for better insights.

## Dataset
The dataset contains the following key columns:
- **carrier_name**: Airline name.
- **arr_flights**: Total number of flights.
- **arr_del15**: Number of delayed flights (15+ minutes).
- Other columns related to delays (e.g., weather, security).

## Steps
1. Load the dataset into PySpark.
2. Group data by airline to calculate total flights and delayed flights.
3. Compute delay percentages for each airline.
4. Visualize the delay percentages using a bar graph.
5. Release resources by stopping the SparkSession.

## Results
- Airlines with the highest and lowest delay percentages were identified.
- The visualization provided a clear comparison of delay percentages across airlines.
- Insights can help improve airline punctuality and customer satisfaction.

