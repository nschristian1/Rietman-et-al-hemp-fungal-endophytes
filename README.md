# Rietman-et-al-hemp-fungal-endophytes

This is the code and data repository for the paper: Hemp microbiome composition and function under developing pest management solutions 

Please see GenBank (accession numbers PQ427211-PQ427268) for information on our consensus sequences. 

Authors: Allison Rietman, Lucia Amani, Connor Morozumi, Nicole Gauthier, and Natalie Christian. 

# Scope 
We investigate how fungicide application and pathogen inoculation impact the endophytic leaf microbiome of field-grown hemp. We also conduct a challenge assay to test the possibility of utilizing a hemp-isolated fungal endophyte as a biological control against corn earworm. 

# Data 

This repository contains multiple data sets: 
+ pivot table containing a tabulation of all isolated and identified fungal species: 'otu_matrix_S1_seaquencher.csv'
+ environmental data: 'new_env_S21_fungicide.csv'
+ plant growth metric data: 'plant-growth-metrics-S21.csv'
+ bacteria abundance data: 'new_bacteria_abun_S21.csv'
+ corn earworm choice trial data, which denotes food preference at time of observation: 'ChoiceTrialData_CornEarwormOR.csv'
+ corn earworm choice trial food mass data: 'ChoiceTrialData_FoodMass.csv'
+ corn earworm survival trial data: 'LevelsTrialData_CornEarwormOR.csv'
+ subset of corn earworm data used for Cox Regression analysis: 'cox_cornearnworm.csv'

# Code Overview 
We've combined all code into one R Notebook titled 'master_code_hemp_microbiome_CNM.Rmd' which consists of: 

Fungicide-Pathogen Inoculation Trial
1. Endophyte community analysis
2. Diversity metric analysis
3. Indicator species analysis
4. Bacterial abundance analysis
5. Visual presence of pathogen infection analysis

Biological Control Trial
1. Choice trial analyses
2. Survival trial analysis
