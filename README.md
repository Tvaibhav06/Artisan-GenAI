# 🌟 Artisans GenAI  

<p align="center">
  <img src="logo.gif" alt="Artisans GenAI Logo" width="200"/>
</p>  

## 🎨 Introduction  
**Artisans GenAI** is a Streamlit-based web application that integrates **Google Generative AI** with **Firebase authentication** to empower artisans and creators.  

It enables authenticated users to:  
✨ Interact with AI models  
✨ Explore generative design ideas  
✨ Manage and schedule creative sessions  

---

## 📑 Table of Contents  
- [Introduction](#-introduction)  
- [Preview](#-preview)  
- [Features](#-features)  
- [Installation](#-installation)  
- [Usage](#-usage)  
- [Dependencies](#-dependencies)  
- [Configuration](#-configuration)  
- [Examples](#-examples)  
- [Troubleshooting](#-troubleshooting)  
- [Contributors](#-contributors)  
- [License](#-license)  

---

## 👀 Preview  

Here’s a sneak peek of the app in action:  

<p align="center">
  <img src="logo.gif" alt="Login Page" width="220"/>  
  <br/>
  <em>🔐 Login page with Firebase authentication (placeholder)</em>
</p>  

👉 Once you run `frontend.py`, take **real screenshots** of:  
- Login page (Firebase Auth in Streamlit)  
- Main dashboard with AI interaction  
- Calendar view (`streamlit-calendar`)  

Save them in a folder like `assets/` and update the README image paths, e.g.:  
```markdown
<img src="assets/dashboard.png" alt="Dashboard Preview" width="600"/>

🚀 Features

🔐 User Authentication with Firebase

🤖 Generative AI Models powered by Google

🖼️ Custom UI with artisan branding

🗓️ Calendar Scheduling for collaboration

🎛️ Streamlit-powered Interface

🛠️ Installation
git clone https://github.com/jatin-encrypted/Artisans-GenAI.git
cd Artisans-GenAI
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt

💻 Usage
streamlit run frontend.py

📦 Dependencies

From requirements.txt:

streamlit – UI framework

google-generativeai, vertexai – AI integration

firebase-admin, pyrebase4 – Firebase auth & DB

streamlit-authenticator – Login system

streamlit-calendar – Schedule manager

Pillow, PyYAML – Utilities

⚙️ Configuration

Firebase Setup – Create project, download Admin SDK JSON, update firebase_auth.py.

Google Cloud Setup – Enable Vertex AI + Generative AI APIs.

Secrets / Env Vars – Store credentials in .streamlit/secrets.toml or .env.

🧩 Examples

Generate design concepts with AI

Organize artisan workshops with calendar integration

Customize branding with your own logo

🛠️ Troubleshooting

Login issues → Check Firebase config

API errors → Ensure Google Cloud APIs are enabled

Streamlit errors → Run pip install -r requirements.txt

👨‍💻 Contributors

@jatin-encrypted
@Tvaibhav06

📜 License

MIT License – see LICENSE

---

✅ Just paste this into your project’s `README.md`.  
✅ Since you already uploaded `logo.gif` to the repo, it will display correctly on GitHub.  

Do you want me to also create the **folder structure diagram** (in Markdown) and append it right after the **Introduction**? It’ll help contributors know where to place assets like `logo.gif`, `frontend.py`, etc.
