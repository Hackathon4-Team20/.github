# Shu'ur (شعور): Arabic Sentiment Analysis for Customer Support Conversations

![Screenshot 2025-06-14 at 12 42 46 AM](https://github.com/user-attachments/assets/691ba5d8-5888-4c9a-9189-e532b450b8e4)


## 🚀 Overview

**Shu'ur** is an AI-powered platform that automatically analyzes, classifies, and visualizes Arabic customer support conversations (including Palestinian dialect) to help organizations instantly understand customer sentiment, spot dissatisfaction, and improve service quality.

- **Live Demo:** [Watch a demo here](https://drive.google.com/file/d/1TCldCDTJ9PGOrrSvyskuHwGnpwC5WeZK/view?usp=sharing)  

---

## ✨ Features

- **Arabic Sentiment Analysis**: Detects positive, negative, and neutral sentiment in Arabic (including dialects).
- **Real-Time Dashboard**: Visualizes sentiment trends, agent performance, and common issues.
- **Automatic Tagging**: Highlights dissatisfied customer messages for rapid intervention.
- **Comprehensive Metrics**: Accuracy, Precision, Recall, F1-Score, MAE, RMSE, and more.
- **Real Time Chatting**: Designed for live chat, and web-based customer support systems.
- **Secure API Integration**: Uses OpenRouter LLM APIs with API key authentication.

---

## 🧑‍💻 Demo

- **Live Demo:** [Demo Video](https://drive.google.com/file/d/1A5L8d5nUe8wQ4QjDEMO-LINK-EXAMPLE/view?usp=sharing)  
  *(Replace with your real demo link)*

---

## 🏗️ How It Works

1. **API Authentication**  
   Secure connection to OpenRouter LLM APIs with your API key.

2. **Prompt Creation**  
   Each customer message is formatted and sent to the LLM with context.

3. **Model Inference**  
   The LLM returns a sentiment score and explanation.

4. **Data Analysis & Visualization**  
   Results are aggregated, analyzed, and visualized in real-time dashboards.

---

## 🧠 Technologies Used

- **Python** (backend, AI model interaction)
- **Jupyter Notebook** (data analysis, prototyping)
- **TypeScript** (dashboard/web frontend)
- **OpenRouter API** (LLM inference)
- **Mistral AI** (pre-trained models)
- **Matplotlib, Seaborn** (visualizations)
- **Pandas, scikit-learn** (data processing & metrics)

---

## 📊 Example Performance

| Metric         | Value  |
|:--------------:|:------:|
| Accuracy       | 0.730  |
| Precision      | 0.730  |
| Recall         | 1.000  |
| F1-Score       | 0.844  |
| MAE            | 0.470  |
| RMSE           | 0.686  |
| True Positive  | 73     |
| True Negative  | 0      |
| False Positive | 27     |
| False Negative | 0      |

---

## 📦 Repository Structure

- `ai-model/` — Python backend for sentiment analysis
- `data-analysis/` — Jupyter Notebooks for data exploration and evaluation
- `web/` — TypeScript frontend for the dashboard

---

## 🛠️ Setup & Usage

1. **Clone the repository**
    ```
    git clone https://github.com/YOUR-TEAM-ORG/ai-model.git
    ```

2. **Install dependencies**
    ```
    cd ai-model
    pip install -r requirements.txt
    ```

3. **Set your OpenRouter API key**
    ```
    export OPENROUTER_API_KEY=your_api_key_here
    ```

4. **Run the backend**
    ```
    python evaluate_model.py
    ```

5. **Start the frontend dashboard**
    ```
    cd ../web
    npm install
    npm start
    ```

---

## 🌍 Future Roadmap

- **Production Deployment**: Integrate with Bank of Palestine’s infrastructure
- **Dialect Expansion**: Support for more Arabic dialects
- **Real-time Alerts**: Live dashboards and automated escalation
- **Predictive Analytics**: Customer satisfaction forecasting
- **Multi-channel Support**: Voice, email, social media integration

---

## 🙌 Team

Palestine Launchpad 4th Graduate Hackathon - Team20-P3
Contact: yazansedih@gmail.com

---

## ⭐️ If you like this project, please star the repo and share your feedback!

