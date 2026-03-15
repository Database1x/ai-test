# 🐛 GPT CLI - OpenRouter Edition

**GPT CLI** is a sleek command-line interface (CLI) for interacting with LLMs via OpenRouter API. It supports multiple models, automatic language detection, and customizable settings — all in a terminal-friendly format.

> ⚡ Lightweight. Powerful. Fully terminal-based. Made with ❤️ by [Database](https://github.com/Database1x)

---

## 🚀 Features

- 🔗 OpenRouter API integration
- 🌍 Auto language detection (via `langdetect`)
- 🗣️ Multi-language support: English, Indonesian, Spanish, Arabic, Thai, Portuguese
- 💬 Interactive chat session with typing effect
- 🎨 Stylish CLI UI with colors and banners
- 🔧 Easy configuration of API key and model
- 💾 Config auto-saved in `gpt_config.json`

---

## 📦 Requirements

- Python 3.6+
- `pip` installed
- OpenRouter API key ([get one here](https://openrouter.ai/))

---

## ⚙️ Installation

Clone the repo:

```bash
git clone https://github.com/Database1x/ai-test
cd gpt
python3 gpt.py
```

## 🔑 Set Your API Key

You can set your OpenRouter API key via the main menu:
```
[3] Set API Key
```

Or manually edit the config file:
```
{
  "api_key": "YOUR_API_KEY_HERE",
  "base_url": "https://openrouter.ai/api/v1",
  "model": "deepseek-v3.2",
  "language": "English"
}
```

## 🧠 Usage Example

```
python3 ai.py
```

## Menu will appear:

```
[ Main Menu ]
1. Language: English
2. Model: deepseek-v3.2
3. Set API Key
4. Start Chat
5. Exit
```

## 🧪 Custom Models

From the menu, you can enter your own model ID (from OpenRouter).

Example:
```
01-ai/Yi-34B-Chat
meta-llama/llama-3-8b-instruct:nitro
```

### 📷 Example Screenshot
![GPT CLI Example](assets/example.jpg)

## 👨‍💻 Author

GitHub: @database1x 

Project URL: https://github.com/Database1x/ai-test
