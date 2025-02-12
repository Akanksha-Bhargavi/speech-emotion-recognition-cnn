# **Deep Learning for Speech Emotion Recognition: A CNN Approach**

## **Project Description**

- This project focuses on developing a deep learning model to classify human emotions from audio data using Convolutional Neural Networks (CNN). Emotions play a vital role in human communication and have a significant impact in various sectors such as healthcare, entertainment, and customer service. This project aims to analyze audio recordings by converting them into spectrograms and utilizing CNNs for emotion classification.

## **Objectives**

- The primary objectives of this project are: To process audio recordings and convert them into spectrograms, capturing time-frequency characteristics.
- To design a CNN that can classify emotions from spectrograms.
- To evaluate the model’s performance and analyze its strengths and limitations in classifying emotions accurately.
  
## **Scope of Project**

- This project deals with the development and evaluation of an emotion recognition model from audio signals. The project covers the following areas:
- Preprocessing of audio data into spectrograms.
- Building and training a CNN for emotion classification.
- Evaluating the model using various performance metrics.
- Exploring possible improvements in model generalization and accuracy.
  
## **Dataset Information*

- The RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) dataset is used in this project. This dataset contains 7,356 audio and visual files of emotional speech and song, with emotions labeled in various categories.
- Emotion Labels: Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, Surprised.
- Sampling Rate: Reduced to optimize model performance and reduce computational load.
  
## **Environment Setup & Dependencies**

- The following tools and libraries were used to develop and run this project:
- Python: Programming language used for the implementation.
- TensorFlow/Keras: Libraries used for building and training the CNN model.
- Librosa: Used for converting audio files into spectrograms.
- Matplotlib/Seaborn: For visualizing results and performance metrics.

## **Results & Findings**

- Performance Metrics: The CNN model achieved a training accuracy of 21.33% and a validation accuracy of 31.11%.
- The confusion matrix highlighted correct classifications (e.g., "Angry" classified correctly 82 times) and misclassifications (e.g., "Angry" misclassified as "Calm" 25 times).
- The model performed well on the training set but struggled to generalize, with validation accuracy improving at a much slower rate.
- Visualizations: Training and Validation Accuracy: The model showed improvement in training accuracy, but validation accuracy increased slower, indicating overfitting.
- Training and Validation Loss: Training loss decreased rapidly while validation loss decreased more gradually, showing potential overfitting.
  
- Key Insights: The CNN effectively identified patterns in spectrograms, but its performance was limited by noise and its ability to generalize across diverse datasets.
- The overlap between similar emotions (e.g., "Sad" vs. "Neutral") and potential class imbalance caused some misclassifications.
  
## **Conclusion**

- This project demonstrated the potential of CNNs in classifying emotions from audio signals. The model achieved a reasonable accuracy rate in identifying emotions from speech but has limitations in generalization and sensitivity to noise. The following improvements could enhance performance:
- Data augmentation techniques, like pitch shifting or adding background noise.
- Experimenting with more advanced architectures, such as hybrid models combining CNNs and RNNs.
- Expanding the dataset for greater diversity in speakers, languages, and environments.
- Investigating transfer learning to use pre-trained models for enhanced performance.

## **References**
- CNN for Speech Emotion Recognition. GitHub, GitHub, https://github.com/speech-emotion-recognition/blob/master/CNN.ipynb.
