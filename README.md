# BCB546-PythonHW_Spring2025

The repository for this assignment contains the following files: 

1. original files folder (containing cytochrome-b sequences of penguin species & csv file containing penguin species info)
2. original python script from Dr. X (colleague)
3. complete & annotated python script in Jupyter Notebook format (.ipynb)
4. generated_figs_files folder (containing all figures and files generated in the .ipynb script)


## Content of python script: 

### Modules needed
* SeqIO from Bio
* CodonTable from Bio.Data
* pandas
* numpy


### Main purpose of script: 
* translates cytochrome-b sequences to amino acids for each of 12 species of penguins
* computes simple summaries of the amino-acid molecular weight and GC content of these sequences (adds these values to a DataFrame)
* plots for data visualization


### Generated functions:
1. get sequences function: reads in fasta file; extracts DNA sequence with species name
2. string-translate function: translates nt seq to corresponding amino acid sequence using the Vertebrate Mitochondrial Codon Table
3. alternate string_translate function: alternate version of function 2 using biopython
4. compute AA molecular weight function: calculates the molecular weight of an AA sequence using Biopython's `ProteinAnalysis`
5. GC content analysis function: calculates the GC-content of a DNA sequence (proportion of guanine (G) and cytosine (C) bases in the sequence)


### Generated figures/files list
1. Average Adult Body Mass by Penguin Species (bar plot)
2. Molecular Weight vs GC Content (dot plot)
3. `penguins_mass_cytb.csv` (new DataFrame containing additional columns)
4. Top 10 Most Common Amino Acids (bar plot)
5. Amino Acid Composition per Penguin Species (stacked bar plot)