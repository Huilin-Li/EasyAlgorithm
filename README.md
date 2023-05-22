# Easy Algorithm: (ongoing)

I want to build a community where people can understand, use, and extend basic algorithms **as simply and concisely as possible, while ensuring that they are correct and reproducible**. This means that there are no fancy words, lengthy introductions, or meaningless descriptions. We will get straight to the core point.

**I hope this work can help you use the algorithm in your work.**

## Tasks
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

<details>
    <summary>:star_struck: Image Classification (binary classification) via CNN in TensorFlow. </summary>

- [Medical Image Classification (Normal vs Pneumonia)](https://www.kaggle.com/code/huilinli/medicalimageclassification-normalvspneumonia/edit)
</details>


<details>
    <summary>:yum: Text mining. </summary>

- [NLP supervised classify topic of documents](NLP_supervised_classify_topic_of_documents.ipynb)
- [Twitter sentiment analysis using Word2vec bi-LSTM](Twitter_sentiment_analysis_using_Word2Vec_bi-LSTM.ipynb)

</details>



## Tips
<details>
<summary>Some Math and Plot Tips:</summary>

[Math & Plot tips](some_math_plot_tips.ipynb)
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
