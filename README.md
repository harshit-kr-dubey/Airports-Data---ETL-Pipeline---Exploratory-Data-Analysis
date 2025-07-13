# 🛩️ Airports Data - ETL Pipeline & Exploratory Data Analysis

This project executes a complete **ETL (Extract, Transform, Load)** pipeline along with **exploratory data analysis (EDA)** on a global airports dataset. The data is extracted from a CSV, cleaned and transformed, loaded into a SQLite database, and analyzed with visualizations.

---

## 📆 Project Structure

```
📁 airports-data-project
│
├── airports.csv                  # Raw dataset
├── transformed_airports.csv      # Cleaned dataset
├── airports.db                   # SQLite database
├── airports_etl.py               # ETL and EDA pipeline script
├── airports_data_pipeline.ipynb  # Implementation in colab
├── README.md                     # Project documentation
```

---

## 🔧 Tech Stack & Libraries

| Tool/Library   | Purpose                            |
| -------------- | ---------------------------------- |
| **Python**     | Core programming language          |
| **pandas**     | Data manipulation & transformation |
| **numpy**      | Numerical operations               |
| **sqlite3**    | Database storage                   |
| **matplotlib** | Visualization                      |
| **seaborn**    | Statistical visualization          |
| **logging**    | Process tracking                   |

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/airports-data-project.git
cd airports-data-project
```

### 2. Place Dataset

Ensure the **airports.csv** file is present in the project folder.

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### 4. Run the ETL Pipeline & EDA

```bash
python airports_etl.py
```

---

## 🔍 Features

### ✅ Extract

* Reads the airports data from CSV.

### ✅ Transform

* Removes duplicates.
* Handles missing and invalid data.
* Converts data types.
* Standardizes text entries.
* Adds **Hemisphere** information.

### ✅ Load

* Saves processed data to CSV.
* Loads data into **SQLite database**.

### ✅ Exploratory Data Analysis (EDA)

* Distribution of **UTC Offset Hours**.
* **Global scatter plot** of airport locations.
* **Top countries by airport count**.
* **Correlation heatmap** of numeric variables.

---

## 📊 Visualizations

* Histogram of time zone offsets.
* World scatter plot of airport locations.
* Bar plot of top 10 countries by airport count.
* Correlation heatmap.

---

## 🚪 Future Enhancements

* Live airport data from APIs.
* Interactive dashboards using **Streamlit** or **Dash**.
* Machine learning predictions on airport traffic.

---

## 🙍 Contribution

Feel free to fork the repository and submit pull requests to:

* Improve data cleaning and transformation.
* Enhance visualizations.
* Add machine learning modules.

---

## 📄 License

Distributed under the **MIT License**.

---

