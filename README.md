# 📊 Growth Mindset Challenge: Data Sweeper Web App

A powerful, user-friendly Python-based web application designed to clean, transform, and analyze data sheets. Built as part of the GIAIC Growth Mindset Challenge, this tool allows users to upload raw CSV or Excel files, perform essential data scrubbing operations, and instantly export the optimized data.

---

## 🎯 Project Vision & Context

This application was developed to solve the daily operational friction of dealing with messy, unformatted datasets. Adhering to the "Growth Mindset" philosophy, the project focuses on programmatic problem-solving—turning raw, error-prone data sheets into clean, structured informational assets through an intuitive graphical user interface.

### 🛠️ Tech Stack & Libraries
* **Core Language:** Python 3.x
* **Web UI Framework:** Streamlit (For rapid dashboard and tool prototyping)
* **Data Manipulation Engine:** Pandas (High-performance data structures and analytical tools)
* **File Handling:** OpenPyXL / Whirlwind dependencies (For flawless Excel `.xlsx` processing)

---

## ✨ Core Functional Features

* **📥 Multi-Format File Support:** Seamlessly accept and process both Comma-Separated Values (`.csv`) and Microsoft Excel (`.xlsx`) data uploads.
* **🧹 Smart Data Cleaning (Data Sweeping):**
  * **Deduplication:** Scan the uploaded dataset and remove duplicate rows instantly with a single click.
  * **Missing Value Imputation:** Detect empty data blocks or null parameters and fill them with smart averages (mean values) or default structural tokens to preserve row data.
* **🔄 Dynamic Column Prototyping:** Inspect the uploaded data grid header rows and choose explicitly which column arrays to keep, drop, or re-order.
* **📈 Immediate Data Visualizations:** Automatically maps numeric trends into interactive charts and line vectors to analyze values on the fly.
* **📤 Universal Format Conversion:** Download your cleaned, processed dataset back to your desktop in either `.csv` or `.xlsx` formats dynamically, regardless of what the original input format was.
