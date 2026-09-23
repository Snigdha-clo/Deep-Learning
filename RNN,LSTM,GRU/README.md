## Experiment 6: Sequence Learning and Video Understanding

This experiment implements and compares **Vanilla RNN, LSTM, and GRU** models for sequence classification. It also demonstrates **CNN-based video understanding** and **Sequence-to-Sequence learning using an Encoder-Decoder architecture**.

 Objectives

- Understand recurrent neural networks and sequence learning.
- Implement a Vanilla RNN using `SimpleRNN`.
- Implement LSTM and GRU networks.
- Understand Backpropagation Through Time (BPTT).
- Study vanishing and exploding gradient problems.
- Compare RNN, LSTM and GRU using different performance metrics.
- Perform video understanding using a CNN + LSTM pipeline.
- Implement a simple sequence-to-sequence Encoder-Decoder model.

Dataset
### 1. UCI Human Activity Recognition Dataset
The primary dataset used is the **UCI Human Activity Recognition Using Smartphones Dataset**.
The dataset contains six activities:
- WALKING
- WALKING UPSTAIRS
- WALKING DOWNSTAIRS
- SITTING
- STANDING
- LAYING

The raw sensor data is represented as sequences of:
128 time steps × 9 features
Vanilla RNN
Input (128 × 9)
      ↓
SimpleRNN (32 units)
      ↓
Dropout
      ↓
Dense (16, ReLU)
      ↓
Dense (6, Softmax)


LSTM
Input (128 × 9)
      ↓
LSTM (32 units)
      ↓
Dropout
      ↓
Dense (16, ReLU)
      ↓
Dense (6, Softmax)

GRU
Input (128 × 9)
      ↓
GRU (32 units)
      ↓
Dropout
      ↓
Dense (16, ReLU)
      ↓
Dense (6, Softmax)
