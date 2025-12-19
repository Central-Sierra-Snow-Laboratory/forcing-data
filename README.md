# forcing-data
CSSL scripts to prepare forcing data for snow modeling. 

## raw_forcing data file description 
*some of these are available at cssl.berkeley.edu/data, while others will be available online soon

### cssl - 
manual_observations_WY2025.csv - cssl.berkeley.edu/data: [Snowpack, precipitation, and temperature measurements](https://datadryad.org/dataset/doi:10.6078/D1941T) - note, WY71-25 available \
3000mm_Geo_Prcp_15MinAvg.dat - CSSL internal file; URL access comming \
S2S1_Met_data.dat - CSSL internal file; URL access comming \
S2S1_Flux_CSFormat.dat - CSSL internal file; URL access comming (variables defined in [table 4.10](https://mail.google.com/mail/u/0/#search/table+4.10/FMfcgzQcpwxVJXLMmHNbQlkZqqDvDBSH?projector=1&messagePartId=0.1)) 

### partnered agencies (instrumentation on-site at cssl) - 
150inDruck_Prcp_hourly.csv (NRCS; https://wcc.sc.egov.usda.gov/nwcc/site?sitenum=428) - use the report generator or a tool to programatically access data


## Snow Models we're using (or in the process of setting up!)
iSnobal, specifially [pointSnobal](https://github.com/M3Works/pointsnobal) by [M3Works](https://m3works.io/) \
SUMMA \
SNOWPACK 
