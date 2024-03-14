# GPTalk - OpenAI Chatbot Project

## Introduction
This project is a Python-based tool that leverages the OpenAI API to create an interactive chatbot. It integrates various Python libraries including `python-dotenv` for environment variable management, `pydub` for audio file manipulation, `instabot` for Instagram interactions, and `Pillow` for image processing. The chatbot is designed to provide users with a versatile interaction experience, ranging from text-based chatting to handling multimedia content.

## Requirements
- Python 3.x
- A valid OpenAI API key

## Installation

### Clone the repository
First, clone the repository to your local machine using:

```
git clone https://github.com/lfelipediniz/GPTalk.git
```

### Set up the virtual environment
Navigate to the project directory and create a virtual environment:

```
cd ./GPTalk
python3 -m venv chatbot
```

Activate the virtual environment:

- On Windows:
```
chatbot\Scripts\activate
```

- On Unix or MacOS:
```
source chatbot/bin/activate
```

### Install dependencies
Install the required Python libraries with pip:

```
pip install openai python-dotenv pydub instabot Pillow
```

### Configure environment variables
Create a `.env` file in the root of your project directory. Add your OpenAI API key and any other required configurations:

```
OPENAI_API_KEY='your_api_key_here'
```

Replace `'your_api_key_here'` with your actual OpenAI API key.

## Running the Project

To run the chatbot, navigate to the project directory, ensure your virtual environment is activated, and execute the main script:

```
python main.py
```

