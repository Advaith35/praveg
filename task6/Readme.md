## Screenshots

![Bot Screenshot](preview.jpg)

This screenshot shows the bot's user interface and how it interacts with users.

```markdown
# Movie Info Telegram Bot

A Telegram bot that provides movie information and allows exporting the data in CSV format.

## Getting Started

To use this bot, follow these steps:

1. Install the required dependencies by running:
   ```bash
   pip install telebot requests
   ```

2. Obtain a Telegram bot token by creating a new bot on Telegram and get an OMDB API key by registering on the [OMDB API website](http://www.omdbapi.com/).

3. Replace the placeholders in the script with your Telegram bot token and OMDB API key.

4. Run the bot script:
   ```bash
   python bot.py
   ```

## Usage

- Start the bot by sending the `/start` or `/hello` command. The bot will respond with a greeting.

- Use the `/help` command to get information about available commands.

- To get movie details, use the `/movie` command followed by the movie name, like `/movie The Shawshank Redemption`.

- Use the `/export` command to export all movie data in CSV format.

- Stop the bot with the `/stop` or `/bye` command.

## Prerequisites

- Python 3.x
- `telebot` library
- `requests` library

## Acknowledgements

- This bot uses the [Telebot](https://github.com/eternnoir/pyTelegramBotAPI) Python library for interacting with the Telegram Bot API.

- Movie information is fetched using the [OMDB API](http://www.omdbapi.com/).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

This README template includes sections for getting started, usage instructions, prerequisites, acknowledgments, and licensing information. Remember to adapt it to your specific project and provide accurate details.
