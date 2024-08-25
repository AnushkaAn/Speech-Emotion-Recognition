# Speech Emotion Recognition using LSTM and MFCC Features

This project focuses on recognizing emotions from speech using machine learning techniques. The dataset used for this task is the Toronto Emotional Speech Set (TESS), and features are extracted using Mel Frequency Cepstral Coefficients (MFCC). A Long Short-Term Memory (LSTM) neural network is used to train the model.

# Introduction

Speech Emotion Recognition (SER) is a growing area in AI and machine learning, aimed at detecting emotions from speech signals. This project utilizes the TESS dataset to classify emotions like anger, fear, happiness, sadness, and more. The primary goal is to build a system that accurately classifies emotions from audio data.

# Dataset

The dataset used in this project is the Toronto Emotional Speech Set (TESS), which contains 2,800 audio files labeled with seven different emotions: Angry, Disgust, Fear, Happy, Neutral, Pleasant Surprise (ps), and Sad. Preprocessing steps include loading the audio data, normalizing it, and preparing it for feature extraction.

# Feature Extraction

Feature extraction is a critical step in speech emotion recognition. The project primarily uses MFCC (Mel Frequency Cepstral Coefficients) to capture relevant information from the audio signals. Additionally, other features such as formant frequencies, pitch and pitch contour, speech rate, energy, and zero crossing rate are explored to enrich the dataset.

# Model Building

The project employs an LSTM (Long Short-Term Memory) neural network for emotion classification. The LSTM model is chosen for its ability to handle sequential data, making it suitable for audio processing tasks. The model consists of one LSTM layer followed by dense layers and dropout layers for regularization.

# Evaluation

Model evaluation is performed using performance metrics like accuracy, and the results are visualized using accuracy/loss plots and a confusion matrix. The confusion matrix provides a detailed analysis of the model’s performance across different emotion classes.

# Deployment

The trained model can be deployed in real-world applications, such as customer service systems, health monitoring tools, or voice-activated assistants. It can be integrated into applications where detecting emotions from speech can enhance user interactions.

# Conclusion

This project successfully demonstrates the effectiveness of using LSTM models and MFCC features in Speech Emotion Recognition. The model achieves reasonable accuracy and can be further improved with advanced techniques and larger datasets. Future work could include real-time deployment and exploring more complex deep learning architectures.

# References

1. Librosa Documentation: Librosa
2. Keras Documentation: Keras
3. Scikit-Learn Documentation: Scikit-Learn
4. Toronto Emotional Speech Set (TESS) Dataset: Kaggle - TESS Dataset
5. "Speech Emotion Recognition: A Review" by El Ayadi, Kamel, and Karray (2011)
6. "A Comparative Study of Machine Learning Algorithms for Speech Emotion Recognition" by S. Khan et al. (2020)

