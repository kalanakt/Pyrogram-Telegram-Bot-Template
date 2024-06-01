# Pyrogram Telegram Python Bot Template

This is a template for creating Telegram bots using Pyrogram, MongoDB, and Python.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Pyrogram library
- MongoDB

### Installing

1. Clone the repository:

   ```bash
   git clone https://github.com/kalanakt/Pyrogram-Telegram-Bot-Template telegrambot
   cd telegrambot
   ```

2. Install the dependencies:

   
   ```bash
   #optional
   python3 -m venv env
   source env/bin/activate # in mac OS
   env/Scripts/activate.bat #In CMD
   env/Scripts/Activate.ps1 #In Powershel
   ```

   ```bash
   pip install -r requirements.txt
   ```

4. Set up your MongoDB database and get the connection URI.

5. Create a `.env` file in the project root and add your MongoDB connection URI and your Telegram bot token:

   ```plaintext
   DATABASE_URI=your-mongodb-connection-uri
   DATABASE_NAME=your-database-name
   API_ID=your-api-id
   API_HASH=your-api-hash
   BOT_TOKEN=your-bot-token
   ```

6. Run the bot:

   ```bash
   python bot.py
   ```

## Features

- Pyrogram framework for interacting with the Telegram API.
- MongoDB for storing data.
- Easily extendable for adding more features.

## Contributing

Contributions are welcome! Please follow the standard guidelines when contributing.

## License

This project is licensed under the MIT [License](LICENSE).
