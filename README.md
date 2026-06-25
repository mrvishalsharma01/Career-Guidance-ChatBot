# 🎯 Career Guidance Chatbot

An AI-powered web chatbot that gives you personalized, future-proof career suggestions based on your background, skills, and interests. It uses **Google's Gemini 2.5 Flash API** to generate smart, supportive, and practical career recommendations.

---

## ✨ Features
* **AI Career Suggestions**: Instantly gets 3 tailored career choices matched to your profile.
* **Helpful Resources**: Provides trusted links for you to explore each suggested career path.
* **Chat History**: Keeps track of your queries and recommendations during your session.
* **Modern & Clean UI**: Built using Streamlit for a fast, responsive, and friendly layout.

---

## 🛠️ Tech Stack
* **Language**: Python
* **Web Framework**: Streamlit
* **AI Model**: Google Gemini 2.5 Flash API
* **Libraries**: `requests` (for API calls), `python-dotenv` (for loading variables)

---

## 🚀 How to Set Up & Run the App

Follow these steps to run the application on your computer:

### 1. Clone the Project
Open your terminal and clone the repository:
```bash
git clone https://github.com/mrvishalsharma01/Career-Guidance-ChatBot.git
cd Career-Guidance-ChatBot
```

### 2. Install Dependencies
Make sure you have Python installed, then install the required packages:
```bash
pip install -r requirements.txt
```

### 3. Add your Gemini API Key
1. Get a free API Key from [Google AI Studio](https://aistudio.google.com/).
2. Create a folder named `.streamlit` in the project root.
3. Inside it, create a file named `secrets.toml` and add your API key:
   ```toml
   GEMINI_API_KEY = "your_gemini_api_key_here"
   ```

*(Alternatively, you can create a `.env` file in the root directory with `GEMINI_API_KEY=your_key`)*

### 4. Run the Chatbot
Start the Streamlit server:
```bash
python -m streamlit run careerBot.py
```
This will automatically launch the web interface in your default browser at `http://localhost:8501`.

---

## 🛡️ License
This project is licensed under the **MIT License**.
