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

📂 Project Structure . ├── src/ │ └── langgraphagenticai/ │ ├── ui/ │ │ └── streamlitui/ │ │ ├── loadui.py │ │ └── display_result.py │ ├── LLMS/ │ │ └── groqllm.py │ └── graph/ │ └── graph_builder.py ├── app.py └── README.md

⚙️ Installation

Clone the repository:

git clone https://github.com/yourusername/langgraph-agenticai.git cd langgraph-agenticai

Create and activate a virtual environment:

python -m venv .venv source .venv/bin/activate # Mac/Linux .venv\Scripts\activate # Windows

Install dependencies:

pip install -r requirements.txt

▶️ Running the App

Launch the Streamlit app:

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

🚀 Roadmap

Add support for more LLM backends (OpenAI, Anthropic, etc.)

Richer news visualization (graphs, categories).

Multi-agent collaboration.

Deploy on cloud platforms (Streamlit Cloud / HuggingFace Spaces).

📖 License

MIT License © 2025

About
LangGraph AgenticAI is a Streamlit-based application that combines news summarization, web search, and an agentic AI chatbot into a single interface. It uses graph-based reasoning and a configurable LLM backend to deliver concise news insights, real-time web results, and intelligent conversational responses.

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Releases
No releases published
Create a new release
Packages
No packages published
Publish your first package
Footer

