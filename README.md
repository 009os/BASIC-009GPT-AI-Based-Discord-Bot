# 009GPT-AI-Based-Discord-Bot (COLLEGE ASSIGNMENT)

An AI-powered Discord chatbot built with Python, powered by OpenAI's GPT model. This project leverages the `discord.py` library for seamless integration with Discord and utilizes the OpenAI API to provide intelligent, conversational responses to user queries within any Discord server.

---

## Features

- **AI-Powered Chatbot**: Uses OpenAI's GPT models to generate human-like responses.
- **Discord Integration**: Built on top of `discord.py`, making it easy to add to any server.
- **Customizable Commands**: Supports custom commands and extensible functionality.
- **Easy Deployment**: Designed to be easily deployed on platforms like Replit or any Python-supported environment.
- **Secure API Usage**: Sensitive API keys are managed through environment variables for security.

---

## Installation

### Prerequisites

- Python 3.8+
- [discord.py](https://github.com/Rapptz/discord.py)
- [OpenAI Python SDK](https://github.com/openai/openai-python)

### Setup

1. **Clone the repository**
    ```bash
    git clone https://github.com/009os/BASIC-009GPT-AI-Based-Discord-Bot.git
    cd BASIC-009GPT-AI-Based-Discord-Bot
    ```

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up environment variables**

    Create a `.env` file or set environment variables for:
    - `DISCORD_TOKEN`: Your Discord bot token
    - `OPENAI_API_KEY`: Your OpenAI API key

    Example `.env`:
    ```
    DISCORD_TOKEN=your_discord_bot_token
    OPENAI_API_KEY=your_openai_api_key
    ```

4. **Run the bot**
    ```bash
    python main.py
    ```

---

## Usage

- Invite your bot to a Discord server.
- Interact with the bot by mentioning it or using configured commands.
- The bot will respond with AI-generated replies using GPT.

---

## File Structure

```
├── main.py                # Main bot logic
├── requirements.txt       # Python dependencies
├── README.md              # This file
├── .env.example           # Example environment file
└── ...                    # Other supporting files/modules
```

---

## Configuration

- **Custom Commands**: You can extend the bot by adding new commands or features inside `main.py` or by creating new modules.
- **OpenAI Parameters**: Tweak model temperature, max tokens, and other settings in API call sections for different response behaviors.

---

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Acknowledgements

- [discord.py](https://github.com/Rapptz/discord.py)
- [OpenAI API](https://openai.com/api/)
- [Replit](https://replit.com/) (for online deployment)

---

## Contact

For questions or support, please open an issue on GitHub or contact [009os](https://github.com/009os).
