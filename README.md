# Amibot
* **Amibot 🤖 – The Friendly Amity Assistant**
* **AskAmity**
* **CampusWhiz**
* **AmityBuddy**
* **UniPal – Your Amity Companion**


# 🤖 Amibot – Your Friendly Amity Assistant

A smart, conversational assistant built with **Gradio**, **PyTorch**, and **OpenAI**, designed to help Amity University students with admissions, placements, notes, syllabus—and even a good laugh. Think of it as your AI-powered campus buddy.

---

## 🧠 What Can Amibot Do?

- 🎓 Answer questions about **Amity University** (admissions, syllabus, etc.)
- 📝 Provide links to **notes**, **past year papers**, and resources
- 💼 Share **average package details** for different departments
- 😄 Cheer you up with **motivational quotes** or **jokes**
- 🌐 Handle **general questions** using Wikipedia or DuckDuckGo
- 💬 Supports **intent detection** via fuzzy matching

---

## 🛠️ Tech Stack

| Layer           | Tools / Frameworks         |
|----------------|----------------------------|
| Language        | Python                     |
| UI              | Gradio                     |
| AI Integration  | OpenAI GPT-3.5, DuckDuckGo |
| NLP Matching    | RapidFuzz (fuzzy logic)    |
| Knowledge Base  | Wikipedia API, Custom Data |
| Hosting Ready?  | Yes, via Gradio & Python   |

---

## 🏗️ How It Works

### 1. Intent Detection
Uses fuzzy matching (RapidFuzz) to detect user intent:  
Example: `"how to get into amity"` → matched to `admission`

### 2. Data Sources
- Hardcoded package info per department
- Wikipedia summaries
- DuckDuckGo fallback answers
- OpenAI GPT response as last resort

### 3. Fun Element
If the user is sad or bored, Amibot throws:
- 🌈 Motivational Quotes
- 😂 Random jokes via JokeAPI

---

## 🚀 Quick Start

1. **Clone the repo**  
```bash
git clone https://github.com/your-username/amibot.git
cd amibot
````

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the chatbot**

```bash
python amity_bot.py
# or launch the notebook if you're using Jupyter
```

> ⚠️ Don’t forget to set your `OPENAI_API_KEY` as an environment variable.

---

## ✨ Sample Intents Supported

| Intent      | Example Queries                       |
| ----------- | ------------------------------------- |
| Admissions  | "How to get into Amity?"              |
| Syllabus    | "Show me the course structure"        |
| Notes       | "Any previous year papers for CSE?"   |
| Cheer Up    | "I'm feeling low\..."                 |
| Placement   | "What's the average package for ECE?" |
| Portal Link | "How to access Amizone?"              |
| Joke        | "Tell me a joke!"                     |

---

## 📸 Screenshots (Add These!)

* ✅ Chat UI preview
* 📈 Response to “average package for CSE”
* 😂 Joke or motivational quote response

---

## 💡 Ideas to Expand

* Add student login & authentication
* Integrate with Amizone API (if public)
* Deploy on HuggingFace/Streamlit Cloud
* Add language support (Hindi, etc.)

---

## 🙋‍♂️ Made By

Built with ❤️ by **Rahul Raj**
Student @ Amity University, Noida
Let’s connect: [LinkedIn](https://www.linkedin.com/in/yourprofile)

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, remix, or expand it!

```

---

Would you like this saved as a `.md` file for download?  
And if you're deploying this somewhere (Hugging Face, Streamlit, etc.), I can add deploy buttons too.
```
