# NM-Projects
📘 Project 1: Speech-to-Text with Noise Robustness
This project aims to build a speech recognition system that performs well even in noisy environments using pre-trained models and noise-augmented data.

✅ Features
Uses wav2vec2.0 pretrained model (from Hugging Face Transformers)

Incorporates noise-robust preprocessing (e.g., Voice Activity Detection)

Supports real-time and batch transcription

Computes Word Error Rate (WER) and accuracy

📥 Inputs
Clean and noisy .wav audio samples

Ground truth transcripts (for evaluation)

📤 Outputs
Transcribed text

WER, accuracy, confusion matrix

📘 Project 3: Acoustic Model Training and Evaluation
This project builds and evaluates acoustic models using extracted speech features.

✅ Features
HMM and deep learning-based acoustic models

Uses MFCCs as input

Compares models based on accuracy and WER

Supports early stopping and checkpointing

📥 Inputs
Processed MFCC features

Corresponding phoneme/word labels

📤 Outputs
Trained acoustic model

Evaluation metrics: accuracy, WER, precision/recall


📘 Project 4: End-to-End ASR Pipeline with Integration
Integrates the language model and acoustic model into a full pipeline for end-to-end speech recognition.

✅ Features
Combines acoustic model predictions with language model probabilities

Implements beam search decoder

Supports batch transcription

Real-time inference visualization

📥 Inputs
Raw audio files

Trained acoustic and language models

📤 Outputs
Final transcriptions

Model performance reports

Comparison of standalone vs. integrated system
