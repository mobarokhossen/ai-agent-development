# 🤖 AI Agent Projects (Google Colab Compatible)

This repository contains two practical Python-based AI automation tools. You can use these directly on **Google Colab** for experimentation, demos, and integration into your workflow.

---

## 📁 Project Files

| File | Description |
|------|-------------|
| [`linkedin_post_generate_by_ai.py`](./linkedin_post_generate_by_ai.py) | AI-powered LinkedIn post generator |
| [`project_build_a_basic_ai_powered_faq_bot.py`](./project_build_a_basic_ai_powered_faq_bot.py) | Basic AI FAQ bot that responds to user queries |

---

## 🧠 linkedin_post_generate_by_ai.py

This script uses AI (e.g., OpenAI's GPT) to generate professional LinkedIn posts based on prompts or keywords.

### ✅ Features
- Prompt-based LinkedIn content generation
- Easily extendable to work with APIs or schedulers (Zapier, n8n)
- Lightweight and Google Colab-friendly

### ▶️ Example

```python
Enter a topic: AI in Healthcare
Generated Post:
"AI is revolutionizing healthcare. From predictive diagnosis to robotic surgery, the future of patient care is smarter, faster, and more personalized. #AI #Healthcare #Innovation"
````

---

## 💬 project\_build\_a\_basic\_ai\_powered\_faq\_bot.py

A simple command-line chatbot that uses AI to answer FAQs interactively.

### ✅ Features

* Load FAQ context and answer queries using an AI model
* Interactive CLI for testing responses
* Extendable to web or app interfaces

### ▶️ Example

```bash
User: What services do you offer?
Bot: We provide AI-driven automation tools, including chatbots and content generators.
```

---

## 🛠️ Setup Instructions

These scripts are designed for quick use in **Google Colab** or local environments.

### ✅ Requirements

* Python 3.8+
* OpenAI API key (or other LLM API)
* Required Python packages

### 📦 Install Requirements

In Google Colab:

```python
!pip install openai python-dotenv
```

In `.env` (or directly in code):

```python
import os
os.environ["OPENAI_API_KEY"] = "your-api-key"
```

---

## 📌 To-Do / Improvements

* [ ] Add Streamlit or Gradio web interface
* [ ] Deploy FAQ bot as a REST API
* [ ] Add persistent memory for FAQ history
* [ ] Export LinkedIn posts to `.txt` or Google Docs

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Mobarok Hossen**
Senior Software Engineer
🔗 [MobarokHossen.com](https://mobarokhossen.com)
🟢 *Silent help, strong results.*

---

## ⭐ Star the Repo

If this helped you, please consider giving a ⭐ to support more open-source AI tools.

```

---

Let me know if you want:
- The GitHub URLs filled in directly
- A `requirements.txt` generated
- Deployment guide for Streamlit or Flask added
```
