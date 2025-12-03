# Race and ethnicity and the risk of community-acquired third-generation cephalosporin-resistant uropathogens: a systematic review and meta-analysis

This repo contains the analyses and visualizations conducted as part of this study.

### Data
Risk ratios and standard errors are provided in the file, "effect_measures.xlsx"
Risk ratios were either provided by studies or calculated in Excel using raw case counts provided in the studies.
Standard errors were calculated in Excel using provided or calculated risk ratios.

### Meta-Analysis
After conducting a systematic review, four studies were included in the meta-analyses. Three meta-analyses were conducted, each including 3-4 studies. Meta-analyses examined the risk between Hispanic/Latinx persons vs. White persons, Black/African American persons vs. White persons, and Asian persons vs. White persons, respectively. Hispanic/Latinx persons were found to be at significantly higher risk of community acquired third-generation cephalosporin-resistant uropathogens compared to White persons.

#### Forest Plots
The following forest plots were created to visualize the pooled effect measures of each meta-analysis.

##### Hispanic/Latinx persons & White persons
<img width="1000" height="700" alt="hw_forest_plot" src="https://github.com/user-attachments/assets/68e8c8f9-eee6-4b96-9c35-20e41cef7d25" />

##### Black/African American persons & White persons
<img width="1000" height="700" alt="bw_forest_plot" src="https://github.com/user-attachments/assets/2a1ca773-c8ad-4e3d-ba32-a10a343c4f32" />

#### Asian persons & White persons
<img width="1000" height="700" alt="aw_forest_plot" src="https://github.com/user-attachments/assets/8ec7a43d-d84f-43c9-a24b-4d29e3bfe3d0" />

Meta-analysis code is provided in "meta_analysis_code.rmd"
An HTML file of the code is provided in "meta_analysis_html.html"
Analyses and visualizations were conducted in R.

### Publication
This study was published in _Antimicrobial Stewardship and Healthcare Epidemiology_ and is cited below.

Balaji S, Blackmon S, Avendano EE, et al. Race and ethnicity and the risk of community-acquired third-generation cephalosporin-resistant uropathogens: a systematic review and meta-analysis – CORRIGENDUM. Antimicrobial Stewardship & Healthcare Epidemiology. 2025;5(1):e232. doi:10.1017/ash.2025.10143
