# Fake News Detection Using Machine Learning

## Project Overview

This project is a Machine Learning-based Fake News Detection system developed using Python. The objective is to classify news articles as **Real** or **Fake** based on their textual content.

The project uses Natural Language Processing (NLP) techniques for text preprocessing and feature extraction, followed by a Machine Learning classification model for prediction.

## Problem Statement

With the rapid spread of information through online platforms, fake news has become a significant challenge. This project aims to automatically identify misleading or false news articles using Machine Learning techniques.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Regular Expressions (Regex)
- TF-IDF Vectorization
- Jupyter Notebook / Google Colab

## Machine Learning Workflow

### 1. Data Collection
- Loaded fake and real news datasets.
- Combined and labeled the data for training.

### 2. Data Preprocessing
- Removed special characters and punctuation.
- Converted text to lowercase.
- Removed unnecessary words.
- Cleaned and prepared textual data for analysis.

### 3. Feature Engineering
- Converted text into numerical features using TF-IDF Vectorization.

### 4. Model Training
- Split the dataset into training and testing sets.
- Trained a Machine Learning classification model.

### 5. Model Evaluation
- Evaluated model performance using accuracy and classification metrics.

### 6. Prediction
- Tested the model on unseen news articles.
- Classified articles as Real News or Fake News.

## Project Structure

```text
Fake-News-Detection/
│
├── Fake_News_Detection.ipynb
├── README.md
├── requirements.txt
├── Fake.csv
└── True.csv
```

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the Project

Open the notebook and execute all cells:

```bash
jupyter notebook
```

or upload the notebook to Google Colab.

## Sample Output

**Input:**

```text
Government announces new policies to improve education infrastructure.
```

**Prediction:**

```text
Real News
```

## Skills Demonstrated

- Data Cleaning
- Text Preprocessing
- Natural Language Processing (NLP)
- Feature Engineering
- Machine Learning Classification
- Model Evaluation
- Python Programming

## Learning Outcomes

Through this project, I gained hands-on experience with:

- Machine Learning workflows
- Text classification problems
- TF-IDF Vectorization
- Data preprocessing techniques
- Model training and evaluation

## Acknowledgements

This project was developed as part of my Machine Learning learning journey. The initial implementation was inspired by a tutorial from the Simplilearn YouTube channel, and was used to understand the end-to-end workflow of building a Fake News Detection system.

## Future Enhancements

- Deploy the model using Streamlit
- Build a web interface for predictions
- Experiment with advanced NLP models such as BERT
- Improve model accuracy through hyperparameter tuning

## License

This project is intended for educational and learning purposes.
