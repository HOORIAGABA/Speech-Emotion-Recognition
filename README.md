# Speech Emotion Recognition with Librosa

## Introduction
In the digital age, understanding human emotions through speech can transform a wide range of applications, from improving customer service interactions to supporting mental health monitoring. This **Speech Emotion Recognition with Librosa** project is designed to leverage audio processing techniques to detect and classify emotions from speech. Using Python libraries like **Librosa**, **Soundfile**, and **sklearn**, this project introduces core concepts in audio processing, feature extraction, and machine learning, providing a foundation for more advanced models, such as those based on deep learning.

## Objectives
- Load and process sound files using **Librosa** and **Soundfile** libraries.
- Perform feature extraction from audio data.
- Train a **Multi-Layer Perceptron (MLP)** classifier model using **sklearn** to recognize emotions in speech.
- Gain foundational knowledge in audio processing and machine learning to enable further advancements in speech emotion recognition.

## Methodology
1. **Data Collection and Preprocessing**
   - Collect a dataset of speech recordings labeled with corresponding emotions.
   - Load and preprocess these sound files using the **Librosa** and **Soundfile** libraries to prepare them for feature extraction.

2. **Feature Extraction**
   - Extract relevant audio features such as **Mel-frequency cepstral coefficients (MFCCs)**, **chroma**, and **spectral contrast** using **Librosa**.
   - Compile these features into a structured format suitable for input into the MLP classifier.

3. **Model Training**
   - Use the **sklearn** library to define and train a **Multi-Layer Perceptron (MLP)** classifier on the extracted features.
   - Implement cross-validation and parameter tuning to optimize the model's performance.

4. **Evaluation and Analysis**
   - Evaluate the trained MLP classifier using appropriate metrics such as **accuracy**, **precision**, **recall**, and **F1-score**.
   - Analyze results to identify the model's strengths and limitations in recognizing speech emotions.

## Tools and Technologies
- **Librosa**: For audio processing and feature extraction.
- **Soundfile**: For reading and writing sound files.
- **sklearn**: For machine learning model development and evaluation.
- **Python**: As the programming language to integrate these libraries and implement the project.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/HOORIAGABA/Speech-Emotion-Recognition-with-Librosa.git
   cd Speech-Emotion-Recognition-with-Librosa
