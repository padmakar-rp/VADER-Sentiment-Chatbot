# VADER-Sentiment-Chatbot
A Python-based Sentiment Analysis Chatbot built using NLTK and VADER. The chatbot analyzes user input as Positive, Negative, or Neutral and generates dynamic responses while logging conversation data for analysis.

NOTE : { CHATBOT CREATED USING GOOGLE COLAB}

# VADER Sentiment Analysis Chatbot

## Project Overview

This is a Python-based Sentiment Analysis Chatbot built using NLTK and the VADER Sentiment Analyzer.

The chatbot:
- Analyzes user input sentiment (Positive, Negative, Neutral)
- Generates dynamic responses based on detected sentiment
- Logs conversation history
- Displays sentiment statistics at the end
- Organizes conversation data using Pandas for structured analysis

---

## Features

- Sentiment detection using VADER (Valence Aware Dictionary and sEntiment Reasoner)
- Text preprocessing (tokenization, stopword removal, stemming)
- Random dynamic responses (20 responses per sentiment category)
- Conversation logging
- Sentiment statistics summary
- DataFrame display using Pandas

---

## Technologies Used

- Python
- NLTK
- VADER Sentiment Analyzer
- Pandas
- Random module
- String processing utilities

---

## Project Structure

```
VADER-Sentiment-Chatbot/
│
├── chatbot.py
├── README.md
└── output_screenshots/
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/VADER-Sentiment-Chatbot.git
cd VADER-Sentiment-Chatbot
```

### 2. Install Required Libraries

```bash
pip install nltk pandas
```

---

## How to Run

```bash
python chatbot.py
```

Start chatting with the bot in the terminal.

Type `exit` to stop the chatbot.

---

## Example Output

```
You: I am feeling very happy today!
Bot: That's wonderful! I'm glad to hear that.
[Sentiment: Positive, Score: 0.851]
```

---

## Sentiment Categories

- Positive → Compound Score ≥ 0.05
- Negative → Compound Score ≤ -0.05
- Neutral → Between -0.05 and 0.05

---

## How It Works

1. User input is received.
2. Text is preprocessed (lowercase conversion, punctuation removal, stopword removal, stemming).
3. VADER analyzes the raw input text.
4. Sentiment label is determined using compound score thresholds.
5. A random response is selected from the corresponding sentiment category.
6. Interaction details are logged into a conversation history list.
7. At the end of the session, conversation statistics are displayed using Pandas.

---

## Future Improvements

- Add graphical user interface (GUI) using Tkinter or Streamlit
- Deploy as a web-based application
- Compare VADER with machine learning sentiment models
- Export conversation logs to CSV file
- Add user authentication and session storage

---
