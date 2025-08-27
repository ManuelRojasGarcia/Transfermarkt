# 📊 Transfermarkt Data Mining  

Welcome to the **Transfermarkt Data Mining Project** ⚽📈  
This repository contains data analysis and visualization of football players’ statistics, inspired by the Transfermarkt database.  

## 📂 Project Structure  
- **`data/`** – Raw and processed datasets used in the analysis.  
- **`docs/`** – Documentation, reports, images, and supporting materials.  

## 🔍 Overview  
The project applies **data mining techniques** to player performance indicators, such as:  
- Goals ⚽  
- Assists 🎯  
- Minutes played ⏱️  
- Cards 🟨🟥  

Through preprocessing, visualization, and modeling in **R**, we aim to uncover insights about player value and performance trends.  

## 🛠️ Tools & Technologies  
- **R** (tidyverse, ggplot2, caret, etc.)  
- **RMarkdown** / **RPubs** for reporting  
- **Data visualization** and **predictive modeling**  

---

## 📷 Visualizations  

Below are some key results and visualizations from the project:  

---

### 1. Relation between Performance Score and Market Value  
This scatterplot shows the relationship between a player's **Performance Score** (goals + assists) and their **market value** in euros.  
Even though there is a positive trend, the dispersion indicates that market value depends on many other factors beyond goals and assists.  

![Relation between Performance Score and Market Value](docs/img/1.png)  

---

### 2. Player Clustering with CLARA (5 clusters)  
Using **CLARA clustering** with Manhattan distance, players were grouped into 5 distinct clusters.  
This analysis helps identify different **profiles of players** based on their performance indicators.  

![Player Clustering with CLARA](docs/img/2.png)  

---

### 3. Goals Distribution by Position  
This bar chart highlights how different positions contribute to scoring.  
As expected, **centre-forwards** dominate goal scoring, followed by wingers and attacking midfielders.  

![Goals Distribution by Position](docs/img/3.png)  

---

### 4. Goals Scored by Team  
This visualization compares total goals scored by clubs.  
Top European clubs such as **Barcelona, Bayern Munich, and Real Madrid** lead the ranking, reflecting their attacking dominance.  

![Goals Scored by Team](docs/img/4.png)  

---

## 📑 Documentation  
📄 Detailed reports and notebooks are available in the **`docs/`** folder.  

## 🚀 Future Work  
- Expand analysis to more seasons and leagues 🌍  
- Incorporate advanced machine learning models 🤖  
- Enhance visualization with interactive dashboards 📊  

