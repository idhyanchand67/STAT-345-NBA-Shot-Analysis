# STAT 345 Midterm: Chicago Bulls Shot Analysis  

This project explores **NBA shot data** for the **Chicago Bulls (2014–2024)** using R.  
It combines data collection from the `nbastatR` package with custom visualizations to analyze team shot efficiency, volume, and trends over time.
Note this doesn't include data from 2017 (missing data).

---

## Project Overview
- **Goal:** Examine how the Bulls’ shot selection and efficiency have evolved across seasons.  
- **Tools Used:** R, ggplot2, gganimate, nbastatR, dplyr, viridis, cowplot.  
- **Main Deliverables:**
  - Animated **shot chart GIF** showing makes and misses across seasons  
  - **Zone efficiency visualization** (bubbles on the court) for recent seasons  
  - **Heatmap** of field goal percentage by zone and season  
  - **Line chart** showing changes in shot volume over time  
- Includes a **front-office style report** summarizing findings and insights  

---

## Key Findings
- Highest efficiency occurs in the **restricted area** and **above-the-break three** zones  
- **Midrange shots** remain the lowest-efficiency area  
- **Three-point attempts** have increased steadily in recent seasons  
- Shot distribution patterns are stable, emphasizing rim and top-of-arc threes  

---

##  Data Source
Shot-level data retrieved using the [`nbastatR`](https://github.com/abresler/nbastatR) package via the `teams_shots()` function.  
Data covers **regular-season games** for the Chicago Bulls between **2014–2024**.

---

## 🏀 Author
**Isaac Dhyanchand**  
University of Wisconsin–La Crosse  
Course: STAT 345
