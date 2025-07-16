# 🧠 Reddit Persona Generator

This project builds a **user persona** by analyzing any Reddit user's recent posts and comments, using:
- Reddit API (via PRAW)
- A local Hugging Face language model (`google/flan-t5-small`)

It:
- Fetches posts & comments from a Reddit user profile
- Summarizes them into a persona, with quotes from real content
- Saves the result as a timestamped text file

---

## 🚀 Features
- Runs locally (no paid API required)
- Uses an open-source small model (`flan-t5-small`)
- Works from notebook or script
- Persona saved as `username_persona_YYYYMMDD_timestamp.txt`

---

## 📦 Installation
Install dependencies:
```bash
pip install -r requirements.txt
