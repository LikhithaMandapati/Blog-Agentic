# Blog-Agentic

Blog-Agentic is a Python-based application that integrates **LangChain**, **LangGraph**, and **FastAPI** to build intelligent, agent-driven blog workflows. It allows you to generate, manage, and serve AI-powered blog content in a structured and efficient manner.

---

## 🚀 Features

- ⚡ **AI-Powered Agents** – Build and run agent workflows with LangGraph + LangChain.
- 📝 **Content Generation** – Automate blog creation with intelligent prompts and workflows.
- 🌐 **API Ready** – Serve content through a FastAPI backend.
- 🔄 **Live Reloading** – Supports auto-reload for development using Watchdog.
- ⚙️ **Extensible** – Easily customizable with configuration files and modular structure.

---

## 📂 Project Structure

```
BlogAgentic/
├── app.py                # Entry point of the FastAPI app
├── main.py               # Core logic to load and run LangGraph agent
├── requirements.txt      # Python dependencies
├── pyproject.toml        # Project metadata and dependencies
├── langgraph.json        # LangGraph configuration file
├── .gitignore            # Git ignore file
└── src/                  # Source code directory
```

---

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/LikhithaMandapati/Blog-Agentic.git
   cd Blog-Agentic
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # On Windows: .venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage

To start the FastAPI application with Uvicorn:

```bash
uvicorn app:app --reload
```

The app will be available at: **http://127.0.0.1:8000**

---

## 🧪 Testing

If you are using **pytest**, run:

```bash
pytest
```

---

## ⚙️ Configuration

- **pyproject.toml** – Defines project metadata and dependencies.
- **langgraph.json** – Contains workflow configurations for LangGraph agents.
- **requirements.txt** – Python dependencies list.

---

## 📦 Dependencies

Key dependencies include:
- **FastAPI** – Web framework for APIs
- **Uvicorn** – ASGI server
- **LangChain** – Building blocks for LLM applications
- **LangGraph** – Agent workflows
- **Watchdog** – File system monitoring

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
