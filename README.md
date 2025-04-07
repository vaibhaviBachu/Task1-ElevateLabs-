# Task1-ElevateLabs-

 Data Cleaning and Preparation Pipeline for Sales Dataset

 This dataset contains detailed records of customer orders from a retail store, including order dates, shipping details, customer info, product categories, and sales amounts. It helps analyze purchasing behavior, regional trends, and product performance.
 

The dataset represents historical retail transactions, capturing essential details like order IDs, shipping modes, customer demographics, product categories, and sales amounts. The primary goal of this data cleaning task was to prepare the raw dataset for analysis and modeling by ensuring its accuracy, consistency, and structure. The process began by loading the dataset and inspecting its shape, column types, and missing values. Columns with missing data, such as postal_code, were imputed using the mode, while rows with duplicate entries were identified and removed to maintain data integrity. Text-based fields had whitespace replaced with underscores for consistency, and column names were standardized to lowercase with underscores.

Next, date fields like order_date and ship_date were converted to datetime format, and categorical fields were explicitly cast to the category data type to optimize memory and performance. Outliers in numerical columns, particularly sales, were detected using the IQR method and removed to minimize distortion in analysis. One-hot encoding was then applied to transform categorical variables into numeric form for compatibility with machine learning algorithms. Subsequently, numerical columns were scaled using StandardScaler to ensure uniformity across features.







