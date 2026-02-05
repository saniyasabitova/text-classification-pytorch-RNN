# rnn-text-classification-pytorch
 Project Overview
This project implements a text classification pipeline using Recurrent Neural Networks (RNN) in PyTorch. Beyond standard model training, the core focus is an empirical study of how different hidden state aggregation methods (pooling strategies) impact final classification performance.

 Key Features
Architecture: RNN-based model designed to handle variable-length sequences.

Pooling Strategies Comparison: Two distinct approaches were implemented and evaluated to transform RNN hidden states into a fixed-length feature vector:

Global Max Pooling: Captures the most prominent features across the entire sequence.

Global Mean Pooling: Averages contextual information to represent the overall sentence meaning.

Data Pipeline: Custom end-to-end preprocessing, including tokenization, vocabulary building, and padding management for batch processing.

Comprehensive Evaluation: Performance analysis using Accuracy to ensure robust evaluation, especially critical for imbalanced text datasets.
