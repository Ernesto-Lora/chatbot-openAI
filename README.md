# Chatbot openai-API

Django application that integrates with the OpenAI API to generate natural language responses to user inputs. The application is designed to work with both Telegram and web browsers, allowing users to interact with it in whichever way is most convenient for them.

The application comes with Login, Logout, and Sign up pages, which allow users to create accounts and access the full functionality of the app. Additionally, users have the option to remove their conversation with one click, ensuring that their privacy is protected.

Once a user inputs a message via Telegram or the web interface, the Django application uses the OpenAI API to generate a response, which is then sent back to the user via the same channel. The application's integration with the OpenAI API allows for a wide range of possible use cases, from customer service chatbots to intelligent assistants for websites and apps.

![app](app.png)

The code is written in Python, using the Django web framework and the OpenAI API for natural language processing. The repository includes all the necessary files to run the application, as well as documentation on how to set it up and use it.

If you're interested in exploring the possibilities of natural language generation with Django and the OpenAI API, this repository is a great starting point. Feel free to clone the repo and start experimenting!

Prerequisites:

Python >=3.10

OpenAI API key

Telegram bot token (if using Telegram integration)

`git clone https://github.com/Ernesto-Lora/chatbot-openAI.git`

Build and run app.
`docker-compose run --build`
