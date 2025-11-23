# FXAdvisor-Currency-Conversion-ChatBot

FXAdvisor is a smart and lightweight currency conversion chatbot built using Flask, Dialogflow, and an online currency conversion API. It enables users to convert amounts between different currencies in real time simply by chatting with the bot.
This project includes a complete backend service written in Python (Flask) and a front-end interface integrated with Dialogflow.

## Features

💬 Dialogflow-powered conversational interface

🔁 Real-time currency conversion using an external API

🌐 Flask backend to process and respond to webhook requests

📱 Minimal, clean, and user-friendly design

## How It Works
1. Dialogflow Interaction

The chatbot receives user queries (amount + source currency + target currency) through Dialogflow’s webhook system.

2. Flask Backend

The backend (app.py) processes POST requests from Dialogflow, extracts parameters, fetches conversion rates, and returns a response.

3. Currency Conversion

The app fetches live conversion rates using an external API.

4. Frontend UI

A simple HTML interface embeds the Dialogflow bot and provides a friendly landing page for users.
