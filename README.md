# About inland_empire_cp
Repository of data files and record of analysis steps

## Getting the data
- Downloaded 2017-2018 to 2025-2026 Adjusted Cohort Graduation Rate and Outcome (ACGR) data from the California Department of Education (CDE) website (https://www.cde.ca.gov/ds/ad/filesacgr.asp) as .txt files.

## For each file ACGR file, 2017-2018 to 2025-2026:
1. Opened .txt files on Microsoft Excel.
2. Excel automatically removed leading zeros
3. Saved files as <filename>.xls
4. Filtered by Column F, "CountyName"
5. Unselected "Select All"
6. Selected "Riverside"
7. Selected "San Bernardino"
8. Selected all with Cmd + a
9. Copied all with Cmd + c
10. Opened new Google Sheet
11. Renamed Google Sheet to "IE ACGR 2016-2026"
12. Pasted all into new Sheet tab with Cmd + v

## For each tab in "IE ACGR 2016-2026":
1. Hid Columns:
- "CountyCode"
- "DistrictCode"
- "SchoolCode"
- "Regular HS Diploma Graduates (Count)"
- "Met UC/CSU Grad Req's (Count)"

2. Added Filter to Columns:
- "AggregateLevel" = "S"
- "SchoolName" = Not "Nonpublic, Nonsectarian Schools"
- "CharterSchool" = "NO"
- "DASS" = "NO"
- "ReportingCategory" = "TA"
- "CohortStudents" = Not "*"
