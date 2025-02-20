# NHS Outcomes Framework - Indicator 2.2: Employment of People with Long-Term Conditions

## Overview

This document provides details about Indicator 2.2 of the NHS Outcomes Framework, which focuses on the employment of people with long-term health conditions in England. The indicator measures the difference in employment rates between the general working-age population and people of working age who report having a long-term condition.

## Key Objectives

*   To improve employment rates for people with long-term health conditions.
*   To monitor and reduce the employment gap between this population and the general population in England.

## Data Source

*   **Primary Source:** Labour Force Survey (LFS) data, published by the Office for National Statistics (ONS).
*   **Release Frequency:** Quarterly data released approximately three months after the end of the relevant quarter.
*   **Link to Data:** [ONS Labour Market Statistics](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/employmentandemployeetypes/bulletins/uklabourmarket/previousReleases)

## Indicator Calculation

1.  **Employment Rate (General Population):**
    *   **Denominator:** Total number of people of working age (16-64) in England.
    *   **Numerator:** Number of working-age people in employment (including employees, self-employed, participants in government employment programs, and unpaid family workers).

2.  **Employment Rate (People with Long-Term Conditions):**
    *   **Denominator:** Total number of working-age people who report having a long-term health condition (expected to last more than a year).
    *   **Numerator:** Number of working-age people with long-term conditions who are in employment.

3.  **Indicator Value:** The difference between the employment rate of the general population and the employment rate of people with long-term conditions (expressed as a percentage point difference).

## Data Filters

*   Data is filtered to include only respondents residing in England.

## LFS Variables Used

*   **MF1664:** Indicates working age (16-64).
*   **INECAC05:** Indicates employment status (employee, self-employed, etc.).
*   **LNGLST:** Indicates if a respondent has a health problem or disability that is expected to last more than a year (used from 2013 Q2 onwards).
    *   **Note:** Prior to 2013 Q2, **LNGLIM** was used instead of LNGLST.

## Data Weighting

*   The Labour Force Survey (LFS) data is weighted using person-level weights. The specific weight variable changes over time as follows:
    *   Q1 2006 - Q4 2010: PWT10
    *   Q1 2011 - Q2 2014: PWT11
    *   Q3 2014 - Q4 2015: PWT14
    *   Q1 2016 - Q4 2016: PWT16
    *   Q1 2017 - Present: PWT17

## Data Breakdowns

The data is disaggregated by the following variables:

*   **Gender (SEX)**
*   **Age (AGE)** (banded)
*   **Ethnicity (ETH01 to end 2010, then ETH11EW)**
*   **Region (GOVTOF)**
*   **Unitary Authority/Local Area (UALA)**
*   **NS-SEC Category (NSECM10)**
*   **Religion (RELIG to end 2010, then RELIGE)**

## Time Period

*   Quarterly data is available from 2006 onwards.

## Presentation

*   Data is presented at the England level and for various breakdowns:
    *   Demographic: Gender, age bands, ethnicity, NS-SEC category, and religion.
    *   Geographic: England, regions, and unitary authority/local area levels.

## Disclosure Control

*   Statistical disclosure control is applied to the LFS data by ONS. Data is suppressed where sample sizes are small to protect individual privacy. Any estimates based on a sample size of 1 or 2 are suppressed and secondary suppression is carried out.

## Output Columns

The output data includes the following columns:

*   Year, Quarter, Period of Coverage
*   Person Level Weight used
*   Breakdown (e.g. England, Gender, Age)
*   Level (a further description of breakdown)
*   Employment rate of people with long-term conditions (percentage)
*   Employment rate of population (percentage)
*   Indicator value (percentage point difference)
*   Long-term condition numerator (number of people)
*   Long-term condition denominator (number of people)
*   Population numerator (number of people)
*   Population denominator (number of people)

## Notes and Definitions

*   Users should be aware that estimates based on sample sizes below 10,000 are subject to a high degree of sampling variability.
*  Data is rounded.
*  The indicator values are calculated using unrounded employment rates.
*  Data is suppressed due to small numbers (marked with *).
*  There are notes about errors associated with "Not classified or inadequately stated" in the NS-SEC variable, which have been removed for Quarters 1 and 3 of 2011.
*   A "Don't know/Refused" category has been added to the Ethnicity and Religion breakdowns from Quarter 3 of 2014.

## Contact Details
*   **Author:** Clinical Indicators Team, NHS Digital
*   **Responsible Statistician:** Sally Jones
*   **Public Enquiries:** Telephone: 0300 303 5678, Email: enquiries@nhsdigital.nhs.uk
*   **Press Enquiries:** Telephone: 0300 303 3888

## References
* NHS Outcomes Framework - February 2020 publication: https://digital.nhs.uk/data-and-information/publications/statistical/nhs-outcomes-framework/february-2020

## License
*   You may re-use this document/publication (including logos) free of charge in any format or medium, under the terms of the Open Government Licence v3.0.

## Copyright
*  Copyright © 2020, Health and Social Care Information Centre. NHS Digital is the trading name of the Health and Social Care Information Centre.

This README provides an overview of the key information about the NHS Outcomes Framework Indicator 2.2 dataset.
