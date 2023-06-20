# Chatbot in PyTorch

This is a simple Conversational AI that was developed by me and Kuber Vajpayee(https://github.com/kuber2001) during the final presentation phase in SIH 2022
It is hosted on Telegram and can easily be deployed on the local systems create your own Telegram Bot that uses NLP.

# Introduction

Conversational AI refers to the use of natural language processing (NLP) and other technologies to enable human-like communication with computer systems. This can include speech recognition, text-to-speech synthesis, and natural language understanding. Some examples of conversational AI include virtual assistants, chatbots, and voice assistants. These systems can be used in a variety of applications such as customer service, e-commerce, and personal assistance. The goal of conversational AI is to make interactions with computers more natural and intuitive for users.

# Working
The primary model is developed in PyTorch using the Artificial Neural Networks and although the model is not itself very robust, or integrated with feedback system. It is primarily based on the architecture of Google Dialogflow which focuses on the detecting the intents and then generating the responses accordingly.
It has been integrated with the Telegram bot that is freely available.


## Run Locally

### To construct the Google Dialogflow bot

1.	Go to the DialogFlow ES console
2.	Create a new Project
3.	Import the zip file provided in the repository
4.	Create the Flask Server and enable webhook services in Dialogflow providing the Webhook url of ngrok

### Deploy the Flask Server

Clone the project

```bash
  git clone https://github.com/Demogorgon24242/SIH_Chatbot
```

Go to the project directory

```bash
  cd SIH_Chatbot
```

Install libraries

```python
  pip install -r requirements.txt
```

Run python file

```bash
  python train.py
  python chat.py
  python app.py
```
Create a bot on the Telegram Bot Channel

Integrate with the api key provided there in the file chat.py

