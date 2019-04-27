# Sentiment-Analysis
#### Introduction
In general, Sentiment Analysis is about determining attitudes. Some of the common uses of sentiment analysis are for understanding customer's intent, preferences and feedback. Recent developments in the areas of machine learning, AI, and natural language processing are the driving force behind increasing use of sentiment analysis for a large range of applications.

In this project I create the machine learning model which can classify positive and negative result of the sentence by using word2vec and LSTM. enjoy it 🙂

![](https://formtitanhelpdeskimage.s3.amazonaws.com/70c78f9df2fd5c130e7021644f78f4c5.jpg)
### Setup
**Make sure you have the following is installed:**
- Python3
- Tensorflow
- NumPy
- SciPy
- Pandas
- Matplotlib

### Dataset
for the dataset please make sure your training data .txt file is like following:

| Sentence  | Class  |
| ------------ | ------------ |
|  I like this movie! | 1  |
| I hate this feeling.  |  0 |
|............... | ..|

### Pipline

The following is the project pipline:
![](https://github.com/Jakelee24/Sentiment-Analysis/blob/master/Pipline.png?raw=true)

### Run

Once you prepared the training data, you can simply by execute the **example.py** to run the whole pipline.
```shell
python example.py
```
Or If you want to run the pipline step by step, please make sure you prepared the needed dataset for each module, Please check the Pipline chart to find it out. 

```shell
python word2vec_module.py
python DataProcess_module.py
python LSTM_module.py
```




