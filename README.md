# 🏏 IPL Analysis Dashboard (2008–2025)

## **A professional Power BI project using 17 seasons of IPL cricket data to showcase advanced DAX, interactive dashboards, and real-world sports analytics skills — perfect for data analytics, BI, and sports data portfolios.**

---

## 📌 Project Overview
This project provides an end-to-end analytical view of IPL performance, season by season. Designed for clarity and storytelling, it offers powerful features like:

- 🧢 **Orange Cap Analysis** – Highest run scorers per season  
- 🎯 **Purple Cap Analysis** – Most wickets by a bowler each year  
- 💥 **Maximum Sixes & Fours** – Hard-hitting batsman insights  
- 🏆 **Dynamic Points Table** – Track team standings season-wise  
- 🔍 **Team vs. Player Performance** – Across formats and years  
- 📉 **Trends & Visualizations** – Graphical insights year-over-year  

⚡ Crafted with precision and powered entirely by **DAX queries**, every statistic, leaderboard, and visual insight is calculated through custom DAX expressions — delivering accuracy, reusability, and performance.

---

## 💡 Key DAX Calculations
Some examples of DAX measures used:

~~~DAX
Total Runs = SUM(Batting[Runs])
Most Sixes = CALCULATE(COUNTROWS(Batting), Batting[Type] = "6")
Orange Cap = RANKX(ALL(Players), [Total Runs], , DESC)
Total Wickets = COUNT(Wickets[Dismissal Type])
Purple Cap = RANKX(ALL(Bowlers), [Total Wickets], , DESC)
Points = CALCULATE(SUM(Results[Points]))
~~~

Over **50+ custom DAX measures** were used to:
- Create leaderboards  
- Handle filters dynamically  
- Apply conditional visual cues  
- Provide drill-downs by season, player, team, and more

---

## 🛠 Tools & Technologies Used
- **Power BI** – Visualization & data modeling  
- **DAX (Data Analysis Expressions)** – All calculations  
- **Excel** – Raw data cleaning & preprocessing  
- **GitHub** – Version control & portfolio showcase

---

## 🎯 Ideal For
- 🎓 Aspiring Data Analysts / BI Professionals  
- 📊 Dashboard Designers & Power BI Users  
- 🏏 Cricket & Sports Analytics Enthusiasts  
- 💼 Recruiters assessing real-world problem-solving skills

---

## 🧠 Learning Outcomes
Through this project, I gained practical experience in:
- Real-time dashboard design using UI/UX best practices  
- Advanced DAX measures & calculated columns  
- Interactive drill-through & tooltip-based navigation  
- Storyboarding insights for decision-makers

---

## ⭐ Let’s Connect!
If you found this project insightful or helpful:
- 🌟 Give it a **star** on GitHub to support my work  
- 💬 Share your **feedback** — I’d love to improve further  
- 🤝 Connect with me on [LinkedIn](https://www.linkedin.com/in/yourprofile) to discuss **data analytics** or **sports analytics**

---

## 🏷 Hashtags
#PowerBI #IPLAnalysis #DAX #DashboardDesign #DataAnalytics #SportsAnalytics #DataVisualization #Fuqqu1711
