# 🧠 Math & Knowledge Assistant: Solve Text-Based Math and Reasoning Problems

This Streamlit app is a **Text-to-Math Problem Solver** and **Knowledge Assistant** powered by LangChain and the blazing-fast **Groq API** using the **Gemma2-9b-It** model. It can:

- 🧮 Solve **text-based math problems** step by step  
- 🔍 Answer **reasoning questions** with logical explanations  
- 🌐 Search **Wikipedia** to enhance knowledge-based answers  

---

## 🚀 Features

- 🧠 Natural language understanding for math and reasoning
- 🧮 Math solving using LangChain's `LLMMathChain`
- 🌍 Wikipedia integration for factual lookup
- 💬 Chat interface with memory
- ⚡ Powered by Groq’s `Gemma2-9b-It` model

---

## 🛠️ Tech Stack

- [LangChain](https://www.langchain.com/)
- [Groq API](https://console.groq.com/)
- [Streamlit](https://streamlit.io/)
- [Wikipedia API Wrapper](https://python.langchain.com/docs/integrations/tools/wikipedia/)
- [Python 3.10+](https://www.python.org/)

---

## 📁 Project Structure

### 1. Clone the Repository

  ```bash
  git clone https://github.com/mohitmittal1988/Text_math_solver.git
  cd text_summary
  ```

### 2. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set Environment Variables

Create a `.env` file in the root directory:

```env
GROQ_API_KEY=your_groq_api_key
```

### 5. Run the App

```bash
streamlit run app.py
```

---

## 🔐 API Key Requirement

When prompted in the UI, provide your **Groq API Key** to access the `Llama3-8b-8192` LLM.

---

## 📁 Project Structure

```plaintext
├── app.py                     # Main Streamlit application
├── requirement.txt           # Required packages
├── .env                       # Environment token for HuggingFace
└── README.md                  # Documentation
```

---

