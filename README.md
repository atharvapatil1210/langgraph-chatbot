# LangGraph Chatbot

LangGraph Chatbot is an interactive, AI-powered chatbot designed to engage users with natural language understanding and responses. This notebook demonstrates the creation, training, and deployment of a chatbot using advanced machine learning and natural language processing (NLP) techniques.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Project Overview

The LangGraph Chatbot leverages pre-trained language models and integrates them into a conversational flow. The project utilizes NLP techniques and can be further customized or expanded to support additional features like web scraping, token tracking, and voice search.

## Features

- **Natural Language Processing**: Understands and responds to user inputs in natural language.
- **Integration**: Connects with web scraping, CSV data, and custom user inputs.
- **Multilingual Support**: Includes options for Rajasthani regional language and other languages.
- **Text-to-Speech and Voice Search**: For enhanced accessibility and user experience.
- **Streamlit Integration**: Provides a graphical user interface (GUI) for interacting with the chatbot.

## Requirements

- Python 3.7 or later
- Jupyter Notebook
- Streamlit
- Key Libraries: `gpt_index`, `langchain`, `pandas`, `numpy`, `nltk`, `transformers`

Install the required libraries by running:

```bash
pip install -r requirements.txt
```

> Note: Ensure all dependencies from the `requirements.txt` file are installed.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/atharvapatil1210/langgraph_chatbot.git
    cd langgraph_chatbot
    ```

2. **Set Up Virtual Environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Required Libraries**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Launch Jupyter Notebook**:
    ```bash
    jupyter notebook langgraph_chatbot.ipynb
    ```

## Usage

1. Open the Jupyter notebook `langgraph_chatbot.ipynb` and run each cell sequentially to initialize and interact with the chatbot.
2. Use the Streamlit app by running:
    ```bash
    streamlit run app.py
    ```
3. Follow the on-screen instructions to communicate with the chatbot. Customize further based on your requirements.

## License

This project is licensed under the MIT License.
