Folder Navigation
- `code`: contain the code used as well as the one presented in the slide
  - `Emotion Recognition from Multi-Channel EEG through Parallel Convolutional Recurrent Neural Network.pdf`: reference paper used in the implementation
  - `cnnrnn_preprocess.ipynb`: preprocessing the original data to the data that model can consume
  - Experiment
    - Train on all participants
      - Case 1 `cnnrnn_train.ipynb`: From 32 participants,
        - First 25 participants: Train
        - Last 7 participants: Test
      - Case 2 `cnnrnn_train_random_split.ipynb`: Random Split with test_size = 0.2
    - Train on one participants (1st participant)
      - Case 1 `cnnrnn_train_subject_dependent.ipynb`: From 40 clips,
        - First 32 clips: Train
        - Last 8 clips: Test
      - Case 2 `cnnrnn_train_subject_dependent_random_split.ipynb`: Random Split with test_size = 0.2

- `code_not_used`: contain some of the translated preprocessing and feature selection step from [this github](https://github.com/Daisybiubiubiu/EEG-Emotion-Recognition)
- `Paper`: contain some of the read paper and its summary
