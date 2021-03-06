
<!-- badges: start -->

[![Travis build
status](https://travis-ci.com/Capucine0210/CourseraProject.svg?branch=main)](https://travis-ci.com/Capucine0210/CourseraProject)
[![R-CMD-check](https://github.com/Capucine0210/CourseraProject/workflows/R-CMD-check/badge.svg)](https://github.com/Capucine0210/CourseraProject/actions)
<!-- badges: end -->

# CourseraBuildingRPckg

This package is built for the Peer Assignement of [Building R Package
Course on
Coursera](https://www.coursera.org/learn/r-packages/home/welcome).

The goal of the package is to help you *process* and *plot* data
downloaded from the US National Highway Traffic Safety Administration’s
[Fatality Analysis Reporting
System](https://www.nhtsa.gov/research-data/fatality-analysis-reporting-system-fars)
about fatal injuries suffered in motor vehicle traffic crashes in the
US.

## Installation

You can install the development version of CourseraBuildingRPckg from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("Capucine0210/CourseraProject")
```

## Functions

There are two main functions to process and plot FARS data:

-   `fars_summarize_years()` summarizes FARS report accidents by month
    and year in a tibble

-   `fars_map_state()` plots all accident locations for a given year on
    a US federal state map
