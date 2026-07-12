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
  # DASHBOARD
  
