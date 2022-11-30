# Repository Roadmap: Project 1 (Group3)
# An analysis of global power generation facilities and the relationship between green/low-carbon power generation capacity and HDI.

# This repository is comprised of the following folders and files:


# 1. Resources Folder:
# -------------------------------------------------------------------------------------------------------------
# The Resources folder contains the raw csv files that our group used and created at various stages of the project. These include: 
#
#     "API_NY.GDP.MKTP.CD_DS2_en_csv_v2_4701247.csv": contains the country-level GDP data extract used in our regression analysis estimating the relationship between green/low-carbon power generation capacity and HDI
#     "country_codes.csv": contains the country code and region values for each country included in the Global Power Plant Dataset. We used these sub-region classifications to create dummy variables to control for region in the context of the regression analysis.
#     "country_total_capacity.csv": a dataframe containing the total power generation capacity for each country in the Global Power Plant Dataset. We incorporated these values in the final dataframe used for our regression analysis, which included a column calculating the % of each country's power generation capacity that came from facilities that use green/low-carbon fuel sources as their primary fuel type.
#     "global_pwrplant_database.csv": contains the raw database of power generation facilities assembled by the World Resources Institute. Key columns include those pertaining to Facility Name, Country, Primary Fuel Type, Latitude and Longitude, and Capacity (MW).
#     "global_pwrplant_green_reduced.csv": dataframe containing only those power generation facilities that use green/low-carbon fuel type as their primary fuel
#     "green_energy_grp.csv": dataframe containing the total capacity for all the green/low-carbon power generation facilities, grouped by country
#     "Human Development Index - Full.csv": raw data extract containing HDI values for each of the countries included in the Global Power Plant Dataset.



# 2. Project Proposal Folder
# -----------------------------------------------------------------------------------------------------------------
# The Project Proposal Folder contains our group's original project proposal document (Word format), entitled "Project1_Proposal_g3.docx"


# 3. Map Visualizations Folder
# -----------------------------------------------------------------------------------------------------------------
# The Map Visualizations Folder contains the interactive HTML files displaying the geographic locations of the world's largest fossil fuel-powered and green/low-carbon power generation facilities. Dot size for each facility corresponds to total capacity (MW) and dot color corresponds to fuel type. Hover over dots to reveal facility name, country, capacity, and fuel type.



# The repository also contains the following jupyter notebooks containing the actual code used in our analyses:
# -----------------------------------------------------------------------------------------------------------------
#     1. "PowerPlantDatabase_analysis.ipynb": contains the code for our main analysis of the Global Power Plant Dataset, including examination of: top countries with the most power generation capacity; top countries with most power generation facilities; breakdown of the energy mix by fuel source for countries with the most power generation capacity; and top countries with the most green/low-carbon power generation capacity. Also contains code used to create bar and pie charts in PPT presentation.

#     2. "Map_visualization.ipynb": contains the code used to develop the interactive html maps displaying the geographic locations of the world's largest fossil fuel-powered and green/low-carbon power generation facilities.

#     3. "Regression_analysis.ipynb": contains the code used to merge the country-level power generation capacity data with the data extracts containing the GDP and HDI information for each country. The final part of the notebook performs the regression analysis to estimate the relationship between green/low-carbon power generation capacity and HDI.


# Lastly, the repository also includes a Word document contains our group's final write-up for this project:
# -----------------------------------------------------------------------------------------------------------------
#     1. "Group 3 Project Analysis.docx": summarizes our group's findings and conclusions accompanied by the supporting data/visualizations. 


# Happy browsing!










