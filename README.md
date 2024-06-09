## Final Project Folder
# Project Overview
Course work for EPI 203: Methods for Reproducible Research
Task: Final Project
Created: June 2024
Course term: Spring 2024, Stanford University 

#Project and Folder Descriptions
Data Folder Includes:
- Original data ("raw-data" used in analysis), see "Cohort Description" below for more information
Original Data Repository: <https://github.com/MethodsForReproducibleHealthResearch/Assignment7.git>

Analysis Folder Includes:
- Quarto file with annotated code ("Final_Project_Quarto_Bowman_RR.qmd")
- Quarto report and references produced from Quarto file ("Final_Project_Quarto_Bowman_RR.pdf" and "references.bib")

- Renv folder, which stores "activate.R" for activation, "library" which contains current packages used in project, and "settings.json" for current preferences/settings
- Renv.lock which includes package metadata for re-installation 
- .Rprofile for configuration to project settings
R-Environmental functionality: <https://rstudio.github.io/renv/articles/renv.html>

#Cohort Description:
There were 5,000 observations in this database, 4810 of which did not have an incident myocardial infarction. Approximately 66% of individuals who had a myocardial infarction reported annual out-of-pocket care costs of >$9950, compared to 21.4% of individuals without an incident myocardial infarction documented. The majority of individuals with a myocardial infarction did not have a history of smoking (59.5%); a finding that was shared with the myocardial infarction group (91.0%). There were more male participants in the myocardial infarction group than females (90.0%). Finally, the mean age across both myocardial infarction and non-myocardial infarction groups was approximately 40 years.

# Package Versions at time of Creation
packageVersion('table1'):‘1.4.3’ 
packageVersion('arsenal'):‘3.6.3’
packageVersion('tidyverse'):‘1.3.2’
packageVersion('dplyr'):‘1.1.4’
packageVersion('rmeta'):‘3.0’

# Software Versions at time of Creation
R version 4.2.2 (2022-10-31)
Platform: x86_64-apple-darwin17.0 (64-bit)
Running under: macOS Monterey 12.6

Matrix products: default
LAPACK: /Library/Frameworks/R.framework/Versions/4.2/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] rmeta_3.0       forcats_0.5.2   stringr_1.5.0   dplyr_1.1.4     purrr_1.0.1     readr_2.1.3    
 [7] tidyr_1.3.0     tibble_3.2.1    ggplot2_3.5.1   tidyverse_1.3.2 arsenal_3.6.3   table1_1.4.3   