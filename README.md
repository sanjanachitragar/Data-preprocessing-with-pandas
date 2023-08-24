# Data Preprocessing with Pandas

This repository contains Python scripts that demonstrate data preprocessing tasks using the Pandas library. The scripts showcase how to identify and handle duplicate rows and how to remove columns with only one unique value from a dataset.

## Usage

1. Download or clone this repository to your local machine.

2. Place the respective CSV files ("iris.csv" and "oil_spill.csv") in the same directory as the scripts.

3. Open a terminal or command prompt and navigate to the repository directory.

4. Run the Python scripts:

   ```bash
   python remove_duplicates.py
   python remove_columns.py

## About the Scripts

### `remove_duplicates.py`

This script loads the "iris.csv" dataset using Pandas and demonstrates how to identify and handle duplicate rows. It calculates whether there are any duplicates, lists all duplicate rows, and then deletes duplicate rows from the dataset.

### `remove_columns.py`

This script loads the "oil_spill.csv" dataset using Pandas and showcases how to summarize the number of unique values in each column. It identifies columns with only one unique value and deletes those columns from the dataset.

## Input

The scripts use the "iris.csv" and "oil_spill.csv" datasets, which contain data for demonstration purposes.

## Output

Both scripts output information about duplicates and columns with a single unique value, and they modify the datasets accordingly.

