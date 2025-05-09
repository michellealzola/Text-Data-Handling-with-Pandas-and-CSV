
# 📈 Mastering Text Data Handling with Pandas and CSV  
## A Practical Problem Set Using Sensor Logs

This repository and blog post showcase a hands-on problem set designed to help you **master text data handling with Python's pandas**. The exercises are built around a simulated sensor log dataset — ideal for those working in **manufacturing**, **SCADA systems**, or **IoT analytics**.

---

## 🧠 Blog Summary: What You'll Learn

This blog walks you through **realistic data-cleaning challenges** involving:

- Parsing messy CSV files
- Extracting and transforming string-based values
- Handling missing or malformed entries
- Grouping and summarizing by categories
- Using `pandas.crosstab()` for pivot-style summaries
- Replacing and standardizing status labels
- Computing rolling statistics

These are **essential skills** for preprocessing and analyzing operational data from machines and sensors.

---

## 📊 Sample Challenges

Some key tasks explored in the notebook:

- ✅ Create a `StatusFlag` column (1 for OK, 0 for others)
- 🔁 Replace `'Critical'` ➝ `'CR'`, `'Warning'` ➝ `'WRN'`
- 📌 Count rows per status using `groupby`
- 📉 Compute rolling averages for selected values
- 🧹 Drop rows with non-numeric or malformed entries
- 🧮 Use `pd.crosstab()` to summarize sensor statuses by location

---

## 📂 What's in This Repo

- `pandas_text_data_handling_exercises.ipynb`  
  📒 A Jupyter Notebook with guided exercises and detailed solutions.

- `sensor_data_pipe.txt`  
  📄 Simulated sensor log file with timestamps, numeric values, text statuses, and location codes.

---

## 🚀 How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/text-data-handling-pandas.git
   cd text-data-handling-pandas
   ```

2. **Install dependencies:**

   ```bash
   pip install pandas jupyter
   ```

3. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook pandas_text_data_handling_exercises.ipynb
   ```

4. **Follow the exercises**, examine solutions, and experiment with your own code!

---

## 🧰 Skills You’ll Build

- CSV Parsing with `read_csv()`
- Token-based string extraction
- Data cleaning and transformation
- Grouping and aggregation
- Conditional column creation
- Working with mixed data types
- Status code mapping and flagging
- Time series rolling window operations

---

## 💼 Use Case Examples

This project is especially useful for:

- Manufacturing system log monitoring
- Predictive maintenance data preparation
- Cleaning IoT device data
- SCADA sensor signal preprocessing
- QA and operations analytics

---

## 📜 License

MIT License — use, share, and modify freely.

---

## 🔖 Tags

pandas, python, text data processing, sensor logs, csv parsing, data cleaning, data preprocessing, data transformation, python pandas tutorial, data science, manufacturing data, iot data analysis, machine data, scada systems, practical pandas problems

---

## 🔗 Further Reading

- [Pandas Official Documentation](https://pandas.pydata.org/)
- [Python for Data Analysis by Wes McKinney](https://wesmckinney.com/book/)
- [SCADA System Overview on Wikipedia](https://en.wikipedia.org/wiki/SCADA)

