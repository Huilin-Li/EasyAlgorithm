# Easy Algorithm: (ongoing)

I want to build a community where people can understand, use, and extend basic algorithms **as simply and concisely as possible, while ensuring that they are correct and reproducible**. This means that there are no fancy words, lengthy introductions, or meaningless descriptions. We will get straight to the core point.

For example:
- the name of the algorithm (you will know what algorithm you will be familiar with).
- the core idea of the algorithm (you will understand the mechanism underlying the algorithm, and some of them will be given a scratch-implementation version).
- an application (you will know how to use this algorithm in one task).

**I hope this work can help you use the algorithm in your work.**

<details>
    <summary>:grinning: Implement a Neural Network (one input layer, one hidden layer with two nodes, one output layer) from the scratch only via Numpy/Pandas</summary>

   - [This is a complete report that explains how the neural network works from the very scratch.](Report_How_Neural_Network_Really_Works.ipynb)
        - This is a comprehensive neural network tutorial that covers all aspects of the topic.
        - You only need to be familiar with +-x/ and derivative calculation.
        - We will go through:
            - **Forward propagation** process with **activation function (sigmoid and softmax)** in the hidden layer and in the output layer.
            - **Backward propagation** process with **derivative calculation** and **cross-entropy of each parameter (weight and bias)**.
            - **Update each parameter (weight and bias) simultaneously**.
   - [This is a classification example.](Nerual_Network_from_scratch_4features_3classification.ipynb)
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
</details>

<details>
    <summary>:kissing: Digital Image Pre-Processing and pre-knowlegde</summary>
    
- [Digital Image Pre-Processing and pre-knowlegde](Digital_Image_Pre_Processing.ipynb)
    - Bit depth and Gray Levels (the specific value of each pixel)
    - ```skimage.io.imread``` read pictures as ```y,x,c``` where ```c``` is ```RGB``` 3 channels.
</details>
    

<details>
    <summary>:stuck_out_tongue: Convolution Neural Nework in One Image</summary>
    
- [Convolution Neural Nework in One Image.](Convolution_Neural_Nework_in_One_Image.ipynb)
</details>

<details>
    <summary>:slightly_smiling_face: Principle Component Analysis (PCA) from the scratch and via Sklearn</summary>

- [Principle Component Analysis (PCA) from the scratch and via Sklearn](PCA_from_scratch_and_via_Scikit_Learn.ipynb)
</details>


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




<details>
<summary>Some Math and Plot Tips:</summary>

[Some Math and Plot Tips](some_math_plot_tips.ipynb)
</details>

<details>
<summary>Notes:</summary>

[interesting notes](interesting_notes.ipynb)
</details>

<details>
<summary>Reference:</summary>

1. https://youtu.be/HGwBXDKFk9I
2. https://youtu.be/NItHNRc3awY
3. https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md
</details>
