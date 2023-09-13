# ETC5543 - Business Analytics Creative Activity : Data Analysis Revolutinizing Journalism

ETC5543 Report is a brief summary of the analysis we have conducted at 360info organisation. It contains draft and final analysis for the two topics assigned during our internship. It also includes exploratory data analysis for knowledge purposes.

Topic 1: Our initial task was researching datasets related to child marriage, particularly during Covid-19. Followed by data wrangling for tidying data and combining datasets for the final visualization. The above visualisations were the initial drafts for the editor’s reference and have played a crucial role in arriving at the final visualisation.

In order to understand the contrast between the child marriage rate across the globe and the legal policy existing in each country, we wanted to create one visualisation which could display both. 

Topic 2: The aim was to observe the trend of HDI and Happiness Score(Life Ladder Score) over the past years. While HDI is more quantitative and defined and Happiness Score is more subjective based on well-being, the difference in trends of both the scores speaks volumes. Unlike the first topic, the idea behind this visualisation was conceived from the start once the datasets had been shortlisted. The countries in this visualisation were shortlisted based on the unique trend observed amongst all the countries.

Repo name: https://github.com/360-info/internship-childmarriage-healtheconomics.git

## Use + Remix rights

![[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0)](https://mirrors.creativecommons.org/presskit/buttons/80x15/png/by.png)

These charts, as well as the analyses that underpin them, are available under a Creative Commons Attribution 4.0 licence. This includes commercial reuse and derivates.

<!-- Do any of the data sources fall under a different licence? If so, describe the licence and which parts of the data fall under it here! if most of it does, change the above and replace LICENCE.md too -->

Data in these charts comes from:

[World Happiness Report](https://worldhappiness.report/ed/2022/)

[Human Development Index](https://hdr.undp.org/data-center/human-development-index#/indicies/HDI)

Minimum Age of Child Marriage Rate: [United Nations](https://gender-data-hub-2-undesa.hub.arcgis.com/datasets/8ba8255a4ba047fcb0e6dbe8041a0eb0/explore)

Covid-19 Stringency: [Our World in Data](https://ourworldindata.org/metrics-explained-covid19-stringency-index)

Laws on Child Marriage: [Our World in Data](https://ourworldindata.org/grapher/laws-on-child-marriage)

Child Marriage Rate from 2005–2021: [UN DESA Statistics Division](https://unstats-undesa.opendata.arcgis.com/datasets/undesa::indicator-5-3-1-proportion-of-women-aged-20-24-years-who-were-married-or-in-a-union-before-age-18-percent/explore?location=2.960853%2C1.735981%2C2.67)

Child Marriage Rate during Covid-19: [UNICEF Data](https://data.unicef.org/resources/data_explorer/unicef_f/?ag=UNICEF&df=GLOBAL_DATAFLOW&ver=1.0&dq=.PT_F_20-24_MRD_U15+PT_F_20-24_MRD_U18+PT_F_15-19_MRD..&startPeriod=2016&endPeriod=2022)

**Please attribute 360info and the data sources when you use and remix these visualisations.**

## Reproduce the analysis

### Manual setup

To setup a development environment manually, you'll need to:

- [Download the install R](https://www.r-project.org)
- Satisfy the R package dependencies. In R:
  * Install the [`renv`](https://rstudio.github.io/renv) package with `install.packages("renv")`,
  * Then run `renv::restore()` to install the R package dependencies.
  * (For problems satisfying R package dependencies, refer to [Quarto's documentation on virtual environments](https://quarto.org/docs/projects/virtual-environments.html).)

Now, render the `.rmd` files in R with (for example):

```r
rmarkdown::render("Report.Rmd")
```
