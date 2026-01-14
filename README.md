# Analyzing NYC's 311 complaints handled by the NYPD.
Author: Abdelrahman Aggour

![Median Response Hours for Complaints by Neighborhood](plots/nyc_311_response_map.pdf)

## Table of Contents

## Introduction
Following recent discourse on equity in public services after New York City’s mayoral election, this study evaluates whether the New York City Police Department (NYPD) resolves service requests uniformly across boroughs.

In this project, I explored and analyzed NYC's 311 complaints handled by the NYPD. Specifically, I attempted to answer the following questions:

* Are certain complaints more common in some boroughs than others?
* Do response times differ by borough?
* Does the likelihood of police action differ by borough?
* Do complaint durations vary by mayoral administration?
* Do certain complaint types get resolved faster than others?

## Context

New York City, the largest city in the United States, has a population of approximately 8.48 million residents. It is divided into five administrative regions known as boroughs, each with its own distinct character and demographics. These boroughs are:
| Borough        | Population |
|----------------|------------|
| Brooklyn       | 2,617,631  |
| Queens         | 2,316,841  |
| Manhattan      | 1,660,664  |
| Bronx          | 1,384,724  |
| Staten Island  | 498,212    |

## Data

The data used in this project were obtained from NYC Open Data via two separate API calls, both restricted to 311 service requests handled by the New York City Police Department (NYPD). The first API call retrieved records created between January 1, 2020 and January 1, 2022, corresponding to the final years of Mayor Bill de Blasio’s administration. The second API call retrieved records created between January 1, 2022 and January 1, 2026, corresponding to the Eric Adams administration. While data from both periods were collected to provide context and enable comparison, the majority of the analysis in this project focuses on complaints handled during the Eric Adams administration.

## Statistical Analysis

### Data Distribution
The first thing that I looked at is the data distribution of the "duration in hours" column

![orignal data distribution](plots/op_hist_dist.pdf)


