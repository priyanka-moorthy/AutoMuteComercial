# AutoMuteComercial

## Goal:
The Goal is to auto mute advertisements/commercials on youtube. The media streaming on youtube is taken as input. Video is then segmented into shots and audio which are fed into the classifiers and the end result will be used to mute and unmute the audio. MFCC BoW feature will be used for audio features and visual features such as shot length and presence of text bands will be used along with AWS lambda, S3 , EC2 to bucket the and process the video.

## Architecture
![alt architecture]()
