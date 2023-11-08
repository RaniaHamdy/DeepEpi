# DeepEpi
deep learning framework to predict gene expression from histone modification using variation model of LSTM and CNN with aid of attention mechanism
# Reference Paper
[DeepEpi: Deep Learning Model for Predicting Gene Expression Regulation based on Epigenetic Histone Modifications] ([https://www.eurekaselect.com/article/119403](https://www.eurekaselect.com/article/133816?utm_source=TrendMD&utm_medium=cpc&utm_campaign=Current_Bioinformatics_TrendMD_0))

__variation convolutional models__

* CNNLSTM
* CNNLSTM_att
* ConvLSTM

The DeepEpi found that CNNLSTM_att proposed model get the highest between the models AUC score with an average of 0.8887. 

# Dataset 
DeepEPI used datase from Roadmap Epigenomics Mapping Consortium (REMC) database from the Roadmap Epigenomics Projects. The original dataset can be downloaded from this [repository](https://egg2.wustl.edu/roadmap/web_portal/processed_data.html).
The dataset used after preprocessing from another previous work mentioned in the paper and can be downloaded from this [repository](https://github.com/ly-zhu/CRNN-gene-expression-with-histone-modifications)




# Running The Model Script

you can try see [DeepEpi](https://github.com/RaniaHamdy/DeepEpi/blob/main/DeepEpi.ipynb) architecture  

# Citation
Hamdy Rania*, Omar M.K. Yasser and Maghraby A. Fahima, DeepEpi: Deep Learning Model for Predicting Gene Expression Regulation based on Epigenetic Histone Modifications, Current Bioinformatics 2023; 18 () . https://dx.doi.org/10.2174/1574893618666230818121046
