# Easy Algorithm: How to explain an algorithm to a layman. (ongoing)

I want to help you learn and understand algorithms **as simple as possible, as less words as possible, but they must be correct and reproducible!**

Only by:
- the name of the algorithm (you will know what algorithm you will be familiar with).
- the core idea of the algorithm (you will understand the mechanism underlying the algorithm, and some of them will be given a scratch-implementation version).
- an application (you will know how to use this algorithm in one task).

### You can understand this as a tool, which help you use the algorithm in your research.
### Correct and Reproducible!

## :grinning: Implement a Neural Network (one input layer, one hidden layer with two nodes, one output layer) from the scratch only via Numpy/Pandas
1. [This is a hand-written report that explains how the neural network works.](NN.ipynb)
   - This is a comprehensive neural network tutorial that covers all aspects of the topic.
   - You only need to be familiar with +-x/ and derivative calculation.
   - We will go through:
        - **Forward propagation** process with **activation function (sigmoid and softmax)** in the hidden layer and in the output layer.
        - **Backward propagation** process with **derivative calculation** and **cross-entropy of each parameter (weight and bias)***.
        - **Update each parameter (weight and bias) simultaneously**.
2. [This is a classification example.](Nerual_Network_from_scratch_4features_3classification.ipynb)
   - Dataset: Iris dataset with 4 features and 3 classifications
   - Implement 
     - data pre-processing (one-hot encode), 
     - forward propagation,
     - backward propagation,
     - activation functions, 
     - cross-entropy (loss calculation), 
     - derivative calculation, 
     - update parameters (weight and bias) simultaneously, 
     - training model on the train dataset, 
     - prediction in the test dataset, 
     - accuracy calculation on the test dataset 
   - from the scratch only via ```Numpy``` and ```Pandas```.
    
## 

## Time-series analysis
1. [ARIMA_shampoo_sales_prediction](Time_series_prediction_shampoo_sales_via_ARIMA.ipynb)
2. [DNN_house_price_prediction](Time_series_prediction_shampoo_sales_via_DNN.ipynb)

## Image analysis
1. [CT_lung_segmentation_CNN](CT_lung_segmentation_CNN.ipynb)
2. [Medical_Image_Classification_via_CNN](Medical_Image_Classification_via_CNN.ipynb)

## Optimization/Decision-making
1. [GA_in_Tune_Hyperparameters_example](GA_in_Tune_Hyperparameters_example.ipynb)

## Text mining
1. [NLP_supervised_classify_topic_of_documents](NLP_supervised_classify_topic_of_documents.ipynb)
2. [Twitter_sentiment_analysis_using_Word2vec_bi-LSTM](Twitter_sentiment_analysis_using_Word2Vec_bi-LSTM.ipynb)
