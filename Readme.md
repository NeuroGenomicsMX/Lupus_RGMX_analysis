Readme

This projec run analysis for the preprint intitled: "Lupus RGMX: Demographic and clinical characteristics of Systemic Lupus Erythematosus in a Mexican Cohort."

# Data sets

Database is integrated by three data sets.

**DATA_2023-01-05_0147_Complete_db_patients_under_SLE_medication_5.csv** 

Contains the entire anonymized RedCap database of participants with lupus who are undergoing lupus treatment, or are taking corticosteroids. This control was carried out with a cutoff in RedCap on January 5, 2023. 

In addition, based on the script titled *01_Finding_duplicated_registries_from_LupusRGMX.Rmd*, duplicated registries were discarded, keeping the replica that had the most completed registry. This script was run locally on the liigh.

**DATA_2023-01-05_0147_Complete_db_controls_from_RedCap.csv**

Contains the entire anonymized database of lupus controls that registered in RedCap up to January 5th, 2023.


**DATA_2023-01-13_twin_control_lupus.csv**

Contains participants from the TwinsMX project, who will be compared against lupus patients, this database was provided by TwinsMX team on January 13th, 2023.


Repository: <https://github.com/NeuroGenomicsMX/Lupus_RGMX_analysis.git>