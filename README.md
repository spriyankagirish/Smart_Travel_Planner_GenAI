
# 🚀 AI-Powered Travel Planner using Gemini Pro + Streamlit

An intelligent travel assistant built with Streamlit and Google Gemini Pro (via LangChain), designed to provide personalized travel recommendations including cab, train, bus, and flight options along with cost estimates, travel time, and useful tips.

![Made with Streamlit](https://img.shields.io/badge/Made%20with-Streamlit-red?logo=streamlit)
![LangChain](https://img.shields.io/badge/Powered%20by-LangChain-blueviolet?logo=python)
![Google Gemini Pro](https://img.shields.io/badge/Google-Gemini%20Pro-yellow?logo=google)

---

## 🌍 Live Demo

👉 [Try it out on Hugging Face Spaces][(https://huggingface.co/spaces/PriyankaSG/AIpoweredTravelPlanner_GenAI)](https://huggingface.co/spaces/PriyankaSG/SmartTravelPlanner_GenAI)

---

## 📌 Features

- 🧠 AI-generated travel suggestions (cab, bus, train, flight)
- 💰 Includes estimated cost and duration
- 💡 Travel tips and recommendations
- ✍️ Simple and intuitive Streamlit interface
- 🔒 API key handled securely via Streamlit Secrets

---

## 📦 Tech Stack

- **Python**
- **Streamlit**
- **Google Gemini Pro API** (via LangChain)
- **LangChain Framework**

---

## ⚙️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/your-username/AIpoweredTravelPlanner_GenAI.git
cd AIpoweredTravelPlanner_GenAI
```

2. **Create and activate virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Add your Google GenAI API Key**

Create a file `.streamlit/secrets.toml` and add your API key:

```toml
GOOGLE_API_KEY = "your_google_genai_api_key_here"
```

5. **Run the Streamlit app**

```bash
streamlit run app.py
```

---

## 📸 Screenshots



---

## 🙌 Acknowledgments

- [LangChain](https://www.langchain.com/)
- [Google Generative AI](https://ai.google.dev/)
- [Streamlit](https://streamlit.io/)
- [Hugging Face Spaces](https://huggingface.co/spaces)

