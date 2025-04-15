
# 🔍 File Comparison Tool

A Python script to compare two datasets (CSV or Excel) and identify:
- Rows present in both files
- Rows unique to the current file
- Rows unique to the previous file

It uses user-specified columns as comparison keys, supports `.csv`, `.xls`, and `.xlsx` formats, and outputs a detailed summary in a readable text file.

---

## 📦 Features

- ✅ Supports both CSV and Excel formats
- 🔑 Compares using specific key columns
- ✨ Cleans and normalizes data before comparison
- 📊 Detects changes row-by-row using hashing
- 📝 Saves results to a formatted `.txt` file
- 📁 Automatically creates output folder if missing

---

## 📁 Example Output

- Summary of common and differing rows
- Detailed view of unmatched rows
- Easy-to-read text format for documentation or audit purposes

---

## 🧪 Requirements

- Python 3.6+
- pandas

Install dependencies (if needed):

```bash
pip install pandas
