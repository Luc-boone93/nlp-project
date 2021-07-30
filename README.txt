Description of the repository

requirements.txt file:
- requirements file contains all packages necessary to run the code


'work' folder:
- Contains the 3 Jupyter notebooks. 
   * DTM_paragraph: Code for making a dynamic Topic Model for the United Nation Speeches Corpus
   * LDA_models_paragraph_final: Code for making  static Topic Model for the United Nation Speeches Corpus
   * bigram_trigram_speeches : Code related to making bi_trigram phrasers for the data preprocessing in the main code files.
- The pretrained LDA(static) models can be found for every decade in the folders 70s-2000s 
- The DTM_model files contain additional BoW files, indeed someone wants to replicate the exact study
- The bigram_trigram_speeches_model folder contains the files needed if the user wants to use a pre-trained phraser

Note: due to the vast size of the DTM model, a pre-trained version is  not available on github (The model had a 500mb size).
Note2: the DTM model takes 30-40hours to run on a standard computer. If a user is interested, you can always contact me, and I will provide a download link for the already trained DTM model. 

