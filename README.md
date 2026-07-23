# ✈️ Europe Travel Assistant

An AI-powered travel chatbot built using **Streamlit**, **Groq API**, and **Llama 3.3 70B Versatile**. The assistant helps users plan trips across Europe by providing personalized travel recommendations, visa guidance, itinerary planning, hotel suggestions, transportation advice, and much more through a conversational interface.

---

## 🚀 Features

- 💬 Interactive AI chat interface
- 🌍 Europe travel planning
- 🗺️ Personalized itinerary generation
- 💰 Budget estimation and trip planning
- 🛂 Schengen visa guidance
- 🏨 Hotel recommendations
- ✈️ Flight suggestions
- 🚆 Transportation recommendations
- 🍝 Local food recommendations
- 📍 Tourist attraction suggestions
- ⚡ Real-time streaming responses using Groq API
- 🗑️ Clear chat history functionality

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **Groq API**
- **OpenAI Python SDK**
- **Llama-3.3-70B-Versatile**

---

## 📂 Project Structure

```
Europe-Travel-Assistant/
│
├── app.py
├── requirements.txt
├── .streamlit/
│   └── secrets.toml
├── README.md
└── assets/
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/europe-travel-assistant.git

cd europe-travel-assistant
```

---

### 2. Create a virtual environment

#### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

#### Linux / Mac

```bash
python3 -m venv venv

source venv/bin/activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Groq API Setup

Create a folder named

```
.streamlit
```

Inside it create

```
secrets.toml
```

Add your Groq API key

```toml
GROQ_API_KEY="your_groq_api_key"
```

You can obtain a free API key from

https://console.groq.com/

---

## ▶️ Run the application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 💬 Example Questions

- Plan a 10-day Europe trip under €2000.
- What is the Schengen Visa process for Indian citizens?
- Best places to visit in Switzerland?
- Recommend budget hotels in Paris.
- Cheapest transportation from Amsterdam to Brussels.
- Best Italian food to try in Rome.
- Create a Europe itinerary for first-time travelers.
- Best time to visit Norway.
- How much money should I carry for a two-week Europe trip?
- What are the must-visit attractions in Prague?

---

## 🧠 AI Model

This project uses

- **Llama-3.3-70B-Versatile**
- Hosted by **Groq**
- Streaming responses for faster user experience

---

## 📸 Application Preview

<img width="100%" src="assets/demo.png">

*(Replace with your application screenshot.)*

---

## 🔄 Chat Features

- Persistent chat history during the session
- Streaming AI responses
- Sidebar displaying message count
- One-click chat reset

---

## 📦 Requirements

```
streamlit
openai
```

or install using

```bash
pip install streamlit openai
```

---

## 🔒 Environment Variables

| Variable | Description |
|----------|-------------|
| GROQ_API_KEY | Groq API Key |

---

## 📈 Future Improvements

- 🌤️ Live weather integration
- 🗺️ Interactive maps
- 💱 Currency conversion
- 💸 Real-time flight prices
- 🏨 Booking.com integration
- 🚄 Train schedule integration
- 🧳 Packing checklist generator
- 📄 PDF itinerary download
- 🌍 Multi-language support
- 🎙️ Voice-enabled travel assistant

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository

2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Akhil Vikram Singh**

AI Engineer | Machine Learning Engineer | Generative AI Developer

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
