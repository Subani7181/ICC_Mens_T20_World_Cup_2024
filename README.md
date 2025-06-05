# 🏏 T20 World Cup 2024 Analytics Dashboard

## 📌 Overview
This project presents a comprehensive data analysis of the **ICC T20 World Cup 2024**, focusing on both **batting and bowling performances**. Using Power BI and structured datasets, the project uncovers key insights, highlights top players, and visualizes tournament trends in an interactive and informative dashboard.

---

## 🎯 Objective
- Analyze and visualize batting and bowling statistics from the T20 World Cup 2024.
- Identify top-performing players, teams, and country-wise trends.
- Build an interactive Power BI dashboard to aid analysts, fans, and strategists.

---

## 📊 Dataset
The project uses two curated datasets:

- `T20_WC_2024_Batting.csv`: Player-wise batting data including runs, strike rate, 4s, 6s, average, etc.
- `T20_WC_2024_Bowling.csv`: Bowling performance data including overs bowled, wickets taken, economy rate, strike rate, etc.

> 📌 These datasets are based on live tournament data and were extracted via **web scraping using Python**.

---

## 🔍 Methodology

1. **Data Collection**:
   - Used **Python** and libraries like `requests`, `BeautifulSoup`, and `pandas` to scrape data from official cricket statistics websites.
   - Extracted structured tables and exported them into CSV files.

2. **Data Cleaning**:
   - Removed null and duplicate records.
   - Standardized team and player names.
   - Converted data types for numerical analysis (e.g., float, integer).
   - Removed unwanted data.

3. **Data Transformation**:
   - Added derived metrics such as:
     - Full country names
     - Dismissal type in key innings (e.g., out or not out)
   - Created rankings and classifications (e.g., Top 10 Batsmen/Bowlers).

4. **Data Visualization**:
   - Imported cleaned datasets into **Power BI**.
   - Designed interactive dashboards with slicers, KPIs, charts, and drill-through features.
   - Enabled filtering by **player**, **team**, **country**, **match**, and **performance type**.

---

## 🧰 Requirements

- **Power BI Desktop** (to open `.pbix` file)
- **Jupyter Notebook** (for scraping and preprocessing):
  - `Python`
  - `pandas`
  - `beautifulsoup4`
  - `requests`

---

## 📁 Files in This Repository

| File Name                  | Description                                |
|---------------------------|--------------------------------------------|
| `T20_WC_2024_Batting.csv` | Raw batting dataset for T20 WC 2024        |
| `T20_WC_2024_Bowling.csv` | Raw bowling dataset for T20 WC 2024        |
| `T20.pbix`                | Power BI report file with all dashboards   |

---

## 📈 Results

**Key Findings:**
- 🏏 **Top Batsmen**: Identified using total runs, strike rate, and average.
- 🎯 **Top Bowlers**: Based on economy rate, wickets, and strike rate.
- 🧢 **Team Insights**: Highlighted most balanced teams by all-round performance.
- 🌍 **Country-Level Analysis**: Compared batting and bowling strength across participating nations.
- 🔍 **Impact Metrics**: Showed clutch players in high-pressure games.


---

## 📊 Visualizations

The Power BI dashboard consists of **two main views**: **Batting Dashboard** and **Bowling Dashboard**, each packed with interactive and insightful visual elements.

---

### 🏏 **Batting Dashboard Highlights** :

- **🎯 Cards**:  
  - Total Matches  
  - Hundreds  
  - Total Runs  
  - Batting Average  
  - Strike Rate  
  - Fours and Sixes  
  - Balls Faced  
  - Innings  
  - Country Selector (for filtering by nation)

- **📋 Matrix**:  
  - Sixes & Fours by Player and Country

- **🌍 Treemap**:  
  - Total Runs distributed by Country

- **📈 Scatter Plot**:  
  - Strike Rate vs. Average by Country

- **📊 Bar Charts**:
  - ✔️ Top 10 Run Scorers  
  - ✔️ Highest Balls Faced  
  - ✔️ Most Zeroes  
  - ✔️ Highest Individual Scores  
  - ✔️ Most Fifties  

---

### 🎯 **Bowling Dashboard Highlights** :

- **🎯 Cards**:  
  - Total Wickets  
  - Economy Rate  
  - Bowling Average  
  - 4-Wicket and 5-Wicket Hauls  
  - Strike Rate  
  - Balls Bowled  
  - Innings  
  - Matches  
  - Country Selector

- **📋 Matrix**:  
  - 4W & 5W Hauls by Player and Country

- **🌍 Treemap**:  
  - Total Wickets distributed by Country

- **📈 Scatter Plot**:  
  - Economy Rate vs. Strike Rate by Country

- **📊 Bar Charts**:
  - ✔️ Top 10 Wicket Takers  
  - ✔️ Most Runs Conceded  
  - ✔️ Most Balls Bowled  
  - ✔️ Most 4-Wicket Hauls  
  - ✔️ Overs & Maidens  

---

## ✅ Conclusion

This dashboard-driven project provides a data-rich and user-friendly view of the ICC T20 World Cup 2024. It serves as a dynamic analytical tool for exploring player performances, team strategies, and game dynamics through interactive visual storytelling. The insights can aid cricket analysts, sports strategists, journalists, and enthusiastic fans alike.

---

## 🙌 Contributions

Feel free to fork, improve, or raise issues if you’d like to extend this analysis or integrate new data. Contributions are welcome!

---

## 📬 Contact

For queries or collaborations:

**Syed Mahabub Jani**  
📧 [syedmahaboobjani772@gmail.com](mailto:syedmahaboobjani772@gmail.com)
