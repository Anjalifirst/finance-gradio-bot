# Finanace-gradio-bot

#  Multimodal Gradio Bot

This is a **multimodal Gradio chatbot** designed to help users with financial queries. It supports **text, file, and image inputs**, and provides intelligent financial insights powered by Google's Gemini API.

## ✨ Features

- Answer questions related to **financial concepts**
- Analyze uploaded **PDFs**, **CSVs**, and **images**
- Generate financial insights and provide clear explanations
- Automatically create a **PDF** of the Gemini response by typing `"generate PDF"`

## 🚀 How to Use

1. **Chat**: Just type your question into the chat interface.
2. **Upload**: Send a financial file (PDF, CSV, or image).
3. **Download**: To get a copy of the bot's reply as a PDF, type: "generate PDF"

> ⚠️ The bot only responds to **finance-related** queries and accepts **PDF, CSV, or image files**.

## 🛠 Setup

1. **Create a `.env` file** and add your Gemini API credentials:
- GOOGLE_API_KEY=your_google_api_key
- MODEL_ID=your_model_id

2. **Install dependencies**:
```bash
pip install -r requirements.txt
```
3. **Run the bot**:
```bash
python multi_modal_bot.py
```
