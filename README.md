# Electric Vehicle Trends and Sustainability Metrics (2017–Present)

This project is a comprehensive analysis of electric vehicle (EV) rebate trends based on the **NYSERDA Drive Clean Rebate Dataset** from 2017 to the present. This study, conducted as part of my **INT375 Project** during the B.Tech CSE program at **Lovely Professional University**, focuses on understanding how rebate programs influence EV adoption patterns, popular vehicle models, environmental impact, and regional uptake in New York State.

## Project Overview

The primary goal of this project is to draw actionable insights from a real-world government dataset using **Python**, **Pandas**, **Seaborn**, and **Matplotlib**. These insights aim to support sustainable decision-making and policy development.

Key aspects analyzed include:

- Trends in rebate distribution over time  
- Popular electric vehicle models receiving rebates  
- County-wise rebate distribution across New York State  
- Rebate amount patterns and variations  
- Environmental impact (GHG and petroleum reductions)  
- Distribution of rebate amounts by EV type  

---

## Dataset Information

- **Source**: NYSERDA Electric Vehicle Drive Clean Rebate Dataset  
- **Link**: [NYSERDA Electric Vehicle Rebate Dataset](https://catalog.data.gov/dataset/nyserda-electric-vehicle-drive-clean-rebate-data-beginning-2017)  
- **Publisher**: New York State Energy Research and Development Authority  
- **Frequency**: Continuously updated  
- **Scope**: Includes details like vehicle model, EV type, rebate amount, GHG reduction, petroleum reduction, county, and date.

---

## Exploratory Analysis Objectives

### Objective 1: Understanding Relationships Between Rebate Amount, GHG Reduction, and Petroleum Reduction
We aimed to visualize the strength of the linear relationships between the rebate amount and environmental benefits, focusing on the three key numerical features: rebate value, GHG reduction, and petroleum reduction. A heatmap was used to represent these relationships and help us understand how these factors move together across the dataset.

### Objective 2: Identifying the Most Popular EV Models for Rebates
A bar chart was created to display the top EV models based on the number of rebates issued. This visualization reveals which electric vehicle models are most frequently purchased or leased with state incentives, offering a quick overview of consumer preferences for EVs supported by rebates.

### Objective 3: Understanding the Distribution of Rebate Amounts
A Kernel Density Estimation (KDE) plot was used to show how rebate amounts are distributed across the dataset. Unlike histograms, KDE provides a smooth curve representing the probability density of rebate values, helping us understand the distribution pattern without assuming a fixed bin size.

### Objective 4: Identifying the Top 10 Counties with the Most EV Rebates
This visualization focuses on the counties in New York State with the highest number of EV rebates issued. By identifying the top 10 counties, we gained insight into where EV programs are most actively utilized, which could reflect regional interest, accessibility, or the influence of local policies regarding clean transportation.

### Objective 5: Analyzing the Distribution of Rebate Amounts Across Different EV Types
A violin plot was used to compare the distribution of rebate amounts for each type of electric vehicle (e.g., Battery Electric, Plug-in Hybrid). This plot combines a box plot with a kernel density estimate to show the spread, central tendency, and overall distribution shape for each EV category, providing deeper insights into how rebates are allocated across different vehicle types.

---

## Tools & Technologies

- **Programming Language**: Python  
- **Libraries**: Pandas, Seaborn, Matplotlib  
- **Environment**: Jupyter Notebook  
- **Visualization Techniques**: Heatmap, Bar Chart, KDE Plot, Violin Plot  
- **File Format**: .csv  xlsm

---

## Conclusion

This project demonstrates how electric vehicle rebate programs play a crucial role in promoting clean energy adoption. While rebates show a moderate correlation with environmental benefits like GHG and petroleum reductions, the analysis highlights the significance of state-driven incentives in accelerating the growth of electric vehicle adoption. Through effective data visualizations, the project sheds light on EV adoption trends, consumer preferences, and the distribution of rebates across New York counties. The NYSERDA dataset proves invaluable in understanding how incentives shape the market for electric vehicles.

---

## Future Scope

- Integrate demographic and income-level data to analyze rebate accessibility and equity  
- Expand the analysis to include data from multiple states for a comparative study  
- Use machine learning models to predict rebate efficiency and EV adoption likelihood  
- Analyze before-and-after impacts of major policy changes to assess their effectiveness  

---

##  Contact & Feedback

Feel free to connect or provide feedback:

- [LinkedIn Profile](http://linkedin.com/posts/mayank-g22_electricvehicles-datascience-pythonproject-activity-7316328360727457792-1lPZ/?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAEYqqRkBTCzQDjh2NtMegA8m5n7lL8xnPWs)  
- [GitHub Repository](https://github.com/mayank2295/EV-Trends-and-Sustainability-Analysis)

---

##  License

This project is intended for academic, educational, and research purposes only. The dataset used is owned and maintained by NYSERDA and is publicly available for analysis and transparency.

---

