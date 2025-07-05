# 🎬 Movie Revenue Analysis with SQL & Python

This project explores the financial performance of top-grossing movies using **SQLite** and **Python (Pandas & Matplotlib)**. The analysis is based on the dataset `All Time Worldwide Box Office`, focusing on cleaning, querying, and visualizing box office revenue data.

---

## 📊 Objectives

- Clean and transform raw movie revenue data
- Analyze revenue trends by year and by region (domestic vs international)
- Categorize movies by revenue scale (e.g. Mega Blockbuster)
- Visualize insights using barplots and comparative charts

---

## 🗃 Dataset

**Source:** [All Time Worldwide Box Office.csv]  
**Columns include:**
- Movie name
- Release year
- Domestic box office revenue
- International box office revenue
- Worldwide box office revenue

---

## 🧼 Data Cleaning

Performed using **Pandas**:
- Removed currency symbols and commas
- Converted strings to numeric values
- Renamed columns for SQL compatibility
- Handled missing values using column mean

---

## 🧠 SQL Analysis Highlights

- **Top 10 Movies** by worldwide revenue
- **Revenue Category Classification** using `CASE`:
  - `> 1.5B`: Mega Blockbuster
  - `1B - 1.5B`: Blockbuster
  - `< 1B`: Hit / Average
- **Domestic vs Worldwide Ratio**
- **Revenue Averages per Year**

---

## 📈 Visualizations

- Barplot: Top 10 Movies by Worldwide Revenue
- Stacked Barplot: Domestic vs International Revenue
- Ratio Plot: Domestic/Worldwide Revenue by Movie

All charts are built using **Matplotlib** and included in the notebook.

---

## 🔍 Insights

- `Avatar` and `Avengers: Endgame` lead global revenue with over $2.7B
- Most high-revenue films have strong international earnings
- Average movie revenue peaked around the late 2000s
- Some movies had strong domestic support but underperformed globally

---

## 📈 Tools Used
- Python (Pandas, Matplotlib)
- SQLite (via `sqlite3`)
- Jupyter Notebook

---

## 💼 Author

**Salwa Zahra**  
Data Science Student & SQL Enthusiast

---

## 🔗 How to Use

1. Clone or download the repository
2. Open `SQL_Movie_Analysis_Final.ipynb` using Jupyter Notebook
3. Run the notebook to reproduce analysis and visuals

---

## 🌐 License

This project is licensed for educational and portfolio use.

---

## 📧 Contact
If you're hiring or want to collaborate, feel free to reach out via [https://www.linkedin.com/in/salwa-zahra-801303325?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app] or GitHub!
