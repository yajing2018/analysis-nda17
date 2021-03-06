## A collection of analysis scripts for NDA-17

The NDA-17 interim data release contains data for the first 4,524 participants of the Adolescent Brain, Cognitive Development study. This repository contains a collection of scripts developed at ABCD's Data Analysis and Informatics Center (DAIC, UC San Diego) to process data that is part of the first public interim data release of ABCD.

The data for this release can be downloaded from NDA using a pre-generated package "ABCD-RELEASE-1" using the Download Manager tool provided by NDA. Place the data into the data folder of this project.

#### Create a single data spreadsheet
 - [Merge individual spreadsheets (using R)](notebooks/general/merge_data.md)
 - [Recover categorical variables (using R)](notebooks/general/categorical_extension.md)

#### Create a single data dictionary
 - [Merge individual data dictionaries (using R)](notebooks/general/merge_data_dictionaries.md)

#### Recode values
 - [Impute missing core demographic variables (using R)](notebooks/general/impute_demographics.md)
 - [Recode some core demographic variables (using R)](notebooks/derived/core_demographic.md)

#### Interpretation of quality control information
 - [Quality control metrices for image data (using R)](notebooks/derived/image_qc.md)

Let us know if you have a script that you think should be part of this project.
