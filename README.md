# Fake-News-Classifier
model is implemented using the bidirectional LSTM in RNN .This model is trained using the kaggle fake news classifier dataset
In this initially we preprocessing the data like removing the special charecter from the data,stopwords removel,and stemming the data
after that we converting each and every word in the  sentence is one hot encoded the padding is done to make the length of all the senetence to be same
after that we embedding the data of the length 40 and then returing the vector of each sentence in the length of 32 
on top of this Bidirectional LSTM is applied with 100 nodes
