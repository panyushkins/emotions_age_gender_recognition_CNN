# Emotions, age, gender recognition from web-cam or video-file using Deep Neural Networks (CNN)

-----------------------------------------------

# Used Software
1. CNN to detect age, gender on pictures: https://github.com/yu4u/age-gender-estimation;
2. CNN to detect emotions + opencv to crop faces from stream / video file https://github.com/isseu/emotion-recognition-neural-networks;
3. OpenCV, Keras (tensorflow).

-----------------------------------------------

# Launch

1. Download model weights from https://github.com/yu4u/age-gender-estimation/releases/download/v0.5/weights.18-4.06.hdf5 and put it in 'pretrained_models/' folder.
2. Run 'emotions_recorder.ipynb' to analyse stream from web-cam or video-file. Save result in "time-reaction-reaction_tense-age-gender" .csv format.
3. Run 'emotions_analyser.ipynb' to draw charts of your user's reaction by second. 
