# Week 7 Assignment - Delta Lake MERGE Implementation

## Objective
The objective of this assignment is to understand the fundamentals of Delta Lake and implement the MERGE operation using PySpark in Databricks. The assignment also includes basic data cleaning and validation before performing incremental data updates.

---

## Dataset
- **Dataset:** Superstore Dataset
- **Format:** CSV

---

## Steps Performed

### 1. Load the CSV Dataset
- Loaded the Superstore CSV dataset into a PySpark DataFrame.
- Verified the schema and previewed the data.

### 2. Convert to Delta Table
- Converted the CSV dataset into a Delta table.
- Stored the data in Delta format for efficient processing.

### 3. Data Cleaning
- Renamed columns to ensure compatibility with Delta Lake.
- Removed duplicate records using `dropDuplicates()`.
- Handled missing values using appropriate methods.

### 4. Create Incremental Dataset
- Created a sample incremental dataset containing both existing and new records to simulate real-world updates.

### 5. Perform MERGE Operation
- Used the Delta Lake `MERGE` operation to:
  - Update existing records.
  - Insert new records that were not present in the target table.

### 6. Validation
- Verified the results of the MERGE operation.
- Displayed the updated Delta table.
- Validated the record count and checked for duplicate records using the unique identifier.

---

## Conclusion

This assignment demonstrates how Delta Lake enables efficient and reliable data management through ACID transactions and MERGE operations. By combining PySpark with Delta Lake, incremental updates can be handled effectively while maintaining data consistency and integrity.
