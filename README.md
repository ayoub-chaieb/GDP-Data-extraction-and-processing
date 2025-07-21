# 🌍 GDP Data Extraction & Processing – Practice Project

## ✅ Project Summary

This notebook project successfully implements a full data pipeline to **extract, process, and save economic data** using Python. The project focuses on identifying the **Top 10 largest economies by GDP (nominal)** from a Wikipedia page, using **web scraping**, **pandas**, and **NumPy**.

The work was carried out under a scenario where an international firm needs to analyze GDP data to guide expansion decisions. The resulting dataset is cleaned, structured, and saved in a CSV format for downstream analysis or reporting.

---

## 📌 Achievements

* ✅ Extracted HTML tables from a live (archived) Wikipedia page using `pandas.read_html()`
* ✅ Isolated and cleaned GDP-related data for all listed countries
* ✅ Parsed, converted, and formatted GDP values to proper numeric format (Billion USD)
* ✅ Ranked countries by GDP and selected the top 10
* ✅ Stored the cleaned dataset in a structured **CSV** file
* ✅ Used `NumPy` to enhance numerical operations and formatting

---

## 📦 Technologies Used

* 🐍 **Python 3.x**
* 📊 **pandas**
* ➗ **NumPy**
* 🌐 **lxml** for HTML parsing

---

## 🗂 Output Preview

```plaintext
| Rank | Country      | GDP (Billion USD) |
|------|--------------|-------------------|
| 1    | United States| 26,854.60         |
| 2    | China        | 17,963.18         |
| ...  | ...          | ...               |
| 10   | Italy        | 2,186.45          |
```

---

## 🧠 Learning Outcomes

This notebook demonstrates practical skills in:

* 🌐 Web scraping using `pandas` (without needing BeautifulSoup or requests)
* 🧼 Data wrangling (cleaning, renaming, type conversion)
* 🧮 Performing calculations and formatting with `NumPy`
* 📤 Saving clean datasets to disk (`CSV`)

---

## 📁 Files Produced

* `top_10_gdp_countries.csv` – Final cleaned dataset of the largest economies by nominal GDP
* `practice_project.ipynb` – Jupyter notebook containing the full workflow

---

## 📍 Data Source

Extracted from the archived Wikipedia page:
📄 [List of countries by GDP (nominal)](https://web.archive.org/web/20230902185326/https://en.wikipedia.org/wiki/List_of_countries_by_GDP_%28nominal%29)

---

## 👨‍💻 Author

Developed by **Ayoub CHAIEB**
