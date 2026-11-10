# SYSTEMS-HORROR-MERIDIAN-FORGE-ROBOTICS
## Week 7 — Can We Trust the Data?

Week 7 focuses on checking the quality of inspection records for Meridian Forge Robotics. The goal was to use Excel and Power Query to identify missing information, duplicate records, invalid values, and inconsistencies without changing the original data.

**Main work completed:**
- Used Power Query to prepare 20 inspection records while keeping the original Raw worksheet unchanged.
- Cleaned the Status column by removing extra spaces and converting the values to uppercase.
- Checked five data-quality rules (Q01–Q05) using the Audit worksheet.
- Identified 12 rule flags across 11 different records, affecting 55% of the data.
- Completed the Report worksheet with findings, explanations, and recommendations for verifying the information.
- Tested the Power Query refresh by changing an inspection duration from 20 to 0, refreshing the data, and confirming that Q04 changed from OK to FLAG.
- Restored the original value and refreshed again to confirm that Q04 returned to OK.
- Exported the completed Report worksheet as a two-page PDF and saved a screenshot of the Power Query Applied Steps.

**Files and locations:**
- `Week07/Artifact/` — Completed Excel workbook, two-page data-quality report PDF, and Power Query Applied Steps screenshot.
- `Week07/Receipt/` — Week 7 Mission Receipt PDF.

**What I learned:**

This assignment helped me understand how important data quality is when working with spreadsheets. I learned how to use Power Query to clean and prepare information without changing the original records. I also learned that just because a record says READY does not mean the information is accurate or that a machine is safe. Missing or incorrect information needs to be verified before making decisions.
