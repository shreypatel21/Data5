# GHG Emission Analysis and Prediction

This project analyzes historical greenhouse gas (GHG) emissions data, predicts future trends, calculates emission reduction requirements, and estimates the potential carbon credits generated. The project uses Python for data analysis, modeling, and visualization.

## Features

- Analyzes GHG emission data from historical records (1970–2022).
- Fits a polynomial curve to model emission trends.
- Predicts future emissions (e.g., for the next 10 years).
- Calculates annual and total emission reduction requirements to meet specified targets.
- Estimates potential carbon credits generated from emission reductions.
- Visualizes data, predictions, and reduction targets.

## Project Structure

- **Code**: Python scripts for data analysis, modeling, and visualization.
- **Data**: GHG emissions data stored in a CSV file (`ghg_emissions.csv`).
- **Visualization**: Graphs showing historical data, polynomial fit, future predictions, and emission reduction targets.

## Prerequisites

- Python 3.x
- Required Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `sklearn`



## Example CSV File Format

The `ghg_emissions.csv` file should have the following structure:

```csv
Year,GHG Emissions
1970,100
1971,110
1972,120
...
2022,2300
```