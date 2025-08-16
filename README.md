# 🏏 Cricket World Cup EDA (1975–2019)

## 📌 Overview  
This project performs an **Exploratory Data Analysis (EDA)** on historical Cricket World Cup match results (1975–2019). The goal is to uncover **trends, team performance patterns, and key factors influencing match outcomes**.  

The analysis can serve as a resource for:  
- 📊 **Sports analysts** seeking data-driven insights  
- 🎙️ **Broadcasters & commentators** looking for historical references  
- 🔮 **Researchers & enthusiasts** aiming to build predictive models  

---

## 📂 Dataset  
- **Source:** [Kaggle – All Cricket World Cup Match Results](https://www.kaggle.com/datasets/sidmalang/all-cricket-world-cup-match-result)  
- **Coverage:** Matches from **1975 to 2019**  
- **Contents:** Historical match data, including teams, results, dates, and venues  

---

## ⚙️ Methodology  

### 🔹 Data Preprocessing  
- Imported essential libraries: **pandas, numpy, matplotlib, seaborn**  
- Loaded individual CSV files for each World Cup year  
- Concatenated into a single comprehensive **DataFrame**  
- Standardized column names for consistency  
- Converted **Date** column into datetime format for **time-series analysis**  

### 🔹 Exploratory Data Analysis (EDA)  
- Calculated **total number of matches** played across all World Cups  
- Implemented a **custom function** to extract the winning team from the `Result` column  
- Tallied **win counts** to determine the most successful teams  
- Analyzed **win percentages** and historical dominance trends  

---

## 📊 Key Insights (Highlights)  
- 📌 Total matches analyzed: **1975–2019** tournaments  
- 📌 Identified the **most successful teams** in World Cup history  
- 📌 Win percentages highlight dominance trends across different eras  
- 📌 Foundation set for **future predictive modeling** (e.g., win probability, performance forecasting)  

---

## 🛠️ Requirements  
To run the notebook, install the following dependencies:  

```bash
pip install pandas numpy matplotlib seaborn
```
---

## ▶️ Usage  
1. Clone this repository:  
   
   ```bash
   git clone https://github.com/AbdulMoizZuberi/EDA-on-Cricket-World-Cup-
   cd cricket-worldcup-eda
   ```

2. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

3. Run the cells.

---

## 📌 Future Work

🏆 Player-level performance analysis (batsmen & bowlers)

🌍 Venue-based performance trends

🔮 Machine learning models for match outcome prediction

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome! Please open an issue or submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.
