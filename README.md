# EmotionClassification

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [References](#references)

## Project Overview
This project aims to compare the performance of Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) models in detecting emotions from Electroencephalogram (EEG) signals. The goal is to determine if the computationally cheaper GRU model can achieve similar accuracy to the LSTM model.

Due to GitHub's limitations in rendering `.ipynb` files, the code cannot be previewed directly on GitHub. To view and run the code, please download the files and upload them to an environment that supports Jupyter notebooks.

## Dataset
The dataset used in this project, "Emotions.csv," originates from a research project conducted at Aston University, Birmingham (J. Bird et al., 2019).

## Installation
The two code files are independent and can be run separately. To use the code:

1. Download the code files and the dataset "emotion.csv.zip."
2. Unzip the dataset file.
3. In the code files, update the path to the "emotion.csv" file to match its location on your system.

We recommend using Google Colab for running the code. If you choose to use a different environment, you may need to install additional libraries such as `keras` and `tensorflow`.

### Example Setup in Google Colab
1. Upload the code files and the unzipped dataset to your Google Drive.
2. Open the code files in Google Colab.
3. Modify the file path to point to the location of "emotion.csv" in your Google Drive.
4. Run the cells to execute the code.

## References 
J. Bird, J., Ekart, A., D. Buckingham, C., & R. Faria, D. (2019). Mental Emotional Sentiment Classification with an EEG-based Brain-machine Interface. Conference: The International Conference on Digital Image & Signal. 


