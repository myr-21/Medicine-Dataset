# Medicine Dataset

A merged and cleaned dataset containing **552,101 unique medicine names** compiled from **11 publicly available datasets**. This dataset is designed primarily for **medicine autocomplete**, **search indexing**, **healthcare applications**, **pharmacy billing systems**, and **NLP/AI projects**.

---

## 📊 Dataset Statistics

| Metric | Value |
|--------|------:|
| Source Datasets | 11 |
| Original Records | 577,377 |
| Final Unique Medicine Names | 552,101 |
| Duplicate Records Removed | 25,276 |

---

## ✨ Features

- Merged data from 11 public medicine datasets
- Automatic medicine name column detection
- Data cleaning and normalization
- Duplicate removal
- Alphabetically sorted dataset
- Unique sequential IDs assigned to every medicine
- Ready for autocomplete systems and database import

---

## 🛠 Data Processing Pipeline

```
Raw CSV Files
      │
      ▼
Column Detection
      │
      ▼
Merge Datasets
      │
      ▼
Data Cleaning
      │
      ▼
Normalization
      │
      ▼
Duplicate Removal
      │
      ▼
Sorting
      │
      ▼
ID Generation
      │
      ▼
Medicine_Autocomplete.csv
```

---

## 🧹 Cleaning Performed

- Removed empty medicine names
- Trimmed leading and trailing whitespace
- Removed hidden newline and tab characters
- Standardized spacing
- Normalized medicine names for duplicate detection
- Removed duplicate entries
- Sorted medicine names alphabetically
- Assigned sequential IDs

---

## 📦 Output

The final dataset contains the following columns:

| Column | Description |
|---------|-------------|
| id | Unique sequential identifier |
| Medicine Name | Cleaned medicine name |

Example:

| id | Medicine Name |
|---:|---------------|
| 1 | A to Z Gold Capsule |
| 2 | Abamlo 5 Tablet |
| 3 | Abciximab Injection |

---

## 💡 Use Cases

- Medicine autocomplete
- Pharmacy billing software
- Electronic Health Records (EHR)
- Healthcare search engines
- NLP and AI applications
- Drug name lookup
- Educational and research projects

---

## ⚠️ Disclaimer

This dataset contains **medicine names only**. It does **not** include dosage information, pricing, manufacturer details, medical advice, or prescribing information. It is intended for educational, research, and software development purposes.

---

## 🚀 Future Improvements

- Generic medicine mapping
- Manufacturer information
- Dosage normalization
- Drug classification
- ATC code mapping
- API support
- Periodic dataset updates
