## Final Project Folder
# Project Overview
Course work for EPI 203: Methods for Reproducible Research
Task: Final Project
Created: June 2024
Course term: Spring 2024, Stanford University 

# Project and Folder Descriptions

Data Folder Includes:
- Original data ("raw-data" used in analysis), see "Cohort Description" below for more information
Original Data Repository: <https://github.com/MethodsForReproducibleHealthResearch/Assignment7.git>

Analysis Folder Includes:
- Quarto file with annotated code ("Final_Project_Quarto_Bowman_RR.qmd")
- Quarto report and references produced from Quarto file ("Final_Project_Quarto_Bowman_RR.pdf" and "references.bib")

- Renv folder, which stores "activate.R" for activation, "library" which contains current packages used in project, and "settings.json" for current preferences/settings
- Renv.lock which includes package metadata for re-installation 
- .Rprofile for configuration to project settings

File Uses and Renv Instructions:
R-Environmental functionality: <https://rstudio.github.io/renv/articles/renv.html>
- To use renv functionality, open Analysis.Rproj and call renv::restore() in local machine

# Cohort Description:
There were 5,000 observations in this database, 4810 of which did not have an incident myocardial infarction. Approximately 66% of individuals who had a myocardial infarction reported annual out-of-pocket care costs of >$9950, compared to 21.4% of individuals without an incident myocardial infarction documented. The majority of individuals with a myocardial infarction did not have a history of smoking (59.5%); a finding that was shared with the myocardial infarction group (91.0%). There were more male participants in the myocardial infarction group than females (90.0%). Finally, the mean age across both myocardial infarction and non-myocardial infarction groups was approximately 40 years.

# Package Versions at time of Creation
packageVersion('table1'):‘1.4.3’ 
packageVersion('arsenal'):‘3.6.3’
packageVersion('tidyverse'):‘2.0.0’
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
[1] stats     graphics  grDevices datasets  utils     methods   base     

other attached packages:
 [1] yaml_2.3.8      rmarkdown_2.27  rmeta_3.0       lubridate_1.9.3 forcats_1.0.0   stringr_1.5.1   dplyr_1.1.4    
 [8] purrr_1.0.2     readr_2.1.5     tidyr_1.3.1     tibble_3.2.1    ggplot2_3.5.1   tidyverse_2.0.0 arsenal_3.6.3  
[15] table1_1.4.3   

loaded via a namespace (and not attached):
 [1] pillar_1.9.0      compiler_4.2.2    tools_4.2.2       digest_0.6.35     evaluate_0.23     timechange_0.3.0 
 [7] lifecycle_1.0.4   gtable_0.3.5      pkgconfig_2.0.3   rlang_1.1.4       cli_3.6.2         rstudioapi_0.16.0
[13] xfun_0.44         fastmap_1.2.0     withr_3.0.0       knitr_1.47        generics_0.1.3    vctrs_0.6.5      
[19] hms_1.1.3         grid_4.2.2        tidyselect_1.2.1  glue_1.7.0        R6_2.5.1          fansi_1.0.6      
[25] Formula_1.2-5     farver_2.1.2      tzdb_0.4.0        magrittr_2.0.3    MASS_7.3-60       htmltools_0.5.8.1
[31] scales_1.3.0      colorspace_2.1-0  renv_1.0.7        labeling_0.4.3    utf8_1.2.4        stringi_1.8.4    
[37] munsell_0.5.1 