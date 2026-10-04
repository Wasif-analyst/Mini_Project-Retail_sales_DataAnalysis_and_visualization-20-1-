# Retail Sales Data Analysis and Visualization

A mini data-analysis project that explores retail sales data, cleans the dataset, performs statistical analysis, and creates different visualizations for sales, profit, quantity, category, region, month, and day-of-week performance.

## Project Overview

This project uses Python and Jupyter Notebook to analyze the `retail_sales.csv` dataset.

The project includes:

- Loading and inspecting the retail sales dataset.
- Checking dataset dimensions, data types, and missing values.
- Cleaning invalid and missing data.
- Converting dates and numerical columns.
- Creating month, quarter, month-name, and day-of-week columns.
- Analyzing sales and profit by product category.
- Analyzing sales and profit by region.
- Studying monthly sales and profit trends.
- Comparing performance by day of the week.
- Creating a correlation heatmap.
- Creating a four-chart retail sales dashboard.
- Generating key business insights and recommendations.

## Project Files

```text
Retail-Sales-Data-Analysis/
│
├── Mini_Project-Retail_sales_DataAnalysis_and_visualization-1.ipynb
├── retail_sales.csv
└── README.md
```

> Make sure that `retail_sales.csv` is present in the same folder as the Jupyter Notebook.

## Dataset Columns

The dataset contains the following columns:

| Column | Description |
|---|---|
| `Date` | Date of the transaction |
| `Category` | Product category |
| `Sales` | Sales amount |
| `Quantity` | Number of items sold |
| `Profit` | Profit amount |
| `Region` | Sales region |

## Technologies Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn

## Python Libraries

Install the required libraries with this command:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## How to Run the Project

### 1. Clone the repository

```bash
git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
```

Replace `your-username` and `your-repository-name` with your own GitHub username and repository name.

### 2. Open the project folder

```bash
cd your-repository-name
```

### 3. Start Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the notebook

Open the following file in Jupyter Notebook:

```text
Mini_Project-Retail_sales_DataAnalysis_and_visualization-1.ipynb
```

### 5. Run all cells

Run the notebook cells from top to bottom. The notebook will load the CSV file, clean the data, perform analysis, and display the visualizations.

## Data Cleaning

The project performs the following data-cleaning steps:

- Converts the `Date` column into a datetime format.
- Creates `Month`, `Quarter`, `MonthName`,
