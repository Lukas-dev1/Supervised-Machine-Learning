
# Vehicle Dataset Analysis

This project involves the analysis of a vehicle dataset obtained from [Kaggle](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho). The dataset contains information about various vehicles, including details like the model year, selling price, fuel type, and more. The analysis focuses on understanding the relationships between different attributes and aims to provide insights for car pricing.

## Installation

To run the code in this notebook, you need to install the required dependencies. The main packages used are:

- `statsmodels==0.14.2`
- `pandas`
- `numpy`
- `scipy`
- `matplotlib`

You can install them using the following command:

```bash
pip install statsmodels==0.14.2 pandas numpy scipy matplotlib
```

## Overview of the Notebook

1. **Data Loading**: The dataset is loaded from a CSV file and initial exploration is performed.
2. **Nulls and Duplicates Check**: The dataset is checked for null values and duplicate records.
3. **Data Cleaning**: Any missing or duplicate data is handled appropriately.
4. **Statistical Analysis**: Various statistical models are used to analyze the relationship between vehicle features and prices.
5. **Visualization**: Graphs and charts are generated to visualize data trends and relationships.

## How to Use

- Clone this repository and navigate to the directory where the notebook is stored.
- Install the necessary packages using the above installation command.
- Run the Jupyter notebook to perform the analysis and view the results.

## Dataset Information

The dataset includes the following columns:

- **Model Name**: The name of the vehicle model.
- **Year**: The manufacturing year of the vehicle.
- **Selling Price**: The price at which the vehicle is sold.
- **Present Price**: The current market price of the vehicle.
- **Kilometers Driven**: The total kilometers driven by the vehicle.
- **Fuel Type**: The type of fuel used by the vehicle (Petrol, Diesel, CNG).
- **Seller Type**: Whether the vehicle is sold by a dealer or an individual.
- **Transmission**: The type of transmission (Manual or Automatic).
- **Owner**: The number of previous owners.

## License

This project is for educational purposes and uses a dataset provided by Kaggle. Please check the original dataset's license for more details.
