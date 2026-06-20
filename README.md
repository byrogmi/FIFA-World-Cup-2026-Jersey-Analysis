# FIFA World Cup 2026 – Jersey Analysis Dashboard

In this interactive Dashboard i explored the 96 jerseys from the FIFA World Cup 2026. All 48 nations have different brand, primary colors and Home and Away Jerseys. 

## Dashboard Preview
<img width="701" alt="Preview_JerseyAnalysis_FIFA2026" src="https://github.com/user-attachments/assets/720d2fc6-9639-4e4b-9a19-ec4fb10e6c01">

---

**[View the Interactive Tableau Dashboard Here](https://public.tableau.com/app/profile/roger.michel/viz/FIFAWorldCup2026JerseysAnalysis/WorldCup2026Jerseys)**

---

## Project Overview & Motivation

This Project is part of my Portfolio as a self-taught Data Analyst. I wanted to build a unique project completly from scratch and to solve a challenge: **How can i visually analyze the FIFA World Cup 2026 Jerseys on a global scale?**

Every piece of this project was completely build from scratch! Starting by gathering the Data in Google Sheets to a finished Tableau Dashboard that is interactive and fun to interact with. 

---

## The Challenge & Core Features

With this Projects i had some challenges i needed to overcome, especially the visual challenges: 

1. **Custom "Viz-in-Tooltip" Image Pipeline:**
   Instead of just showing text data, i thaught it would be nice, to see both the **Home and Away Jerseys** on the world map, side-by-side. 
2. **Automated Asset Mapping:**
   Overcoming a small issue i build a local string formatting rule (`[Country] + "_" + [Kit_Type]`) to force Tableau to dynamically pair 
3. **UI/UX Optimization:**
   I locked the map to prevent accidental dragging, panning or infinite zooming. This allows a stable, alsmost web-app-like UX. 
---

## Data Collection & Engineering (End-to-End)

Because no ready-made dataset exists for the 2026 World Cup Jerseys, I needed to collect and gather them by myself:

* **Data Gathering:** Manually researched and structured a dataset tracking 96 unique Jerseys (Home & Away for 48 competing nations). 
* **Data Fields:** Captured categorical variables including *Country, Brand (Puma, Nike, Adidas, etc.), Kit Type (Home/Away) and Primary Color*.
* **Storage:** Cleaned, structured, and aggregated the raw data within **Google Sheets** to prepare it for seamless relational import into Tableau Desktop.
* **Asset Curation:** Individually collected and standardized the 96 distinct kit image files, creating a custom shape repository utilizing standardized naming keys for automated file-to-data mapping.

---

## Key Technical Skills Demonstrated

* **Data Engineering & Preparation:** Manual web scraping, data cleaning, restructuring long/wide formats, and relational joins.
* **Advanced Tableau Tooltips:** Advanced implementation of dynamic sheets embedded directly inside multi-layered tooltips (`maxwidth`/`maxheight` scaling, layout container management).
* **Tableau UI Design:** Disabling map layers, fixing viewports (`Entire View` alignment), removing default scrollbars, and building minimalist, highly functional analytic layouts.
* **Problem Solving:** Overcoming global field-assignment limitations in Tableau by designing composite calculated dimensions to keep Home and Away sheet variables strictly separated.

---

## About Me

My Name is Roger and i am a in the process of becoming a Data Analyst by studying Data Analys on my own. This portfolio project represents my commitment to mastering data tools by tackling real-world, complex visual problems from the ground up.

* **Tableau Public:** [My Profile](https://public.tableau.com/app/profile/roger.michel/vizzes)
* **Project Status:** Complete & Live!

---
*Feel free to explore the dashboard, check out the data structure, or reach out if you have any questions about the visualization pipeline!*
