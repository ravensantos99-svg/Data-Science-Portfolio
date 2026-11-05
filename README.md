# "Plastic cup manufacturing may waste 13% of materials due to trimming losses and production inefficiencies, this should be less than 10%” 


## Executive Summary
  An analysis of 731 days of simulated operational data spanning two years confirms that current manufacturing operations average an overall material waste rate of 12.99%, directly validating the study's primary premise.

  Out of 600,637.00 kg of raw plastic material consumed over the two-year period, 77,784.20 kg was lost as scrap. To maintain operational competitiveness and cost efficiency, manufacturing standards dictate an industry baseline waste target of under 10.0%. Operating at ~13% resulted in 17,720.50 kg of excess material loss above the maximum allowable tolerance.
Portfolio Purpose Note: This dataset and study were developed as a technical demonstration to showcase advanced Excel data processing, data cleaning, and Power BI interactive dashboard visualization competencies.



## Methodology
This study utilizes a synthetic dataset generated via ChatGPT to simulate 731 daily manufacturing records spanning January 1, 2024, to December 31, 2025. To prepare the data for analysis, a thorough data-cleaning and validation process was conducted in Excel:

1.	Data Verification & Cleaning:

  
    a. Audited raw material input ("kg" ), scrap weight ("kg" ), and usable output ("kg" ) across all daily rows.


  
    b. Recalculated sum totals, validated batch-level metrics, and verified waste rate percentages ("Material Waste" /"Material Used" ) to ensure complete mathematical consistency.


Uncleaned Dataset (Before)
<img width="975" height="502" alt="image" src="https://github.com/user-attachments/assets/c653c72f-7a2d-442d-b0a4-3ff74f771033" />

Cleaned Dataset (After)
<img width="975" height="538" alt="image" src="https://github.com/user-attachments/assets/05b355dc-f72b-4bc5-8905-a1de5805a6c9" />



2.	Benchmarking & Loss Categorization:


    a. Aggregated performance metrics were evaluated against an industry-standard 10.0% waste target to quantify operational efficiency gaps.


    b. Losses were segmented into trimming losses, process inefficiencies, and quality defects to model real-world root-cause distribution.



3.	Portfolio Purpose & Demonstration:


   Note: This study is designed specifically as a technical demonstration of advanced Excel data processing, mathematical verification, data modeling, and Power BI interactive dashboard construction and visualization skills.




## Data Visualization

**1.	Annual Production and Waste Summary Metrics (2024 vs. 2025)**

<img width="979" height="234" alt="image" src="https://github.com/user-attachments/assets/8c96a8dc-7e7c-42cf-ae49-f3444c4e10e3" />

The KPI summary cards provide a high-level comparative overview of total manufacturing volume and loss efficiency between 2024 and 2025. In 2024, the plant consumed 301.48K kg of raw material, resulting in 39.34K kg of waste and an average waste rate of 13.09%. Similarly, in 2025, production consumed 299.16K kg of material, yielding 38.44K kg of waste with an average waste rate of 12.90%. These metrics demonstrate that material consumption and inefficiency remained remarkably consistent year-over-year, firmly establishing the structural ~13% baseline well above the 10% target threshold.


**2.	Monthly Average Waste Rate Trend Analysis (2024 vs. 2025)**

<img width="937" height="552" alt="image" src="https://github.com/user-attachments/assets/0d1c27cd-9164-4dc8-9b4f-1659df273eb3" />

The multi-line time series chart tracks monthly fluctuations in average waste rates across both operational years, highlighting seasonal peaks and stability patterns. The 2024 curve exhibits significant volatility, peaking sharply in June at nearly 13.8% and October near 13.7%, whereas the 2025 curve shows improved stability during those mid-year periods but touches a high of 13.3% in December. This visualization emphasizes that while certain months achieve lower loss levels, waste rates consistently breach acceptable operational limits year-round. 


**3.	Total Material Waste Breakdown by Primary Loss Reason**

<img width="943" height="561" alt="image" src="https://github.com/user-attachments/assets/e79b4853-dbf7-46d0-b010-13bbdb07020f" />


**Key Analytical Findings**

•	Primary Scrap Driver: Trimming loss is the single largest contributor to material loss, accounting for 49.82% of total scrap (38,751.70 kg).

•	Secondary Drivers: Process inefficiencies contribute 30.28% (23,554.20 kg), while defective units and other quality issues represent 19.90% (15,478.30 kg)

•	Year-over-Year Trajectory: Waste rates remained persistent across both years, measuring 13.05% in 2024 and 12.85% in 2025, demonstrating that current waste levels are systemic rather than transient anomalies.

Achieving the less than 10.0% threshold will immediately recover over 17.7 tons of resin material over a two-year cycle, significantly lowering cost of goods sold (COGS) and increasing total usable yield.


## Recommendation

To bridge the gap between our current 12.99% average waste rate and the corporate target of < 10.0% which will recover 17,720.50 kg of excess material operational interventions must directly address the baseline scrap distribution:

**1. Redesign Thermoforming Tooling & Cavity Layouts (Addressing Trimming Losses)**

  •	Data Basis: Trimming loss is the single largest driver of material waste, representing 49.82% of all scrap (38,751.70 kg out of 77,784.20 kg total loss).
  
  •	Action: Re-engineer web spacing and mold cavity geometry to reduce structural webbing margins between cups, permanently cutting skeletal scrap volume at the primary source.


**2. Execute Total Productive Maintenance on Heating Units & Molds (Addressing Process Inefficiencies)**

  •	Data Basis: Process inefficiencies account for 30.28% of total scrap (23,554.20 kg), driven by startup purges, thermal drift, and machine setting recalibrations.

  •	Action: Schedule routine preventative calibration for heating elements, thermoformed plug assists, and trim dies to prevent quality drift and eliminate machine downtime scrap during batch runs.


**3. Deploy Real-Time Defect Detection (Addressing Defect Losses)**

  •	Data Basis: Quality defects and other production errors constitute the remaining 19.90% of total scrap (15,478.30 kg).

  •	Action: Integrate optical inline vision inspection systems to instantly identify sheet gauge irregularities and rim deformities, auto-rejecting off-spec units early before continuous defective production runs occur.


