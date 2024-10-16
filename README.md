# Answering the 5 Ws of Epidemiology: 
## Who, What, When, Where and Why/How

### 1. Who - The patients
   * Clinical case distribution across ages

### 2. What - The clinical manifestations
   * Clinical case distribution and clinical outcome 
   
### 3. When - Time of the event
   * Temporal singal of clinical cases: Time series
  
### 4. Where - Geographical location
   * Spatial distribution of clinical cases

### 5. Why/How - Transmission paths
  * Identifying transmission food vehicles (Food sampling sources)

    

# epidemological-visualisations

"Receipt Date" is the sequence collection date.

Analysis that permits visualisation of the patterns, causes and effects of diseases. The code presented here has been applied to answer questions on *Listeria monocytogenes* however the same approach can be applied to investigate other pathogens.


# Input data structure
The analysis can work with any form of genomic classification and cluster intedification methods, however in this instance SNP-calling (column "SNP" in the human data file) was utilised and clusters were identified at a 5 SNP single linlage distance level (column "Cluster Level" in the human data file). 


![Github_clinical_datatable](https://github.com/user-attachments/assets/70c68cba-d327-44d3-90f7-044181049627)


![Github_food_datatable](https://github.com/user-attachments/assets/917ecc9f-e8fb-4e7d-95ef-3a873c1b3d16)
<sub>Examples of the data structure and data types are displayed within the jupyter notebook repository ("Epi_visualisations_Github.ipynb")</sub>



# Associated Publications
The script presented here has been used in the methodology underlying the results of these two publications:

[Genomic epidemiology of the clinically dominant clonal complex 1 in the Listeria monocytogenes population in the UK](https://www.microbiologyresearch.org/content/journal/mgen/10.1099/mgen.0.001155)


[![DOI](https://zenodo.org/badge/DOI/10.5281/mgen.0.001155.svg)](https://doi.org/10.1099/mgen.0.001155)


and


[Listeria monocytogenes: the silent assassin](https://www.microbiologyresearch.org/content/journal/jmm/10.1099/jmm.0.001800)

[![DOI](https://zenodo.org/badge/DOI/0.1099/mgen.0.001155.svg)](https://doi.org/10.1099/jmm.0.001800)


