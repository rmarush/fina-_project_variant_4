Business needs

 Automated analysis of students' academic performance and prediction of the risk of expulsion.
Requirements

    python 3.12.6
    
    numpy==1.26.1
    pandas==2.1.3
    sklearn==1.3.0
    matplotlib==3.8.1
    
Exploratory Data Analysis:

    To explore the dataset you can use the 1_lab.ipynb file.  
    It has general information on the dataset. 
    
Feature Engineering:

    To prepare your training dataset to be used you can use the 2_3_4_lab.ipynb file.  
    It will impute all missing data, encode categorical values.
    
Model Selection:

    To choose the best model for the dataset you can use the 2_3_4_lab.ipynb file.  
    There you can see a different metrics for the K-Nearest Neighbours, Naive Bayes and Random Forests models.
    Based on the Accuracy, F1 and Confusion Matrix, you can choose the best fitting option.

    To choose the hyperparameters which has the best metrics for the selected model you can use the 2_3_4_lab.ipynb file.  

Running:

    To predict the classes for a new dataset with created model you can use the predict.ipynb file.  

    After running the script will be generated <prediction_results.csv> 
    The file has 'class' column with the result value.


Training a Model:
    
     To train the model you can use the train.ipynb file.

    The model accuracy is 84%
    There is no fraud check.