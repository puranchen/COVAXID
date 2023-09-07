# COVAXID

## Overview
The COVAXID clinical trial (EudraCT: 021-000175-37, clinicaltrials.gov: NCT04780659) was launched at Karolinska University Hospital to address the knowledge gap concerning immune responses to SARS-CoV-2 mRNA vaccination in individuals with primary and secondary immunodeficiencies. This GitHub repository serves as a resource for all projects associated with the COVAXID Clinical Trial. It houses documentation, database schema, data analysis code, and figure-reproduction scripts pertinent to published studies. Collaborators on COVAXID-related initiatives are encouraged to contribute relevant materials to this repository. While the original data is not freely available, it can be made accessible upon formal request, subject to necessary approvals and data sharing agreements (see below). However, for transparancy and reproducability, the data preprocessing steps, analysis and database updates can all be accessed through this repository - and following full access to the original data can be used in a end-to-end pipeline to reproduce all figures and analysis, as well as for auxilliary analysis. 

## Table of Contents
- *Getting Started
- Database Schema
- Data Analysis and Figures
- *Installation
- *Usage
- Data sharing
- *Contributing
- *License
- *Acknowledgements

* = To be added...
  
## Database Schema
For detailed information on the database schema, please refer to our separate Schema Documentation.

## Data Analysis and Figures
This section describes Python script to reproduce the data analysis and figures in the listed publications. 

Paper 1: Chen et al. Real-world assessment of immunogenicity in immunocompromised individuals following SARS-CoV-2 mRNA vaccination: a one-year follow-up of the prospective clinical trial COVAXID. eBioMedicine 2023;94: 104700

Publications/Paper_1/
* 'analysis_script.py': Python script for initial data analysis
* 'figure_generation.py': Python script to reproduce figures used in publication
* 'database_update.py': Python script that handles all updates of the database

## Data sharing
Data requests are submitted to principal investigator of the COVAXID clinical trial, Soo Aleman, MD, PhD <soo.aleman(at)regionstockholm.se>.
