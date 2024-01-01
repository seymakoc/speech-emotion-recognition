# speech-emotion-recognition

This is a project to detect emotion from sound samples. In the AI, voice assistant era it's important to detect emotions from voice. Hence I wanted to try to develop a model for this purpose.

I used 4 different datasets in this project which are Tess, Crema, Ravdess and Savee. I combined them into a dataframe and extracted the features of them with the help of librosa library and mfcc algorithm. Then I used Convolution neural network and deployed a network model with specific layers. I used the keras library for this step.

In the end, for the training I got 93% accuracy and 18% loss, for the validation I got %54 accuracy and as the test results I got again 57% accuracy.

It can be improved with finetuning as I saw from the results or we can try to split validation sets with different approaches.
