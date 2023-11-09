![title](https://github.com/mtinti/VSG_single_cell/blob/main/wcar.png)


# Single Cell analysis of Antigen Expression in the African Trypanosome

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10061206.svg)](https://doi.org/10.5281/zenodo.10061206)



![title](https://github.com/mtinti/VSG_single_cell/blob/main/vsg_single_cell.png)

# Code Supporting *An allele-selective inter-chromosomal protein bridge supports monogenic antigen expression in the African trypanosome* 

## Affiliation

    Wellcome Centre for Anti-Infectives Research
    School of Life Sciences, University of Dundee

## Instructions

    The analysis has been performed in a Python Jupyter Notebook with the rpy2 package to call R functions. 
    The environment for the Jupyter Notebook is saved in env.txt.
    The R packages used are listed in sessionInfo.txt.

    For each experiment, we have two replicates:
    VEX1_RNAi_1 & VEX1_RNAi_2 (RNA interference for VEX1)
    VEX2_RNAi_1 & VEX2_RNAi_2 (RNA interference for VEX2)
    VSG-2_1 & VSG-2_1 (VSG2 expression analysis)
    VSG-2_VSG-6_1 & VSG-2_VSG-6_1  (VSG2 and VSG6 expression analysis, control for doublets)

    Each experiment tag corresponds to a folder ( with the Cell Ranger Software outputs, not provided
    just a placeholder) and Jupyter Notebook (with the analysis code). The notebooks with the "merge" tag
    analyse the replicated experiments together.

    
