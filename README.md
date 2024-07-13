# Sales-EDA

## Overview

**Sales-EDA** is an exploratory data analysis (EDA) project focused on sales data. This project aims to uncover insights, patterns, and trends within the sales data, utilizing various data visualization and statistical techniques. It is designed to help businesses understand their sales performance and make data-driven decisions.

## Features

- **Data Cleaning**: Preprocessing and cleaning of raw sales data to ensure accuracy and consistency.
- **Descriptive Statistics**: Summary statistics to provide an overview of the sales data.
- **Data Visualization**: Graphical representations of data to identify patterns, trends, and anomalies.
- **Correlation Analysis**: Examination of relationships between different variables.
- **Sales Trends**: Analysis of sales trends over time, including seasonal patterns.
- **Customer Segmentation**: Identification of distinct customer groups based on purchasing behavior.

## Dataset

The sales data used in this project can be found in the `data` directory. It includes the following fields:
- `Order ID`
- `Product`
- `Quantity Ordered`
- `Price Each`
- `Order Date`
- `Purchase Address`

## Installation

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- [Other dependencies listed in `requirements.txt`]

### Installation Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/P1X3LD3M0N/Sales-EDA.git
   cd Sales-EDA
   ```

2. **Create a virtual environment and activate it:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Start Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

5. **Open and run the `Sales_EDA.ipynb` notebook:**

   Navigate to the notebook file and execute the cells to perform the EDA.

## Usage

### Notebooks

- `Sales_EDA.ipynb`: Main notebook containing all the analysis and visualizations.
- `Data_Cleaning.ipynb`: Notebook focused on data cleaning and preprocessing.
- `Visualization.ipynb`: Notebook dedicated to creating various visualizations.

### Scripts

- `data_cleaning.py`: Script for cleaning and preprocessing the data.
- `visualization.py`: Script for generating visualizations.

## Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/stable/)
