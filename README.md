### Summary

1. **Loading the Data**:
   - The dataset is loaded using `pandas` from a CSV file.

2. **Checking for Missing Values**:
   - The initial count of missing values in each column is displayed.

3. **Imputing Missing Values**:
   - Missing values in the 'Age' column are filled using the mean value.
   - Rows with missing values in the 'Embarked' column are dropped.
   - Missing values in the 'Cabin' column are filled with 'Unknown'.
   - Missing values in the 'Fare' column are filled with the median value.
   - Missing values in the 'Boat' column are filled with 'Unknown'.
   - The 'Body' column is converted to string type, and missing values are filled with 'Not Recovered'.
   - Missing values in the 'Home.dest' column are filled with 'Unknown'.

4. **Verifying Changes**:
   - The final count of missing values in each column is displayed to ensure all missing values have been handled.

5. **Visualization (Optional)**:
   - Various plots are created using `seaborn` to visualize the distribution of passengers by class, gender, and age, as well as the survival rates by class and gender.

This code helps clean the Titanic dataset by handling missing values and provides visual insights into the data.
