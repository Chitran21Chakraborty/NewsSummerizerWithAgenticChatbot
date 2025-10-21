🌟 LangGraph AgenticAI – Streamlit App

LangGraph AgenticAI is a modern AI-powered application that combines graph-based reasoning, LLMs, and an interactive Streamlit UI to deliver three key features:

📰 News Summarizer – Summarize news from the last 1, 7, or 30 days.

🌐 Web Search – Search the web and retrieve structured results.

🤖 Agentic Chatbot – Chat with an AI agent powered by a configurable LLM and reasoning graphs.

Built on top of Streamlit and modular components (GroqLLM, GraphBuilder, custom UI modules), this project makes agentic AI systems both accessible and extensible.

✨ Features

📊 Graph-Based Reasoning – Use LangGraph to structure agent workflows.

📰 News Summarizer – Get concise summaries of the latest news.

🌐 Web Search Integration – Fetch and display web results in real-time.

🤖 Agentic Chatbot – An LLM-driven chatbot that can adapt per use case.

⚡ Streamlit UI – Interactive, chat-like interface with buttons and states.

🔧 Modular Design – Easily extend with new use cases or LLM backends.



▶️ Running the App

streamlit run app.py


📝 Usage

News Summarizer
Choose 1 Day / 7 Days / 30 Days timeframe.

Get an AI-generated summary of trending news.

Web Search
Enter a query in the chat input.

Get structured web results with summaries.

Agentic Chatbot
Select a use case in the UI.

Ask questions or interact with the chatbot.

Responses are powered by GroqLLM + GraphBuilder workflows.


⚠️ Error Handling

Missing input → "Error: Failed to load user input"

No LLM → "Error: LLM Model could not be initialized"

No use case → "No usecase selected"

Graph error → "Graph setup failed-{error}"




