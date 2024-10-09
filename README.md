This project focuses on developing a deep learning model to detect signs of depression from textual and audio data using the DAIC-WOZ and extended DAIC-WOZ datasets. The model integrates RoBERTa for natural language processing and a Convolutional Neural Network (CNN) for semantic feature extraction, enhancing classification accuracy.
**Introduction**
Depression is a significant mental health issue worldwide. This project aims to detect signs of depression from interview transcripts and audio data by leveraging state-of-the-art natural language processing (NLP) and deep learning techniques. The model classifies participants as either 'depressed' or 'not depressed' based on their responses.

**Technologies Used**
Python
PyTorch
RoBERTa (for NLP tasks)
CNN (for enhancing feature extraction)
Whisper Speech Recognition (for audio transcription)

**Data**
The model utilizes the DAIC-WOZ and extended DAIC-WOZ datasets, which contain interviews designed to identify depression in participants. Both textual transcripts and audio data are included for comprehensive analysis.

**Model Architecture**
RoBERTa Model: Fine-tuned for text-based depression detection by classifying interview transcripts.
Convolutional Neural Network (CNN): Integrated with RoBERTa to improve semantic feature extraction.
Whisper Speech Recognition: Used to process and convert audio data into textual format.
**Experiments and Results**
RoBERTa Fine-Tuning: Performed on interview transcripts to classify participants as 'depressed' or 'not depressed.'
CNN Integration: Used to enhance the semantic understanding of the text, leading to better classification accuracy.
Accuracy: Achieved up to 80% accuracy, which is a significant improvement over traditional text-based detection models.
