# Speech Emotion Analyzer

* The idea behind creating this project was to build a machine learning model that could detect emotions from the speech we have with each other all the time. Nowadays personalization is something that is needed in all the things we experience everyday. 

* So why not have a emotion detector that will guage your emotions and in the future recommend you different things based on your mood. 
This can be used by multiple industries to offer different services like marketing company suggesting you to buy products based on your emotions, automotive industry can detect the persons emotions and adjust the speed of autonomous cars as required to avoid any collisions etc.

## Analyzing audio signals
![](images/joomla_speech_prosody.png?raw=true)

[©Fabien_Ringeval_PhD_Thesis](https://drive.google.com/file/d/0B2V_I9XKBODhcEtZV1lRWW1fYTg/view).
<br>

### Datasets:
Made use of two different datasets:
1. [RAVDESS](https://zenodo.org/record/1188976).
This dataset includes around 1500 audio file input from 24 different actors. 12 male and 12 female where these actors record short audios in 8 different emotions i.e 1 = neutral, 2 = calm, 3 = happy, 4 = sad, 5 = angry, 6 = fearful, 7 = disgust, 8 = surprised.<br>
Each audio file is named in such a way that the 7th character is consistent with the different emotions that they represent.

2. [SAVEE](http://kahlan.eps.surrey.ac.uk/savee/Download.html).
This dataset contains around 500 audio files recorded by 4 different male actors. The first two characters of the file name correspond to the different emotions that the potray. 

## Conclusion
Building the model was a challenging task as it involved lot of trail and error methods, tuning etc. The model is very well trained to distinguish between male and female voices and it distinguishes with 100% accuracy. The model was tuned to detect emotions with more than 70% accuracy. Accuracy can be increased by including more audio files for training.
