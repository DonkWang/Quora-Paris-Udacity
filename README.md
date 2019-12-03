# Quora-Paris-Udacity
graduation project of Udacity
## required package
*gensim*,
*fuzzywuzzy*,
*textblob*,
*nltk*,
*tqdm*,
*sklearn*,
*scipy*,
*keras*,
*tensorflow*,
*wordcloud*,
## required hardware
* GPU(Tesla P100-PCIE-16GB) on Google Colab
* at least 15GB disk space and 12GB memory
* windows10
## running notes
1. traning time may cost 1 whole day. (details in jupyter notebook)
2. model running results

Model|Train_acc|Train_loss|Val_acc|Val_loss|LB_score|Train_time|Predict_time
|-|-|-|-|-|-|-| 
|Base_LR (no embedding)|0.8740|0.1830|0.9280|0.1950|0.17459|3.5min|5s

Base_LR	0.8714	0.1849	0.9304	0.1875	0.16837	7.1min	13s
Siamese-LSTM(optimized)	0.9021	0.1606	0.9395	0.1707	0.15672	37.7min	84s
Siamese-BiLSTM	0.9065	0.1523	0.9374	0.1759	0.16177	121.0min	182s
Siamese-CNN_ARC-I	0.8854	0.1703	0.9303	0.1867	0.17054	45.1min	26s
Siamese-CNN_ARC-II	0.8739	0.1848	0.9304	0.1881	0.18381	38.2min	74s
