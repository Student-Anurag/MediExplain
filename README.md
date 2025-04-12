# 🩺 MediExplain

**MediExplain** is a GenAI-powered tool that translates complex medical terms, symptoms, or diagnostic reports into simple, plain language. It aims to make medical information more accessible and understandable for everyone — especially patients without a medical background.

---

## 🚀 Features

- 🔍 Enter any medical term or lab report result
- 🧠 Uses Generative AI to explain in layman's terms
- 📚 Fallback dictionary for offline/simple use
- 🌐 Clean and user-friendly web interface
- 📦 Ready to deploy with Flask/FastAPI backend and OpenAI integration

---

## 🧩 Tech Stack

- **Frontend**: HTML, CSS, JS (or React)
- **Backend**: Python + Flask / FastAPI
- **GenAI**: OpenAI GPT-3.5 / GPT-4
- **Data**: MediQA-AnS, WikiDoc, SymCat
- **Deployment**: Render / Replit / Hugging Face Spaces

---

## 📁 Folder Structure

MediExplain/
├── frontend/           # UI code (HTML/CSS/JS or React)
├── backend/            # API server (Flask/FastAPI)
├── genai_module/       # Prompt engineering & GPT functions
├── data/               # Medical datasets or fallback terms
├── demo/               # Demo video, screenshots
├── README.md           # Project documentation
└── requirements.txt    # Dependencies (e.g., OpenAI, Flask, FastAPI)

---

## 🧪 Example Usage

> **Input**: “Elevated bilirubin levels”  
> **Output**: “This means your liver might not be working properly, or it’s having trouble removing waste from your body.”

---

## ⚠️ Disclaimer

> MediExplain is an educational tool and **not a replacement for professional medical advice.** Always consult a healthcare provider for serious concerns.

---

## 👨‍💻 Team Members

- [Anurag](https://github.com/Student-Anurag)
- [Adityaraj](https://github.com/Adityaraj-web)
- [Abhroneel](https://github.com/neel-09)
- [Poulami](https://github.com/polo784)

---

## 🎥 Demo

📽️ A 2–3 min walkthrough video will be added here.

---

## 📦 How to Run

```bash
git clone https://github.com/Student-Anurag/MediExplain.git
cd MediExplain/backend
pip install -r requirements.txt
uvicorn app:app --reload
