# BirdCallClassification
Identify bird calls in soundscapes

## Datasets
  - Dataset 1 - [BirdCLEF](https://www.kaggle.com/competitions/birdclef-2023/data)
  - Dataset 2 - [BirdCLEF Mfccs](https://www.kaggle.com/datasets/akshatpathak/bird-clef-mfccs)

## EDA
  - Total of 264 classes.
  - A lot of classes have very few data points. (soln : take only classes with >500 data points)
  - Min clip_length=0.548 which might be a problem while processing data
## Image generation
  - Short-time Fourier transform (STFT)
  - Convert an amplitude spectrogram to dB-scaled spectrogram
  - Spectral Rolloff (frequency below which a specified percentage of the total spectral energy)
## Authors
[Anish Ghiya](https://github.com/anishsghiya), 
[Aadhishrii Patiil](https://github.com/aadhishrii), 
[Ashwamegha Holkar](https://github.com/ashunitinholkar), 
[Sairaj Pokale](https://github.com/Sairaj-Pokale)
