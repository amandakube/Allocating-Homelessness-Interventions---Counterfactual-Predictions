# Allocating-Homelessness-Interventions---Counterfactual-Predictions
This repository holds OOS counterfactual predictions based on the BART model described in Kube et al. 2019

## Attribution
If you plan to use this data, we ask that you cite the following paper:

> Kube, A., Das, S., & Fowler, P. J. (2019, July). Allocating interventions based on predicted outcomes: A case study on    homelessness services. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 33, pp. 622-629).

Which can be found here: https://www.aaai.org/ojs/index.php/AAAI/article/view/3838

## Description of the Data
The csv file contained in this repository consists of 13940 rows and 6 columns. Each row represents a homeless household. 
The variable named Original represents the homeless service the household was assigned to by caseworkers (the factual allocation). 
The variable named Outcome has two potential values, 1 or 0. A value of 1 indicates that the houshold was in need of more homeless services within 2 years after exiting the system. A value of 0 indicates no need for services within those 2 years (the ideal outcome). 
The rows labeled ES, TH, RRH, and Prev give the counterfactual prediction for whether or not that household would ened services again within 2 years if they had been allocated to that intervention. ES stands for Emergency Shelter, TH Transitional Housing, RRH Rapid Rehousing, and Prev stands for Homelessness Prevention.

