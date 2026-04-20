📌 Project Title
Wine Dataset Analysis and Preprocessing using Python
This project uses a Wine dataset to analyze chemical properties of wines, clean the data, detect outliers, transform features, and visualize relationships between variables. 

📖 About the Project
The notebook focuses on understanding the dataset through:
Loading and inspecting data
Statistical summary
Missing value analysis
Duplicate record detection
Outlier detection using Z-score and IQR
Outlier treatment (capping values)
Log transformation
Feature selection
Data visualization with multiple chart types 

⚙️ How It Works (Step-by-Step)
Step 1:
Import libraries.

Step 2:
Load Wine dataset.

Step 3:
Check rows, columns, datatypes.

Step 4:
Analyze missing values and duplicates.

Step 5:
Visualize Magnesium distribution.

Step 6:
Detect outliers using Z-score and IQR.

Step 7:
Treat outliers.

Step 8:
Apply log transformation.

Step 9:
Visualize relationships between wine features.

Step 10:
Drop selected columns and prepare cleaned data. 

📂 Project Structure
                 ┌──────────────────────┐
                 │   Start Project      │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Import Libraries     │
                 │ Pandas, NumPy,       │
                 │ Matplotlib, Seaborn  │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Load Wine Dataset    │
                 │ CSV File into DF     │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Data Inspection      │
                 │ head(), shape(),     │
                 │ info(), describe()   │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Data Cleaning        │
                 │ Null Check           │
                 │ Duplicate Check      │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Outlier Detection    │
                 │ Z-Score Method       │
                 │ IQR Method           │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Outlier Treatment    │
                 │ Capping Values       │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Data Transformation  │
                 │ Log Transformation   │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Data Visualization   │
                 │ Histogram, Boxplot   │
                 │ Scatter, Bubble etc. │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Feature Selection    │
                 │ Drop Columns         │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Final Clean Dataset  │
                 │ Ready for ML Model   │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │      End Project     │
                 └──────────────────────┘ 
🛠 Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Plotly
SciPy 

🎯 Final Outcome
This project helps learn:
Data cleaning
Outlier handling
Statistical analysis
Visualization techniques
Feature engineering
Preparing dataset for Machine Learning
