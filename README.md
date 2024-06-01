# FIFA 2021 Data Cleaning Project

## Overview

This project involves cleaning the FIFA 2021 dataset using Python and the pandas library. The main objectives of this project are to:

- Load and explore the dataset
- Handle missing values
- Correct data types
- Remove duplicates
- Perform feature engineering
- Save the cleaned dataset for further analysis

## Dataset

The dataset used in this project is the FIFA 2021 player data, which includes various attributes of players such as age, nationality, club, overall rating, potential, and more.

## Repository Structure

FIFA_2021_Data_Cleaning/
├── data/
│ ├── fifa_2021_raw.csv # Raw dataset
│ ├── fifa_2021_cleaned.csv # Cleaned dataset
├── notebooks/
│ ├── FIFA_2021_Data_Cleaning.ipynb # Jupyter notebook with data cleaning steps
├── README.md # Project overview and instructions


## Installation

To run this project, you need to have Python installed along with the following libraries:

- pandas
- numpy

You can install these libraries using pip:

```sh
pip install pandas numpy
```

## Usage
1. **Clone the repository:**

```sh
git clone https://github.com/your-username/FIFA_2021_Data_Cleaning.git
cd FIFA_2021_Data_Cleaning
```

2. **Run the Jupyter notebook:**
Open FIFA_2021_Data_Cleaning.ipynb in Jupyter Notebook or Jupyter Lab to follow along with the data cleaning steps.

3. **Data Cleaning Steps:**
The notebook includes the following data cleaning steps:

**Loading the data:** Load the raw dataset into a pandas DataFrame.
**Exploratory Data Analysis (EDA):** Perform basic EDA to understand the structure and contents of the dataset.
**Handling missing values:** Identify and handle missing values appropriately.
**Correcting data types:** Convert columns to their appropriate data types.
**Removing duplicates:** Remove duplicate rows to ensure data quality.
**Feature engineering:** Create new features and modify existing ones for better analysis.
**Saving the cleaned data:** Save the cleaned dataset to a CSV file for future use.

## Results
The cleaned dataset is saved as fifa_2021_cleaned.csv in the data directory. This cleaned data can be used for further analysis, such as building machine learning models or visualizing player statistics.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue to discuss your proposed changes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements
The dataset is provided by Kaggle, and all credits for the data go to the original authors.