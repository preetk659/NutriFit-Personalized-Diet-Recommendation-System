# 🥗 Diet Recommendation System

This is a full-stack Diet Recommendation System designed to provide personalized food recommendations based on user input. It uses **FastAPI** for the backend and **Streamlit** for the frontend interface.

---

## 🚀 Features

- 🍱 Personalized diet recommendations
- 🔍 Content-based filtering for custom food options
- 🧠 Machine learning model integration (via `model.py`)
- 🖼 Visual UI using Streamlit
- 🐳 Dockerized for easy deployment

---

## 🛠 Tech Stack

- Backend: [FastAPI](https://fastapi.tiangolo.com/)
- Frontend: [Streamlit](https://streamlit.io/)
- ML: [scikit-learn](https://scikit-learn.org/)
- Deployment: Docker, docker-compose

---

## 📂 Project Structure

```bash
Diet-Recommendation-System/
│
├── FastAPI_Backend/             # Backend API using FastAPI
│   ├── main.py
│   ├── model.py
│   └── requirements.txt
│
├── Streamlit_Frontend/          # Frontend using Streamlit
│   ├── Generate_Recommendations.py
│   ├── pages/
│   └── requirements.txt
│
├── Data/
│   └── dataset.csv              # Dataset (optional - may need LFS)
│
├── Assets/                      # Images and diagrams
├── docker-compose.yml
├── .gitignore
└── README.md
