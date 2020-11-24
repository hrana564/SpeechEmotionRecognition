[![N|Solid](https://miro.medium.com/max/1620/0*tqQ-x7QM2zKhJB9F.jpg)
# Speech Emotion Recognition with librosa
[~ By Mayuresh Patil]()

Speech Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human emotion and affective states from speech. This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch.
## Emotion and classification

we will use the libraries librosa, soundfile, and sklearn (among others) to build a model using an MLPClassifier. This will be able to recognize emotion from sound files. We will load the data, extract features from it, then split the dataset into training and testing sets. Then, we’ll initialize an MLPClassifier and train the model. Finally, we’ll calculate the accuracy of our model.


## Dependencies
```
pip install librosa soundfile numpy sklearn pyaudio
```
