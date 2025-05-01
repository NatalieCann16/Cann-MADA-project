#raw-data

This folder contains the unedited data used in this course project. Both data did not come with a codebook - instead the variable names are described on the CDC website. 

**Covid vaccine dataset:**

There are 109 variables, so I will only include specific variables of
interest here. The full list with descriptions can be found at:
https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-Jurisdi/unsk-b7fc/about_data

-   Date: Date data are reported on CDC COVID Data Tracker
    (https://covid.cdc.gov/covid-data-tracker/#vaccinations)
-   MMWR_week: The week of the epidemiologic year as defined by the
    Morbidity and Mortality Weekly Report
    (https://ndc.services.cdc.gov/wp-content/uploads/MMWR_week_overview.pdf)
-   Location: Jurisdiction (State/Territory/Federal Entity)
-   Distribued: Total number of delivered doses
-   Distributed_Janssen: Total number of J&J/Janssen doses delivered
-   Distributed_Moderna: Total number of Moderna doses delivered
-   Distributed_Pfizer: Total number of Pfizer-BioNTech doses delivered
-   Distributed_Novavax: Total number of Novavax doses delivered
-   Distributed_Unk_Manuf: Total number of doses delivered from other
    manufacturers
-   Administered: Total number of administered doses based on the
    jurisdiction (state/territory) where administered
-   Administered_Janssen: Total number of J&J/Janssen doses administered
-   Administered_Moderna: Total number of Moderna doses administered
-   Administered_Pfizer: Total number of Pfizer-BioNTech doses
    administered
-   Administered_Novavax: Total number of Novavax doses administered
-   Administered_Unk_Manuf: Total number of doses administered from
    other manufacturers

**Population dataset:**

In order to control for population size, I used U.S. Census Bureau Population data: https://www.census.gov/popclock/data_tables.php?component=growth

The population for each major region of the U.S. (South, Midwest, Northeast, West) between 2021 and 2023 is provided. 
