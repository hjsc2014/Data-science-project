# Data-science-project
Revised Plan:
1.	Order the original dataset by mean HbA1c and requesting postcode.
2.	Enter list of postcodes into the English indices of deprivation database to return deprivation data https://imd-by-postcode.opendatacommunities.org/imd/2019
3.	This returned a new dataset contained mean HbA1c by various markers of deprivation which I fully anonymised to ensure there were no single results identifiable.
4.	I excluded postcodes with number of requests <20

My new questions were then as follows:
1.	What is the distribution of HbA1c requests by geographic area? LSOA code will be used from a public data source.
2.	Can the difference in numbers of requests be explained by:
a.	Social deprivation using index of multiple deprivation?
b.	Health and disability status?
c.	Prevalence of diabetes (I don’t have this info in my dataset but further work could be to find this data)
3.	Is mean/median HbA1c influenced by:
a.	Social deprivation using index of multiple deprivation?
b.	Health and disability status?


