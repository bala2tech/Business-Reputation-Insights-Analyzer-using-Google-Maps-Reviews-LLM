# Business-Reputation-Insights-Analyzer-using-Google-Maps-Reviews-LLMs-

# 🧠 Google Reviews Sentiment & Recommendation Engine

🧠 Google Reviews Sentiment & Insights Dashboard

An interactive AI dashboard that fetches real Google Maps reviews using SerpAPI, performs sentiment & topic analysis with TextBlob + NLTK, and generates summaries and improvement suggestions using LangChain + Hugging Face Transformers — all within an elegant Gradio web app.

🌍 100% open-source • 💬 Real-time NLP insights • 🧠 No paid API required

🧰 Tools & Technologies Used
Category	Tools / Libraries	Purpose
Data Fetching	🧩 SerpAPI
	Fetch Google Maps Reviews via API
Data Processing	🐼 pandas, re, datetime	Clean and organize review data
Natural Language Processing (NLP)	💬 TextBlob, 🧠 NLTK (VADER)	Sentiment scoring and emotion detection
Machine Learning / AI Models	🤗 Hugging Face Transformers (facebook/bart-large-cnn)	Summarization and text generation
AI Orchestration	🔗 LangChain + HuggingFacePipeline	Unified prompt-based LLM workflow
Interface / Visualization	🎛️ Gradio	Interactive web dashboard for real-time insights
Environment & Security	🔐 getpass, os	Hidden API key input and environment variable handling
🚀 Techniques & Concepts Learned

By exploring or building upon this project, you’ll learn how to:

🔍 Integrate external APIs (Google Maps Reviews via SerpAPI) in Python workflows

🧹 Preprocess and clean textual data using Pandas, Regex, and Datetime parsing

💬 Perform sentiment and emotion analysis using NLTK and TextBlob

🧠 Use transformer models (e.g. BART) for text summarization and insight extraction

🔗 Leverage LangChain to build prompt-driven analytical workflows with Hugging Face models

🎨 Build interactive AI dashboards using Gradio Blocks for visualization and interaction

💡 Generate actionable insights and improvement suggestions from user feedback automatically

🧾 Automate NLP pipelines combining classical ML (VADER) with LLMs (Transformers)
