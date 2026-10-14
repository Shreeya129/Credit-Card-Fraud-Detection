# Credit Card Fraud Detection using Deep Learning

An unsupervised anomaly detection system built in Python using Keras and TensorFlow to detect fraudulent credit card transactions. The system utilizes an Autoencoder neural network architecture to learn normal transaction patterns and flag highly deviant transactions as potential fraud.

## 🚀 Key Features
- **Unsupervised Anomaly Detection:** Utilizes Autoencoders to reconstruct normal transaction patterns and flag high reconstruction errors.
- **Data Preprocessing:** Implements standard scaling on transaction amounts and features to handle variance.
- **Performance Evaluation:** Evaluates model performance using Precision, Recall, and Receiver Operating Characteristic (ROC) curve analysis.

## Tech Stack & Libraries
- **Language:** Python 3
- **Deep Learning Frameworks:** TensorFlow 2.x, Keras
- **Data Science Libraries:** Pandas, NumPy, Scikit-Learn
- **Visualization:** Matplotlib, Seaborn

## Dataset Structure
The system is built to process highly imbalanced datasets containing credit card transactions, identifying the rare fraudulent instances from a massive pool of legitimate records.

## How to Setup and Run
1. Clone this repository to your local system:
   ```bash
   git clone https://github.com
   ```
2. Open the Jupyter Notebook file:
   ```bash
   jupyter notebook fraud_detection.ipynb
   ```
3. Run the cells sequentially to preprocess the data, train the Autoencoder network, and visualize the anomaly metrics.
