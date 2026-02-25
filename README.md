# OpenAI CLI Chatbot

A lightweight Python CLI chatbot that lets you chat with OpenAI models from your terminal in an interactive conversation loop (default: **GPT-3.5 Turbo**).

## Features

- **Interactive terminal chat** with a simple conversational loop
- **OpenAI API integration** for high-quality responses
- **Configurable behavior** (model, temperature, max tokens) via `config.json`
- **Minimal setup** and easy to run locally

## Requirements

- **Python 3.7+**
- An **OpenAI API key**

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Achintha-999/openai-cli-chatbot.git
   cd openai-cli-chatbot
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set your OpenAI API key**

   macOS / Linux:
   ```bash
   export OPENAI_API_KEY="your_api_key_here"
   ```

   Windows (PowerShell):
   ```powershell
   setx OPENAI_API_KEY "your_api_key_here"
   ```

   Note: After using `setx`, restart your terminal so the environment variable is available.

## Usage

Run the chatbot:

```bash
python app.py
```

Then type your messages and press **Enter** to receive responses.

To exit the chat, use `Ctrl+C` (or follow any on-screen exit prompt if implemented in the script).

## Configuration

You can customize chatbot settings in `config.json`, for example:

- **model**: the OpenAI model name to use  
- **temperature**: creativity level (higher = more creative)
- **max_tokens**: maximum length of responses

If you change `config.json`, re-run `python app.py` to apply changes.

## Troubleshooting

### `OPENAI_API_KEY` not found
Make sure the environment variable is set and available in your current terminal session:

```bash
echo $OPENAI_API_KEY
```

If it prints nothing, set it again (see Installation step 3) and restart the terminal if needed.

### Dependency / Python version issues
Confirm your Python version:

```bash
python --version
```

If you have multiple Python versions installed, you may need to use `python3` and `pip3`.

## Contributing

Contributions are welcome.

1. Fork the repo
2. Create a feature branch
3. Commit your changes
4. Open a pull request

## License

MIT — see [LICENSE](LICENSE).

## Acknowledgments

- [OpenAI](https://openai.com/) for the models and API
- The open-source community for inspiration and tooling
