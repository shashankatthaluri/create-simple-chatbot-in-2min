# Simple ChatGPT Chatbot in Python 🤖

This is a simple implementation of a chatbot using the OpenAI API and Python. With just a few lines of code, you can create a conversational chatbot that can respond to your prompts. 💬

## Prerequisites 📋

Before running this code, make sure you have the following:

- Python installed on your machine 🐍
- OpenAI Python library (`openai`) installed (`pip install openai`) 📥
- An OpenAI API key (you can get one from https://platform.openai.com/account/api-keys) 🔑

## Usage 🚀

1. Open the `simple_chatbot.py` file and replace `"YOUR API KEY GOES HERE"` with your actual OpenAI API key.

2. Run the script:

```bash
python simple_chatbot.py
```
3.  The script will prompt you to enter your message. Type your message and press Enter. 💬

4. The chatbot will respond with its generated response based on your input. 🔊

5. To exit the chatbot, type quit, exit, or bye. 🚪


## How It Works ⚙️

The script defines a chat_gpt_ function that takes a prompt as input and uses the OpenAI API to generate a response. The response is then printed to the console.

The main loop of the script continuously prompts the user for input. When the user types quit, exit, or bye, the loop breaks, and the script terminates.

With this simple implementation, you can quickly set up a chatbot and experiment with the OpenAI API. 🎉
