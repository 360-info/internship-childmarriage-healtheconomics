# Datasets used

## Filename: w_18.csv : "Average Child Marriage Rate 2005 - 2020"

### Description: 
- This dataset is part of the Global SDG Indicator Database compiled through the UN System in preparation for the Secretary-General's annual report on Progress towards the Sustainable Development Goals.
Indicator 5.3.1: Proportion of women aged 20–24 years who were married or in a union before age 15 and before age 18
- Target 5.3: Eliminate all harmful practices, such as child, early and forced marriage and female genital mutilation
- Goal 5: Achieve gender equality and empower all women and girls

### URL: [UN DESA Statistics Division](https://unstats-undesa.opendata.arcgis.com/datasets/undesa::indicator-5-3-1-proportion-of-women-aged-20-24-years-who-were-married-or-in-a-union-before-age-18-percent/explore?location=2.960853%2C1.735981%2C2.67)

### Data Dictionary: spec_tbl_df [131 x 33]

* geoAreaCode : num [1:131] Country Code
* geoAreaName : chr [1:131] Country Name
* level_      : num [1:131] Numeric
* parentCode  : num [1:131] Numeric
* parentName  : chr [1:131] Sub Continental Region
* type        : chr [1:131] Geographical level
* X           : num [1:131] Latitude
* Y           : num [1:131] Longitude
* ISO3        : chr [1:131] ISO3 country code
* latest_value: num [1:131] Child Marriage Rate


## Filename: child_marriage.csv : Child Marriage Rate in Sub-continental region during Covid-19

### Description: 
This dataset contains Percentage of women (aged 20-24 years) married or in union before age 18 **during Covid-19 period**

### URL: [UNICEF Data](https://data.unicef.org/resources/data_explorer/unicef_f/?ag=UNICEF&df=GLOBAL_DATAFLOW&ver=1.0&dq=.PT_F_20-24_MRD_U15+PT_F_20-24_MRD_U18+PT_F_15-19_MRD..&startPeriod=2016&endPeriod=2022)

### Data Dictionary: spec_tbl_df [131 x 33]

* Geographic area = chr - Country Name  = col_character()
* Time period = Year of observation  = col_character()
* OBS_VALUE:O Child Marriage Rate  = col_character()
* OBS_FOOTNOTE: Footnote` = col_character()
* SERIES_FOOTNOTE: col_logical()
* DATA_SOURCE: Data Source` = col_character(),
* SOURCE_LINK: Citation of or link to the data source` = col_logical(),
* CUSTODIAN: col_logical(),
* TIME_PERIOD_METHOD: Time period activity related to when the data are collected` = col_character(),
* REF_PERIOD: Reference Period` = col_logical(),
* COVERAGE_TIME: The period of time for which data are provided` = col_character(),
* AGE: age group covered in dataset = col_character()


## Filename: legal_age.csv : Countries with minimum legal marriage age less than 18

### Description: 
This dataset contains minimum legal age for marriage without consent

### URL: [UNICEF Data](http://data.un.org/Data.aspx?q=marriage&d=GenderStat&f=inID:19)

### Data Dictionary: spec_tbl_df [131 x 33]

* ObjectId = col_double(),
* indicator_label = col_character(),
* indicator_id = col_character(),
* indicator_desc = col_character(),
* minset_series = col_character(),
* minset_series_desc = col_character(),
* ref_area = col_double(),
* ref_area_desc = col_character(),
* iso3 = col_character(),
* x = col_double(),
* y = col_double(),
* sdg_region = col_character(),
* sex = col_character(),
* sex_desc = col_character(),
* time_period = col_double(),
* time_detail = col_character(),
* value_category = col_double(),
* value_category_desc = col_character(),
* nature = col_character(),
* nature_desc = col_character(),
* reporting_type = col_character(),
* reporting_type_desc = col_character(),
* comment_obs = col_double(),
* source_detail = col_character(),
* source_detail_url = col_character(),
* source_year = col_double(),
* dimensions = col_character(),
* is_latest_year = col_double()


## Filename: law_2.csv : "Laws for Child marriage(2019)"

### Description: Legal provisions for child marriage, 2019

### URL: [Our World in Data](https://ourworldindata.org/grapher/laws-on-child-marriage)

### Data Dictionary: spec_tbl_df [131 x 33]

* iso_a3  : ISO3 Country Code
* Entity  : Country Name
* Year    : Year
* Law     : Legal code


## Filename: stringency.xlsx : Covid-19 Stringency Index

### Description: COVID-19: The stringency index is a composite measure based on nine response indicators including school closures, workplace closures, and travel bans, rescaled to a value from 0 to 100 (100 = strictest). 

### URL: [Our World in Data](https://ourworldindata.org/metrics-explained-covid19-stringency-index)

### Data Dictionary: spec_tbl_df [131 x 33]

* iso_a3  : ISO3 Country Code
* Entity  : Country Name
* Year    : Year
* Law     : stringency index


## Filename: hdi_timeseries.xlsx : Human Development Index by UNDP

### Description: The Human Development Index (HDI) is a summary measure of average achievement in key dimensions of human development: a long and healthy life, being knowledgeable and having a decent standard of living. The HDI is the geometric mean of normalized indices for each of the three dimensions. 

### URL: [UNDP](https://hdr.undp.org/data-center/human-development-index#/indicies/HDI)


## Filename: 2015_a.xlsx : World Happiness Report

### Description: This report ranks countries based on their happiness score and their subjective well-being. It estimates this score based on various factors like income, life expectancy, social support, freedom, generosity, and perceptions of corruption. It believes that subjective well-being is measured through life evaluations and our emotions - positive and negative.

### URL: [World Happiness Report](https://worldhappiness.report/ed/2022/)


## Filename: wellbeing-otherfactos.xlsx : World Happiness Report

### Description: This report ranks countries based on their happiness score and their subjective well-being. It estimates this score based on various factors like income, life expectancy, social support, freedom, generosity, and perceptions of corruption. It believes that subjective well-being is measured through life evaluations and our emotions - positive and negative.

### URL: [World Happiness Report](https://worldhappiness.report/ed/2022/)










