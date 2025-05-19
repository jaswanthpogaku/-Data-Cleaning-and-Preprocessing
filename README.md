# 🧹 Data-Cleaning-and-Preprocessing

This repository contains a Python-based pipeline for **automated data cleaning and preprocessing** of CSV files using **Google Colab**. It helps in cleaning real-world datasets to prepare them for data analysis or machine learning tasks.

---

## 🚀 Features

- 📤 Upload multiple CSV files manually in Google Colab
- 🔍 Detect and handle file encoding automatically
- 🧽 Clean column names (remove special characters, make lowercase, etc.)
- ❌ Remove duplicate rows
- ⚠️ Handle missing values (mode for categorical, median for numeric)
- 🔡 Standardize text (lowercase, stripped whitespace)
- 🗓️ Convert date columns to consistent `dd-mm-yyyy` format
- 🔢 Fix numeric data types (e.g., convert age columns to integers)
- 💾 Save cleaned files into a local directory and download them

---

## 🛠️ Requirements

- Python 3.x
- pandas
- chardet
- Google Colab environment

Install the required library:

```bash
!pip install chardet
