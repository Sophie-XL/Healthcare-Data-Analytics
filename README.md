## Healthcare-Data-Analytics
#### Hospital Efficency Analysis with New York State Data

### [Power BI dashboard: NY Hospital Efficiency in Elective Hip Replacement](https://app.powerbi.com/view?r=eyJrIjoiN2ZhMzBmMmItOTU0Ni00ZGRlLWEzMjAtYTdjMmY0ODYzNDNhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=133a73de4581df2c8d13)

![Length of Stay (LOS) Comparison Page](https://github.com/user-attachments/assets/9500c054-5ec4-487e-9327-dde6fe2b5b4a)


**************************

## Project Description:

In healthcare, improving efficiency while maintaining high-quality patient care is a top priority. HealthStat is a consulting company that explores in patient dataset to uncover hospital efficiency insights. In this project, I analyzed an anonymized dataset from hospitals to uncover insights on potential hospital efficency opportunities.

In the dashboard the following features are included:

1. The Dataset:
   - [x] New York State-wide hospital discharge data for elective hip replacement surgery patients in 2016
   - [x] One table with 30 columns and 26286 rows of patient demographic, diagonosis, hospital stay, hostiptal cost, etc. data
2. Home Page: Navigation bar to LOS, Cost Comparison and Hospital Profile pages
3. LOS Comparison Page: Length of stay (LOS) is the duration in days for a patient stay in a hospital. Reducing LOS can lower costs, increase capacity, and improve throughput.
   - [x] Tracked average LOS of 151 hospitals in New York state and compared it with state-wide LOS averages
   - [x] Tracked Total Surgeons, Average LOS, Total Hospitals and Total Discharges with options to filter for 8 different Health Sercie Areas in New York State
   - [x] Highlighted top 3 and bottom 3 hospitals in terms of LOS in clustered bar charts including % variance to state average in tooltips
   - [x] Identified key influencers and segmentations for LOS considering key factors like risk of mortality, severity of illness, diagnosis, patient demography, hospital size and location, etc.
4. Cost Comparison Page: Average cost per discharge is defined as total costs / total discharges. It is a useful benchmark to compare cost efficiency between hospitals.
   - [x] Tracked Average Cost per Discharge, Average LOS, Total Hospitals and Total Discharges with options to filter for 8 different Health Sercie Areas in New York State
   - [x] Showed the relationship betoween Average LOS and Average Cost per Discharge in a bubble chart with options to drill down into 8 different Health Sercie Areas in New York State
   - [x] Highlighted top 3 and bottom 3 hospitals in terms of Cost in clustered bar charts including % variance to state average in tooltips
   - [x] Identified key influencers and segmentations for cost considering key factors like risk of mortality, severity of illness, diagnosis, patient demography, hospital size and location, etc.
5. Hospital Profile Page: Hospital efficiency KPIs for each hospital
   - [x] Gauge charts for LOS and Cost 
   - [x] Clustered column charts for Total Discharges vs. Illness Severity and Risk of Mortality
   - [x] Donut charts for Total Discharges distribution across diagonsis and patient disposition

**************************

## Project Key Insights:

- [x] Top influencers increasing average LOS and cost:
      Extreme illness severity
      Extreme/ Major mortality risk
      Hospitals in New York City
      Patient disposition to skilled nursing home 
- [x] NYC hospitals stand out with highest cost and LOS, whereas Finger Lakes hospitals are the lowest relative to the state average.
- [x] NYU Lutheran Medical Center has the highest cost while Memorial Hospital for Cancer and Allied Diseases has the highes LOS. The result may due to case complexity rather than lower efficiency. More studies are needed to arrive a sound conclusion.
- [x] There is a negative corelation between Surgical Program Size and LOS and Cost, however, the Surgical Program Size is not among the top influencers to LOS and/or Cost considering illness severity and patient disposition.

**************************

## Key Skills Demonstrated in the Project:

- [x] Exploratory Data Analysis
- [x] Basic and complex DAX formulas
- [x] Data modeling 
- [x] Dashboard/Report designing principles
- [x] Visualizations (Bar/column/line chart, donut chart, KPI card and gauge chart)
- [x] Filters, ranks and page navigation
- [x] Root Cause Analysis (Key Influencers/Top segment)
- [x] Framework for healthcare quality: Safety, Effectiveness, Timeliness, Patient-Centered, Equity and Efficiency
- [x] Hospital Efficiency Measures: LOS and Cost per Discharge
- [x] Healcare concepts: inpatient, discharge, disposition, elective
- [x] Hospital/Healthcare data analytics
