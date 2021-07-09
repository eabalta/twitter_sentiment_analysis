# **Twitter Sentiment Analysis**
___

NLP Project for AI Methods class. <br>
The project purpose detecting sexist/racist tweets on Twitter. 
*   Used Frameworks and Versions
    *   Numpy       1.19.5
    *   Pandas      1.1.5
    *   Matplotlib  3.2.2
    *   TensorFlow  2.5.0
    *   PIL         7.1.2
    *   NLTK        3.2.5
    *   WordCloud   1.5.0
    *   TextAugment 1.3.4
* Dataset : <a href="https://www.kaggle.com/arkhoshghalb/twitter-sentiment-analysis-hatred-speech">Twitter Sentiment Analysis
Detecting hatred tweets, provided by Analytics Vidhya</a>
* The dataset is an **unbalanced dataset**, so we used an augmentation framework which is TextAugment.
  * Before the augmentation
    * ![Unbalanced Data](./unbalanced.png)
  * After the augmentation
    * ![Balanced Data](./balanced.png)
* Models' Accuracy Metrics<br><br>
| Models | binary_accuracy |  loss  | val_binary_accuracy: | val_loss | test_binary_accuracy | test_loss |
|:------:|:---------------:|:------:|:--------------------:|:--------:|:--------------------:|:---------:|
|  First |      0.9600     | 0.1041 |        0.9492        |  0.1359  |        0.9430        |   0.1384  |
| Second |      0.9682     | 0.1592 |        0.9502        |  0.2086  |        0.9519        |   0.2286  |