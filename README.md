---
title: LanggraphAgenticAI
emoji: 🐨
colorFrom: blue
colorTo: red
sdk: streamlit
sdk_version: 1.42.0
app_file: app.py
pinned: false
license: apache-2.0
short_description: Refined langgraphAgenticAI
---

# Agentic-AI Project

A stateful agentic AI application built with LangGraph and LangChain that demonstrates the implementation of conversational AI agents with tool integration capabilities.

![image](https://github.com/user-attachments/assets/15877c4e-a876-4d67-bb99-e1fdc109fd24)

## 🌟 Features

- **Multiple LLM Support**: Currently integrated with Groq LLM models
- **Multiple Use Cases**:
  - Basic Chatbot: Simple conversational AI
  - Chatbot with Tool Integration: Enhanced chatbot with Tavily search capabilities
- **Modular Architecture**:
  - Graph-based workflow management
  - State management
  - Tool integration framework
- **User-friendly Interface**: Built with Streamlit for easy interaction

## 🛠️ Prerequisites

- Python 3.8+
- Groq API Key (Get it from [Groq Console](https://console.groq.com/keys))
- Tavily API Key (Required for tool-enabled chatbot - Get it from [Tavily](https://app.tavily.com/home))

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/rahulsamant37/Agentic-AI-Project.git
cd Agentic-AI-Project
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Running the Application

1. Start the Streamlit application:
```bash
streamlit run app.py
```

2. Access the web interface at `http://localhost:8501`

## 💻 Usage

1. In the sidebar:
   - Select your preferred LLM (currently Groq)
   - Choose a model from available options
   - Enter your API key(s)
   - Select a use case (Basic Chatbot or Chatbot with Tool)

2. Enter your message in the chat input
3. Interact with the chatbot and view responses

## 🏗️ Project Structure

```
Agentic-AI-Project/
├── src/
│   ├── LLMS/           # LLM configurations
│   ├── graph/          # LangGraph implementation
│   ├── nodes/          # Graph nodes implementation
│   ├── state/          # State management
│   ├── tools/          # Tool integrations
│   ├── UI/             # User interface components
│   └── main.py         # Application entry point
├── app.py              # Streamlit app launcher
└── requirements.txt    # Project dependencies
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## ⚠️ Important Notes

- Ensure your API keys are kept secure and never committed to version control
- The application requires active internet connection for LLM and tool interactions
