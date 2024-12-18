# Analysis of Electronic Shop Data (2019)

This repository contains an analysis of electronic shop sales data from the year 2019 using Python Pandas and Matplotlib libraries.

## Setup

To access all of the files, you can either fork this repository and then clone it locally. Instructions on how to do this can be found [here](https://help.github.com/en/github/getting-started-with-github/fork-a-repo).

Another option is to click the green "Code" button and then select "Download ZIP". You can then extract all the files to your preferred location to edit the code.

### Installation Instructions

- **Installing Jupyter Notebook**: [Jupyter Notebook Installation](https://jupyter.readthedocs.io/en/latest/install.html)
- **Installing Pandas Library**: [Pandas Installation](https://pandas.pydata.org/pandas-docs/stable/install.html)
- **Installing Matplotlib Library**: [Matplotlib Installation](https://matplotlib.org/stable/users/installing.html)

## Background Information

This repository accompanies my analysis of electronic shop sales data from 2019. The data includes detailed records of sales transactions from the store, broken down by month, product type, cost, purchase address, etc.

### Data Cleaning

The initial step involves cleaning the data to ensure accuracy. Tasks in this section include:

- Dropping NaN values from DataFrame
- Removing rows based on specific conditions
- Changing the type of columns using `to_numeric`, `to_datetime`, and `astype`

### Data Exploration

After cleaning the data, we explore it to answer high-level business questions. This section uses various pandas and matplotlib methods to gain insights.

**Business Questions Explored**:

1. What was the best month for sales? How much was earned that month?
2. What city sold the most products?
3. What time should we display advertisements to maximize the likelihood of customer purchases?
4. What products are most often sold together?
5. Which product sold the most and why?

### Analytical Techniques

To answer these questions, several pandas and matplotlib methods are employed:

- Concatenating multiple CSV files to create a new DataFrame (`pd.concat`)
- Adding columns
- Parsing cells as strings to create new columns (`.str`)
- Applying functions with `.apply()`
- Using `groupby` to perform aggregate analysis
- Plotting bar charts and line graphs to visualize the results
- Labeling graphs for better understanding

## Usage

Clone this repository to your local machine, navigate to the project directory, and open the Jupyter Notebook to follow along with the analysis.

```bash
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
jupyter notebook
```
