# 🎬 IMDB Sentiment Analysis using BiLSTM with Attention

This project implements a deep learning pipeline for binary sentiment classification on the IMDB movie reviews dataset using Bidirectional LSTMs (BiLSTM) combined with Additive and Multiplicative Attention mechanisms.

The goal is to compare different attention techniques and optimizers to identify the most effective model for sentiment analysis.

# 🚀 Key Features
# 🔤 Text Preprocessing Pipeline
🔹Cleaning (HTML removal, lowercasing, noise reduction)
🔹Tokenization with limited vocabulary (10,000 words)
🔹Sequence padding for LSTM compatibility
# 🧠 Deep Learning Architecture
🔹Embedding Layer (128-dim vectors)
🔹Bidirectional LSTM (context from both directions)
🔹Custom Attention Layer:
1. Additive Attention (Bahdanau)
2. Multiplicative Attention (Luong)
🔹Dense classifier with dropout regularization
# ⚙️ Training & Optimization
🔹Loss Function: Binary Cross-Entropy
🔹Optimizers: Adam & RMSprop
🔹Model comparison across 4 configurations
# 📊 Performance
🔹Best Model: Multiplicative Attention + Adam
🔹Accuracy: ~89.1%
🔹AUC-ROC: ~0.957
# 💾 Deployment Ready
🔹Model saved as best_model.h5
🔹Tokenizer saved as tokenizer.pkl
🔹End-to-end inference pipeline included

# 🏆 Results Summary
Multiplicative Attention consistently outperformed Additive Attention in:
🔹Accuracy
🔹F1 Score
🔹Convergence Speed

# 🛠️ Tech Stack
🔹Python
🔹TensorFlow / Keras
🔹Scikit-learn
🔹NumPy
