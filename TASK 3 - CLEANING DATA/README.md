# OASIS INFOBYTE INTERNSHIP

## TASK 3: CLEANING DATA

### Objective

Demonstrate professional data cleaning skills by transforming a messy dataset into a clean and analysis-ready dataset.

### Tech Stack

* Python
* Pandas
* NumPy
* Jupyter Notebook

### Data Cleaning Steps

* Created a data quality report.
* Identified and handled missing values.
* Identified and removed duplicate rows.
* Standardised inconsistent formatting.
* Corrected data types.
* Detected numerical outliers using the IQR method.
* Created a before vs. after data quality summary.
* Saved the cleaned dataset as a new CSV file.

### Dataset

Titanic dataset containing passenger information such as passenger ID, survival status, passenger class, name, sex, age, ticket, fare, cabin, and embarkation details.

### Missing Data Handling

* Age → Median imputation
* Embarked → Mode imputation
* Cabin → Replaced missing values with "Unknown"

### Outlier Handling

Outliers in numerical columns were detected using the IQR method. The detected outliers were retained because they may represent genuine passenger records.

### Output

The final cleaned dataset was saved as:

`cleaned_titanic.csv`

### Conclusion

The dataset was successfully cleaned and transformed into an analysis-ready format. The project demonstrates practical data cleaning techniques using Python and Pandas.

### Internship

**OASIS INFOBYTE – Data Analytics Internship**
