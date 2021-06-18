# Coursera-IBM

## Predicting the fake news

Now a days there is a huge market of fake news. fake news and other types of false information can take on different faces. They can also have major impacts, because information shapes our world view.

we make important decisions based on information. So if the information we saw on the Web is false, we won’t make good decisions. So this project will helps us to detect wether the news is fake or true. 
The deep learning techniques and python libraries like numpy, pandas and tensorflow makes it more easy and powerfull.

## Synopsis

The Project involves the following tasks to be carried out:

1) Data Collection
2) Data prepration 
3) Data Analysis
4) Data Visualisation
5) Feature selection
6) Feature engineering
7) Modeling
8) Evaluation and Prediction


## Requirements

1) Keras
2) Tensorflow
3) Pandas
4) Numpy
5) tqdm
6) scikit-learn
7) matplotlib
8) seaborn

## Modeling

The model Is a RNN (recurrent Neural Net) LSTM (Long short term memory). we have use the keras sequential API and start with an embedding layer. An embedding layer stores one vector per word. When called, it converts the sequences of word indices to sequences of vectors. These vectors are trainable. After training (on enough data), words with similar meanings often have similar vectors.

The tf.keras.layers.Bidirectional wrapper can also be used with an RNN layer. This propagates the input forward and backwards through the RNN layer and then concatenates the output. This helps the RNN to learn long range dependencies.



## Files

1) The project file(.ipynb)
2) Dataset
3) Readme
4) ADD (Architectural Decisions Document)
5) Project Presentation can be found https://youtu.be/VLEJGIWa51Y

## Dataset

1) The Dataset can be downloaded from here: https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset
