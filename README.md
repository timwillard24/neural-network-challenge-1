# neural-network-challenge-1 - Student Loans Prediction Using Deep Learning

This project involves building a deep learning model using Keras to predict student loans outcomes. The project aims to analyze loan data and develop a model that can classify or predict outcomes related to student loans, utilizing neural networks.

## Project Structure

### 1. Data Preprocessing
- **Data Scaling:** The input data is scaled using `StandardScaler` from `sklearn` to ensure that all features are on a similar scale, improving model performance.
- **Feature Selection:** Features related to student loan history, employment status, salary, and interest rates are used.

### 2. Deep Learning Model
- **Architecture:** A Sequential model is built using Keras, with multiple dense layers, activation functions like `ReLU`, and dropout layers to prevent overfitting.
- **Compilation:** The model is compiled with:
  - `adam` optimizer for efficient optimization.
  - `binary_crossentropy` as the loss function for binary classification tasks.
  - `accuracy` as the performance metric.
- **Training:** The model is trained over 50 epochs with a batch size of 32. The dataset is split into training and validation sets to monitor validation performance.

### 3. Evaluation
- **Accuracy and Loss:** The model achieved:
  - Training accuracy: ~75%
  - Validation accuracy: ~57%
  - Final test accuracy: ~73%
- The test set was used to evaluate the model's generalization capability.

### 4. Challenges Addressed
- **Data Privacy:** The dataset includes sensitive financial information, so handling privacy and confidentiality is a concern.
- **Bias/Fairness:** Ensuring fairness in the model to avoid disadvantaging certain demographic groups based on socio-economic status, gender, or geographic location.

## How to Use

### Prerequisites
- Python 3.x
- Keras, TensorFlow, NumPy, Pandas, Scikit-learn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/timwillard24/student-loan-prediction.git

