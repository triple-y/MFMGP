```
                               / $$$$$$       / $$$$$$
                              / $$$_ $$$     / $$$_ $$$
                             / $$$  \ $$$   / $$$  \ $$$
                            / $$$    \ $$$ / $$$    \ $$$
                           / $$$      \ $$$$$$$      \ $$$
                          / $$$        \_____/        \ $$$
                         / $$$                         \ $$$
                        |___/                           \__/ 
                        
                                /$$$$$$$$$$$$$$$$$$$       
                               | $$$$$$$$$$$$$$$$$$$ 
                               | $$$$_____________/
                               | $$$$  
                               | $$$$$$$$$$$$$$$$$
                               | $$$$___________/  
                               | $$$$   
                               | $$$$  
                               | $$$$  
                               |___/
                        
                               / $$$$$$       / $$$$$$
                              / $$$_ $$$     / $$$_ $$$
                             / $$$  \ $$$   / $$$  \ $$$
                            / $$$    \ $$$ / $$$    \ $$$
                           / $$$      \ $$$$$$$      \ $$$
                          / $$$        \_____/        \ $$$
                         / $$$                         \ $$$
                        |___/                           \__/ 
                        
                                _/ $$$$$$$$$$$$$$$
                              _/ $$$$$$$$$$$$$$$$$
                            _/ $$$$$____________/
                          _/ $$$$$
                         | $$$$$              | $$$$$$$$$$$$$
                         | $$$$$              | $$$$$$$$$$$$$
                         | $$$$$               \__  $$$$$    
                         | $$$$$                 _| $$$$$    
                          \_ $$$$$              / $$$$$    
                            \_ $$$$$$$$$$$$$$$$$$$$$        
                              \_ $$$$$$$$$$$$$$$$$
                                \_______________/
                        
                                /$$$$$$$$$$$$$$$$
                               | $$$$$$$$$$$$$$$$$$ 
                               | $$$$$$$___  $$$$$$$$
                               | $$$$$$$   \_ $$$$$$$$
                               | $$$$$$$   |__ $$$$$$$$ 
                               | $$$$$$$   /_ $$$$$$$$ 
                               | $$$$$$$  / $$$$$$$$
                               | $$$$$$$$$$$$$$$$$$
                               | $$$$$$$$$$$$$$$ 
                               | $$$$$$$ 
                               | $$$$$$$ 
                               | $$$$$$$  
                               |______/  
```

## MFMGP: An integrated machine learning fusion model for genomic prediction

#### The Multiple Machine Learning Fusion Model for Genomics Prediction (MFMGP) is a fusion model developed based on a variety of machine learning approaches with Bayesian optimization for optimal hyperparameter selection. MFMGP was designed to combine the advantages of high prediction accuracy and computational efficiency, which has been tested and demonstrated for its applications in genomic selection breeding on 34 traits of large datasets from five species (rice, wheat, maize, cotton, and pig). MFMGP has proven to have high prediction accuracy, especially for traits with low heritability, when compared to seven traditional, machine and deep learning models. The software of MFMGP for interactive GS analyses was made available at website: https://www.biohuaxing.com/#/MFMGP.



> #### Required dependency package  
> pip install sys  
> pip install time  
> pip install numpy  
> pip install pandas  
> pip install sklearn  
> pip install scipy  
> pip install skopt  
> pip install lightgbm  
> pip install xgboost  

- #### Run command  
```python
python3 script/MFMGP.py Heading_date.geno.csv Heading_date.phe.csv >output.txt
```

- #### MFMGP website  
https://www.biohuaxing.com/#/MFMGP

- #### Variant data of rice  
https://3kricegenome.s3.amazonaws.com/snpseek-dl/3k-pruned-v2.1/pruned_v2.1.bed
https://3kricegenome.s3.amazonaws.com/snpseek-dl/3k-pruned-v2.1/pruned_v2.1.bim
https://3kricegenome.s3.amazonaws.com/snpseek-dl/3k-pruned-v2.1/pruned_v2.1.fam
https://3kricegenome.s3.amazonaws.com/snpseek-dl/3k-pruned-v2.1/readme_pruned-v2.1.txt

- #### Phenotypic data   
data/Rice phenotype 3k accessions.xlsx
