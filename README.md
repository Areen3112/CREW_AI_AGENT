# 🤖 AI Blog Generator using CrewAI Multi-Agent Framework

An intelligent multi-agent AI application that automatically converts YouTube videos into well-structured blog posts using the **CrewAI** framework. The project demonstrates how multiple AI agents collaborate to perform research, content analysis, and blog writing in a sequential workflow.

---

## 🚀 Overview

Writing blogs manually from long YouTube videos is repetitive and time-consuming. This project automates the entire workflow using AI agents.

Given a topic, the application:

1. Searches a specific YouTube channel.
2. Finds the most relevant video.
3. Extracts the video transcript.
4. Understands and summarizes the content.
5. Generates a professional Markdown blog post.

The system uses **CrewAI's multi-agent architecture**, where specialized AI agents communicate with one another to accomplish complex tasks efficiently.

---

# 🏗️ Architecture

```
                User Topic
                     │
                     ▼
        ┌─────────────────────────┐
        │   Research Agent        │
        │ - Search YouTube        │
        │ - Fetch Transcript      │
        │ - Analyze Content       │
        └────────────┬────────────┘
                     │
                     ▼
        ┌─────────────────────────┐
        │   Writer Agent          │
        │ - Summarize             │
        │ - Create Blog           │
        │ - Save Markdown File    │
        └────────────┬────────────┘
                     │
                     ▼
            blog_post.md
```

---

# ✨ Features

* Multi-Agent AI workflow using CrewAI
* Dedicated Research Agent
* Dedicated Blog Writer Agent
* Automatic YouTube transcript retrieval
* AI-powered content summarization
* Markdown blog generation
* Sequential agent communication
* Memory-enabled agents
* Modular architecture
* Easily extendable with additional agents and tools

---

# 🧠 AI Agents

## 1. Research Agent

Responsibilities:

* Search relevant YouTube videos
* Retrieve transcript
* Analyze technical content
* Extract useful information
* Pass findings to Writer Agent

---

## 2. Blog Writer Agent

Responsibilities:

* Understand research output
* Create structured blog content
* Write engaging explanations
* Generate Markdown blog file

---

# 🛠️ Tools Used

* CrewAI
* CrewAI Tools
* YouTube Channel Search Tool
* OpenAI GPT Models
* Python
* Markdown Output

---

# 📂 Project Structure

```
AI-Blog-Generator/
│
├── agents.py
├── tasks.py
├── tools.py
├── crew.py
├── requirements.txt
├── .env
├── blog_post.md
└── README.md
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/AI-Blog-Generator.git
```

Move into the project:

```bash
cd AI-Blog-Generator
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment:

Windows

```bash
venv\Scripts\activate
```

Linux / Mac

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file.

```env
OPENAI_API_KEY=your_api_key
OPENAI_MODEL_NAME=gpt-4o-mini
```

---

# ▶️ Running the Project

```bash
python crew.py
```

The application will:

* Search the YouTube channel
* Analyze the selected video
* Generate a Markdown blog
* Save the output as:

```
blog_post.md
```

---

# 🔄 Workflow

1. User enters a topic.
2. Research Agent searches the YouTube channel.
3. Transcript is extracted.
4. Content is analyzed.
5. Writer Agent creates the blog.
6. Blog is saved automatically.

---

# 💡 Example Use Cases

* Content Repurposing
* Educational Blog Automation
* YouTube Knowledge Base
* AI Documentation Generation
* Technical Blogging
* Course Content Generation
* Internal Knowledge Management

---

# 📦 Dependencies

* Python 3.10+
* CrewAI
* crewai-tools
* OpenAI API
* dotenv

Install with:

```bash
pip install -r requirements.txt
```

---

# 🚀 Future Improvements

* Support multiple LLM providers (Gemini, Claude, Llama)
* PDF knowledge base integration
* Web search tools
* Automatic image generation
* SEO optimization
* WordPress publishing
* Streamlit interface
* FastAPI backend
* Docker deployment
* Multi-channel support
* Hierarchical CrewAI workflows
* Human-in-the-loop approval

---

# 🎯 Learning Outcomes

This project demonstrates:

* Multi-Agent AI Systems
* CrewAI Framework
* Agent Collaboration
* Task Orchestration
* Tool Integration
* LLM-Based Automation
* Prompt Engineering
* AI Workflow Design
* Modular Python Development

---

# 📜 License

This project is open-source and intended for educational and learning purposes.

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
