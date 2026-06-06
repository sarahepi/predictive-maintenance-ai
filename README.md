 Dataset

The dataset used in this project was created from real-world storage failure data provided by Backblaze on Kaggle.

It is based on Backblaze Hard Drive failure datasets, where:

Training set: 4 files from the year 2017
Test set: 1 file from the year 2016

These datasets contain real operational hard drive metrics used for predictive maintenance tasks.

Methodology

This project focuses on failure prediction and time-series forecasting using deep learning and transformer-based models.

Three different architectures were implemented and compared:

🔹 Transformer model
🔹 BiLSTM (Bidirectional LSTM)
🔹 CNN + LSTM hybrid model
Objective

The main goal is to:

Predict equipment (hard drive) failures in advance
Compare performance of different deep learning architectures
Evaluate accuracy and generalization on real-world industrial data
