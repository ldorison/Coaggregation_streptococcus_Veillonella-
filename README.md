# Supplementary information relative to the article: 
# Identification of V. parvula and S. gordonii adhesins mediating co-aggregation and its impact on physiology and mixed biofilm structure

File S1 and S2 contain transcriptomic information (gene, annotation, Log2Fold, and P-value or list of significative comparisons) for both _V. parvula_ and _S. gordonii_ 

### File S1 contains the data concerning _V. parvula_ present on 6 different sheets: 
- Genes_specific_coculture: contains all genes dysregulated in **all co-culture** conditions
- specific_aggregation_coculture: contains all genes dysregulated in all co-culture **with some type of aggregation** conditions
- genes_specific_noaggregation_c: contains all genes dysregulated in all co-culture **with no aggregation** conditions
- All_genes_with_important_logfol: contains all genes dysregulated in **at least one condition.**
- raw_data: Contains the raw RNA-seq data. 
- gene_correspondance: correspondance to the genes and their different annotations.

### File S2 contains the data concerning _S. gordonii_ present on 3 different sheets: 
- Genes_specific_coculture: contains all genes dysregulated in **all co-culture** conditions
- All_genes_with_important_logfol: contains all genes dysregulated in **at least one condition.**
- raw_data: Contains the raw RNA-seq data. 

### file S3 contains the parameters calculated for each image in BiofilmQ. 
- Condition: pair of bacteria present in the image
- Experiment: replicate number (exp1, 2 or 3) 
- unique_id_well : unique identifier of the image
- column and row: column and row localisation within the plate
- image number: corresponding to one of the four set position in each well.
- channel:  BacGO or Syto61, corresponds to the imaging channel.
All other columns contain the information of parameters calculated by BiofilmQ. See https://drescherlab.org/data/biofilmQ/docs/ for more information. 
