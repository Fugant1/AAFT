# Considering Audio Flamingo 3 as the main model to be fine-tuned, the best preprocessing steps I'd make are:
1. Extract raw .wav files
2. Normalize than to 16kHz, mono
3. +- 2dB 
4. Oversampling due to extreme imbalance
5. Adding previous turns of the conversation to help in context