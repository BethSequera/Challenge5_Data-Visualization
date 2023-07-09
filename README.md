# DataVisualization-Challenge: Pymaceuticals Anti-Cancer Medication Study Analysis

This project involves analyzing a real-world dataset from Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications. The dataset consists of data from an animal study that aimed to find potential treatments for squamous cell carcinoma (SCC), a form of skin cancer.

## Project Objective

As a senior data analyst at Pymaceuticals, your task is to generate the necessary tables, figures, and a summary of the study results for the technical report. The focus is on comparing the performance of Pymaceuticals' drug of interest, Capomulin, against other treatment regimens.

## Project Structure

The project is organized into the following tasks:

1. **Data Preparation**: Merge the mouse metadata and study results data into a single DataFrame. Check for duplicate time points and create a cleaned DataFrame for further analysis.

2. **Summary Statistics**: Generate summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume. The statistics should be grouped by drug regimen.

3. **Bar Charts and Pie Charts**: Create bar charts to display the total number of rows (Mouse ID/Timepoints) for each drug regimen. Additionally, generate pie charts to visualize the distribution of female and male mice in the study.

4. **Quartiles, Outliers, and Box Plot**: Calculate the final tumor volume for each mouse across selected treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin). Determine potential outliers using quartiles and interquartile range (IQR). Create a box plot to display the distribution of the final tumor volume, highlighting any potential outliers.

5. **Line Plot and Scatter Plot**: Create a line plot showing the tumor volume versus time point for a mouse treated with Capomulin. Additionally, generate a scatter plot to depict the relationship between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.

6. **Correlation and Regression**: Calculate the correlation coefficient and perform a linear regression analysis between mouse weight and average observed tumor volume for the Capomulin treatment regimen. Plot the linear regression model on top of the scatter plot.

## Dependencies

The project utilizes the following dependencies:

- Pandas: For data manipulation and analysis.
- Matplotlib: For data visualization and plotting.

Ensure that these libraries are installed in your Python environment to run the analysis successfully.

## Getting Started

1. Clone this repository to your local machine.
2. Open the Jupyter notebook, `pymaceuticals_main.ipynb`, in your preferred environment.
3. Execute each cell in the notebook to run the analysis.
4. Review the generated tables, figures, and summary to gain insights into the study results.
5. Follow the instructions within the notebook for each task to complete the analysis.

Feel free to explore the dataset and perform additional analysis to derive further insights from the study.

If you have any questions or require further assistance, please let me know.
