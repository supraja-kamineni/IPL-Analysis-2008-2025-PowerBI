# 🏏 IPL Analysis Dashboard (2008–2025) | Power BI

## 📌 Project Overview

The IPL Analysis Dashboard is an interactive Power BI project designed to analyze the performance of IPL teams and players across seasons from **2008 to 2025**.

The dashboard enables users to select any IPL season and instantly explore key insights including championship winners, player achievements, season statistics, and team standings through dynamic visualizations and KPIs.

This project demonstrates expertise in:

- Power BI Dashboard Development
- Data Modeling
- DAX Calculations
- Interactive Reporting
- Sports Analytics
- Data Visualization

---

## 🎯 Business Objective

To create an interactive dashboard that provides season-wise insights into IPL performance and allows users to:

- Analyze team performance
- Compare player achievements
- Explore season statistics
- View dynamic points tables
- Gain insights through interactive filters and visuals

---

# 📂 Dataset Information

The project uses the following datasets:

### 1. IPL Matches Data
Contains:<a href="https://github.com/supraja-kamineni/IPL-Analysis-2008-2025-PowerBI/blob/main/teams_data.csv">IPL Matches Data</a>

- Match ID
- Season
- Venue
- Toss Details
- Match Winner
- Match Result

### 2. Ball By Ball Data
Contains:

- Batter Runs
- Total Runs
- Wickets
- Bowling Information
- Match Events

### 3. Players Data
Contains:

- Player Name
- Player Image URL
- Team Information

### 4. Teams Data
Contains:

- Team Name
- Team Logo URL

---

# 📊 Dashboard Features

## Season Filter

Users can select any IPL season between **2008 and 2025** and all visuals update dynamically.

---

# 🏆 Primary KPIs

### IPL Winner

Displays:

- Winning Team
- Dynamic Team Logo

### Runner-Up Team

Displays:

- Runner-Up Team
- Dynamic Team Logo

---

# 📈 Secondary KPIs

The dashboard dynamically displays:

| KPI | Description |
|------|-------------|
| Total Sixes | Total sixes hit during the selected season |
| Total Fours | Total fours hit during the selected season |
| Total Matches Played | Number of matches played |
| Total Teams Participated | Number of teams participated |
| Total Centuries | Number of centuries scored |
| Total Half-Centuries | Number of half-centuries scored |
| Total Venues Used | Number of venues used |

---

# 🟠 Orange Cap Statistics

Displays the leading run scorer of the selected season.

### Metrics

- Orange Cap Holder Name
- Total Runs Scored
- Team Represented
- Dynamic Player Image

---

# 🟣 Purple Cap Statistics

Displays the leading wicket taker of the selected season.

### Metrics

- Purple Cap Holder Name
- Total Wickets Taken
- Team Represented
- Dynamic Player Image

---

# 🔥 Most Fours in Season

Displays:

- Player Name
- Total Fours
- Team Represented
- Dynamic Player Image

---

# 💥 Most Sixes in Season

Displays:

- Player Name
- Total Sixes
- Team Represented
- Dynamic Player Image

---

# 📋 Dynamic Points Table

The points table updates automatically based on the selected season.

### Fields Included

| Column |
|----------|
| Team Logo |
| Team Name |
| Matches Played |
| Won |
| Lost |
| No Result |
| Tie |
| Total Points |

---

## Points Calculation

```text
Total Points =
(Wins × 2) +
(Ties × 1) +
(No Results × 1)
```

---

# 🛠 Tools & Technologies Used

### Power BI

- Data Modeling
- Power Query
- DAX
- Interactive Visualizations

### Data Sources

- CSV Files

### Version Control

- GitHub

---

# 🧮 Key DAX Measures

### Team KPIs

- Winner Team
- Runner-Up Team
- Total Matches
- Total Teams Participated
- Total Venues Used

### Batting KPIs

- Orange Cap Holder
- Orange Cap Runs
- Most Fours Player
- Most Sixes Player
- Total Fours
- Total Sixes
- Total Centuries
- Total Half-Centuries

### Bowling KPIs

- Purple Cap Holder
- Purple Cap Wickets

### Points Table KPIs

- Matches Played
- Wins
- Losses
- No Results
- Ties
- Total Points

---

# 🏗 Data Model

### Fact Tables

- ball_by_ball_data
- ipl_matches_data

### Dimension Tables

- players_data
- teams_data

### Relationships

- Match ID → Match Table
- Team Name → Team Dimension
- Player Name → Player Dimension

---

# 📷 Dashboard Screenshot


---

# 🚀 How to Use

### Clone Repository

```bash
git clone https://github.com/supraja-kamineni/IPL-Analysis-2008-2025-PowerBI.git
```

### Open Project

1. Download repository
2. Open Power BI Desktop
3. Open `.pbix` file
4. Refresh data if required

---

# 📈 Key Insights Generated

- Season Champions and Runner-Ups
- Top Run Scorers
- Top Wicket Takers
- Most Fours and Sixes Hitters
- Team Performance Analysis
- Season-wise Points Table
- Venue Utilization Analysis

---

# 💡 Learning Outcomes

Through this project I gained hands-on experience in:

- Data Cleaning
- Data Modeling
- DAX Calculations
- Power Query Transformations
- Dashboard Design
- Sports Analytics
- GitHub Project Documentation

---

# 📁 Repository Structure

```text
IPL-Analysis-2008-2025-PowerBI
│
├── Dataset
│   ├── ball_by_ball_data.csv
│   ├── ipl_matches_data.csv
│   ├── players_data.csv
│   └── teams_data.csv
│
├── PowerBI
│   └── IPL_Analysis_2008_2025.pbix
│
├── Images
│   ├── Dashboard_Overview.png
│   ├── Orange_Cap.png
│   ├── Purple_Cap.png
│   └── Points_Table.png
│
├── README.md
│
└── LICENSE
```

---

# 👩‍💻 Author

### Supraja Kamineni

Aspiring Data Analyst with skills in:

- SQL
- Power BI
- Excel
- Python

### GitHub Profile

https://github.com/supraja-kamineni

---

## ⭐ If you found this project useful, consider giving it a Star!
