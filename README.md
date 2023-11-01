# NASA-Battery-project
# Battery Testing Data Analysis

This repository contains analysis and insights derived from battery testing data.

## Dataset Overview

The dataset 'CS2_37_1_18_11.xlsx' includes information about battery performance during testing. 

### Columns Description

- `Data_Point`: Sequential data index.
- `Test_Time(s)`: Duration of the battery test in seconds.
- `Date_Time`: Timestamp of the recorded data point.
- `Step_Time(s)`: Duration of the current step within the test.
- `Step_Index`: Numerical index for different test steps.
- `Cycle_Index`: Numerical index representing specific cycles of the test.
- `Current(A)`: Electric current flowing in or out of the battery.
- `Voltage(V)`: Electric potential across the battery.
- `Charge_Capacity(Ah)`: Capacity during the charging process.
- `Discharge_Capacity(Ah)`: Capacity during the discharging process.
- `Charge_Energy(Wh)`: Energy consumed or produced during charging.
- `Discharge_Energy(Wh)`: Energy consumed or produced during discharging.
- `dV/dt(V/s)`: Rate of voltage change over time.
- `Internal_Resistance(Ohm)`: Battery's internal resistance.

## Data Preprocessing

- Dropped columns related to insignificant data ('Is_FC_Data', 'AC_Impedance(Ohm)', 'ACI_Phase_Angle(Deg)').
- Normalized features related to battery health.

## Battery Health Analysis

Analyzed battery health metric based on specific features and their weights. Derived battery health statuses as 'Healthy,' 'Intermediate,' and 'Unhealthy' based on thresholds.

## Aggregations

- Calculated step-based and cycle-based statistics for Voltage and Current.

## Discharge Efficiency

Analyzed battery discharge efficiency based on 'Charge_Energy(Wh)' and 'Discharge_Energy(Wh)'. Visualized its distribution and time-series trends based on battery health status.

### Insights
- The distribution of battery health status shows an even spread across health categories.
- Discharge efficiency is within a diverse range, depicting varying performance.

## Visualizations

The repository includes visualizations depicting trends and distributions of different battery-related metrics.

## Repository Structure

- **Notebooks**: Jupyter notebooks with analysis code.
- **Data**: Dataset used for the analysis.
- **Visualizations**: Graphical representations of battery-related insights.

