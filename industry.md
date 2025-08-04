---
layout: page
---

<div class="text-center">
  <h1>  Experiences in Industry </h1>
    </div>


<div class="text-center">
  <h3>  SANOFI | 3 months | Data Scientist </h3>
    </div>

### CONTEXT

Development of machine learning (ML) models combined with molecular features to characterize and identify novel lipid nanoparticle (LNP) components with enhanced properties, such as efficiency in delivering mRNA to cells (i.e. transfection efficiency), thermostability, and biodegradability.

### PROJECT DETAILS

* Provide an interactive platform (Streamlit application) to explore and visualize lipid data
   - Develop Generative AI algorithms for new lipid compounds
   - Integrate molecular dynamics and machine learning projects
      - Performance evaluation
      - Writing and Reviewing documentation
      - Implementation of models into the application

 * TECHNICAL ENVIRONMENT: Python, Streamlit, AWS, S3, Git

## Success:
   - Deliverables: Streamlit app and documentation

--------------------------------------------------------------------------
--------------------------------------------------------------------------
<div class="text-center">
  <h3>  SANOFI | 3 months | Data Scientist </h3>
    </div>

### CONTEXT

Implement functionality enhancements and bug fixes to MIDAS, a data visualization and consumption application used at the mRNA Center of Excellence.

### PROJECT DETAILS

* The Manufacturing Sciences team manages data relating to pre-clinical manufacturing, clinical manufacturing, and raw materials attributes, and performs data entry and verification of data generated during the manufacturing and testing of material. Once data is entered into the data system, the users access to these data into the application called MIDAS.
   - My project was to provide faster and improved accessibility to manufacturing data, through the MIDAS application:
      - List of functional improvements and bug fixes
          - Download all rows or selected rows (DataTable R package)
          - Process data bug, and clean up attribute names
          - Fixing the connection between the process step and the raw materials to enable a better analysis view
          - Ability to set the limits on the graphs
          - Ability to drill down into a specific line/batch to show
      - Code the improvements in Sandbox environment, which will be tested by Manufacturing Sciences prior to being pushed to the Production environment



 * TECHNICAL ENVIRONMENT: R, RShiny

## Success:
 - Deliverables: Documentation of new features and improved data visualization MIDAS

--------------------------------------------------------------------------
--------------------------------------------------------------------------
   
<div class="text-center">
  <h3>  SANOFI | 12 months | Biomarker statistician </h3>
    </div>


I am supporting the biomarker team of a pharmaceutical global company for early phase development.

### PROJECT DETAILS

* Exploratory analysis
   - Study of the Treg activation to validate a potential therapeutic target:
   - DNA-methylation analysis:
      - Checking for the activated state of Treg after treatment
      - Blood samples were collected for different timepoints (Line plots).
   - Assessment of methylation data as a substitute for flow cytometry to detect the modulation of cell types for the MOA of the drug.
      - Two markers used: CD4 and FOXP3
         - Correlation analysis
         - Statistical tests (t-test/Wilcoxon test)
            - Performed both blood and skin samples.
    - RNA-seq analysis
       - Preprocessing, filtering, and normalization (TMM)
       - Differential analysis with Limma
       - Signature analysis with GSVA
       - Deconvolution analysis with xCell and cibersort
       - Validation of interest signatures (Tregs)
       
* Data analysis
    - Statistical analysis plan, analysis, and reporting for genomic datasets:
  	- RNASeq, gene expression, Olink data (proteomics)
  	- Deconvolution analysis
    - Performed deconvolution analyses to evaluate the cell composition on different datasets.
       - Use of xCell and Cibersort methods
       - Benchmarked signature analysis methods on a toy dataset to select the best method for further analysis.
     - Comparison of GSVA, ssGSEA, singscore, and Z-score
        - Creation of plots to help with the validation of a method (heatmaps, boxplots)
     - Study of the deconvolution method: Cibersort
        - Assessment of the use of custom signature matrices with skin samples
        - Creation of plots to validate the signature matrix.
          
* Clinical activities
   - Contributed to the review of the biomarker section of study protocols.
   - Wrote in collaboration with other team members the SAP for biomarkers or to contribute with the clinical statistician for the clinical SAP for the biomarker part.
   - Development of the biomarker design:
      - Selection of the best statistical methods according to the rationale
      - Presentation of the Biomarker plan to the translational team of the study
   - Sample size calculation. 

* TECHNICAL ENVIRONMENT: R

## Success:
   - Deliverables: Rmarkdow reports, ppt presentation, visualizations


--------------------------------------------------------------------------
--------------------------------------------------------------------------


<div class="text-center">
  <h3>  SERVIER | 18 months | Biomarker Biostatistician and App developer </h3>
    </div>

I am supporting the biomarker team of a pharmaceutical global company for early phase development.

### PROJECT DETAILS

* Development of a ML model to predict human hepatoxicity of compounds (from tidymodels R package)
   - Benchmarking of different models of ML (Random Forest, Logistic model, XGBosost, NaiveBayes, SVM linear and stacking) using Cross-Validation and bootstrap approaches
   - Implementation of final best model (publication in progress)
   
* Creation of Rshiny application to predict human hepatoxicity of compounds
   - Development of a Shiny application for the Tox team to use the developed model to predict human hepatoxicity of new compounds easily
       - Discussion with the TOX team about the visualizations, outputs (plots, tables)
       - Updating functions of the RShiny application regarding the team’s feedback
       
* Exploratory analysis
   - Use of statistical methods to check the potential interest of biomarkers
         - Identification of gene signature and associated pathway to describe the treatment’s effect in immunology
   - Validation of interest signatures
         - Signature analysis in interest disease in immunology
   - Indication ranking in oncology
         - Behavior of interest signature in different Databases (such as TCGA and MET1000)
         
* Data analysis
    - Cytokines
     	- Performing both intra- and inter-donor analyses to compare the treatments and the environment setting in immuno-oncology
    - Deconvolution analysis in immune oncology
        - Performing deconvolution analyses to evaluate the cell composition on different datasets
        - Use of quanTIseq and MCPcounter methods
        - Considering only deconvolution MCPcounter results, for the treatment status (pre/post) and the response (responder/non-responder), then performing a wilcoxon test and changes, and adjusted p-values (FDR) are used to identify Cell types
        - Summarizing here the results of deconvolution analysis by dataset with heatmaps
    - Transcriptomics
    
* Machine Learning methods to categorize the responder patients in oncology
    - Use of tidymodels packages
    - Use of different methods such as:
        - Random Forests
        - XGBoost
        - Logistic model
        - Neural Network
        - SVM linear
        - Stacking models
    - Cross-validation and bootstrap approaches
    - Applied on mutation, clinical and PK datasets

* Upstream stages:
     - Presentation of survival analysis
     - Presentation of tidymodels package
     - Presentation of stacking methods

* Method comparison:
     - Deconvolution methods for the bulk RNA-seq and micro-array datasets
   
* Data analysis: Cytokines, RNA-seq, microarrays

* TECHNICAL ENVIRONMENT: R

## Success
   - Deliverables: Rmarkdow reports, ppt presentation, RShiny application
   - Successfully supported preclinical development phase:
      - Oncology - Solid Tumors: Anti-NKG2A
      - BCL-2 inhibitor + Mcl1 inhibitor (S64315) - S65487 - Acute Myeloid Leukemia
      - Autoimmune disease

