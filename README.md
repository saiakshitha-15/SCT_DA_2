#  Data Cleaning & Preparation | SkillCraft Technology Internship

## 📌 Task Overview
Cleaned and prepared the Titanic dataset using Python and Pandas in Google Colab.

## 🛠️ Tools Used
- Python (Pandas, NumPy)
- Google Colab
- Dataset: Titanic Dataset (Kaggle)

## ✅ What Was Done
- Loaded dataset (891 rows × 12 columns)
- Checked for missing values
- Filled missing Age with median value
- Filled missing Embarked with most common value
- Dropped Cabin column (too many missing values)
- Removed duplicate rows
- Converted data types (Survived, Pclass to string)
- Exported cleaned data to new CSV file

## 💡 Key Findings
- Age column had 177 missing values — filled with median
- Cabin column had 687 missing values — dropped
- No duplicate rows found
- Average Age: 29.7 years

## 📁 Files
| File | Description |
|------|-------------|
| `SCT_DA_2.ipynb` | Main Colab notebook with all code |
| `Titanic-Dataset.csv` | Original raw dataset |
| `cleaned_titanic.csv` | Final cleaned dataset |

## 🏢 Internship Details
**Organization:** SkillCraft Technology
**Track:** Data Analytics
**Task:** 02 — Data Cleaning & Preparation
