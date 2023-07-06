# Drug-interaction-prediction

### Data preprocessing:
[MASSC.ipynb](https://github.com/nemoliu1103/Drug-interaction-prediction/blob/main/MACCS.ipynb): 
This file generates MACCS encoding for drugs.<br />

Input: 
file with SMILES<br />
Output: 
SMILES and MACCS encoding for each drug

[Encoding Map (Deeppurpose).ipynb](https://github.com/nemoliu1103/Drug-interaction-prediction/blob/main/Encoding%20Map%20(Deeppurpose).ipynb): 
This file generates Deeppurpose encodings for proteins/drugs.<br />
For more information on deeppurpose encodings you can check out here: https://github.com/kexinhuang12345/DeepPurpose <br />
You will need to clone the DeepPurpose directory first before running this code.<br />

Input: file with SMILES/protein sequence<br />
Output: file containing drug/protein encoding

### Drug-drug interaction model
[drugdrug.ipynb](https://github.com/nemoliu1103/Drug-interaction-prediction/blob/main/drugdrug.ipynb):
This file generate protein-drug interaction features for drugs and predict drug-drug interaction.






