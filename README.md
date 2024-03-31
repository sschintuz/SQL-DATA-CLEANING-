This repository hosts a collection of SQL scripts designed to handle Nashville housing dataset cleaning, transformation, and analysis. The dataset includes property sales details such as addresses, sale dates, prices, etc. The scripts aim to:

1. Standardize Date Formats: Ensure consistency by converting various date formats to a uniform MySQL date format.
2. Fill Missing Data: Address missing property addresses by utilizing data from other records.
3. Split Addresses into Separate Columns: Break down full addresses into individual columns (e.g., PropertySplitAddress, PropertySplitCity) for easier analysis.
4. Update Data Values: Convert shorthand notations (e.g., 'Y' and 'N') in the SoldAsVacant field to 'Yes' and 'No' for clarity.
5. Remove Duplicate Entries: Identify and remove duplicate rows based on specific criteria to maintain dataset integrity.
6. Eliminate Unused Columns: Delete unnecessary columns to streamline the dataset.

The repository includes a queries.sql file containing all SQL queries necessary for these tasks.

To use the scripts:
1. Clone the repository.
2. Import your dataset into MySQL, assuming it's named NashvilleHousing.
3. Execute the SQL scripts provided in queries.sql in sequential order.

The queries.sql file provides detailed breakdowns of each task, from standardizing date formats to removing unused columns. Contributions and feedback are welcome under the open-source MIT License. Remember to back up your data and test scripts in a controlled environment before applying them to a production database.
