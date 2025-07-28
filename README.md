# Power BI data Validation Implementation Steps

# Disclaimer:
This project is inspired by a real-world staff data validation initiative in a large academic organisation. All institution names, department titles, and datasets have been anonymised. This version is for public sharing and portfolio demonstration purposes only. 

# Demonstration of My Expertise in DAX and Data Problem Solving
This project highlights my expertise in using DAX to address real-world data challenges. During the development of the Staff Validation System, I applied advanced DAX techniques to solve issues such as detecting duplicate records, validating FTE values, and flagging inconsistencies across multiple data sources. The logic in the code files reflects how complex business rules can be turned into clear, actionable insights through DAX, helping to streamline the validation process and improve data reliability at scale.

# Problem Statement:
In any large organisation, especially in public sector and/or within a higher education setting, keeping staff data accurate across multiple systems is a constant challenge. Information about employees is often stored in different places, such as HR systems, faculty records, and operational platforms. When these systems do not match up, it becomes difficult to rely on the data.
The Staff Validation System (SVS) project was launched to address this issue. Teams were facing problems like:
1. Employees appearing more than once due to duplicate entries
2. Inconsistent or missing FTE (Full-Time Equivalent) values
3. Differences in job roles or names for the same person across systems
4. Fields like Final FTE, Contract FTE, or FTE being blank or outside expected ranges
   
These problems made it harder for departments to know exactly how many people were working, what their roles were, and how much time they were actually contributing. As a result, it affected several key areas:
1. Accurate headcount validation and reporting
2. Fair allocation of budgets and resources
3. Readiness for audits and compliance checks
4. Smooth coordination between HR, faculty, and operational teams
   
Before this project, spotting and fixing these issues required manual work, including digging through spreadsheets, comparing disconnected systems, and spending valuable time resolving conflicts.
The goal of this project was to bring all staff data into a single view, automatically highlight any errors or inconsistencies, and give clear, actionable insights to analysts, administrators, and team leads so they can quickly review, trust, and clean the data.

# Power BI Data Tables (Staff Validation Model)
1. Faculty A
Dataset submitted by Faculty A for validation. Contains staff-related records to be reviewed against central reference data.
2. Faculty B
Dataset from Faculty B, used in the same way as Faculty A for staff data validation.
3. Raw Data
Central administrative dataset that includes core employee information. Used as the baseline for validating and cross-checking faculty-submitted records.
4. Leavers
The Leavers table is used to compare employee numbers from faculty data with the central HR records. Its purpose is to validate employee exit information and ensure accurate alignment across systems.
5. Removals
The Removals table is used to identify which employee records should be kept or excluded by comparing against defined removal criteria. It supports dynamic filtering and plays a key role in data cleansing and validation.
