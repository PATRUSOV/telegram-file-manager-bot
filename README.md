# 📝 Telegram File Manager Bot

A professional, asynchronous Telegram bot built with **aiogram 3.x** and
**aiosqlite**.\
It allows you to organize messages, media, and personal notes into
custom categories with a clean hybrid interface.

------------------------------------------------------------------------

## 🚀 Features

-   **Dynamic Categories** -- Create, rename, and delete categories at
    runtime
-   **Universal Content Support** -- Save text, photos, videos,
    documents, and more
-   **Hybrid UI** -- Reply keyboards for navigation and inline keyboards
    for contextual actions
-   **Persistent Storage** -- Asynchronous SQLite database for reliable
    performance

------------------------------------------------------------------------

## 📂 Project Structure

    .
    ├── databases/          # SQLite storage directory
    ├── src/
    │   └── main.py         # Main application entry point
    ├── .env                # Private environment variables (DO NOT COMMIT)
    ├── .gitignore          # Git exclusion rules
    ├── requirements.txt    # Python dependencies
    └── README.md           # Project documentation

------------------------------------------------------------------------

## 🛠 Installation

### 1. Clone the Repository

``` bash
git clone https://github.com/PATRUSOV/telegram-file-manager-bot.git
cd telegram-file-manager-bot
```

### 2. Fill Environment File

Fill in the `.env` file in the project root:

``` env
BOT_TOKEN="your_token_here"
LOG_LEVEL="INFO"
```

### 3. Install Dependencies

``` bash
pip install -r requirements.txt
```

### 4. Run the Bot

``` bash
cd src
python main.py
```

------------------------------------------------------------------------

## ⚙️ Configuration

| Variable   | Description                                  | Default   |
|------------|----------------------------------------------|-----------|
| BOT_TOKEN  | Telegram Bot API token from BotFather        | None      |
| LOG_LEVEL  | Logging level: DEBUG, INFO, WARNING, ERROR   | INFO      |

------------------------------------------------------------------------

## 📄 License

This project is open-source and available under the MIT License.
