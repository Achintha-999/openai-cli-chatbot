# 🤖 OpenAI CLI Chatbot 🚀

<div align="center">

**A lightweight Python CLI chatbot powered by OpenAI (default: GPT‑3.5 Turbo).**  
Chat with an AI directly from your terminal in a simple interactive loop.

---

### ✨ Fast • 🧠 Smart • 🧩 Configurable • 🖥️ Terminal-first

</div>

---

## 📌 Overview

The **OpenAI CLI Chatbot** is a simple, terminal-based chatbot written in **Python**.  
It connects to OpenAI’s API to generate responses, allowing you to hold a continuous conversation from the command line.

---

## 🌟 Highlights

- 💬 **Interactive CLI chat** (conversation loop)
- 🔌 **OpenAI API integration** for high-quality responses
- 🛠️ **Configurable settings** via `config.json` (model, temperature, max tokens)
- 🐍 **Pure Python** and easy to run locally
- 🧼 **Minimal setup** (install deps → set API key → run)

---

## 🧰 Tech Stack

- 🐍 **Python** (3.7+)
- 🤝 **OpenAI API**
- 📄 Config via **JSON** (`config.json`)

---

## ✅ Prerequisites

Before you start, make sure you have:

- 🐍 **Python 3.7 or higher**
- 🔑 An **OpenAI API key**  
  Create one at: https://platform.openai.com/

---

## 📥 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Achintha-999/openai-cli-chatbot.git
cd openai-cli-chatbot
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Set your OpenAI API key

#### macOS / Linux (bash/zsh)
```bash
export OPENAI_API_KEY="your_api_key_here"
```

#### Windows (PowerShell)
```powershell
setx OPENAI_API_KEY "your_api_key_here"
```

> 📝 Note (Windows): After running `setx`, **restart your terminal** so the variable is available.

---

## 🚀 Quick Start

Run the chatbot:

```bash
python app.py
```

Then type your message and press **Enter**.  
To stop the program, use **Ctrl + C** (or follow any built-in exit prompt if your script provides one).

---

## ⚙️ Configuration

You can customize the chatbot by editing **`config.json`**:

- 🧠 **model** — Choose the model name (default: GPT‑3.5 Turbo)
- 🎛️ **temperature** — Controls creativity (higher = more creative)
- 📏 **max_tokens** — Controls max response length

> 🔁 After editing `config.json`, re-run `python app.py` to apply changes.

---

## 🧪 Example Session (CLI)

```text
You: Hello!
Bot: Hi! How can I help you today?
```

---

## 🛡️ Troubleshooting

### 🔑 `OPENAI_API_KEY` not found

Check whether your key is available in the current terminal session:

```bash
echo $OPENAI_API_KEY
```

If nothing appears, set it again (see installation step 3).

---

### 🐍 Python / pip mismatch

If your machine uses `python3` and `pip3`, try:

```bash
python3 --version
pip3 install -r requirements.txt
python3 app.py
```

---

## 🗺️ Roadmap (Ideas)

- 🧾 Save chat history to a file
- 🧠 System prompt / persona selector
- 🧰 CLI arguments (model, temperature, max tokens)
- 🌐 Support for multiple providers (optional)

---

## 🤝 Contributing

Contributions are welcome and appreciated! 🙌

1. 🍴 Fork the repo  
2. 🌿 Create a branch (`feature/my-change`)  
3. ✅ Commit your changes  
4. 🔁 Open a Pull Request  

---

## 📜 License

🪪 MIT License — see [LICENSE](LICENSE)

---

## 💡 Acknowledgments

- 🤖 [OpenAI](https://openai.com/) for the models and API
- 🌍 The open-source community for tools and inspiration

---

<div align="center">

⭐ If you like this project, consider starring the repository!

</div>
