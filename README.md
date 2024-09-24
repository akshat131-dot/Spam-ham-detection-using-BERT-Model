This project is focused on classifying email or message content as Spam or Ham (Not Spam) using a BERT (Bidirectional Encoder Representations from Transformers) model. The model leverages the power of BERT for understanding natural language and effectively differentiating between spam and non-spam messages.

The project handles a small dataset, which introduces challenges with data splitting, but the robustness of the BERT model ensures strong classification performance.

Features:- 

- Spam vs Ham Classification: Classifies messages into two categories: Spam and Ham based on their textual content.
- Pre-trained BERT model: Utilizes the BERT model, fine-tuned for this binary classification task.
- Small Dataset Adaptation: Tackles the challenges of training on a limited dataset with appropriate data preprocessing and model optimization.

Tech Stack:- 

Python: The primary programming language used for building the model.
Hugging Face Transformers: For loading and fine-tuning the pre-trained BERT model.
scikit-learn: For data preprocessing, splitting, and evaluation metrics.
Pandas: Used for handling and analyzing the dataset.
PyTorch or TensorFlow: As the backend framework for training and deploying the model.

Project Structure

Dataset: Contains labeled spam and ham data.
Model Training: Scripts for fine-tuning the BERT model.
Evaluation: Code for evaluating the model on the test data and generating performance metrics.
Visualization: Includes plots for model evaluation such as confusion matrices and accuracy curves.
