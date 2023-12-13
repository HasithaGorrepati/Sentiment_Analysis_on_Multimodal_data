# Multimodal-Sentiment-Analysis-Project

## Overview
This project focuses on sentiment analysis using the CMU-MOSI dataset, which includes multimodal data—audio, video, and text. The goal is to predict sentiment labels based on these different modalities.

## Dataset
The CMU-MOSI dataset consists of audio, video, and text samples. Each modality provides a unique perspective on sentiment, enriching the analysis.

### Text Data Preprocessing
- Tokenization: The text data is tokenized to break down sentences into individual words.
- Stopword Removal: Common stopwords are removed to focus on more meaningful words.
- Stemming: Words are stemmed to reduce them to their root form, aiding in feature extraction.

### Audio Data Preprocessing
- MFCC Extraction: Mel-frequency cepstral coefficients (MFCCs) are extracted from audio samples.
- Frame Restriction: The number of frames is restricted to capture essential features.
- Padding MFCCs: Padding ensures uniformity in the input data.

### Video Data Preprocessing
- Frame Extraction: Frames are extracted from video samples.
- Resizing: Frames are resized for consistency.
- Normalization: Frame pixel values are normalized to facilitate model training.

## Model Architecture
The project explores two models: CubeMLP and BERT, each tailored to handle the unique characteristics of multimodal data.

### VGG16 for Facial Expression Extraction
The VGG16 model is employed to extract facial expressions from the video modality, providing valuable visual features for sentiment analysis.

## Acknowledgments
We used CMU-MOSI dataset, cubemlp model and bert model
Feel free to reach out for any questions or issues!
