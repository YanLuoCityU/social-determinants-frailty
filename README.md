# Cross-national analysis of social determinants of frailty among middle-aged and older adults in the USA, England, and China

This is the code repository for the paper "Cross-national analysis of social determinants of frailty among middle-aged and older adults in the USA, England, and China". It contains directories for code and data.

## Directory
### code
- **0_package_installation**: For installing and configuring required packages and dependencies for the project.
- **1_analysis**: Main folder for data analysis, containing different modeling approaches.
  - **ga2m**: Contains data modeling based on GA2M method, with 3 Jupyter notebook files (*.ipynb) for CHARLS, ELSA, and HRS datasets.
  - **xgboost**: Contains data modeling using XGBoost algorithm, with R Markdown files (*.Rmd) for CHARLS, ELSA, and HRS datasets.
- **2_visualization**: For data visualization files and scripts that display analysis results graphically.

### data
- **raw**: original data files obtained from the [offical website](data\raw\README.md) of each cohort.
- **processed**: processed data files.

## System requirements
All codes were originally processed using:

- System hardware:
  - R version 4.1.1 (2021-08-10)
  - Platform: x86_64-w64-mingw32/x64 (64-bit)
  - Running under: Windows 10 x64 (build 19045)
&nbsp;
- Software:

| name_version | name_version | name_version |
|---------|---------|---------|
| broom_1.0.5 | dials_1.2.1 | doParallel_1.0.17 |
| dplyr_1.1.4 | forcats_1.0.0 | foreach_1.5.2 |
| ggplot2_3.5.0 | ggpubr_0.6.0 | ggrepel_0.9.5 |
| ggtext_0.1.2 | gridExtra_2.3 | gtsummary_1.7.2 |
| haven_2.5.4 | infer_1.0.6 | iterators_1.0.14 |
| lubridate_1.9.3 | missRanger_2.4.0 | modeldata_1.3.0 |
| parsnip_1.2.0 | patchwork_1.2.0 | purrr_1.0.1 |
| readr_2.1.5 | recipes_1.0.10 | reshape2_1.4.4 |
| rsample_1.2.0 | scales_1.3.0 | shapviz_0.9.3 |
| sjlabelled_1.2.0 | skimr_2.1.5 | stringr_1.5.1 |
| tibble_3.2.1 | tictoc_1.2 | tidymodels_1.0.0 |
| tidyr_1.3.0 | tidyverse_2.0.0 | tune_1.1.2 |
| utile.visuals_0.3.3 | VIM_6.2.2 | viridisLite_0.4.2 |
| workflows_1.1.4 | workflowsets_1.0.1 | yardstick_1.3.0 |
| boot_1.3-30 |  |  |

## License
This project is available under the MIT license.

## Contact
Yan Luo - luo.yan@my.cityu.edu.hk