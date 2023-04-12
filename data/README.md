/data

# Dataset used

## Plot Name: "Average Child Marriage Rate 2005 - 2020"

### Description: 
- This dataset is part of the Global SDG Indicator Database compiled through the UN System in preparation for the Secretary-General's annual report on Progress towards the Sustainable Development Goals.
Indicator 5.3.1: Proportion of women aged 20–24 years who were married or in a union before age 15 and before age 18
- Target 5.3: Eliminate all harmful practices, such as child, early and forced marriage and female genital mutilation
- Goal 5: Achieve gender equality and empower all women and girls

###URL: [UN Stats](https://unstats-undesa.opendata.arcgis.com/datasets/undesa::indicator-5-3-1-proportion-of-women-aged-20-24-years-who-were-married-or-in-a-union-before-age-18-percent/explore?location=2.960853%2C1.735981%2C2.67)

### Filename: w_18.csv

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

Dataset used in "Child Marriage rate - Women vs Men below 18 years - 2021"
filename: cm_2021_new.xlsx
URL: https://data.unicef.org/wp-content/uploads/2021/10/Table-12-Child-Protection-SOWC2021-EN.xlsx
Description
Data Dictionary: tibble [183 x 6] (S3: tbl_df/tbl/data.frame)
 $ Country   : chr [1:183] "Afghanistan" "Albania" "Algeria" "Andorra" ...
 $ w15       : chr [1:183] "4.2014570000000004" "1.38724" "0" "-" ...
 $ w18       : chr [1:183] "28.257380000000001" "11.760540000000001" "3.8" "-" ...
 $ m18       : chr [1:183] "7.3" "1.2" "-" "-" ...
 $ Region    : chr [1:183] "Asia" "Europe" "Africa" "Europe" ...
 $ Population: num [1:183] 4112

Dataset used in "Average Child Marriage Rate in Sub Continental Region in 2021"
filename: child_marriage.csv
URL: https://data.unicef.org/resources/data_explorer/unicef_f/?ag=UNICEF&df=GLOBAL_DATAFLOW&ver=1.0&dq=.PT_F_20-24_MRD_U15+PT_F_20-24_MRD_U18+PT_F_15-19_MRD..&startPeriod=2016&endPeriod=2022
Description
Data Dictionary: spec_tbl_df [12 x 12]
       `Geographic area` = col_character(),
  ..   `TIME_PERIOD:Time period` = col_double(),
  ..   `OBS_VALUE:Observation Value` = col_double(),
  ..   `OBS_FOOTNOTE:Observation footnote` = col_character(),
  ..   `SERIES_FOOTNOTE:Series footnote` = col_logical(),
  ..   `DATA_SOURCE:Data Source` = col_character(),
  ..   `SOURCE_LINK:Citation of or link to the data source` = col_logical(),
  ..   `CUSTODIAN:Custodian` = col_logical(),
  ..   `TIME_PERIOD_METHOD:Time period activity related to when the data are collected` = col_character(),
  ..   `REF_PERIOD:Reference Period` = col_logical(),
  ..   `COVERAGE_TIME:The period of time for which data are provided` = col_character(),
  ..   `AGE:Current age` = col_character()

Dataset used in "Countries with minimum legal marriage age less than 18"
filename: legal_age.csv
URL: https://opendata.arcgis.com/api/v3/datasets/8ba8255a4ba047fcb0e6dbe8041a0eb0_0/downloads/data?format=csv&spatialRefId=4326&where=1%3D1
Description
Data Dictionary: cols(
  ..   ObjectId = col_double(),
  ..   indicator_label = col_character(),
  ..   indicator_id = col_character(),
  ..   indicator_desc = col_character(),
  ..   minset_series = col_character(),
  ..   minset_series_desc = col_character(),
  ..   ref_area = col_double(),
  ..   ref_area_desc = col_character(),
  ..   iso3 = col_character(),
  ..   x = col_double(),
  ..   y = col_double(),
  ..   sdg_region = col_character(),
  ..   sex = col_character(),
  ..   sex_desc = col_character(),
  ..   time_period = col_double(),
  ..   time_detail = col_character(),
  ..   value_category = col_double(),
  ..   value_category_desc = col_character(),
  ..   nature = col_character(),
  ..   nature_desc = col_character(),
  ..   reporting_type = col_character(),
  ..   reporting_type_desc = col_character(),
  ..   comment_obs = col_double(),
  ..   source_detail = col_character(),
  ..   source_detail_url = col_character(),
  ..   source_year = col_double(),
  ..   dimensions = col_character(),
  ..   is_latest_year = col_double()
  .. )

Dataset used in "Legality of Child Marriage(2017)"\
filename: law_prohibit.csv
URL: https://ourworldindata.org/grapher/does-law-prohibit-or-invalidate-child-or-early-marriage
Description
Data Dictionary:  cols(
  ..   Entity = col_character(),
  ..   Code = col_character(),
  ..   Year = col_double(),
  ..   Law = col_double()
  .. )


Dataset used in "Laws for Child marriage(2019)"
filename: law_2.csv
URL: https://ourworldindata.org/grapher/laws-on-child-marriage
Data Dictionary: Classes 'data.frame':	178 obs. of  4 variables:
 $ iso_a3  : chr  "AFG" "AGO" "ALB" "ARE" ...
 $ Entity  : chr  "Afghanistan" "Angola" "Albania" "United Arab Emirates" ...
 $ Year    : num  2019 2019 2019 2019 2019 ...
 $ Law     : num  1 0.5 0.5 0.5 0.5 0.5 0.5 0.5 0.5 0.5 ...










