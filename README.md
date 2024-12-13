# Fong_ENV872_FinalProject
ENV872 Environmental Data Exploration - Final Project - Vicky Fong (Fall 2024)

## Summary
Project Title: Spatial and Temporal Distribution of Cownose Rays (Rhinoptera bonasus) in North Carolina

Why: Cownose rays are classified as a "Vulnerable" species on the IUCN Red List. Local populations in North Carolina have declined due to negative interactions with commericial shellfish fisheries. Minimal research has been conducted to investigate recent distributions of cownose rays in North Carolina.

Project Goals: This project aims to investigate the spatial and temporal distribution of cownose rays in North Carolina using open-source data.

## Investigator
Vicky Fong, Master of Environmental Management student

Nicholas School of the Environment, Duke University

Contact: vicky.fong@duke.edu

## Keywords
cownose rays, spatial, temporal, distribution, North Carolina

## Database Information
OBIS-SEAMAP (https://seamap.env.duke.edu/species/160985)
- Open-source database on sharks, rays, turtles, seabirds and marine mammals 
- 32,922 records from 66 datasets (government, academic, and private institutions) globally

## Folder structure, file formats, and naming conventions
Folders
- Data/Raw: original datasets
- Data/Processed: cleaned datasets
- Code: R markdown files for each step of data pipeline and final project page, HTML of final project page, images included in final project page

File naming convention: Fong_ENV872_FinalProject_[DescriptiveName]

## Metadata
obis_seamap_species_160985_points.csv (only the following columns were used in this analysis)
- latitude, longitude: location of sighting
- group_size: number of individuals observed
- date_time: date and time observed


## Scripts and code
Fong_ENV872_FinalProject_DataProcessing.Rmd (Code for data processing and cleaning)
Fong_ENV872_FinalProject_DataExploration.Rmd (Code for initial data exploration)
Fong_ENV872_FinalProject_DataAnalysis.Rmd (Code for data analysis)
Fong_ENV872_Project.Rmd (Code for final project page)
Fong_ENV872_Project.html (Final project page)