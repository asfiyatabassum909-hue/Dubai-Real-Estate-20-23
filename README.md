# Dubai Real Estate Sales Dashboard (2020–2023)
A quick look at Dubai's real estate transactions from 2020 to 2023, built in Excel using Pivot Tables, slicers, and a KPI-driven dashboard. The goal was to dig into transaction trends, find the busiest areas, and see how different property types performed over time.

<img width="1617" height="581" alt="Screenshot 2026-09-01 154304" src="https://github.com/user-attachments/assets/f3dc850a-2c7f-424b-a88e-50f5439a9382" />

⚠️ **Note:** 2023 data only goes up to March, so any drop you see for 2023 in the charts isn't a market crash — it's just an incomplete year of data.

## 📊 Dataset

- **Source:** Kaggle
- **Size:** ~1,047,965 transaction records, 2020–2023
- **Fields:** Transaction ID, Property Type, Property Sub Type, Area Name, Nearest Metro/Mall, Procedure Area, Actual Worth, Meter Sale Price, and more

## 🎯 Business Questions

### 1. How did the Dubai real estate market actually move between 2020 and 2023?
Transaction value grew from 2020 into 2021 and increased sharply in 2022, when both transaction value and deal count reached their highest levels. 2023 shows a steep drop, but this should not be interpreted as a decline in market activity because the dataset only contains data through March 2023.

💡 **Recommendation:** Track transaction activity on a monthly or quarterly basis alongside annual trends. This would make it easier to identify changes in market activity and avoid misleading comparisons when a year contains incomplete data.

<img width="1029" height="494" alt="image" src="https://github.com/user-attachments/assets/28fea215-5a79-4d03-b86f-671f2ed0e529" />

### 2. Which areas are actually driving the money in this market?
Marsa Dubai and Palm Jumeirah lead the top 10 areas by transaction value. After the top two areas, transaction value falls into a noticeably smaller range, with Al Hebiah Fourth and Al Thanayah Fifth at the lower end of the top 10.

💡 **Recommendation:** The concentration of transaction value in a small number of areas suggests that these locations warrant closer analysis. Comparing transaction volume, average transaction value, and property mix across areas could help identify what is driving the difference in performance.

<img width="1025" height="492" alt="image" src="https://github.com/user-attachments/assets/678cc38d-57c1-4b1c-a0a4-6c18d534a195" />

### 3. What's actually selling — Units, Land, Villas, or Buildings?
Units dominate both transaction value and transaction count by a wide margin. Land and Villas follow at considerably lower levels, while Buildings represent the smallest category in both measures.

💡 Recommendation: Analyze transaction volume alongside average transaction value for each property type. This would help distinguish categories that generate high value through transaction volume from those driven by a smaller number of higher-value transactions.

<img width="1026" height="494" alt="image" src="https://github.com/user-attachments/assets/c3a3f12b-face-4c6e-81b8-b3294c6262ff" />

## 🖥️ The Dashboard

Put together a single-page dashboard so everything's visible at a glance — yearly trends, the top-performing areas, and a breakdown by property type, with slicers to filter by year, area, or property type. Added a few KPI cards up top that update automatically as you filter, so the numbers always match whatever view you're looking at.

<img width="1617" height="581" alt="Screenshot 2026-09-01 154304" src="https://github.com/user-attachments/assets/badea36e-feae-43e1-b0e2-39d1838646cb" />

## 📁 Access the File

- 📥 [Dubai Real Estate Dashboard](https://1drv.ms/x/c/d4256c51d09a9310/IQBzXjJ_U1kuR48PjqR5GtM0AYevN_JYI9Cm77zj9fj_ECk?e=ddvMvK)

## ✅ Conclusion

Dubai's real estate market showed strong, consistent growth from 2020 through 2022, with activity concentrated in a handful of premium areas and heavily skewed toward Unit sales over Land, Villas, or Buildings. Working through this data end-to-end — from cleaning raw records to building a dashboard that actually holds up under filtering — reinforced how much of good analysis happens before the first chart ever gets made. That's the real takeaway from this project.
