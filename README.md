# Customer Service Request Analysis

This project analyzes customer service requests data to identify trends, patterns, and insights. The analysis includes data cleaning, visualization, and statistical testing.

## Table of Contents
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Steps](#analysis-steps)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used in this project is the "311 Service Requests from 2010 to Present" dataset, which contains information about various service requests made by customers.

## Installation

To run this project, you need to have Python installed along with the following libraries:
- pandas
- matplotlib
- seaborn
- scipy

You can install the required libraries using pip:
```bash
pip install pandas matplotlib seaborn scipy
```

## Usage

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Customer-Service-Request-Analysis.git
```

2. Navigate to the project directory:
```bash
cd Customer-Service-Request-Analysis
```

3. Run the Jupyter Notebook:
```bash
jupyter notebook "Customer Service Requests Analysis Project.ipynb"
```

## Analysis Steps

1. **Load the Dataset**: Load the dataset into a pandas DataFrame.
2. **Inspect the Data**: Check the shape of the dataset and inspect the first few rows.
3. **Check for Null Values**: Identify columns with null values and their counts.
4. **Data Cleaning**:
   - Convert problematic columns to appropriate data types.
   - Drop rows with null values in important columns or fill missing values.
   - Convert date columns to datetime format and handle invalid dates.
5. **Data Visualization**:
   - Plot the frequency of complaints by city.
   - Visualize complaint concentration in Brooklyn using scatter and hexbin plots.
   - Plot the frequency of different complaint types.
   - Visualize the top 10 most frequent complaint types.
   - Create a heatmap of complaint types across cities.
6. **Statistical Analysis**:
   - Calculate the average response time for each complaint type.
   - Perform a Chi-Square Test to analyze the relationship between complaint type and city.

## Results

- The dataset contains 364,558 rows and 53 columns.
- Various columns have null values, which were handled appropriately.
- Visualizations provide insights into the distribution and concentration of complaints.
- The average response time for different complaint types was calculated.
- A Chi-Square Test was performed to analyze the relationship between complaint type and city.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
