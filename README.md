For using the 5-HT1A-LiCAs tool, download the file 5-HT1A-LiCAs-tool.ipynb and open in Google Colab. Upload the following files and run the script:
1. feature_selection_top100_artifacts.pkl
2. xgboost_tuned_label_encoder.pkl
3. xgboost_tuned_model.pkl

Requirements for using the tool 5-HT1A LiCAs:

Following libraries are required for running and using the tool:
1. pandas
2. numpy
3. rdkit-pypi
4. rdkit
5. xgboost
6. scikit-learn
7. joblib
8. Pillow
9. ipython

These libraries will be installed upon running the script but if error regarding libraries appears that library can be installed using the following command:
!pip install library name
for example: !pip install pandas

Upon succesful execution, the script will ask for a SMILE code of the drug of interest from the user, user needs to input the SMILE code of their desired drug. The user can enter multiple SMILES also one by one by pressing enter after every entry. In case the user wants to stop entering SMILES, user needs to press enter twice to stop entering SMILES.


Running Example:
Aripiprazole is an FDA approved rug for 5-hT1a receptor as an agnist. The SIMILE CODE of the drug is provided below.
ClC1=CC=CC(N2CCN(CCCCOC3=CC4=C(CCC(=O)N4)C=C3)CC2)=C1Cl

After runnin gthe script using the above guidelines, paste this SMILE code and the tool will predict it as an agonist.

