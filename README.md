# Bellabeat Case Study - Smart Device Usage Analysis

This project is part of the **Google Data Analytics Capstone**, where we analyze data collected from Fitbit devices to extract insights and support strategic decisions for **Bellabeat**, a wellness technology company focused on women's health.

## Business Task

The marketing analytics team was asked by Bellabeat’s cofounder **Urška Sršen** to analyze how customers use smart devices. The objective is to discover trends and user behavior patterns to inform targeted marketing strategies.

---

## Dataset

- **Source**: Public dataset on [Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit) by user *Arash Nic*  
- **License**: CC0: Public Domain  
- **Format**: Multiple `.csv` files exported by day/minute, across two folders (`3.12.16` and `4.12.16`)
- **Users**: 30 anonymous Fitbit users tracked for ~2 months

---

## Tools Used

- `R` + `RStudio`
- Libraries: `tidyverse`, `lubridate`, `dplyr`, `broom`, `ggplot2`
- Format: `R Markdown (.Rmd)` rendered to `HTML` and `PDF`

---

## Data Cleaning & Preparation

- Merged and standardized data from multiple folders (date unification, ID alignment)
- Converted `minuteSleep` data to daily summaries for consistency
- Scaled METs (Metabolic Equivalent of Task) values for realistic interpretation
- Removed duplicates and handled missing data appropriately
- Created a **consolidated table (`Full_DailyActivity`)** for analysis

---

## Key Analyses

- **Steps per day** (excluding 0s): Avg ≈ 8,200  
- **Sleep duration**: Avg ≈ 6 hours — below recommended  
- **Activity trends**: Increase during first weeks, then decline  
- **METs analysis**: Identified high-activity profiles  
- **User segmentation**: Fitness / Moderately Active / Sedentary

---

## Main Insights

- Users primarily rely on step tracking (87.3%) while sleep (40.8%) and weight (6.8%) functions are underutilized.
- Physical activity tends to increase during the first 3 weeks of usage, then drops off.
- Only a small number of users show significant improvement in sleep habits.
- 4x more users are moderately active or fitness-oriented than sedentary, suggesting Bellabeat users often use devices to support training.

---

## Recommendations for Bellabeat

- Motivate long-term engagement via gamification and progress feedback  
- Promote sleep-tracking with educational nudges and simplified setup  
- Segment campaigns: fitness users = performance tools; moderate users = small goals  
- Encourage weight tracking via smart scale integrations or rewards  

---

## File Structure

├── Bellabeat_Case_Study.Rmd # R Markdown file with full analysis
├── Bellabeat_Case_Study.html # Rendered HTML report
├── Bellabeat_Case_Study.pdf # PDF version of the report
├── /data/ # (Optional) CSVs used in the project
└── README.md # This file

---

## Author

**Daniel Marín**  
Aspiring Data Analyst | Passionate about behavioral insights  
📧 Email - danielguzmar26@gmail.com
🔗 LinkedIn profile - https://www.linkedin.com/in/juan-daniel-marin-guzman-226b09170/

---

## Status

Final version  
Open to feedback and improvements
