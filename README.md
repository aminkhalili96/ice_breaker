# Ice Breaker

# 🧊 Ice Breaker

An **AI-driven web app** that uses **agents**, **LLMs**, and **LangChain pipelines** to generate personalized LinkedIn ice breakers.

## 🚀 Features

- 🤖 Uses **OpenAI GPT-4o** and **Ollama LLaMA3** models.
- 🔗 Leverages **LangChain** to build prompt pipelines and chains.
- 🕵️ Scrapes LinkedIn profiles for target user data (mocked or real with API key).
- 🪄 Generates:
  - A short summary of the person.
  - Two interesting facts about them.
- 🌐 Web interface built with **Flask**.

---

## 🛠️ Tech Stack

- Python
- Flask
- LangChain
- OpenAI API & Ollama LLM
- dotenv (.env) for secrets
- GitHub for version control

---

## 📦 Setup

### Prerequisites

- Python 3.11+
- Pipenv
- OpenAI API key
- (Optional) Scrapin API key for LinkedIn scraping

### Installation

```bash
git clone https://github.com/aminkhalili96/ice_breaker.git
cd ice_breaker
pipenv install


Run the app
pipenv shell
python app.py

By default, the app runs on:
http://127.0.0.1:5001

🔐 Environment Variables

Create a .env file in the root of the project:
OPENAI_API_KEY=your_openai_api_key
SCRAPIN_API_KEY=your_linkedin_scrapin_api_key

## License
This project is not licensed for public use. It is intended for portfolio and educational purposes only.

