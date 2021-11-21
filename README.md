# AT82.01-brain-project-group-4

## Week 1 Progress

### Completed
- TOPIC SELECTED: Val, Dom, Arousal from DEAP dataset
- Analyze and Explore DEAP dataset
- Reading Papers
  - The Impact of Different Sounds on Stress Level in the Context of EEG, Cardiac Measures and Subjective Stress Level: A Pilot Study (Sunny)
  - Finding Emotion Dataset DEAP dataset (Jirasak , Arnajak)
  - DEAP : A database for Emotion Analysis using Physiological Signals (Sunny, Jirasak, Arnajak)
  - EEG Signals to Measure Mental Stress (Arnajak)
  - Emotion Recognition Based on EEG using DEAP Dataset (Jirasak) 

## Week 2 Progress
### In-Progress
- Understanding EEGNet and MNE tool(Arnajak)
- Designing Possible model for DEAP (Jirasak)
- Feature/ Information (preprocessing) Extraction from DEAP dataset (Sunny, Jirasak)



- Reading Papers  - 
  - EEG-Based Emotion Classification Using a Deep Neural Network and Sparse Autoencoder (Jirasak)
  - EEG-based Brain-Computer Interfaces (BCIs): A Survey of Recent Studies on Signal Sensing Technologies and Computational Intelligence Approaches and Their Applications 
  - EEG-based emotion recognition in music listening: A comparison of schemes for multiclass support vector machine (Amanda)

## Week 3 Progress
### Completed
- Propose and demonstrate on using Welch's method to extract feature from data (Sunny)
- Predict the Val, Dom, Arousal using 4 bands of area under the curve of Welch's method transformed data from each channel, using simple fully-connected deep neural network (Jirasak, Sunny)
- Try using EEGNet on the data (Arnajak)

### In-Progress
- Consider Gabor Transform for turning raw data to 3D spectrography, in order to retain temporal feature (Jirasak)
- Look into Data cleaning/preprocessing step (ICA, etc.) to reduce unnecessary noise (Arnajak) 
- Trying out EEGNet and its derivatives on the DEAP dataset directly (Sunny)
- Reading the paper on EEGNET (Sunny)

## Week 4 Progress
### Completed
- Read 3 papers and Upload paper's PDF files and their summary in github/google drive (Jirasak)  
- Read new paper and uploaded the summary on google drive. (Amanda)

## Week 5 Progress
### Completed
- Read 2 paper , Upload paper summary in google drive and Do LSTM model but stuck in Overfitted problem. (Arnajak)
- Creating scalogram using continuous wavelet transform to feed into CNN network.

## Week 6 progress
- Creating STFT + CNN Network for DEAP Valence and Arousal (Sunny)
- face problem overfitting or maybe noise in both of model ( psd->LSTM ) and (STFT -> conv2d)
- Successfully replicate a model using continuous wavelet transform from [this github](https://github.com/Daisybiubiubiu/EEG-Emotion-Recognition), CWT preprocess code and scale selection code also translated from matlab to python   (Jirasak)

st122162 - Jirasak Buranathawornsom  
st122458 - Arnajak Tungchoksongchai  
st122336 - Sunny Kumar Tuladhar  
st122245 - Amanda raj Shrestha  
