## Using machine learning for long-term calibration and validation of water quality ecosystem service models in data-scarce regions 

---

#### General Description:

Authors: Valladares-Castellanos M, de Jesús Crespo R, Douthat T*

*Corresponding Author
  
Reference: "Valladares-Castellanos M, de Jesús Crespo R, Douthat T. 2025. Using machine learning for long-term calibration and validation of water quality ecosystem service models in data-scarce regions. Science of the Total Environment (Accepted)."
version date: "August 2025"

Github:https://github.com/LSU-EPG/Puerto-Rico-ES-Project/tree/main/Data_Scarcity_Framework

#### Overview:

We propose a methodological framework to address partial spatial and temporal data scarcity in the application of ES models. 
We demonstrate the approach using the InVEST NDR model in Puerto Rico as a case study. To support replication and broader 
applicability, we provide the complete set of R and Python scripts in the project’s GitHub repository and as Supplementary Material 1 in the manuscript. 
The framework comprises four sequential stages (Figure 1): (1) classification of the study area based on hydrogeological 
watershed characteristics relevant to the ES model of interest; (2) the selection of reference watersheds based on data availability, 
and temporal data gap filling using machine learning (Script 1); (3) calibration (Script 2) and validation (Script 3) of the InVEST NDR model in reference watersheds 
via an automated, iterative parameter evaluation procedure; and (4) the application of validated model parameters to quantify and map water quality ES in 
data scarce watersheds (Script 4). This approach is designed for regional-scale applications, particularly where the study area consists 
of multiple watersheds with heterogeneous data availability.

#### Scripts Included:

1. Script 1 (R script): Evaluating Spatio-Temporal Data Scarcity in Water Quality Monitoring
2. Script 2 (Python script): InVEST NDR Iterative Model Execution
3. Script 3 (R script): ES Model Calibration and Validation using the Reference Watersheds
4. Script 4 (Python script): Transfering ES model validated parameters to data-scarce watersheds
