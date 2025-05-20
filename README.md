# Audio-Enhanced-Conversational-Media-Intelligence-AI-Chatbot-using-RAG
Transform audio or video (e.g., YouTube) into an interactive, real-time chat interface using RAG, AssemblyAI, LangChain, OpenAI, and Streamlit.

# 🎙️ Audio-Enhanced Conversational AI Chatbot using RAG

An intelligent chatbot system that transforms any video or audio content (like YouTube lectures or podcasts) into an interactive, real-time conversational experience. This project combines **RAG (Retrieval-Augmented Generation)**, **LangChain**, **AssemblyAI**, and **OpenAI GPT models** and presents it through a modern **Streamlit dashboard**.

---

## 🔍 Key Features

- 🔊 **Audio/Video Transcription**: Transcribes content using AssemblyAI.
- 🔎 **Context-Aware Q&A**: Uses RAG with LangChain to understand and retrieve relevant context.
- 💬 **Real-Time Interaction**: Users can chat with the AI about the transcribed content.
- 📊 **Interactive Dashboard**: Built using Streamlit to visualize and chat seamlessly.
- 🔁 **Dynamic Memory**: Maintains recent message history for contextual responses.

---

## 🛠️ Tech Stack

- **Transcription**: AssemblyAI
- **LLM**: OpenAI (GPT-3.5/GPT-4)
- **Frameworks**: LangChain, RAG
- **Frontend**: Streamlit
- **Language**: Python 3.10+

---

## 📁 Project Structure

audio-enhanced-rag-chatbot/
├── app.py # Main Streamlit application
├── utils.py # Helper functions for RAG pipeline
├── components/ # Streamlit UI components
├── .env # API keys (not uploaded)
├── requirements.txt # Python dependencies
└── README.md

## Yaml file

---

## ⚙️ Setup Instructions

```bash
# Step 1: Clone the Repository
git clone https://github.com/yourusername/audio-enhanced-rag-chatbot.git
cd audio-enhanced-rag-chatbot

# Step 2: Create and Activate Virtual Environment
conda create -p env python=3.10 -y
conda activate env

# Step 3: Install Dependencies
pip install -r requirements.txt

# Step 4: Add Environment Variables
touch .env
# Then, edit .env and add your API keys
```
## 🔐 .env File
```
OPENAI_API_KEY=your_openai_key
ASSEMBLYAI_API_KEY=your_assemblyai_key
```
## ▶️ How It Works
Upload a YouTube link or audio file.

Audio is transcribed using AssemblyAI.

LangChain’s RAG pipeline retrieves contextual data.

OpenAI model answers your questions in real time.

Chat UI and results are rendered in Streamlit.
