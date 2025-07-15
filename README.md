# Excel Data Analysis Project: Billionaires Dataset 💰📊

This project demonstrates a complete Excel-based data workflow including cleaning, analysis, and visualization using a dataset of billionaire profiles.

## 🔧 Project Workflow

### 1️⃣ Data Cleaning
- Removed 6 duplicate rows.
- Standardized gender: Replaced `M` with `Male`, `F` with `Female`.
- Created new columns:
  - Birth Date → `=DATE(birthYear, birthMonth, birthDay)`
  - Current Date → `=TODAY()`
  - Age → `=YEARFRAC(Birth Date, Current Date)`
- Cleaned GDP values by removing `$` and `,` using Excel replace.

### 2️⃣ Descriptive Statistics
Used Excel’s **Data Analysis Toolpak** to analyze:
- `finalWorth`, `birthYear`, `Age`, `gdp_country`, `life_expectancy_country`, etc.

### 3️⃣ Pivot Table Analysis
- Top 10 richest individuals by `finalWorth`.
- Age group frequency analysis.
- Used slicers to filter Gender, Category, and Self-Made status.

### 4️⃣ Visualizations
- 📊 Column Chart: Top 10 Richest
- 📉 Bar Chart: Billionaires by Age
- 🧩 Slicers for interactivity

## 🎥 Demo Video
Check out the full walkthrough of this project on LinkedIn (link below)!

## 📎 Key Skills
Excel • Data Cleaning • Pivot Tables • Descriptive Statistics • Data Visualization

## 📌 Author
**Devaki Gopi Krishna Kurakula**

- 📫 Email: kurakuladeva1@gmail.com
- 🔗 LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/devaki-gopi-krishna-kurakula-8bb2482b7/)
