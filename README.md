.. first 62 lines hidden ...                                                                                                                                                                 │
 │    36   - - `tipsTricks.ipynb`: Notebook with various Pandas tips and tricks.                                                                                                                    │
 │    33   + ### 📁 `Leaning_python`                                                                                                                                                                │
 │    34                                                                                                                                                                                            │
 │    38   - ### `pandas_tips_tricks`                                                                                                                                                               │
 │    35   + This folder contains notebooks that dive deeper into the process of learning Python specifically for data science, with an emphasis on Exploratory Data Analysis (EDA).                │
 │    36                                                                                                                                                                                            │
 │    40   - This folder contains additional notebooks with Pandas tips and tricks.                                                                                                                 │
 │    37   + -   **`02_master_pandas_EDA.ipynb`**:                                                                                                                                                  │
 │    38   +     -   **Purpose**: A comprehensive guide to performing EDA using Pandas.                                                                                                             │
 │    39   +     -   **Dataset**: Titanic.                                                                                                                                                          │
 │    40   +     -   **Techniques**:                                                                                                                                                                │
 │    41   +         -   Calculating the percentage of missing values.                                                                                                                              │
 │    42   +         -   Dropping columns with a high number of missing values (e.g., the 'deck' column).                                                                                           │
 │    43   +         -   Imputing missing values in the 'age' column using the mean.                                                                                                                │
 │    44   +         -   Imputing missing categorical data in 'embark_town' using the mode.                                                                                                         │
 │    45                                                                                                                                                                                            │
 │    42   - - `01_Pandas.ipynb`: Introductory notebook on Pandas, including data manipulation and analysis of the Pakistan population dataset.                                                     │
 │    43   - - `output.csv`: Output file from one of the notebooks.                                                                                                                                 │
 │    44   - - `pakistan_data.csv`: Dataset for data analysis.                                                                                                                                      │
 │    45   - - `pk_data.csv`: Another dataset for data analysis.                                                                                                                                    │
 │    46   + -   **`04_skimpy.ipynb`**:                                                                                                                                                             │
 │    47   +     -   **Purpose**: Demonstrates the use of the `skimpy` library for quick and efficient EDA.                                                                                         │
 │    48   +     -   **Dataset**: Titanic.                                                                                                                                                          │
 │    49   +     -   **Details**: Shows how `skimpy` can generate a detailed summary of the dataset, including data types, missing values, and statistical distributions, providing a quick         │
 │           overview of the data's health.                                                                                                                                                         │
 │    50                                                                                                                                                                                            │
 │    47   - ## Files                                                                                                                                                                               │
 │    51   + -   **`12_MasterPandas.iPYNB`**:                                                                                                                                                       │
 │    52   +     -   **Purpose**: Focuses on analyzing the Pakistan Population dataset.                                                                                                             │
 │    53   +     -   **Dataset**: Pakistan Population.                                                                                                                                              │
 │    54   +     -   **Techniques**:                                                                                                                                                                │
 │    55   +         -   Using `pd.set_option()` to display all columns and rows of a large DataFrame.                                                                                              │
 │    56   +         -   Inspecting column data types with `.dtypes`.                                                                                                                               │
 │    57   +         -   Generating a full statistical summary with `.describe()`.                                                                                                                  │
 │    58                                                                                                                                                                                            │
 │    49   - - `Notes.txt`: Notes on setting up a Conda environment for Python.                                                                                                                     │
 │    ════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════  │
 │    59   + -   **`13_yData_Master_Pandas.ipynb`**:                                                                                                                                                │
 │    60   +     -   **Purpose**: Showcases automated EDA using the `ydata-profiling` library.                                                                                                      │
 │    61   +     -   **Datasets**: Titanic and Pakistan Population.                                                                                                                                 │
 │    62   +     -   **Details**: Illustrates how to generate a detailed, interactive HTML report from a DataFrame. This report includes in-depth analysis of each variable, correlations, and      │
 │           missing value information, which is extremely useful for a quick and thorough data overview. The generated reports are saved in the `outputHtml` directory.                            │
 │    63   +                                                                                                                                                                                        │
 │    64   + -   **`lec1.ipynb`**:                                                                                                                                                                  │
 │    65   +     -   **Purpose**: A short notebook covering basic Python programming concepts like conditional logic and loops.                                                                     │
 │    66   +                                                                                                                                                                                        │
 │    67   + ---                                                                                                                                                                                    │
 │    68   +                                                                                                                                                                                        │
 │    69   + ### 📁 `Pandas_Tips_Trick` & `pandas_tips_tricks`                                                                                                                                      │
 │    70   +                                                                                                                                                                                        │
 │    71   + These folders contain various notebooks that offer quick tips, tricks, and practical examples for common data manipulation tasks in Pandas.                                            │
 │    72   +                                                                                                                                                                                        │
 │    73   + -   **`day_10_master_pasndas.ipynb`**:                                                                                                                                                 │
 │    74   +     -   **Purpose**: A master notebook covering a wide range of Pandas functionalities.                                                                                                │
 │    75   +     -   **Dataset**: Titanic.                                                                                                                                                          │
 │    76   +     -   **Techniques**:                                                                                                                                                                │
 │    77   +         -   Data inspection (`.info()`, `.describe()`).                                                                                                                                │
 │    78   +         -   Handling missing values.                                                                                                                                                   │
 │    79   +         -   Using `groupby()` to perform aggregate calculations on different segments of the data.                                                                                     │
 │    80   +         -   Creating a correlation matrix to understand relationships between numerical variables and visualizing it with a `seaborn` heatmap.                                         │
 │    81   +                                                                                                                                                                                        │
 │    82   + -   **`tipsTricks.ipynb`**:                                                                                                                                                            │
 │    83   +     -   **Purpose**: A collection of useful Pandas tips.                                                                                                                               │
 │    84   +     -   **Topics**:                                                                                                                                                                    │
 │    85   +         -   Checking the Pandas version.                                                                                                                                               │
 │    86   +         -   Creating a DataFrame from a NumPy array or random data.                                                                                                                    │
 │    87   +         -   Renaming columns using `.rename()`.                                                                                                                                        │
 │    88   +         -   Replacing spaces in column names with underscores.                                                                                                                         │
 │    89   +                                                                                                                                                                                        │
 │    90   + -   **`sendtip.ipynb`**:                                                                                                                                                               │
 │    91   +     -   **Purpose**: A focused tutorial on a common data cleaning task.                                                                                                                │
 │    92   +     -   **Technique**: Demonstrates how to split a single string column (e.g., 'Full Name') into multiple columns (e.g., 'First Name', 'Last Name') using the `.str.split()` method    │
 │           with `expand=True`.                                                                                                                                                                    │
 │    93   +                                                                                                                                                                                        │
 │    94   + -   **`01_Pandas.ipynb`**:                                                                                                                                                             │
 │    95   +     -   **Purpose**: An introductory notebook for basic Pandas operations.                                                                                                             │
 │    96   +     -   **Dataset**: Pakistan Population.                                                                                                                                              │
 │    97   +     -   **Techniques**: Reading data from a CSV, inspecting the first and last few rows with `.head()` and `.tail()`, and getting a statistical summary with `.describe()`.            │
 │    98   +                                                                                                                                                                                        │
 │    99   + -   **`markdownPractice.ipynb`**:                                                                                                                                                      │
 │    100  +     -   **Purpose**: A reference guide for using Markdown in Jupyter notebooks.                                                                                                        │
 │    101  +     -   **Topics**: Covers syntax for headings, bold/italic text, lists, links, images, code blocks, and tables.                                                                       │
 │    102  +                                                                                                                                                                                        │
 │    103  + ---                                                                                                                                                                                    │
 │    104  +                                                                                                                                                                                        │
 │    105  + ### 📄 Other Files                                                                                                                                                                     │
 │    106  +                                                                                                                                                                                        │
 │    107  + -   **`Notes.txt`**: Contains useful commands and notes for setting up a Conda virtual environment for data science projects, including installing `ipykernel` to make the             │
 │           environment available in Jupyter.                                                                                                                                                      │
 │    108  + -   **`pakistan_data.csv`**, **`tips.csv`**, **`titanic.csv`**: The raw data files used in the notebooks.    
