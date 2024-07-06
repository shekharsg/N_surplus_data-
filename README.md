# N_surplus_data-   
#Assessing Temporal Dynamics of Nitrogen Surplus in Indian Agriculture: District-Scale Data from 1966 to 2017

Code Description
Figure 3.ipynb
This notebook contains the code for plotting Figure 3, which is a snapshot of nitrogen surplus in India at various spatial resolutions.

Figure 2.ipynb
This notebook provides the code for generating Figure 2, depicting the nitrogen surplus at the district level for selected years.

Validation.ipynb
This notebook includes code for comparing our dataset with various nitrogen surplus datasets, both in kg and kg/ha, derived from previous literature.

Details/Citation: Assessing Temporal Dynamics of Nitrogen Surplus in Indian Agriculture: District-Scale Data from 1966 to 2017 by S.S. Goyal, U. Bhatia and R. Kumar.
The dataset can be found at 10.5281/zenodo.12662782

This dataset comprises annual long-term total agricultural cropland nitrogen (N) surplus across India, provided at a district-level spatial resolution for the period from 1966 to 2017. The dataset includes twelve N surplus estimates that incorporate uncertainties stemming from various input data sources and methodological choices in key components of the N surplus. This dataset allows for the aggregation of N surplus at any relevant spatial scale, thereby supporting the development of effective water and land management strategies.



Data description:

1. District-level N Surplus Data (CSV format):  District-level N surplus data (CSV format): This dataset includes 12 columns of N surplus values (Kg N/ha), each representing 52 years (1966-2017) of district-level data. The N surplus is calculated using different methods and data choices.  12_nitrogen_budjet_1966_2017

2. Aggregated N surplus at the state level (CSV format): This dataset contains 52 years (1966-2017) of N surplus data (Kg N/ha) at the state level, including the mean and standard deviation of 12 different estimates.   State_N_surplus_mean_std.csv

3. District centroid locations: This dataset contains latitude and longitude coordinates for the centroid locations of districts in India where data is available, which can be used as identifiers. We have followed district name and classification using ICRISAT 1966 identifiers.   district_centroids_lat_long.csv 

4. Aggregated N Surplus (Kg/ha) at Indian River Basins: This dataset encompasses 52 years (1966-2017) of mean nitrogen surplus (Kg N/ha) data at the basin level,  classified according to the basin classification provided by the Central Water Commission of India. The dataset is available in the file  basin_level_mean_N_surplus_kg_ha_1966_2017.csv

Additionally, a CSV file named river_basin_IDs.csv is provided, which contains the river basin IDs along with their names as assigned by the Central Water Commission (CWC) of India.

5. Aggregated N Surplus (Kg/ha) at Sub-Basin level: This dataset includes 52 years (1966-2017) of mean nitrogen surplus data (Kg N/ha) at the sub-basin level, based on the level 5 HydroSHEDS basin classification. The dataset is available in the file Sub_basin_mean_N_surplus_kg_ha_1966_2017.csv

Unit: kg/ha/yr (ha = Net cropping area )

Time period: 1966-2017

Further information:


Further queries regarding these datasets can be directed to Shekhar Goyal (goyal_shekhar@iitgn.ac.in), Udit Bhatia (bhatia.u@iitgn.ac.in) and Rohini Kumar (rohini.kumar@ufz.de).



