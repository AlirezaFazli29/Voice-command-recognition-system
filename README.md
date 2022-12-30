# Voice-command-recognition-system
In this project, we want to train a GMM(Gaussian Mixture Model) to recognize 2 different commands. For this purpose, we record 30 samples of each class and
then preprocess the recorded audio files to train the models with them. The commands are "TV" and "Refrigerator" that are said in Farsi and then been used 
to train and test the model. <br>
This is a simple work just for educational purposes and can be used for more complicated datasets and audio files with more classes. <br>
The evaluation technique to see if our model works, is to look at the confusion matrix created by true labels of testing set and predicted labels. <br>
From 30 audioes that had been recorded for each class, 20 of each is used for training and rest 10 were used to evaluate our model.<br>
I hope this will be useful for you 😉
