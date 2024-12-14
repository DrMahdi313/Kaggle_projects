# Kaggle Disaster Tweets NLP Notebook

## Overview

This repository contains my solution to the Kaggle Disaster Tweets competition. The primary objective of this project was to practice and refine my natural language processing (NLP) skills, using modern tools like `keras_nlp` and transformer models. While I explored various approaches, this work was not aimed at achieving the highest possible results but rather to experiment and demonstrate my understanding of core NLP concepts.

## Dataset

The dataset is part of the Kaggle Disaster Tweets Competition, where the goal is to classify whether a given tweet is related to a real disaster or not.

The dataset contains:

- **Train.csv**: Training data with labeled tweets.
    
- **Test.csv**: Unlabeled data for prediction.
    

Key Features:

- **id**: Unique identifier for each tweet.
    
- **text**: The tweet text.
    
- **target**: Binary label (1 for disaster-related, 0 otherwise).
    

## Objectives

This notebook serves as a training exercise to:

1. Explore and preprocess text data effectively.
    
2. Implement a data augmentation pipeline for NLP tasks.
    
3. Fine-tune pre-trained transformer models using `keras_nlp`.
    
4. Experiment with different modeling approaches to gain insights.
    
5. Evaluate performance metrics and document findings.
    

## Methodology

### Data Preprocessing

- **Cleaning**: Removal of noise such as URLs, mentions, special characters, and unnecessary spaces.
    
- **Tokenization**: Conversion of text to tokens suitable for transformer models.
    
- **Augmentation**: Custom data augmentation strategies to introduce variability and improve robustness.
    

### Model Training

- Used state-of-the-art transformer models via `keras_nlp`.
    
- Fine-tuned models with hyperparameter optimization.
    
- Implemented performance evaluation metrics such as accuracy, precision, recall, and F1-score.
    

### Experimentation

- Compared results across different pre-trained transformer architectures.
    
- Experimented with varying preprocessing pipelines and augmentation strategies.
    

## Results

This project was exploratory in nature, so the results are not benchmarked against the top Kaggle scores. The primary takeaway is the hands-on experience gained in working with:

- Text data preprocessing.
    
- Fine-tuning and deploying transformers.
    
- Understanding the challenges in real-world NLP tasks.
    

## Limitations

- **Focus**: This notebook is not an optimized solution but a demonstration of learning and experimentation.
    
- **Performance**: Model performance is not maximized due to limited hyperparameter tuning and lack of computational resources.
    

## How to Use

1. Clone the repository.
    
    ```
    git clone https://github.com/yourusername/disaster-tweets-nlp.git
    cd disaster-tweets-nlp
    ```
    
2. Install the required dependencies.
    
    ```
    pip install -r requirements.txt
    ```
    
3. Run the Jupyter notebook to explore the code and results.
    

## Key Takeaways

This project highlights my progress in NLP and my ability to:

- Work with large text datasets.
    
- Build pipelines for preprocessing and augmentation.
    
- Leverage cutting-edge tools like transformers to tackle NLP problems.
    

## Future Improvements

- Extend hyperparameter tuning for improved performance.
    
- Incorporate more advanced augmentation techniques.
    
- Add deeper error analysis and explainability tools.
    

---

**Note**: This project is part of my ongoing learning journey in NLP and is intended to showcase the skills I have gained so far.
