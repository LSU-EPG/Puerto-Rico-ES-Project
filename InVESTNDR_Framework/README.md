## InVEST NDR Validation R Script

---

#### General Description:
Sub Title: A framework for validating watershed ecosystem service models 
using United States long-term water quality data: Applications with the InVEST Nutrient Delivery (NDR) model in Puerto Rico.

Authors: Valladares-Castellanos M, De Jesus Crespo R,  Xu J, Douthat T*

*Corresponding Author
  
Reference: "Valladares-Castellanos M, De Jesus Crespo R,  Xu J, Douthat T. 2024. A framework for validating watershed ecosystem service models 
using United States long-term water quality data: Applications with the InVEST Nutrient Delivery (NDR) model in Puerto Rico. Science of the Total Environment. https://doi.org/10.1016/j.scitotenv.2024.175111"

version date: "May 2025"

Github: "https://github.com/LSU-EPG/Puerto-Rico-ES-Project/blob/main/InVESTNDR_Framework/InVEST%20NDR%20Validation%20R%20Script.Rmd"

#### Overview:
We propose a framework divided into three stages to validate InVEST Nutrient 
Delivery Ratio Model (NDR) estimates for water quality purposes. The first stage 
overviews running the NDR model inputs, processes, and outputs. The second stage
describes building a long-term reference dataset from open-source water quality 
observations. Finally, the third stage focuses on the InVEST model calibration 
and validation using the reference data calculated in Stage 2. To facilitate the 
workflow implementation, we described the process of developing Stage 2 and 
Stage 3 in this R script template, “InVEST NDR Validation R Script.” We provided 
a framework implementation example using the Commonwealth of Puerto Rico as a 
case study. Stage 1 of the workflow described takes place in the InVEST workbench, 
which is available for download at the Natural Capital Project data repository (https://naturalcapitalproject.stanford.edu/software/invest/invest-downloads-data). 
Furthermore, this workflow uses the dataRetrieval package to download NWIS and 
WQP data; for more information about this package, review the dataRetrieval 
documentation (https://cran.r-project.org/web/packages/dataRetrieval/vignettes/dataRetrieval.html).
Finally, we focused on data sources available in the United States; therefore, 
if used outside of the U.S., the user should contemplate comprehensive adjustments 
in the data parameters and units that might be required. 

#### Additional notes:
The headings of the template match the workflow stages of the accompanying article.
Refer to the article for a detailed explanation of each section. Each code chunk 
describes the R code template, followed by an application example (represented in 
each chunk as an "_eg" object).

Finally, before using the script we suggest to download the supporting .csv files
used for the example sections (EPA PointSource Pollution by HUC12, InVEST_MS_Pexp, HUC12_MS),
and save them in the working directory along with the R script.
