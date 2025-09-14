# Speech Emotion Recognition

This project performs speech emotion recognition using the RAVDESS dataset. It analyzes audio files to classify emotions expressed in speech.

## Project Structure

- `Speech Sentiment Analysis.ipynb`: Main Jupyter notebook for data analysis and modeling.
- `speech-emotion-recognition-ravdess-data/`: Directory containing RAVDESS audio files, organized by actor.
- `speech-emotion-recognition-ravdess-data.zip`: Compressed dataset (ignored by git).

## Dataset

The RAVDESS dataset contains emotional speech recordings from 24 actors. Each `.wav` file encodes a specific emotion, intensity, and other metadata.

## Usage

1. **Install dependencies**  
   Install required Python packages:
   ```
   pip install numpy pandas librosa scikit-learn matplotlib
   ```

2. **Run the notebook**  
   Open `Speech Sentiment Analysis.ipynb` in Jupyter and follow the steps to extract features, train models, and evaluate emotion recognition.

## Features

- Audio feature extraction (MFCC, Chroma, etc.)
- Emotion classification using machine learning
- Visualization of results

