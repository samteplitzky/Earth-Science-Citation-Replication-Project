# Earth-Science-Citation-Replication-Project

Repo for 2020 Earth Science Citation Replication Project

## Jupyter Notebooks:
	1.	Citation_Project_Sample.ipynb - Process for creating sample
	2.	Citation Data Clean and API.ipynb - Creating Dataframe and making API call
	3.	Citation_Data_Analysis_All.ipynb - This file combines the top two notebooks for a streamlined replicable process, from sample creation, API call, to plotting the rule.
	4.	data_cleaning.ipynb - Describes the process of exploring the 11,800 messy records, cleaning and recombining; compares 80/20 results for clean and messy data.
	5.	open_access_analysis.ipynb - Identifies and graphs OA articles based on WoS assignment

## Related files:
	1.	master_sample.csv - 1,000 Record Sample comprised of proportional samples from 4 campuses.
	2.	citedRef_master.csv - File with cited references extracted and listed individually
	3.	citedRefsMeta.csv - (55,580 records) - File created after CrossRef API call - all cited references with clean title data where DOIs were present.
	4.	citedRefsMeta_noDOI (File with 11280 citations that had no DOI)
	5.	nodoi.csv - List of the titles without dois sorted by frequency to help aid in data clean up priorities. Used in data_cleaning.ipynb to analyze titles from citedRefsMeta_noDOI after CR column was split by comma.
	6.	citedRefsMeta_2.csv- citedRefsMeta_noDOI was cleaned (described above) and more complete records were added back in to a new file.