# Home-Assignment-1
Name - Thakkiti Nithish Reddy
id -  700764837
CRN - 30679



# TensorFlow Tasks and Analysis

## 1. Tensor Manipulations & Reshaping

### Task Description:

* **Create** a random tensor of shape `(4, 6)`.
* **Find** the rank and shape of the tensor.
* **Reshape** the tensor to shape `(2, 3, 4)`.
* **Transpose** the reshaped tensor to shape `(3, 2, 4)`.
* **Broadcast** a smaller tensor `(1, 4)` and perform addition.

### Expected Outputs:

* Print rank and shape of the tensor before and after reshaping/transposing.
* Explanation of TensorFlow broadcasting.

## 2. Loss Functions & Hyperparameter Tuning

### Task Description:

* **Define** true values (`y_true`) and model predictions (`y_pred`).
* **Compute** Mean Squared Error (MSE) and Categorical Cross-Entropy (CCE) losses.
* **Modify** predictions slightly to observe changes in loss.
* **Plot** loss function values using Matplotlib.

### Expected Outputs:

* Loss values printed for initial and modified predictions.
* Bar chart comparing MSE and Cross-Entropy Loss.

## 3. Train a Neural Network and Log to TensorBoard

### Task Description:

* **Load** the MNIST dataset and preprocess it.
* **Train** a simple neural network model for **5 epochs**.
* **Enable** TensorBoard logging.

### Expected Outcomes:

* Model logs stored in the directory: `logs/fit/`.
* Visualization of training vs. validation accuracy and loss using TensorBoard.

### How to Launch TensorBoard:

```bash
tensorboard --logdir logs/fit
```

Open the displayed URL (usually `http://localhost:6006/`) in your web browser to analyze results.
