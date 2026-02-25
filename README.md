# Serial_killers — Data Analysis

* Loaded 4 datasets — checked shape of each file before merging
* Merged datasets into a single unified DataFrame
* Feature engineering — used GitHub Copilot to extract birth date components into separate columns: birth_date, birth_day, birth_month, birth_year
* Birth date enrichment — initial automated parsing covered partial data; missing dates were researched and verified with Claude AI, then exported to Excel
* Manual verification — imported into Google Sheets for final review and manual lookup of remaining birth dates

Analysis (in progress)

* Zodiac sign distribution
* Geographic breakdown by country
* Activity timeline by year

Tools
* Python
* Google Sheets
* Claude AI
   
Data Source
* Wikipedia
