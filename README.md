# Paper data

### Data and code to reproduce our results ###

ml_predictions.ipynb - jupyter notebook with our code. the cells can be executed in order from top to bottom. The notebook was already pre-run, and the expected outputs are visible. The only requirement are for the data files to be in the same directory as the jupyter notebook file. The runtime should not exceed a couple of minutes, even on a standard laptop

training_data_activity.xlsx - 	The activity (A) was calculated using the formula A = tot. Cl conversion WelO5* mutant / tot. Cl conversion WelO5* GAP (tot. Cl conversion= (SIM1a + SIM1b) / (SIM1a + SIM1b + SIM1c + SIM1)); the sequence of the mutant is shown as a three letter code (e.g. WelO5* V81_A88_I161 = VAI)

training_data_selectivity.xlsx 	- The selectivity (S) was calculated using the formula S = (SIM1a – SIM1b) / (SIM1a + SIM1b); the sequence of the mutant is shown as a three letter code (e.g. WelO5* V81_A88_I161 = VAI)

t_scale.xlsx	- Table with amino acid descriptors, used as features for the machine learning algorithms, from "T-scale as a novel vector of topological descriptors for amino acids and its application in QSARs of peptides" [1].

table_Aa_phys_char.xlsx 	Table with additional amino acid properties, used as features for the machine learning algorithms from ''Role of Different Pfcrt and Pfmdr-1 Mutations in Conferring Resistance to Antimalaria Drugs in Plasmodium falciparum'' [2].


[1] Tian, F., Zhou, P. & Li, Z. T-scale as a novel vector of topological descriptors for amino acids and its application in QSARs of peptides. ‎J. Mol. Struct. 106–115 (2007). doi:10.1016/j.molstruc.2006.07.004

[2] Ibraheem, Z. O., Abd Majid, R., Noor, S. M., Sedik, H. M. & Basir, R. Role of Different Pfcrt and Pfmdr-1 Mutations in Conferring Resistance to Antimalaria Drugs in Plasmodium falciparum. Malar. Res. Treat. (2014). doi:10.1155/2014/950424


# System Requirements

### Hardware requirements ###

To run this code and reproduce our results, only a standard computer is required.

### Software requirements ###

We installed the anaconda python distribution from: https://www.anaconda.com/products/individual and followed their download instructions.
The specific versions we used for our analysis were:

Python 3.7.4  
1.16.5 numpy  
1.1.5 pandas  
0.21.3 sklearn  

