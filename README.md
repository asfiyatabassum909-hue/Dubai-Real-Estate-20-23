# Dubai Real Estate Sales Dashboard (2020–2023)
A quick look at Dubai's real estate transactions from 2020 to 2023, built in Excel using Pivot Tables, slicers, and a KPI-driven dashboard. The goal was to dig into transaction trends, find the busiest areas, and see how different property types performed over time.

<img width="1617" height="581" alt="Screenshot 2026-09-01 154304" src="https://github.com/user-attachments/assets/f3dc850a-2c7f-424b-a88e-50f5439a9382" />

⚠️ **Note:** 2023 data only goes up to March, so any drop you see for 2023 in the charts isn't a market crash — it's just an incomplete year of data.

## 📊 Dataset

- **Source:** Kaggle
- **Size:** ~1,047,965 transaction records, 2020–2023
- **Fields:** Transaction ID, Property Type, Property Sub Type, Area Name, Nearest Metro/Mall, Procedure Area, Actual Worth, Meter Sale Price, and more

## 🎯 Questions I Explored

### 1. How did the Dubai real estate market actually move between 2020 and 2023?
Transaction value grew steadily from 2020 into 2021, then jumped sharply in 2022 — both total value and deal count peaked that year. 2023 shows a steep drop, but that's incomplete data, not a slowdown — this dataset only runs through March 2023, so three months are being compared against three full years.

<img width="1029" height="494" alt="image" src="https://github.com/user-attachments/assets/28fea215-5a79-4d03-b86f-671f2ed0e529" />

💡 **Recommendation:** The real weak point here is reporting cadence, not the market — waiting for a full calendar year to assess performance means 9+ months of blind spot. Move to quarterly tracking with annualized projections, so a dip like this gets caught and explained immediately instead of looking like a market crash on a year-end chart.

### 2. Which areas are actually driving the money in this market?
Marsa Dubai and Palm Jumeirah lead by a wide margin. After the top 2, everything drops into a tighter, noticeably smaller band — Al Hebiah Fourth and Al Thanayah Fifth sit at the bottom of the top 10, at roughly a third of Marsa Dubai's value.

<img width="1025" height="492" alt="image" src="https://github.com/user-attachments/assets/678cc38d-57c1-4b1c-a0a4-6c18d534a195" />

💡 **Recommendation:** The lower-tier areas in the top 10 aren't underperforming because of low demand potential — they're likely underexposed. Targeted marketing pushes, developer incentives, or improved connectivity (new metro links, mall access) in areas like Al Thanayah Fifth and Al Hebiah Fourth could close the gap with the mid-tier performers above them.

### 3. What's actually selling — Units, Land, Villas, or Buildings?
Units dominate both value and count by a wide margin. Land and Villas trail far behind, and Buildings are the smallest category in both metrics.

<img width="1026" height="494" alt="image" src="https://github.com/user-attachments/assets/c3a3f12b-face-4c6e-81b8-b3294c6262ff" />

💡 **Recommendation:** Buildings and Land are the categories that need the push. Since these are higher-ticket, lower-frequency assets, the fix isn't volume marketing — it's liquidity: things like flexible financing options, phased/installment sale structures, or bundling incentives for developers could make these segments move faster instead of sitting stagnant compared to Units.

## 🖥️ The Dashboard

Put together a single-page dashboard so everything's visible at a glance — yearly trends, the top-performing areas, and a breakdown by property type, with slicers to filter by year, area, or property type. Added a few KPI cards up top that update automatically as you filter, so the numbers always match whatever view you're looking at.

<img width="1617" height="581" alt="Screenshot 2026-09-01 154304" src="https://github.com/user-attachments/assets/badea36e-feae-43e1-b0e2-39d1838646cb" />

## 📁 Access the File

- 📥 [Dubai Real Estate Dashboard](https://1drv.ms/x/c/d4256c51d09a9310/IQBzXjJ_U1kuR48PjqR5GtM0AYevN_JYI9Cm77zj9fj_ECk?e=ddvMvK)

