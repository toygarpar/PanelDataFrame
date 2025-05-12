

---

# PanelDataFrame

**PanelDataFrame** is an introductory project aimed at teaching/learning data analysis using Python's powerful libraries such as `pandas`, `matplotlib`, and `seaborn`. Through a series of Jupyter notebooks and accompanying datasets,learn how to manipulate, clean, and visualize data effectively.

## 📁 Repository Contents

### Notebooks

* **`handson-Series.ipynb`**: Introduction to pandas Series, covering creation, indexing, and basic operations.
* **`handson-DataFrame.ipynb`**: Deep dive into pandas DataFrames, including data selection, filtering, and aggregation.
* **`handson-cleaning-values.ipynb`**: Techniques for cleaning and preprocessing data, handling duplicates, and formatting.
* **`handson-missing-data.ipynb`**: Strategies for detecting and handling missing data within datasets.
* **`handson-matplot-viz.ipynb`**: Data visualization using matplotlib, including line plots, bar charts, and histograms.
* **`handsonbasicplotting.ipynb`**: Basics of plotting with pandas' built-in visualization capabilities.
* **`pd-reading-data.ipynb`**: Reading data from various sources like CSV and JSON files using pandas.
* **`pd-reading-excel.ipynb`**: Importing and exporting Excel files with pandas.
* **`pd-reading-from-db.ipynb`**: Connecting to databases and querying data using pandas.

### Datasets

* **CSV Files**:

  * `artists.csv`
  * `btc-eth-prices-outliers.csv`
  * `btc-market-price.csv`
  * `eth-price.csv`
  * `exam_review.csv`
  * `out.csv`
* **JSON Files**:

  * `artists.json`
* **Excel Files**:

  * `exceloutput.xlsx`
  * `exceloutput2.xlsx`
  * `exceloutput3.xlsx`
* **Database**:

  * `chinook.db`: A sample SQLite database for practicing SQL queries and database interactions.

### Visualizations

* **`histogram_plot.png`**: An example histogram generated during the data visualization exercises.

## 🛠️ Getting Started

### Prerequisites

Ensure you have the following installed:

* Python 3.6 or higher
* Jupyter Notebook
* Required Python libraries:

  * `pandas`
  * `matplotlib`
  * `seaborn`
  * `sqlite3` (for database interactions)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/toygarpar/PanelDataFrame.git
   cd PanelDataFrame
   ```

2. **Install the required libraries**:

   It's recommended to use a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install pandas matplotlib seaborn jupyter
   ```

3. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

   Navigate to the cloned repository folder and open the desired notebook to begin.

## 🎯 Learning Objectives



* Understand the fundamentals of pandas Series and DataFrames.
* Learn data cleaning and preprocessing techniques.
* Handle missing data effectively.
* Visualize data using matplotlib and seaborn.
* Read and write data from various file formats and databases.


