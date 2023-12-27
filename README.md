# Use of Regenerative Simulation for Staffing Call Centers

## Introduction
This project focuses on employing regenerative simulation to determine the optimal number of staff required in call centers. The goal is to maintain service quality metrics within an 8-hour workday with 95% confidence.

## Objective
Our main objective is to find the minimum number of call center agents required while ensuring service quality metrics are met, utilizing stochastic modeling and regenerative simulation techniques.

## Methodology
We divided the project into three parts:
- **Part A:** Define parameters and constraints, simulate with a 95% confidence interval, and verify average waiting time and abandonment rate.
- **Part B:** Similar to Part A but under different scenarios or simulation settings.
- **Part C:** Focus on the variances of abandonment rates and call wait times.

### Technologies Used
- Python (NumPy, Pandas, Plotly)
- Stochastic Modeling Techniques
- Regenerative Simulation

## Results
We determined the optimal number of agents required in different scenarios:
- Uniform Distribution Scenario: 67 agents
- Hyperexponential Distribution Scenario: 69 agents

## Visualization
The project includes various data visualizations such as:
- Wait Times vs. Number of Calls
- Abandoned Calls vs. Seconds
- Average Wait Times and Abandonment Rates vs. Number of Agents

