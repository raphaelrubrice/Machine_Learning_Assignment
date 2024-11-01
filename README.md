# AP_PROG Machine Learning Assignment
Created for the evaluated assignment of the AP_PROG Machine Learning course at AgroParisTech given by Mr. Vincent GUIGUE. The details of the asisgnment are given [here](https://github.com/vguigue/tuto_sklearn) (in french). 

In the present repository you will find the html rendered versions of my notebooks for the Classification task I decided to investigate and another for the Regression task I chose. I also made available the actual notebooks for anyone wanting to play with the data and further investigate the problem themselves.   
**You will need to download specified datasets by yourself as they are too heavy to be shared on github.**   

_**Note that these notebooks take quit some time to run and they produce big intermediary files so you may not want to run them if you do not have time / sufficient memory available.**_

#### These notebooks were made using :
- numpy 1.26.4
- pandas 2.2.2
- random
- pickle
- matplotlib 3.9.2
- seaborn 0.13.2
- sklearn 1.5.2
- umap-learn 0.5.6
- optuna 4.0.0 
- shap 0.45.1

### Classification task : Predicting tissue of extraction of B cells.
The goal is to use single-cell RNAseq profiles to predict the tissue from which each B cell was extracted. In the dataset I chose, we have 9 heavily unbalanced classes which we try to predict. I found the dataset on the awesome [Tabula Sapiens Database](https://tabula-sapiens.sf.czbiohub.org/). 

### Regression task : Predicting Life expectancy.
For this problem, the task was to be able to accurately predict Life expectancy based on health and economy factors. The dataset can be found [here on Kaggle](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who).
