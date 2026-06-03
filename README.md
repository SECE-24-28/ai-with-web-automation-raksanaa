AI & Deep Learning Experiments Notebook

This repository contains a collection of Artificial Intelligence, Machine Learning, Deep Learning, Natural Language Processing (NLP), Generative AI, and Speech Processing experiments implemented using Python, PyTorch, Hugging Face Transformers, and other AI libraries.

The notebook serves as a practical learning resource covering fundamental and advanced AI concepts including RNNs, GANs, Sentiment Analysis, Spam Detection, and Text-to-Speech generation.

📌 Topics Covered
1️⃣ Data Analysis using Pandas
Loading datasets from Excel files
Data inspection using:
head()
info()
Missing value analysis
Basic preprocessing

Libraries Used

Pandas
NumPy
2️⃣ Recurrent Neural Network (RNN)

Implementation of a Simple RNN using PyTorch.

Features
Sequence prediction
Hidden state management
Forward propagation
Training on sequential data

Concepts Learned

Time Series Prediction
Sequence Modeling
Hidden Layers
Backpropagation Through Time (BPTT)

Libraries Used

PyTorch
NumPy
Matplotlib
3️⃣ Generative Adversarial Network (GAN) – MNIST

Implementation of a GAN for handwritten digit generation.

Features
Generator Network
Discriminator Network
Noise Vector Input
Synthetic Image Generation
Dataset
MNIST Dataset

Concepts Learned

Adversarial Learning
Image Generation
Generator vs Discriminator Training
4️⃣ Deep Convolutional GAN (DCGAN)

Implementation of DCGAN for generating realistic images.

Features
Image Upsampling
Convolutional Layers
Batch Normalization
Realistic Image Synthesis

Libraries Used

PyTorch
TorchVision
5️⃣ Basic Sentiment Analysis

Rule-based sentiment analysis using predefined positive and negative word dictionaries.

Categories
Positive
Negative
Neutral
Example

Input:

I love this project

Output:

Positive Sentiment
6️⃣ Transformer-Based Text Classification

Using Hugging Face Transformers for advanced NLP tasks.

Model
jinwoo1126/distlbert-base-uncased-finetuned-clinc
Applications
Intent Classification
Text Categorization
NLP Research
7️⃣ DistilBERT Sentiment Analysis

Using pretrained DistilBERT model for sentiment prediction.

Model
distilbert-base-uncased-finetuned-sst-2-english
Output
Positive
Negative
Features
Transformer-based inference
Confidence score prediction
Real-world sentiment classification
8️⃣ Spam Detection System

Machine Learning-based Spam Detection using:

Techniques
TF-IDF Vectorization
Logistic Regression
Workflow
Text Data
      ↓
TF-IDF Vectorizer
      ↓
Logistic Regression
      ↓
Spam / Ham Prediction
Dataset
spam.csv
9️⃣ Text-to-Speech using Hugging Face

Converting text into speech using Facebook MMS TTS model.

Model
facebook/mms-tts-eng
Features
English Speech Generation
WAV File Output
Output
output.wav
🔟 Text-to-Speech using gTTS

Google Text-to-Speech implementation.

Features
Fast speech synthesis
MP3 generation
Output
sentiment_output.mp3
🛠 Technologies Used
Category	Technology
Programming Language	Python
Data Analysis	Pandas, NumPy
Deep Learning	PyTorch
NLP	Transformers
ML	Scikit-Learn
Visualization	Matplotlib
Speech Processing	gTTS, MMS-TTS
Dataset Handling	TorchVision
📂 Project Structure
AI-DeepLearning-Experiments/
│
├── Untitled6.ipynb
├── spam.csv
├── fake_student_dataset.xlsx
├── output.wav
├── sentiment_output.mp3
├── README.md
└── requirements.txt
🚀 Installation

Clone the repository:

git clone https://github.com/your-username/AI-DeepLearning-Experiments.git
cd AI-DeepLearning-Experiments

Install dependencies:

pip install pandas numpy torch torchvision transformers
pip install scikit-learn matplotlib
pip install gtts soundfile
🎯 Learning Outcomes

After completing these experiments, you will understand:

Data preprocessing using Pandas
Sequence modeling with RNN
Image generation using GAN/DCGAN
Sentiment Analysis using NLP
Transformer-based text classification
Spam detection techniques
Text-to-Speech generation
Deep Learning workflow using PyTorch
