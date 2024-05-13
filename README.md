# Mental Health Survey Data Analysis

This project explores a Mental Health Survey dataset sourced from Kaggle. It includes two main files:

1. **Mental_health_EDA.ipynb**: This Jupyter Notebook file contains extensive exploration and analysis of the dataset. It covers various aspects such as data cleaning, visualization, and statistical analysis.

2. **Mental_Health_Viz.ipynb**: This Jupyter Notebook file contains custom functions to generate specific types of graphs. Currently, it includes functions for creating bar charts and heatmaps with customized styling.

## Custom Graph Functions

### `white_bar_plot`

This function generates a bar plot with white text on a transparent background as a PNG file. It includes options to filter data by country and group columns, and to normalize the values if needed.

#### Parameters:

- `df` (DataFrame): The DataFrame containing the data.
- `country` (str, optional): The country to filter the data for. If not provided, plots for all countries.
- `group_col` (str, optional): The column to group the data by and display on the x-axis.
- `value_col` (str, optional): The column containing the values to display as bars or hues.
- `norm` (bool, optional): Whether to normalize the values. Default is False.

#### Output:

- The function generates a bar plot and saves it as a PNG file with 300 DPI resolution and a transparent background.

### `white_heatmap`

This function generates a heatmap with white text on a transparent background as a PNG file. It also includes options to filter data by country and group columns.

#### Parameters:

- `df` (DataFrame): The DataFrame containing the data.
- `country` (str, optional): The country to filter the data for. If not provided, plots for all countries.
- `group_col` (str, optional): The column to group the data by and display on the x-axis.
- `value_col` (str, optional): The column containing the values to display as bars or hues.

#### Output:

- The function generates a heatmap and saves it as a PNG file with 300 DPI resolution and a transparent background.

## Keynote Presentation

The project also includes a PDF file containing a keynote presentation summarizing the key findings and insights from the exploratory data analysis.

## Usage

1. Ensure you have the necessary Python packages installed, including pandas, seaborn, and matplotlib.
2. Open the Jupyter Notebooks (`Exploratory_Data_Analysis.ipynb` and `Custom_Graph_Functions.ipynb`) in your preferred environment.
3. Execute the cells in the notebooks to perform analysis and generate graphs.
4. Customize the functions or analysis as needed for your specific requirements.

## Author

- [Emil Johansson](https://github.com/getfader)

Feel free to reach out for any questions or feedback!
