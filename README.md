# Fake News Detector using LSTM

## Overview

This repository contains the code for a Fake News Detector implemented using Long Short-Term Memory (LSTM) neural networks. The model was trained on a dataset of 20,000 values and evaluated on 5,000 values, achieving an accuracy of 90%. The project utilizes popular libraries such as TensorFlow, Scikit-learn, NLTK, and Keras for building and evaluating the model. Additionally, the Fake News Detector has been deployed using Streamlit for a user-friendly interface.

## Project Structure

1. **data**: Contains the dataset used for training and testing the model.
   
2. **models**: Includes the LSTM model implementation and data exploration, model development, and evaluation.

3. **deploy**: Contains files related to the Streamlit app for deploying the model.

## Dependencies

- TensorFlow
- Scikit-learn
- NLTK
- Keras
- Streamlit

Install the required dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

1. **Data Preprocessing**: Run the data preprocessing script to clean and prepare the dataset.

   ```bash
   python src/data_preprocessing.py
   ```

2. **Model Training**: Execute the script for training the LSTM model.

   ```bash
   python src/train_model.py
   ```

3. **Evaluation**: Evaluate the model on the test set to calculate accuracy and other metrics.

   ```bash
   python src/evaluate_model.py
   ```

4. **Streamlit App Deployment**: Deploy the Fake News Detector using Streamlit.

   ```bash
   streamlit run app/app.py
   ```


## Results

The trained model achieved an accuracy of 90% on the test set, demonstrating its effectiveness in classifying fake and real news.

## Acknowledgments

- The dataset used in this project was sourced from [https://www.kaggle.com/c/fake-news/data#].
