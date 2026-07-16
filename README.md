# Digital-Marketing-Performance-Analysis-EXCEL
End-to-end digital marketing data analysis using Excel, featuring interactive dashboards, KPI tracking, campaign performance, engagement metrics, website traffic, and conversion analysis.
	Greenside Villas — Digital Marketing Tracker & Dashboard
	Cleaned, restructured, and rebuilt as an interactive workbook — ready to upload to Google Sheets.
	
	
	★ FULL AUTOMATION — HOW IT WORKS (read this first) ★
	Every tab is pre-built through 31 Dec 2027 (157 weeks). The pale-yellow rows on Facebook, Instagram, Website, and Airbnb are already dated and already wired into every formula in the workbook — you just type your weekly numbers into the next yellow row. The moment you do, it flows automatically into: the 'Summary' tab, the 'Monthly Summary' pivot-style rollup, every KPI card on the Dashboard, and every chart (Website trend, Airbnb trend, Facebook vs Instagram trend, the funnel, and the channel-selector chart). Nothing needs to be rebuilt, re-pointed, or copied — it is all live formulas referencing full columns and a shared weekly row layout across every tab.
	- Why this works: Facebook, Instagram, Website, and Airbnb all use the exact same list of week-starting dates in the exact same row order, so row 45 is 'the same week' on every tab. Monthly Summary and the KPI cards use whole-column SUMIFS/SUM formulas (e.g. Facebook!$F:$F), which already include any new number you add, anywhere in that column, with zero extra setup.
	- If you ever need weeks beyond Dec 2027: select the last filled row on a tab, then drag its fill handle (bottom-right corner of the selection) down a few rows, or copy that row and paste it below — the date and all formulas continue automatically. Do this on Facebook, Instagram, Website, and Airbnb together to keep every tab's row-alignment intact.
	
	HOW TO USE THIS WORKBOOK
	1. Start on the 'Dashboard' tab — it has KPI cards, trend charts, and a channel selector (cell C70) you can change to update the chart instantly.
	2. Each channel (Facebook, Instagram, Website, Airbnb) has its own cleaned data tab — one row per week, with future weeks already built and pale-yellow so you know where to type next.
	3. 'Monthly Summary' is a formula-driven pivot-style rollup: every number recalculates automatically as you fill in the raw data tabs.
	4. 'Google Business' and 'Reviews' tabs are set up and ready, but no data had been logged in the original file — see Data Quality Notes below.
	5. 'Tourism Context' holds Tanzania national arrival figures for benchmarking Greenside's performance against the wider market.
	6. 'Summary' is a brand-new automatic weekly roll-up — it replaces the old broken/blank 'Summary' tab and pulls Facebook, Instagram, Website, and Airbnb data into one table with zero manual entry.
	
	ADDING SLICERS (FILTER BUTTONS)
	- Every data tab (Facebook, Instagram, Website, Airbnb, Summary, Monthly Summary) is already a named Excel Table with filter-arrow dropdowns built in — click any header arrow to filter or sort that column instantly, and new rows you add right below a table are automatically absorbed into it.
	- For true clickable Slicer buttons: click any cell inside a table, then in Excel go to Table Design > Insert Slicer (or Insert > Slicer), tick the column(s) you want (e.g. Month, Listing Name), and click OK — a floating slicer button box appears that filters the table with one click.
	- In Google Sheets, use Data > Filter views > Create new filter view (or the built-in filter dropdown on the Table headers, which carries over automatically on import) — this is Google's equivalent to an Excel Slicer.
	- The Dashboard's channel-selector dropdown already gives you one-click interactivity without needing a slicer at all.
	HOW TO MOVE THIS TO GOOGLE SHEETS
	1. Go to Google Drive > New > File upload, and upload this .xlsx file (or open it in Claude's file panel and download it first).
	2. Right-click the uploaded file in Drive > Open with > Google Sheets. Google converts the formulas, formatting, charts, and dropdown all automatically.
	3. Once open, use File > Save as Google Sheets to get a native, shareable Sheet (File > Share to collaborate with your team).
	4. The channel-selector dropdown (Data Validation) and all SUMIFS/INDEX/MATCH formulas are Google-Sheets-native and need no adjustment.
	
	DATA CLEANING DECISIONS MADE
	- Removed the broken/empty 'Summary', 'report', and 'Pivot Table 1 AIRBNB' tabs — they contained no usable data, only leftover formatting and a corrupted pivot cache.
	- Blank weekly cells within each channel's active reporting period were treated as 0 (no activity that week), not missing data.
	- Weeks after the last real entry were left completely blank (not 0) and shaded pale yellow, since they haven't happened/been reported yet — filling them in is what triggers the automation.
	- Facebook's real data runs through the week of 2026-07-10; Instagram, Website, and Airbnb run through 2026-06-19 — Facebook was the most current tab in the original file.
	- FLAGGED FOR REVIEW: Instagram week of 2025-01-31 shows Reach = 100,500 against Impressions of only 10,646 — reach is almost always <= impressions, and every neighboring week is in the low hundreds. This looks like a data-entry error (an extra digit or misplaced decimal). It has been kept as-is but highlighted in orange on the Instagram tab — please verify against the original Meta Business Suite export.
	- The 'Google' (Google Business Profile) and 'Reviews' tabs contained column headers only — not a single week of data had been entered. Both are rebuilt as ready-to-fill templates rather than invented.
	
	WHAT'S ON THE DASHBOARD
	- KPI cards: Total Reach, Total Engagement, Website Visitors, Airbnb Bookings, Airbnb Revenue, Average Occupancy — all live SUM/AVERAGE formulas.
	- Awareness -> Interest -> Intent -> Conversion funnel chart, built from combined channel reach, website clicks, inquiries, and bookings.
	- Facebook vs Instagram reach trend, Website traffic trend, and Airbnb bookings & revenue trend — every chart already spans through Dec 2027, so new data appears the moment you enter it.
	- An interactive channel selector (dropdown) that redraws a trend chart for whichever channel you pick.
<img width="932" height="1065" alt="image" src="https://github.com/user-attachments/assets/a75640fc-2140-4e7d-af0f-4d2855464563" />
<img width="1336" height="488" alt="Dashbord 2" src="https://github.com/user-attachments/assets/bdb57579-e440-4e48-85c1-564684e1c8cf" />
<img width="1214" height="432" alt="dashboard 2" src="https://github.com/user-attachments/assets/450e9778-60ef-4d1e-a601-f4a57294133f" />
<img width="1316" height="420" alt="dashboard 1" src="https://github.com/user-attachments/assets/14436559-5815-44f9-b808-64e37a64379b" />
<img width="1275" height="484" alt="dasboard" src="https://github.com/user-attachments/assets/5fa8ded9-03ff-4240-bf7f-1590a506c7ca" />
