# BikeCleaner2025

# Citi Bike Data Processing

## Overview
This Jupyter Notebook processes raw Citi Bike trip data by cleaning, merging, and sampling multiple datasets. The cleaned dataset is optimized for further analysis and ensures data consistency.

## Features
- Loads raw Citi Bike data from multiple CSV files.
- Standardizes column names and formats datetime fields.
- Removes duplicate entries.
- Handles missing values by dropping incomplete rows.
- Merges multiple datasets into a single DataFrame.
- Samples 5% of the data to reduce file size while maintaining representativeness.
- Saves the cleaned and sampled dataset as a CSV file for further analysis.

## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas library

## Installation
1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```
2. Install dependencies:
   ```bash
   pip install pandas jupyter
   ```

## Usage
1. Ensure the raw Citi Bike data files are in the `Resources/` folder.
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Run the provided notebook step-by-step.
4. The cleaned and sampled dataset will be saved as `sampled_citibike_data.csv`.

## Notes
- Ensure all raw CSV files follow the Citi Bike data format.
- The sampling process is used to improve performance without losing key insights.

## License
This project is licensed under the MIT License.

## Contact
For questions or improvements, feel free to open an issue or reach out to the maintainer.

