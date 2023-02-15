# MIMIC Data Exploration; Understanding the prevalence of chronic diseases in the presence of various physiological conditions amongst ICU admitted patients

### Scope of the Project

#### To explore MIMIC data and understand the prevalence of chronic diseases in the presence of various physiological conditions amongst ICU admitted patients.

## Project Overview
#### To understand the impact of various physiological and anatomical factors on the prevalence of Chronic diseases in patients with history of sepsis or requiring mechanical ventilation (and not vasopressers) on first day of ICU admission. It briefly highlights the overall impact on SAPS and SOFA score under such conditions, where patient is on Indwelling Arterial Catheter when in ICU. Existence of such conditions help in predicting 28-day mortality based on the SAPS score or SOFA. 

## Project Objective
### This report will highlight results from data analysis to find the following:
    1. Chronic disease prevalance according to gender,
    2. Impact of vital paramateres on chronic diseases,
    3. Impact on Hospitalization days depending on the number of chronic diseases in a patient,
    4. SOFA score predicting mortality, for various age groups,
    5. Impact on SOFA score due to platelet count.

#### The above objectives would be achieved by exploring the dataset with patient population having underlying condition: 
    - ICU admitted patients
    - History of sepsis
    - patients not requiring vasopressers
    - patients requiring mechanical ventilation of first day of ICU admission
    - patient is on Indwelling Arterial Catherters (IAC)
    
### About the dataset

 Indwelling arterial catheters (IACs) are used extensively in the ICU for hemodynamic monitoring and for blood gas analysis. IAC use also poses potentially serious risks, including bloodstream infections and vascular complications. In 2015, Hsu et al published a study to assess whether IAC use was associated with mortality in patients who are mechanically ventilated and do not require vasopressor support. This dataset was created for the purpose of a case study in the book: Secondary Analysis of Electronic Health Records [1], published by Springer in 2016. The dataset in question was used throughout Chapter 16 (Data Analysis) by Raffa J. et al. [2] to investigate the effectiveness of indwelling arterial catheters in hemodynamically stable patients with respiratory failure for mortality outcomes. The dataset is derived from MIMIC-II, the publicly-accessible critical care database. It contains a summary of clinical data and outcomes for 1,776 patients. The dataset (full_cohort_data.csv) is a comma-separated value file that includes a header with descriptive variable names. 

#### To Access the dataset
Clinical data from the MIMIC-II database for a case study on indwelling arterial catheters. Accessed on: 1st February 2022 [3]. https://physionet.org/content/mimic2-iaccd/1.0/ 

### Questions addressed

The questions we foresee to answer from this dataset:


    1. Chronic disease prevalence according to gender.
         -Liver
         -Kidney
         -Heart
 
    2. Impact of clinical indicators on the occurrence of chronic diseases in patients.
        a. Stating causation of creatinine levels on renal disease.
        b. Hemoglobin count of patients having Congestive heart failure

    3. Correlation between total number of chronic diseases a person has versus the number of days in hospitalization and also the number of days in ICU.

    4. How does the number of patients with chronic diseases in each age group affects:
        the SAPS score on ICU admission leading to ICU mortality
        The SOFA score leading to ICU mortality

    5. Explore SOFA score by understanding platelet count effect on SOFA score
    
### Impact on the real-world
##### Addressing Triple Aim

**Improving the experience of care - **
Healthcare organizations might consider utilizing a greater portion of the facilities for patients with worsen physiological conditions.

**Improving the health of population - **
Analysis of physiological and anatomical factors leading to chronic diseases can help diminish the chances of deteriorating conditions.

**Reducing per capita costs of healthcare - **
As a preventive measure, providing medical attention and care earlier to a vulnerable population will lead to less cost injection in the later deteriorating stages.

### Strength & Weakness of Data

#### Strengths:
    1. Reliable dataset – MIMIC is reputed and open data source for medical data
    2. Extensive – incorporating many attributes (~46 columns)
    3. Meaningfulness - Data dictionary is self-explanatory
    4. Completeness – Less missing values

#### Weakness of your dataset
    1. Less instances – 1776 rows depicting 1776 patients
    2. Validity – source is unknown
