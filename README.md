# cancer-cell-line-mhc-alleles

In 2015, Jelle Scholtalbers and Sebastian Boegel published a useful database of cell line MHC alleles and MHC ligand predictions 
in a paper called [TCLP: an online cancer cell line catalogue integrating HLA type, predicted neo-epitopes, virus and gene expression](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4653878/) 
with an accompanying website at [http://celllines.tron-mainz.de](http://celllines.tron-mainz.de). 

Unfortunately, the website is currently down. In case anyone needs this data, I've parsed a snapshot of the "neoepitope catalog"
(predicted MHC ligands arising from cell line specific mutations) and extracted from it the MHC alleles for each cell line. These 
should match the alleles in TCLP, unless some alleles by chance had no predicted strong MHC ligands. 

Also, the original neoepitope catalogue appears to contain some duplicate fields which make it harder to parse, so I have included
a "fixed" version of the CSV in this repository. 

**Caution**: The HLA types extracted for the "neoepitope catalog" do not always match of all the alleles listed in the earlier 2014 paper [A catalog of HLA type, HLA expression, and neo-epitope candidates in human cancer cell lines](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4355981/). I don't know the source of discrepancy but looking at that paper it does seem that the neoepitope catalog included in their supplement has the same alleles as this repository. 
