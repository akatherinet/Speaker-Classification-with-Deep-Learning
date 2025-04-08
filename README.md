**Speaker Classification with Deep Learning Project**

This project identifies a speaker from a set of speakers based on a given speech sample using a variety of deep learning techniques (CNNs and LSTMs) with up to 88% accuracy.  

Data:  the Accents of the British Isles (ABI-1) Corpus, 284 speakers in total with an average of three recordings of several minutes each per
person

The best performing model used visual geometry group (VGG) architecture
which stacks two or more convolutional and activation layers
before every MaxPooling layer. The learning rate used was 0.005 with three dropout layers, early stopping with patience of 20, 150 epochs, and a batch size of eight, achieving an F1 score of 0.88.
