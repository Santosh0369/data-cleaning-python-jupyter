```markdown
# Hospital Data Cleaning Project

This project involves cleaning and preprocessing a hospital dataset (`hospital_data_unclean.csv`) using Python and the Pandas library. The cleaned data is then saved to a new CSV file (`Hospital_data_cleaned.csv`).

## Dataset Overview
The original dataset `hospital_data_unclean.csv` contains various information related to hospital admissions, including patient demographics, medical conditions, billing, and admission details.

## Cleaning Steps Performed
The following data cleaning and preprocessing steps were applied to the dataset:

1.  **Load Data**:
    *   The `hospital_data_unclean.csv` file was loaded into a Pandas DataFrame.

2.  **Handle Missing Values**:
    *   **Name**: Null values in the 'Name' column were filled with 'unknown'.
    *   **Age**: Null values in the 'Age' column were filled with the mean age of the column.
    *   **Gender**: Null values in the 'Gender' column were filled with the mode (most frequent value) of the column.
    *   **Blood Type**: Null values in the 'Blood Type' column were filled with the mode of the column.
    *   **Medical Condition**: Null values in the 'Medical Condition' column were filled with 'unknown'.
    *   **Doctor**: Null values in the 'Doctor' column were filled with 'unknown'.
    *   **Hospital**: Null values in the 'Hospital' column were filled with 'unknown'.
    *   **Insurance Provider**: Null values in the 'Insurance Provider' column were filled with 'unknown'.
    *   **Room Number**: Null values in the 'Room Number' column were filled with 'not assigned'.
    *   **Admission Type**: Null values in the 'Admission Type' column were filled with 'unknown'.
    *   **Medication**: Null values in the 'Medication' column were filled with 'unknown'.
    *   **Test Results**: Null values in the 'Test Results' column were filled with 'unknown'.

3.  **Standardize Data Formats**:
    *   **Name**: Converted all names to title case (e.g., "john doe" -> "John Doe").
    *   **Gender**: Replaced 
