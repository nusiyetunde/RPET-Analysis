# RPET-Analysis
# OVERVIEW
This project analyzes RPET(Recycled polyethylene terephthalate) production quality data to monitor production performance,contamination levels,moisture content and product quality grades.The objective is to identify trends,measure quality performabce and support data-driven decision making
# DATA SOURCE
This project is based on anonymized internal RPET laboratory quality contol records.Company-identifying information has been removed for confidentiality
# BUSINESS PROBLEM
The production team needed a way to:
- Monitor production quality
- track moisture and total PPM
- identify contamination pattern
- evaluate productquality grade(A,A1,A2,Reject)
- compare production performance across shift.
  # DATASET
  | Varaiable | Description |
  |----------|------------|
  | Bag no | Production bag ID |
  | Batch no | Production batch |
  | Shift | Day\Night |
  | Moisture% | Moisture content |
  | Total PPM | Total contamination |
  | Label | Label conamination |
  | PVC | PVC contamination |
  | Metal | Metal contamination |
  | Quality grade | A,A1,A2,Reject |
  # TOOLS USED
  - Microsoft excel
  - MySQL
  - PowerBI
  # DATA CLEANING(MICROSOFT Excel)
  <img width="621" height="286" alt="Screenshot 2026-07-12 111638" src="https://github.com/user-attachments/assets/8fc0267f-38e7-4beb-81a7-472ebc695f9d" />

   Microsoft Excel was used to prepare the dataset for analysis. The cleaning process incude correcting data types,creating a quality grade column based on contamination thresolds,creating a shift column to distinguish between day and night production,applying formatting to improve readability and using conditional formatting to highlight contamination values that exceeded acceptable limits.These steps ensure that the dataset was accurate,consistent and ready for analuysis in MySQL,PowerBI.

   # POWER BI
  <img width="519" height="265" alt="Screenshot 2026-07-12 112506" src="https://github.com/user-attachments/assets/214a91cd-bf3e-47fb-89b1-6dacff0b02fa" />

   The powerBI dashboards presents production quality metrics in an interactive format. KPI Cards summarize the key performance indicator, while charts display trends in moisture,total PPM and contaminant composition.Slicers allows user to filter the report by shift,batch number and quality grade.

   # KPI Cards
  <img width="398" height="133" alt="Screenshot 2026-07-12 113350" src="https://github.com/user-attachments/assets/0208bfff-829a-4f84-becd-43034ed3a352" />

  KPI Cards display key production metrics incuding Total Bags,Average Moisture,Average Total PPM and Quality Grade counts.

  # SQL
  TOTAL BAGS
  
  <img width="450" height="271" alt="Screenshot 2026-07-19 135645" src="https://github.com/user-attachments/assets/58389366-d087-4c31-886c-c55eaad0d0cb" />

  This query calculate the total bag produce from june 1st-15th.

  AVERAGE TOTAL PPM

  <img width="450" height="319" alt="Screenshot 2026-07-19 135833" src="https://github.com/user-attachments/assets/ec4d26a3-eef6-4aca-b2ed-745d4a278a54" />
  
  This query calculate the average Total PPM across all production bags.This metrics helps assess whether the production process is operating within acceptable quality limits.

  QUALITY GRADE DISTRIBUTION

  <img width="447" height="286" alt="Screenshot 2026-07-19 135913" src="https://github.com/user-attachments/assets/f1a68df1-8523-48d8-a2fe-de398cbb862f" />

  This query counts the number of bags in each quality grade(A,A1,A2 and Reject),helping to evaluate overall production quality.

  SHIFT PERFORMANCE

  <img width="443" height="263" alt="Screenshot 2026-07-19 141710" src="https://github.com/user-attachments/assets/8442a857-70af-47c8-bda3-9c77ebbc65a4" />

  This query calculate the average Total PPM and average yellow flakes across the shift.

  HIGHEST TOTAL PPM

  <img width="442" height="333" alt="Screenshot 2026-07-19 140137" src="https://github.com/user-attachments/assets/f2332521-9c79-401e-bbe5-98962baeda3b" />

This query shows the highest Total PPM across all production bags.

LOWEST TOTAL PPM

<img width="444" height="333" alt="Screenshot 2026-07-19 140029" src="https://github.com/user-attachments/assets/229b6475-891a-48a9-b652-78a457392720" />

This query shows the lowest Total PPM across all productions bags.


# KEY INSIGHTS

- A total of 864 bags were analyzed.
- Average moisture was 1.14% .
- Average Total PPM was 63.21 .
- Grade A1  reoresented the highest proportion of production.
- Label contamination was the most common contaminant.
- Night shift produce the highest bag number more than morning shift.
- Night shift produce  grade A1 Bag more than morning shift.

  




  



  
