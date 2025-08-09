# Business Analytics Project

This project provides a ready-to-use example of a business analytics workflow using a synthetic dataset. It includes the following components:

- **Synthetic dataset** (`synthetic_business_data.csv`): Contains time-series data for a fictional company, including marketing spend, R&D spend, customer satisfaction, employee count, region, and sales.
- **Jupyter notebook** (`analysis_notebook.ipynb`): Guides you through exploratory data analysis (EDA) and builds a predictive model for sales using linear regression. The notebook includes visualizations such as histograms, scatter plots, and correlation heatmaps.
- **Requirements file** (`requirements.txt`): Lists all Python dependencies needed to run the notebook.

## Dataset Description

Each row in the dataset represents a period (e.g., week or month) with the following columns:

| Column | Description |
| --- | --- |
| `Time` | Sequential time index |
| `Marketing_Spend` | Marketing expenditure for the period (USD) |
| `R&D_Spend` | Research and development expenditure (USD) |
| `Customer_Satisfaction` | Customer satisfaction score (0–10 scale) |
| `Employee_Count` | Number of employees |
| `Region` | Geographic region (North, South, East, West) |
| `Sales` | Sales revenue (USD) |

## How to Use

1. Clone this repository to your local machine.

```bash
git clone <repo-url>
```

2. Navigate to the project directory and create a virtual environment (optional but recommended).

```bash
cd <project-directory>
python3 -m venv venv
source venv/bin/activate
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook and open `analysis_notebook.ipynb`:

```bash
jupyter notebook
```

5. Follow the notebook to explore the data and run the predictive model.

## License

This project is provided for educational purposes only. Feel free to use and adapt the code for your own learning or research.