

# 🌾 AI Agent for Smart Farming Advice

This project provides an intelligent conversational AI agent designed to assist small-scale and rural farmers by delivering timely, location-specific, and actionable agricultural advice. It is built and deployed using **IBM Watsonx** with a focus on real-time decision support for sustainable farming.

---

## 🚀 Features

* ✅ Natural language interaction (English + regional language support)
* ✅ Smart recommendations based on weather, soil type, and crop season
* ✅ Access to real-time mandi (market) prices and weather data
* ✅ Lightweight and mobile-friendly interface
* ✅ Deployed on IBM Watsonx Agent in cloud

---

## 💡 Use Cases

* "What crop should I grow this season based on my soil and location?"
* "How can I prevent pest attack on my paddy field?"
* "What's the best fertilizer for groundnut at flowering stage?"
* "Current tomato prices in Hyderabad?"

---

## 🛠️ Tech Stack

| Component        | Technology                                     |
| ---------------- | ---------------------------------------------- |
| Backend AI Agent | IBM Watsonx Assistant                          |
| Deployment       | IBM Cloud Deployment Spaces                    |
| Data Sources     | Weather APIs, Agri Portals, CSV/Knowledge Base |
| NLP Model        | Retrieval-Augmented Generation (RAG) / LLM     |
| Frontend         | Web-based Chat UI or IBM Watsonx interface     |

---

## 🧠 System Architecture

1. **User Input** → Query via Chatbot or UI
2. **Watsonx Agent** → Parses input & fetches info
3. **Knowledge Source / APIs** → Returns region-specific advice
4. **Response** → Displayed in user-friendly format

---

## 🖥️ Installation & Setup (Optional for Devs)

> If you're replicating locally or customizing the agent:

```bash
1. Clone the repository
2. Prepare your CSV or JSON knowledge base
3. Train Watsonx Agent via UI
4. Connect external APIs (e.g., OpenWeather, AgriDB)
5. Deploy on IBM Cloud Deployment Spaces
```

---

## 📊 Evaluation

* 🔍 **Accuracy**: Measured against known farming practices
* 😊 **User Satisfaction**: Collected via feedback
* 🔁 **Response Relevance**: Based on intent matching success

---

## 🔮 Future Scope

* Add image-based disease detection using AI
* Integrate voice assistant for non-literate farmers
* Enable auto-updating real-time price feeds and weather data
* Provide offline support via SMS-based interface

---

## 📚 References

* IBM Watsonx Documentation
* Indian Council of Agricultural Research (ICAR)
* agmarknet.gov.in – Mandi prices
* OpenWeather API
* FAO & Krishi Vigyan Kendra publications

---

Let me know if you want the `README` in `.md` file format, or tailored for GitHub/Docs presentation.
