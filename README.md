🚀 AI Resume Analyzer

An intelligent AI-powered Resume Analyzer built using Python and Streamlit that helps users evaluate their resumes, identify skill gaps, and improve job readiness.

📌 Overview

The AI Resume Analyzer is designed to:

Analyze resumes using AI/NLP techniques
Extract important skills and information
Provide suggestions to improve resumes
Help users align their resumes with job requirements

Such tools typically use NLP and machine learning to extract insights and improve resume quality for better job matching.

✨ Features
📄 Resume Upload (PDF support)
🔍 Resume Parsing & Analysis
🧠 AI-Based Suggestions
📊 Skill Extraction
🎯 Improvement Recommendations
⚡ Fast & Simple UI (Streamlit)
🛠️ Tech Stack
Frontend: Streamlit
Backend: Python
AI Integration: Google Generative AI (Gemini API)
Libraries:
streamlit
google-generativeai
python-dotenv
📂 Project Structure
AI_Resume_Analyzer/
│── app.py              # Main Streamlit app
│── requirements.txt    # Dependencies
│── .gitignore          # Ignored files
│── README.md           # Project documentation
⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/udityaseth3/AI_Resume_Analyzer.git
cd AI_Resume_Analyzer
2️⃣ Create Virtual Environment
python -m venv venv
venv\Scripts\activate   # Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
🔑 Setup API Key (IMPORTANT)

Create a .env file:

GEMINI_API_KEY=your_api_key_here

⚠️ Never upload your API key to GitHub.

▶️ Run the App
streamlit run app.py
🌐 Deployment

You can deploy this app on:

Streamlit Cloud
Render
Railway
