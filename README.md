# Edmonton-Hackathon

## Overview

Develop a Safe Cities-inspired platform for Edmonton, Alberta’s Blueprint for Violence Prevention. The platform would serve as a tool to help understand dispersed data sets from
multiple sectors and identify the most pressing violence-related problems in Edmonton, their main determinants, and the evidence-based solutions needed to address these issues.

## Data Sources

*   **Source**: Edmonton Emergency Departments, Primary, Proprietary data
    * 2018-2025
    * Violence/Harms by category of violence/harm, age group, and year.

## Data Processing & Cleaning

1.  **Filtering*: In Cleaned Sheet 1, the other category in the VIOLENCE/HARM column was filtered out because it is not a known variable

## Data Structure

The data is organized as follows:

*   `Edmonton Extra Resources & Potential Datasets/`: This folder contains data sources from many of Edmonton's partners to explore more crime/related data(Use only as needed)
    *   `BVP Indicator Framework for Local Needs Assessment (CUSM Inventory) - For Hackathon`: This file contains datasets from many crime/related sources, as well as definitions of safety terms. I recommend only using the datasets tab in this excel and not get caught up trying to go through it all. 
    *   `CREWS Preliminary Findings - Edmonton`: This file contains graphs on terrorism and hate on vulnerability and other factors in Edmonton
    *   `Data-Driven Prioritization for Edmonton’s Blueprint for Violence Prevention`: This document provides a summary of the background, current state, and data opportunities for the upcoming urban informatics hackathon. It should serve as a foundational reference.
    *   `Harm-Related Injuries Among Young People Visiting`: This pdf contains data and insights on ED visits from harm-related injuries
    *    `Population Level Data on Violence in Edmonton`: This Excel contains data sources for  Population Level Sources on Violence
*   `City of Edmonton Violence and harms Data for Hackathon`: This raw Excelsheet contains data on emergency department visits by location, count, and type of harm/violence
*   `Cleaned_Edmonton`: This dataset contains emergency department visits by location, count, and type of harm/violence. Other is filtered out of the Harm/Violence category.


## Use Cases and Inspiration

A few use cases to inspire the participants.

1.  **Use Case**: Map the violence/harm category by location and allow users to toggle the data by counts
2.  **Idea**: Create a dashboard with several sources showing different graphs on the same factor, like vulnerability or type of violence done
3.  **Hard Problem**: Figure out which factors are most useful to showcase on a dashboard+ combines several sources. Another option is to standardize all the data from different sources and create a process for the standardization, and create a dashboard with the combined data.
