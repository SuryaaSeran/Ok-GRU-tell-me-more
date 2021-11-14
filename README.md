# Ok-GRU-tell-me-more
> Predicting the next line in movie dialogues using GRUs. 
> The current work involves training data from a scene in Harry Potter and the Philospher's Stone. 
# Steps:
1. The audio is extracted from the video file and converted into text. 
2. Cosine similarity is calculated between the subtitles and generated text to check for the performance. 
3. The generated text is then used to train on a GRU-DNN model with an embedding layer after preprocessing the data. 
4. The trained model is used to predict movie dialogues with seed words.
5. The predicted movie lines is then converted to audio.
# Requirements
+ keras
+ tensorflow
+ speech_recognition
+ moviepy
+ nltk
+ pandas
+ numpy

