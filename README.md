# English-to-Spanish-translator-using-Transformer-model-in-Deeep-Learning

**All the packages which is required for this project:**

1.Numpy

2.Tensorflow 

3.Keras

4.Random

5.Pathlib

6.re(Regular Expression)

7.GPU

**Dataset for this project is provided in this repositories in the format of zip file**

**To convert the text data into vectorize format i used text vectorixzation layer from keras this method convert the text into integer sequences where each integer represents the index of a word in a vocabulary.** 


Architectur of transformer model:
![image](https://user-images.githubusercontent.com/93418572/142771401-e0e16e73-682d-43ba-9811-993330cb97c7.png)


**Model Description:Transformer model consists of a TransformerEncoder and a TransformerDecoder and to provide proper order to vectorize data there is PositionalEmbedding  is also there.The TransformerEncoder consists of 1 multihead attention layer,1 feed forward neural network and 2 normalization layer while TransformerDecoder consists of 2 multihead attention layer, 1 feed forward neural network and 3 normalization layer.**


**According to above image of transformer model similar model is created in this project,after training the model during testing the model gaved 90 percent accurate result which is quite good because i trained the model only for 10 epochs and getting this much accuracy in the result is great this basically indicate that transformer model is good and transformer based model is best for this type of projects,But we can make this result more accurate by replacing multihead attention layer of encoder with fft2d(fourier transformation)layer no need to make any change in decoder.**



**Dataset Zipfile link:http://storage.googleapis.com/download.tensorflow.org/data/spa-eng.zip**
