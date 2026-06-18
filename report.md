# Telegram Chatbot Assignment Report

## Objective

The objective of this project is to create a simple Telegram chatbot using the Telegram Bot API.

## Features Implemented

### /start

Displays a welcome message and instructions for using the bot.

### /help

Shows the list of available commands.

### /echo <message>

Repeats the message entered by the user.

## Design Decisions

* Used Python for implementation.
* Used the python-telegram-bot library because it provides an easy interface to interact with the Telegram Bot API.
* Implemented command handlers to manage different commands separately.

## Bot Setup

1. Open Telegram and search for @BotFather.
2. Create a new bot using the /newbot command.
3. Copy the generated API token.
4. Replace YOUR_BOT_TOKEN in bot.py with the generated token.
5. Install dependencies:

```bash
pip install -r requirements.txt
```

6. Run the bot:

```bash
python bot.py
```

## Testing

Tested the following commands:

* /start
* /help
* /echo Hello World

All commands responded correctly.

## Challenges Faced

* Understanding Telegram Bot API token generation.
* Configuring command handlers properly.
* Ensuring correct parsing of user messages for the /echo command.

## Conclusion

The chatbot was successfully developed, tested, and deployed locally. It responds correctly to all required commands and demonstrates the basic functionality of a Telegram chatbot.
