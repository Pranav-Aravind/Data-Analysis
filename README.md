# Data Analysis and Visualization

This repository contains two small Python projects:
1. **Battery Life Data Analysis**: This project analyzes battery life data from two phones over 100 days. It calculates basic statistics and visualizes the data through histograms.
2. **Clicks and Cost Simulation**: This project simulates the number of clicks on a website over a year using the Poisson distribution. It calculates costs based on the number of clicks and generates visualizations.

### 1. Battery Life Data Analysis
This project works with a dataset of the battery life of **Amy's** and **Brian's** phones over 100 days. The script:
- Reads the data from a CSV file (`phone_battery_life.csv`).
- Calculates basic statistics for both phones, including:
  - **Mean** (average battery life)
  - **Median** (middle value of the data)
  - **Range** (difference between the maximum and minimum battery life)
  - **Standard Deviation** (how spread out the battery life values are)
- Plots histograms showing the distribution of battery life for both phones.

### 2. Clicks and Cost Simulation
This project simulates the number of clicks a website might get in one year (365 days) using a **Poisson distribution**, which models events happening randomly over time.
- The script generates a random number of clicks for each day.
- It then calculates a cost based on the number of clicks (with a base cost and an additional cost per click).
- Two histograms are generated:
  - One shows how often a specific number of clicks occurs in a year.
  - The other shows how the total cost is distributed over the year based on the clicks.
