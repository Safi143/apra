[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4726194.svg)](https://doi.org/10.5281/zenodo.4726194)

# APRANK

**APRANK** is an Antigenic Protein and Peptide Ranker. 

**APRANK** is a bioinformatics pipeline that can:
  1) be run to rank candidate antigens and epitopes from a pathogen proteome; or 
  2) be used with curated antigenicity information to generate and train new models. 

## Using APRANK

To download the files needed to run APRANK as a predictor, go to [***/aprank***](https://github.com/trypanosomatics/aprank/tree/main/aprank) and follow the instructions. You will also need to download the corresponding protein and/or peptide models from [Dryad](https://doi.org/10.5061/dryad.zcrjdfnb1).

## Retraining APRANK

If you want to train APRANK with new species, or if you want to recreate our models from scratch, go to [***/model-development***](https://github.com/trypanosomatics/aprank/tree/main/model-development). This retraining runs the first half of APRANK to parse data from the organisms, so APRANK is needed.

## Citing APRANK

If you find APRANK useful, please cite:  
APRANK: Computational Prioritization of Antigenic Proteins and Peptides From Complete Pathogen Proteomes (2021). Alejandro D Ricci, Mauricio Brunner, Diego Ramoa, Santiago J Carmona, Morten Nielsen, Fernán Agüero. Front Immunol. 12: 702552.  
[DOI: 10.3389/fimmu.2021.702552](https://doi.org/10.3389/fimmu.2021.702552). [PMID: 34335615](https://pubmed.ncbi.nlm.nih.gov/34335615/). [PMCID: PMC8320365](http://www.ncbi.nlm.nih.gov/pmc/articles/pmc8320365/). 

### Quick links

FASTAs from the organisms used to train APRANK: [***aprank/model-development/01_inputs/***](https://github.com/trypanosomatics/aprank/tree/main/model-development/01_inputs)

Antigens from bibligraphy for the organisms used to train APRANK: [***aprank/model-development/11_antigens/***](https://github.com/trypanosomatics/aprank/tree/main/model-development/11_antigens)

The same antigens after expanding antigenicity via BLAST and kmer expansion: [***aprank/model-development/11_antigens/expanded_antigens***](https://github.com/trypanosomatics/aprank/tree/main/model-development/11_antigens/expanded_antigens)
