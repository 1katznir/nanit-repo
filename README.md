Please find:
- GitHub repository GitHub (this is a python project storing data on Google BigQuery)note about storing data: stg prefix means raw data from json file, dwh prefix means tables for BI tool)
- Data Studio BI is used to show the dashboard Dashboard

Data issues I would recommend to fix:
- PRD_2 connects to 2 different product descriptions, this should be fixed as it duplicates the results (normally I would not remove it from the report as I would have liked the dashboard customers to see the data issue as this is a motivation to fix it, but since this is a home assignment, I removed it manually)
- Total columns equals zero
- Quantities do not match, sometimes the quantities on the DispatchLines are higher than the ones in OrderLines, sometimes it's less

Will be happy to meet and explain

Nir Katz
