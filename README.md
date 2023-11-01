# NASA-Battery-project

## Overview

The dataset 'CS2_37_1_18_11.xlsx' contains information about a battery undergoing various testing procedures. It provides multiple parameters and measurements that can be utilized for understanding the battery's health, efficiency, and behavior during different steps and cycles of testing.

### General Dataset Information

- The dataset comprises 9871 entries and 17 columns representing different battery parameters.
- Various features such as Test_Time, Date_Time, Step_Time, Current, Voltage, Capacity, Energy, and Resistance, among others, are included.
- Initial inspection indicates no missing values and diverse data types, primarily float and integer types.

## Exploratory Data Analysis

### Battery Health Metric Calculation

- Data normalization and feature weighting were applied to derive a 'Battery Health Metric.'
- A histogram is plotted to depict the distribution of the calculated metric.
- Categorized battery health status into 'Unhealthy,' 'Intermediate,' and 'Healthy.'

### Battery Health Status Visualization

- A pie chart visualizes the distribution of different battery health statuses.

### Step and Cycle-Based Aggregations

- Calculated statistical measures (mean, median, and standard deviation) of Voltage and Current for both steps and cycles.
- Graphically represented step-based and cycle-based aggregations, illustrating the trends across different steps and cycles.

### Discharge Efficiency Analysis

- Discharge efficiency was computed from charge and discharge energy values.
- A histogram was plotted to demonstrate the distribution of discharge efficiency.

### Time-Series Analysis of Discharge Efficiency

- Utilized time-series analysis to observe the discharge efficiency trends concerning battery health status over time.
- Plotted these trends to visualize how discharge efficiency fluctuates concerning the battery's health status.

## Insights and Observations

- The battery health metric calculation allowed for better understanding of battery health status.
- Aggregations provided insights into step and cycle-based trends of voltage and current.
- Discharge efficiency analysis revealed a distribution, showing the variance in efficiency measurements.

## Conclusion

The analysis provides a comprehensive understanding of the battery's health, efficiency, and behavior during testing procedures. The visualizations and calculations offer insights into the battery's performance, guiding further analysis or actions.

