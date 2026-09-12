# Sentiment Analysis using Streamlit and Hugging Face

## Project Description

This project is a simple Sentiment Analysis web application developed using Python, Streamlit, and Hugging Face Transformers.

The application analyzes a user-entered sentence and predicts whether the sentiment is **Positive** or **Negative**. It also displays the confidence score of the prediction.

## Technologies Used

* Python
* Streamlit
* Hugging Face Transformers
* DistilBERT
* PyTorch

## Model Used

The project uses the Hugging Face model:

`distilbert-base-uncased-finetuned-sst-2-english`

This model is used for text sentiment classification.

## Features

* Simple and user-friendly interface
* Accepts sentences as input
* Predicts Positive or Negative sentiment
* Displays prediction confidence
* Uses a pre-trained Hugging Face model
* Streamlit-based web application

## Project Structure

```text
sentimental/
│
├── app.py
├── requirements.txt
└── README.md
```

## Installation

Open the terminal inside the project folder and install the required packages:

```bash
pip install -r requirements.txt
```

## Requirements

The `requirements.txt` file contains:

```text
streamlit
transformers
torch
```

## How to Run

Open the terminal in the project folder and run:

```bash
python -m streamlit run app.py
```

After running the command, Streamlit will provide a local URL. Open the URL in a web browser to access the application.

## How to Use

1. Open the Sentiment Analysis application.
2. Enter a sentence in the text box.
3. Click the **Analyze Sentiment** button.
4. The application displays the predicted sentiment.
5. The confidence score is also displayed.

## Example

### Input

```text
I really enjoyed this movie!
```

### Output

```text
Sentiment: POSITIVE
Confidence: 99%
```

## Conclusion

This project demonstrates how a pre-trained Hugging Face Transformer model can be integrated with Streamlit to create a simple Sentiment Analysis application. It provides an easy way to analyze the sentiment of text and understand the model's prediction confidence.
