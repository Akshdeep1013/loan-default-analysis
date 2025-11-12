# Loan Default Analysis

Multi-file data processing with Pandas - Joins, DateTime, and String operations

## 📊 Project Overview
Analysis of loan default risk using customer and loan data from multiple CSV files. Implements data joining, temporal analysis, and string cleaning operations.

## 🎯 Features Implemented

### Multi-File Joins
- Read multiple CSV files (customers.csv, loans.csv)
- Join customer + loan data on customer_id
- Inner, left, and right joins
- Handle missing values

### DateTime Operations
- Convert string dates to datetime
- Extract date components (year, month, day)
- Filter data by date ranges
- Calculate date differences
- Find recent loans (last 6 months)

### String Operations
- Clean city names: `.str.upper()`
- Remove whitespace: `.str.strip()`
- Pattern matching: `.str.contains()`
- Split full names
- Replace values: 'Bombay' → 'Mumbai'

### DTI Calculation
- DTI ratio = (loan_emi / monthly_income) * 100
- Identify high-risk customers (DTI > 40%)
- Group by credit score ranges

## 🛠️ Technologies
- Python 3.x
- Pandas
- NumPy

## 📈 Key Concepts
✅ Multi-file joining (merge operations)  
✅ DateTime handling (.dt accessor)  
✅ String manipulation (.str accessor)  
✅ Missing data handling  
✅ Feature calculation (DTI ratio)  

## 📂 Dataset
- customers.csv: 2000 records
- loans.csv: 2000 records
