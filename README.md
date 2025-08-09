# 🌍 Clean Development Mechanism (CDM) Analysis Dashboard

## 📌 Project Description
This project analyzes Clean Development Mechanism (CDM) data — covering over 8,000 international projects focused on emissions reduction — to evaluate global sustainability performance under the Kyoto Protocol. Built using Power BI, Python (Pandas, Jupyter), and Excel, the project integrates multiple data sources from the UNFCCC CDM dataset from their official website to draw actionable insights for policy, finance, and climate impact. It demonstrates strong skills in data analysis, dashboard creation, and policy-driven storytelling, particularly suited for development economics and environmental governance contexts.

## 🧭 Project Overview
This analysis aims to:

1. Visualize project distribution and Certified Emission Reductions (CERs) across countries.
2. Understand the financial characteristics of different CDM project types.
3. Segment countries based on capital investment and issuance performance.
4. Identify which projects are most effective and scalable in reducing emissions, especially in Least Developed Countries (LDCs).

## 🗂️ Dataset Structure (Source: UNFCCC)
CDM Activities: Main table containing registration details, crediting periods, methodologies, financials (investment, IRR), and CER projections.

Issuances: Records of actual CER issuance events linked to each project.

CPA Info: Additional information for programmatic activities (PoAs), including inclusion dates and sub-national info.

Prior Consideration: Dates of intent submission before formal CDM registration.

Country Codes: Reference for ISO2 and country names.

## 📊 Power BI Dashboard Insights
### 🌍 Geographic & Temporal Trends
![State Performance](https://github.com/trinitarn/CDM-Project-Descriptive-Analysis/blob/main/Screenshot%20State.png)
Asia: total 389,559 MW with 81,758.21 MW CDM-installed (20.99% share) — much higher relative contribution than China itself. 

Africa shows notably strong relative shares in some subregions (e.g., Southern Africa ~30.14% share of region’s capacity installed via CDM), signaling strong CDM impact in specific African subregions.

### Sectors Performance
![Sector Performance](https://github.com/trinitarn/CDM-Project-Descriptive-Analysis/blob/main/Screenshot%20Sector.png)
From the scree plot, we can see that sectors generally have the same level of investment and installed capacity. However, afforestation have highest installed capacity relative to its capital investment which means this sector is kinda effective.

Meanwhile, total CER is not always positively correlated with installed capacity, which means in some sectors like Afforestation, the Installed Capacity is not used effectively since it does not increase the amount of CERs. So there is a lot of potential emission which can be reduced but somehow it’s not effective, so it stayed merely as potential.

The sectors usually stop producing CERs in the next year, so this CDM project should increase their long-term feasibility goals. However, there are sectors which shows the CERs amount in the next year which are Hydro, Wind, Coal, and HFCs. 

### China's Condition
![China's Condition](https://github.com/trinitarn/CDM-Project-Descriptive-Analysis/blob/main/Screenshot%20China.png)
China’s CDM number is very big compared to other country, and the second one is Indonesia. China dominates CDM capacity in absolute terms. China’s total renewable capacity (1,453,701 MW) accounts for the largest share of CDM-related capacity and represents 171,378.80 MW installed through CDM projects (11.79% share of China’s total capacity).

In China, the sectors which relatively have high Installed Capacity relative to its Capital Investment are afforestation and cement sectors, so these sectors are effective.

China’s registration time: average 66 days (reported average) when the total participative states average is 100 days — indicating relatively efficient registration but with room to reduce bureaucratic friction for weaker-capacity countries.

China has also a lot of investment on Wind and Hydro which means it is a good sign that most sectors that China’s CDM take parts in are impacting the emission reduction in a long term.

## 💡 Recommendations
### 🌍 Geographic & Administrative Recommendations
1. Streamline Administrative Processes
Observation: China's average CDM registration time is 66 days, compared to the global average of 100 days.
Recommendation: Other countries should analyze and adopt China's efficient administrative procedures to reduce bureaucratic delays. This can involve:
1. Implementing digital platforms for application processing.
2. Establishing clear guidelines and timelines for each stage of the registration process.
3. Training staff to handle applications more efficiently.

2. Targeted Regional Strategies
Observation: Asia (excluding China) and certain African subregions have high relative CDM contributions.
Recommendation: Focus on these regions by:
1. Providing technical and financial support to scale up successful CDM projects.
2. Encouraging knowledge sharing between countries with high CDM success rates and those looking to improve.

### ⚙️ Sectoral Recommendations
3. Invest in High-Impact, Low-Cost Sectors
Observation: Sectors like afforestation and cement in China show high installed capacity relative to capital investment.
Recommendation: Prioritize investments in sectors that offer significant emission reductions at lower cost.

4. Enhance Emission Reduction Effectiveness
Observation: High installed capacity doesn't always correlate with high Certified Emission Reductions (CERs), especially in afforestation.
Recommendation: Improve the efficiency of sectors with untapped potential by implementing better monitoring and evaluation systems.

6. Promote Long-Term CER Generation
Observation: Sectors like hydro, wind, coal, and HFCs continue to produce CERs beyond the initial year.
Recommendation: Encourage projects in these sectors.

### 📈 Strategic Recommendations
6. Develop Sector-Specific Strategies
Observation: Different sectors have varying efficiencies and potentials.
Recommendation: Tailor strategies to each sector's characteristics.

7. Foster International Collaboration
Observation: Sharing best practices can lead to overall improvements.
Recommendation: Encourage collaboration between countries.
