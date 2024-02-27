# Simple Discord AI Chatbot
This Chatbot uses [Pawans](https://discord.pawan.krd) API to generate responses for free.

The bot is really simple and customizable.

## Features:
- Context when running in a dedicated channel
- Asynchronous generation
- Option to run in a dedicated channel (`ai!setchatbotchannel (channel)`)
- Proper permissions
- API Key status for the whole bot (`ai!status`) (can be turned of in main.py)
- Customizable
- Separate model and context length for chatting without context
- Token counter and token limiter

## Setup instructions:
1. Join [Pawan's Discord Server](https://discord.pawan.krd)
2. Verify (if you have to) and go to the channel "#bot"
3. Type in /key
4. Copy the key to config.py
5. Install discord.py, tiktoken and openai (`python -m pip install discord tiktoken openai`)
6. Go to the [Discord Developer Portal](https://discord.com/developers/applications) and Generate a bot token
7. Copy the token to config.py
8. Uncomment one of the models in the config.py file
9. Configure rest of the stuff in the config.py, the comments are there to explain everything
10. Done!

**IMPORTANT! IF YOU GET ANY ERRORS WHEN GENERATING A RESPONSE, RUN /resetip IN THE #bot CHANNEL IN THE PAWAN SERVER YOU JOINED EARLIER**
