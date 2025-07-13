# 🐍 Python Data Science Notebooks

A collection of Jupyter notebooks focused on learning Python for Data Science, particularly around **Pandas**, **Exploratory Data Analysis (EDA)**, and **data cleaning**.

---

## 📁 Learning Python

This section contains notebooks dedicated to foundational Python programming and EDA using Pandas.

### Notebooks

- **`02_master_pandas_EDA.ipynb`**
  - **Purpose**: Comprehensive guide to performing EDA using Pandas.
  - **Dataset**: Titanic
  - **Techniques**:
    - Percentage of missing values
    - Dropping high-missing columns (e.g., `deck`)
    - Imputing missing values in `age` and `embark_town`

- **`04_skimpy.ipynb`**
  - **Purpose**: Demonstrates the use of the `skimpy` library for quick EDA.
  - **Dataset**: Titanic
  - **Details**: Summarizes data types, missing values, and distributions.

- **`12_MasterPandas.ipynb`**
  - **Purpose**: Analyzing the Pakistan Population dataset.
  - **Dataset**: Pakistan Population
  - **Techniques**:
    - `pd.set_option()` for full DataFrame display
    - `.dtypes`, `.describe()`

- **`13_yData_Master_Pandas.ipynb`**
  - **Purpose**: Automated EDA using `ydata-profiling`.
  - **Datasets**: Titanic and Pakistan Population
  - **Details**: Generates an interactive HTML report with full dataset profiling.

- **`lec1.ipynb`**
  - **Purpose**: Covers basic Python concepts like conditionals and loops.

---

## 📁 Pandas Tips & Tricks

These folders (`Pandas_Tips_Trick`, `pandas_tips_tricks`) include focused notebooks for quick reference, practical usage, and common tasks in Pandas.

### Notebooks

- **`day_10_master_pandas.ipynb`**
  - **Purpose**: Master-level Pandas tips.
  - **Dataset**: Titanic
  - **Topics**:
    - `.info()`, `.describe()`
    - Handling missing data
    - `groupby()` operations
    - Correlation matrix + heatmap

- **`tipsTricks.ipynb`**
  - **Purpose**: Quick Pandas tips
  - **Topics**:
    - Check Pandas version
    - Create DataFrame from NumPy/random
    - Rename columns, replace spaces with underscores

- **`sendtip.ipynb`**
  - **Purpose**: Splitting string columns
  - **Technique**: Use `.str.split()` with `expand=True` to split "Full Name" into "First Name" and "Last Name"

- **`01_Pandas.ipynb`**
  - **Purpose**: Intro to basic Pandas
  - **Dataset**: Pakistan Population
  - **Topics**:
    - Reading CSV
    - `.head()`, `.tail()`, `.describe()`

- **`markdownPractice.ipynb`**
  - **Purpose**: Markdown syntax in Jupyter
  - **Topics**: Headings, formatting, lists, links, code blocks, tables

---

## 📄 Other Files

- **`Notes.txt`**: Useful Conda environment setup tips and commands, including `ipykernel` configuration.
- **Datasets**:
  - `pakistan_data.csv`
  - `tips.csv`
  - `titanic.csv`

---

## 🚀 Quick Start

```bash
# Create Conda environment
conda create -n myenv python=3.10
conda activate myenv

# Install essentials
pip install pandas numpy jupyterlab seaborn skimpy ydata-profiling ipykernel

# Add environment to Jupyter
python -m ipykernel install --user --name=myenv
