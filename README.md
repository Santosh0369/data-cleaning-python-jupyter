# 🏥 Hospital Data Cleaning Project

## 📌 Project Overview
This project focuses on cleaning and preprocessing a hospital dataset (`hospital_data_unclean.csv`) using **Python** and the **Pandas** library.  

The goal is to transform raw, inconsistent data into a clean and structured dataset (`hospital_data_cleaned.csv`) suitable for analysis and reporting.

---

## 📂 Dataset Overview
The dataset contains hospital-related information such as:

- Patient demographics (Name, Age, Gender)
- Medical details (Blood Type, Medical Condition, Medication)
- Admission details (Admission Type, Room Number)
- Operational data (Doctor, Hospital, Insurance Provider, Test Results)

---

## 🧹 Data Cleaning Steps

### 1. Load Data
- Imported the dataset into a Pandas DataFrame for processing.

---

### 2. Handle Missing Values
Missing values were treated using appropriate strategies:

- **Name** → filled with `'Unknown'`
- **Age** → filled with **mean age**
- **Gender** → filled with **mode**
- **Blood Type** → filled with **mode**
- **Medical Condition** → filled with `'Unknown'`
- **Doctor** → filled with `'Unknown'`
- **Hospital** → filled with `'Unknown'`
- **Insurance Provider** → filled with `'Unknown'`
- **Room Number** → filled with `'Not Assigned'`
- **Admission Type** → filled with `'Unknown'`
- **Medication** → filled with `'Unknown'`
- **Test Results** → filled with `'Unknown'`

---

### 3. Standardize Data Formats
Data was standardized for consistency:

- **Name** → converted to **Title Case** (e.g., `john doe → John Doe`)
- **Gender** → standardized values (e.g., `male, Male → Male`)
- **Text Columns** → cleaned extra spaces and inconsistent formatting

---

### 4. Data Quality Improvements
- Removed duplicate records (if any)
- Fixed inconsistent entries
- Ensured proper data types for each column

---

### 5. Export Cleaned Data
- Saved the cleaned dataset as:
