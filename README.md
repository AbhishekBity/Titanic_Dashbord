[README.md](https://github.com/user-attachments/files/21570085/README.md)
# 🚢 Titanic Excel Dashboard & Analysis

This project presents a **data analysis and dashboard visualization** of the Titanic dataset using **Microsoft Excel**. It includes detailed KPI metrics, data cleaning steps, business question insights, and interactive elements such as charts and filters for better storytelling.

---

## 📊 Project Overview

The Titanic dataset provides detailed records of passengers aboard the RMS Titanic, including demographics, ticket information, class, fare, and survival status.  
The goal of this project is to **clean, explore, and visualize** the data in Excel to answer meaningful business questions.

---

## 🛠️ Tools Used

- **Microsoft Excel**
  - Pivot Tables
  - Charts (Bar, Column, Pie)
  - Slicers
  - Dashboard sheets
  - Excel Formulas (`TRIM`, `SUBSTITUTE`, `IF`, etc.)

---

## ❓ Business Questions Answered

1. What is the overall survival rate of passengers?
2. What is the average age of passengers?
3. What is the gender-wise distribution and survival rate?
4. Which class had the highest survival rate?
5. What is the distribution of fares paid?
6. Does the embarkation point impact survival rate?

---

## 📈 KPIs & Metrics

- **Total Passengers**
- **Survival Rate**
- **Average Fare**
- **Average Age**
- **Fare Range Distribution**
- **Class-wise & Gender-wise Survival Rates**
- **Family Size Calculation:** `FamilySize = SibSp + Parch`

---

## 🧼 Data Cleaning Performed

- Removed unnecessary columns (`Name`, `Cabin`)
- Trimmed the `Fare` column using the `=TRIM()` function
- Converted binary values in `Survived` to `Yes/No` using `SUBSTITUTE()`
- Replaced embarkation codes (`C`, `S`, `Q`) with full names (`Cherbourg`, `Southampton`, `Queenstown`)
- Categorized `Age` into: `Child`, `Teen`, `Adult`, and `Senior Citizen`

---

## 📂 Project Structure

| Sheet Name         | Purpose                                       |
|--------------------|-----------------------------------------------|
| `Titanic.csv`      | Cleaned dataset with added columns            |
| `KPIs1`            | Key Performance Indicators                    |
| `by fare`, `by class` | Pivot charts and category breakdowns       |
| `Dashboard`        | Main dashboard with slicers and visuals       |
| `Summary`          | Insights and key takeaways                    |

---

## 📌 Key Insights

- **Survival Rate:** _X%_ (Update this with your calculated value)
- **Majority Class:** Most passengers belonged to **3rd class**
- **Gender Insight:** **Women had a higher survival rate** than men
- **Embarkation:** Most passengers boarded from **Southampton**
- **High Fare ≠ Survival:** High fare didn't always guarantee survival

---

## 📷 Screenshots

_Add screenshots or GIFs of your Excel dashboard and charts here for better visual impact._

---

## 🤝 Contribution

This is a beginner-friendly Excel dashboard project.  
Feel free to **fork, modify**, or **replicate** this project using **Google Sheets**, **Power BI**, or **Python** to practice data analysis and visualization.

---

## 📜 License

This project is open-source and available under the **MIT License**.
