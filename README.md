# 🏏 IPL Batting Performance Dashboard

## 📋 Overview
This Power BI dashboard visualizes batting performance across IPL teams and seasons. It provides interactive insights into total runs, matches played, and team-wise contributions, helping users analyze trends and compare team performance effectively.

---

## 📊 Dashboard Components

### 1. **Total Batsman Runs by Team**
- **Type:** Horizontal Bar Chart  
- **Purpose:** Displays total runs scored by each team’s batsmen.  
- **Insight:** Quickly identifies top-performing teams in batting.

### 2. **Total Runs (KPI Card)**
- **Type:** KPI Card  
- **Metric:** Sum of all runs scored (e.g., 194K).  
- **Purpose:** Provides a high-level summary of total batting output.

### 3. **Runs Distribution by Team**
- **Type:** Pie Chart  
- **Purpose:** Shows percentage contribution of each team to total runs.  
- **Insight:** Highlights balance or dominance among teams.

### 4. **Matches Played by Team**
- **Type:** Column Chart  
- **Purpose:** Compares the number of matches played by each team.  
- **Insight:** Correlates match count with batting performance.

### 5. **Season Filter**
- **Type:** Slicer  
- **Values:** 2008–2017  
- **Purpose:** Enables filtering visuals by IPL season.

---

## ⚙️ Data Model
- **Tables Used:** `matches`, `deliveries`, `teams`
- **Key Fields:**
  - `batting_team`
  - `total_runs`
  - `match_id`
  - `season`
- **Relationships:**  
  - `matches[match_id]` ↔ `deliveries[match_id]`  
  - `teams[team_name]` ↔ `deliveries[batting_team]`

---

## 🎨 Design Guidelines
- **Title:** Centered at top — “IPL Batting Performance Dashboard”  
- **Color Theme:** IPL team colors or consistent blue/orange palette  
- **Layout:**
  - Top row: Bar chart, KPI card, Pie chart  
  - Bottom row: Column chart  
  - Right sidebar: Season slicer  
- **Spacing:** Maintain 20–30 px padding between visuals  
- **Font Hierarchy:** Dashboard title > Chart titles > Axis labels

---

## 🚀 How to Use
1. Open the `.pbix` file in Power BI Desktop.  
2. Load IPL dataset (matches & deliveries).  
3. Refresh visuals to populate data.  
4. Use slicers to filter by season or team.  
5. Hover over charts for detailed tooltips.

---

## 🧠 Insights
- Mumbai Indians and Royal Challengers Bangalore lead in total runs.  
- Balanced run distribution across top teams.  
- Strong correlation between matches played and total runs scored.

---

## 🛠 Future Enhancements
- Add **Runs Trend by Season** (Line Chart).  
- Include **Total Teams** KPI card.  
- Integrate **Player-level analysis** for deeper insights.  
- Apply **dynamic color themes** based on selected season.

---

## 📅 Author
**Created by:** Dhanush  
**Tool:** Microsoft Power BI  
**Version:** v1.0  
**Date:** July 2026

---

