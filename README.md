# Final Project - Team Neighborhood Watch

## The Team

* Toluwalase Ahmed - toa30@pitt.edu
* Joe Fayad - jof58@pitt.edu
* Benjamin Truckenbrod - blt37@pitt.edu

## About the Project

For our final project, we decided to look at each neighborhood in the city of Pittsburgh in order to find the best neighborhood. Specifically, we focused our research on the amount of crime, 311 calls and PLI violations that were reported/found. Our datasets listed different instances of these reports being filed with the neighborhood that each were located in. Using this information, we counted the amount of times a neighborhood was associated with these reports.

Datasets
* 311 Data - https://data.wprdc.org/dataset/311-data
* PLI Violations - https://data.wprdc.org/dataset/pittsburgh-pli-violations-report
* Crime Blotter - https://data.wprdc.org/dataset/police-incident-blotter

## Abstract:

Our metric is based on the percentage of reports for each neighborhood. We summed the amount of reports for eich neighborhood and then divided by the maximum to get a value between 0 and 1. Then we added all of the percentages together and found the neighborhood with the lowest scores. The lowest scores corespond to neighborhood with the lowest combined incidence of 311 calls, crime, and PLI violations. After the analysis, we found Arlington Heights had the lowest score. Thus it is the best neighborhood in Pittsburgh! 