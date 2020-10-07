# Earth-Science-Citation-Replication-Project

Repository for 2020 Earth Science Citation Replication Project

## Jupyter Notebooks:
	1. Citation_Project_Sample.ipynb - Process for creating sample
	2. Citation Data Clean and API.ipynb - Creating Dataframe and making API call
	3. Citation_Data_Analysis_All.ipynb - This file combines the top two notebooks for a streamlined replicable process, 
		from sample creation, API call, to plotting the rule.
	4. open_access_analysis.ipynb - Identifies and graphs OA articles based on WoS assignment

## Files:
### Institution_Reference_Files	
	1. University of Colorado, Boulder - Boulder_References.csv
	2. University of California, Berkeley - Berkeley_References.csv
	3. University of California, Los Angeles - UCLA_References.csv
	4. University of Houston - Houston_References.csv
### Samples
	1. Master Sample - master_sample.csv - 1,000 Record Sample comprised of proportional samples from 4 campuses.
	2. University of Colorado, Boulder - cub_sample.csv
	3. University of California, Berkeley - ucb_sample.csv
	4. University of California, Los Angeles - ucla_sample.csv
	5. University of Houston - uh_sample.csv
### Cited Reference Files
	1. citedRef_master.csv - File with cited references extracted and listed individually
	2. citedRefsMeta.csv - (55,580 records) 
		File created after CrossRef API call - all cited references with clean title data where DOIs were present.
### Open Access Analysis
	1. dois_oa.csv

## Appendices related to article
### Appendix 1: Citation Search & Download Protocol
  1. Appendix_1_WOS_Search_Download_Protocol.pdf
### Appendix 2: Open Access Representation
  1. Appendix_2_Open_Access_Representation.csv
### Appendix 3: Data Cleaning and Exploration
	1. citedRefsMeta_noDOI (File with 11280 citations that had no DOI) 
	2. nodoi.csv - List of the titles without dois sorted by frequency to help aid in data clean up priorities. Used in data_cleaning.ipynb to analyze titles from citedRefsMeta_noDOI after CR column was split by comma.  
	3. citedRefsMeta_2.csv - citedRefsMeta_noDOI was edited and more complete records were added back into this file.  
	4. data_cleaning.ipynb - Describes the process of exploring the 11,800 messy records, cleaning and recombining; compares 80/20 results for clean and messy data.  

## Figures
	1. Figure 1: (in paper)
	2. Figure 2: 8020AllFig.png
	3. Figure 3: AgeFig.png
	4. Figure 4: OAinst%.png
	5. Figure 5: OAcitations.png
