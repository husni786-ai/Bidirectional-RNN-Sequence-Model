# 🔄 Bidirectional Recurrent Neural Network (Bi-RNN) Example

This project provides a Jupyter Notebook demonstrating the fundamental architecture and usage of a **Bidirectional Recurrent Neural Network (Bi-RNN)**, a powerful variant of standard RNNs (like SimpleRNN, LSTM, or GRU). The notebook utilizes randomly generated data to illustrate the core concepts of sequence processing for binary classification (e.g., sentiment analysis or text classification).

---

## 🎯 Project Goals

The objective of this notebook is to showcase the implementation of the Bi-RNN architecture in TensorFlow/Keras, specifically covering:

1.  **Data Simulation:** Create synthetic sequence data (`x_train`, `y_train`) to mimic a real-world text classification task.
2.  **Model Definition:** Build a sequential model incorporating the **Embedding** and **Bidirectional** layers.
3.  **Context Capture:** Highlight how the Bi-RNN layer processes sequences in both the forward and backward directions to capture full context.
4.  **Training Mechanics:** Implement standard deep learning practices like **Dropout** and **Early Stopping**.

## ⚙️ Technology Stack and Dependencies

The project is built on the core components of the Python deep learning stack.

| Library | Role |
| :--- | :--- |
| **`tensorflow / keras`** | Core framework for deep learning model construction. |
| **`numpy`** | Used for efficient creation of synthetic (random) data. |
| **`layers.Embedding`** | Converts integer-encoded input sequences into dense vector representations. |
| **`layers.SimpleRNN`** | The base RNN cell used within the bidirectional wrapper. |
| **`layers.Bidirectional`** | The key layer that wraps an RNN (e.g., SimpleRNN) to process sequences in both directions.  |
| **`callbacks.EarlyStopping`** | Used to stop training early and restore the best model weights. |

### Installation

```bash
pip install tensorflow numpy
