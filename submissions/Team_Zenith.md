<h1 align="center">
  <a href="https://github.com/CommunityOfCoders/Inheritance2k25">
    CoC Inheritance 2025
  </a>
  <br>
  Zenith: The AI-Native Code Editor
</h1>

<div align="center">
By [Team Zenith]
</div>
<hr>

<details>
<summary>Table of Contents</summary>

- [Description](#description)
- [Links](#links)
- [Tech Stack](#tech-stack)
- [Progress](#progress)
- [Future Scope](#future-scope)
- [Applications](#applications)
- [Project Setup](#project-setup)
- [Team Members](#team-members)
- [Mentors](#mentors)

</details>

## 📝 Description

Zenith is an **Agentic AI Code Editor** that transforms software development by bridging the gap between traditional coding and autonomous intelligence. It solves the inefficiencies of manual boilerplate and context switching by seamlessly embedding **LangGraph** agents directly into your workflow to plan, execute, and verify to help you build just with natural language commands. Powered by **Google Gemini 1.5 Flash**, **Electron**, and **Python/Flask**, Zenith leverages **RAG** and **Tree-sitter** to provide a deeply context-aware environment that understands your code as well as you do ,along with effortless github actions integration and gamified algorithm visualizer for engineering grads to understand the working of algorithms in gamified way.

---

## 🔗 Links

- [GitHub Repository](https://github.com/trmore-1712/ZENITH-Code-Editor)
- [Demo Video](https://drive.google.com/drive/folders/196SytJDcQ2NA7I5MWv2zz1liEZLUuo0i?usp=sharing)
- [Project Screenshots/Drive](https://drive.google.com/drive/folders/1SeIiYxbn9hZqCycA3bIZA7Myiu4YUk3i?usp=sharing)


## 🏗️ System Architecture

![Zenith System Architecture](https://gist.githubusercontent.com/trmore-1712/8aa4cd661df1ef21aac4cfcf41d9d2af/raw/73334a0814c7dedbbd7cf260994692929d3381e6/architecture.svg)

## 🛠️ Tech Stack

### Frontend
- **Electron**: Cross-platform desktop application framework.
- **Vanilla JavaScript**: Lightweight, high-performance rendering logic.
- **Monaco Editor**: The core editor that capabilities VS Code.
- **Xterm.js**: Full-featured terminal emulator.
- **Node-pty**: Native terminal process management.

### Backend
- **Python & Flask**: Robust API handling AI requests and file operations.
- **LangChain & LangGraph**: State-of-the-art framework for building context-aware, reasoning agents.
- **Google Generative AI (Gemini)**: Fast, efficient LLM for code generation.
- **ChromaDB**: Vector database for high-speed code retrieval (RAG).
- **Tree-sitter**: Incremental parsing system for robust code analysis.
- **GitPython**: Programmatic interface for Git operations.

---

## 📈 Progress

### Fully Implemented Features
- [x] **Agentic AI Chat**: Plan and execute multi-file edits using LangGraph.
- [x] **RAG System**: Context-aware code understanding with ChromaDB.
- [x] **Code Editor UI**: Modern Monaco-based editor with glassmorphism.
- [x] **Terminal**: Integrated xterm.js terminal.
- [x] **File Management**: Create, delete, rename files and folders.
- [x] **Algorithm Visualizer**: Real-time visualization for Python/JS algorithms.
- [x] **Git Integration**: View history, commit, push, pull.

### Work in Progress
- [ ] **Extension Marketplace**: Plugin system structure is in place, content pending.
- [ ] **Real-time Collaboration**: WebSocket infrastructure ready, implementation pending.

---

## 📦 Getting Started

### Prerequisites
- **Node.js** (v16+)
- **Python** (v3.10+)
- **Git**

### Installation

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/trmore-1712/ZENITH-Code-Editor
    cd zenith-code-editor
    ```

2.  **Setup Backend**
    ```bash
    cd Zenith/JaiShreeRam/backend
    pip install -r requirements.txt
    ```
    *Create a `.env` file in the `backend` folder:*
    ```env
    GOOGLE_API_KEY=your_gemini_api_key_here
    ```

3.  **Setup Frontend**
    ```bash
    cd ../frontend
    npm install
    ```

### Running the Application

1.  **Start the Backend Server**
    ```bash
    # In Zenith/JaiShreeRam/backend
    python app.py
    ```

2.  **Start the Editor**
    ```bash
    # In Zenith/JaiShreeRam/frontend
    npm start
    ```

---

## 🔮 Future Roadmap

- [ ] **Extension Marketplace**: A fully functional plugin system for community themes and tools.
- [ ] **Real-time Collaboration**: Google Docs-style live coding.
- [ ] **Multi-Model Support**: Switch between GPT-4, Claude, and Llama locally.

---

## 💸 Applications

1.  **Automated Refactoring**: Agents can handle large-scale generic refactors (e.g., "Migrate all print statements to logging").
2.  **Educational Tools**: The Algorithm Visualizer helps students understand complex logic visually.
3.  **Rapid Prototyping**: Generating boilerplate and basic logic via natural language speed up development.

---

## 👥 Team

- **Tanmay**: [\[Github Profile Link\]](https://github.com/trmore-1712)
- **Neelay**: [\[GitHub Profile Link\]](https://github.com/crazy-coder-neel)
- **Kavya**: [\[GitHub Profile Link\]](https://github.com/champ-byte)
- **Pakshal**: [\[GitHub Profile Link\]](https://github.com/impakshal)

## 👨‍🏫 Mentors

- **Soham Rane**
- **Harshal Kamble**

---

Made with ❤️ and 🤖 using **Zenith**.