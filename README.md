# OpenAI CLI Chatbot

This repository contains a command-line interface (CLI) chatbot built using OpenAI's GPT models. The chatbot allows users to interact with OpenAI's language model directly from their terminal, making it a lightweight and efficient tool for conversational AI.

## Features

- **Interactive CLI**: Engage in real-time conversations with the chatbot via the terminal.
- **Customizable**: Modify the chatbot's behavior and personality by tweaking the prompt or settings.
- **Lightweight**: No heavy dependencies; runs directly in the terminal.
- **OpenAI API Integration**: Seamlessly integrates with OpenAI's API for generating responses.

## Prerequisites

Before using this project, ensure you have the following:

- Python 3.7 or higher
- An OpenAI API key (sign up at [OpenAI](https://platform.openai.com/signup/))

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Achintha-999/openai-cli-chatbot.git
    cd openai-cli-chatbot
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up your OpenAI API key:

    ```bash
    export OPENAI_API_KEY=your_api_key_here
    ```

    Replace `your_api_key_here` with your actual OpenAI API key.

## Usage

Run the chatbot using the following command:

```bash
python chatbot.py
```

Follow the on-screen instructions to start chatting with the bot.

## Configuration

You can customize the chatbot's behavior by editing the `config.json` file. For example, you can adjust the model, temperature, or maximum token limit.

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenAI](https://openai.com/) for providing the GPT models and API.
- The open-source community for their valuable tools and libraries.

---

Feel free to explore, contribute, and enjoy building with this CLI chatbot!