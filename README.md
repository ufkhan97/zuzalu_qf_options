# Zuzalu QF Options

This project is a Python-based implementation of Quadratic Funding (QF) options. It uses Jupyter notebooks and Python scripts to process and analyze data related to funding rounds.

## Key Files and Sections

### `zuzalu_qf_options.ipynb`

This Jupyter notebook is the main file where the data processing and analysis are performed. It includes the following key sections:

- **Data Import and Preparation**: The notebook imports necessary libraries and prepares the data for analysis. It reads data from CSV files and performs data cleaning and transformation operations. See lines 1-37 and 45-71.

- **Data Analysis**: The notebook performs various data analysis tasks, such as calculating average and median donations, and preparing data for different strategies. See lines 100-112 and 121-142.

- **QF Matching Calculation**: The notebook calculates QF matching for different strategies using the `fundingutils.get_qf_matching` function. See lines 124-142.

- **Data Visualization**: The notebook generates various plots to visualize the results of the QF matching calculation. See lines 226-271 and 279-296.

### `fundingutils.py`

This Python script contains helper functions used in the `zuzalu_qf_options.ipynb` notebook. Key functions include:

- prep_donations_data: Prepares the donations data for analysis. See lines 347-350.

- pivot_votes: Transforms the votes data into a pivot table. See lines 352-354.

- get_qf_matching: Calculates QF matching for different strategies. See lines 356-376.

- COCM: Implements the Connection-Oriented Cluster Matching algorithm for QF. See lines 215-284.


## How to Run

To run the analysis, open the `zuzalu_qf_options.ipynb` notebook in a Jupyter environment and execute the cells in order. Make sure the necessary data files are available in the specified paths. The `fundingutils.py` script should be in the same directory as the notebook.