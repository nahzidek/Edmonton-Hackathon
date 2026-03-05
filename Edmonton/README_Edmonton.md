# XYZ Project Data

## Overview

Provide a brief overview of the project/data and its significance/purpose. Explain what this dataset contains and what its focus is (e.g., demographic analysis, police complaints, etc.).

## Data Sources

*   **Source**: Primary or secondary, public or proprietary data
    *   Details, e.g., years covered, specific datasets and a [link](example.com) if possible
    *   List specific datasets.

*   **Source**: Primary or secondary, public or proprietary data
    *   Details, e.g., years covered, specific datasets and a [link](example.com) if possible
    *   List specific datasets.

## Data Processing & Cleaning

Explain the data cleaning process if relevant to the project and/or data. 

If the data was cleaned or processed, mention the need or added benefit of doing so.

Example:
1.  **Standardization**: Column X was standardized ....
2.  **Filtering**: Description of filtering.

## Data Structure

An overview of all data available so the participants can get up to speed quickly.

Use the example below to give an overview of either each file/folder individually or as a collection.

Example: 
The data is organized as follows:

*   `Raw Data/`: This folder contains data taken from US Census, NYPD, etc.
    *   `Subfolder`: This subfolder containes only the data for ...
        *   This folder contains multiple files for multiple quarters
    *   `File.xls`: This file contains X data taken from [a specific website](example.com)
*   `Cleaned Data/`: This folder contains the cleaned data.
    *   `Subfolder`: This subfolder containes a few csv files
        *   `RandomData2020.csv`: Random data from 2020
        *   `RandomData2021.csv`: Random data from 2021
        *   `RandomData2022.csv`: Random data from 2022
    *   `Subfolder`: This subfolder containes a lot of files
        *   A one sentence overview as there are a lot of files
*   `Shapefiles/`: This folder contains shapefiles. (No need to list all .shp, .sbx files individually)
    *   `parcel_boundary_xyz`: Parcel boundary for xyz
    *   `building_footprints_121`: Buidling footprints
*   `Notebook.ipynb`: This python notebook contains code for ...


## Data Dictionary

For any specific files created by you, if a data dictionary can help the participants, please provide it in this format. For secondary data (taken from NYC Open Data or similar sources), the data dictionary would already be present on the source website. So, no need to add that.

| Column Name | Description | Notes |
| :--- | :--- | :--- |
| `Column Name` | Description of the column | Any specific notes |
| `Column Name` | Description of the column |  |

## Use Cases and Inspiration

A few use cases to inspire the participants.

1.  **Use Case**: Description of a possible analysis or visualization.
2.  **Idea**: An idea for an app or dashboard.
3.  **Hard Problem**: A hard problem which is solvable for the duration of the hackathon.
