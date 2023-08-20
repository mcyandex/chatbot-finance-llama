# Financial Bot - Retrieval-based QA Chatbot

Welcome to the Financial Bot project! This project demonstrates the setup of a retrieval-based question-answering (QA) chatbot that uses the langchain library for handling interactions and retrieval.

## Features

- Provides answers to user queries based on a database of financial information.
- Uses a custom prompt template to structure the QA interactions.
- Leverages langchain for language modeling and retrieval.
- Uses chainlit for managing the chatbot interactions.

## Getting Started

## System Requirements

- The `llama-2-7b-chat.ggmlv3.q4_0.bin` model can be run on systems with 8GB of RAM.
  
### Installation

1. Clone this repository: `git clone https://github.com/yourusername/financial-bot.git`
2. Install the required libraries: `pip install langchain chainlit`

### Requirements

To install the required dependencies, you can use the provided `requirements.txt` file. Simply run:

```bash
pip install -r requirements.txt
```

### Usage

1. Configure the `DB_faiss_path` variable to point to your local FAISS database.
2. Customize the prompt template in the `set_custom_prompt` function if needed.
3. Run the chatbot using `chainlit run app.py -w`.



