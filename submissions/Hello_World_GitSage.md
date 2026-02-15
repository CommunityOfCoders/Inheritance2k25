# 🚀 GitSage – AI-Powered GitHub Repository Intelligence

<h1 align="center">
  <a href="https://github.com/CommunityOfCoders/Inheritance2k25">
    CoC Inheritance 2025
  </a>
  <br>
  GitSage: Code Confusion? We've Git You Covered
</h1>

<div align="center">
By <b>Team GitSage</b>
</div>

---

<details>
<summary><b>Table of Contents</b></summary>

- [Description](#-description)
- [Links](#-links)
- [Tech Stack](#-tech-stack)
- [Progress](#-progress)
- [Future Scope](#-future-scope)
- [Applications](#-applications)
- [Project Setup](#-project-setup)
- [Team Members](#-team-members)
- [Mentors](#-mentors)
- [Why GitSage?](#-why-gitsage)

</details>

---

## 📝 Description

GitSage is an AI-powered repository intelligence system that enables users to:

- Ask natural language questions about any GitHub repository  
- Automatically generate structured documentation  
- Compare two repositories intelligently  

It solves the problem of developer onboarding and repository understanding using:

- Retrieval-Augmented Generation (RAG)
- Code + text embeddings
- Persistent vector database search
- Large Language Models for reasoning

GitSage transforms raw source code into structured insights.

---

## 🔗 Links

- 🔗 **GitHub Repository** – [Explore GitSage](https://github.com/RudrakshiChincholkar/GitSage.git)
- 🎥 **Demo Video** – [Watch the Demo](https://drive.google.com/file/d/11Nk_ZAYHYgAbM3OW31i5-8UEXWJPHPZ5/view?usp=drive_link)
- 🖼 **Screenshots** – [View Project Gallery](https://drive.google.com/drive/folders/1v6kbEnOcbywVCAgcLQpSavP6xt5LLqrx)


---

# 🤖 Tech Stack

---

## 🏗️ System Architecture

```mermaid
graph LR
    A[User Input] --> B[FastAPI Backend]
    B --> C[Ingestion Pipeline]
    C --> D[Embedding Pipeline]
    D --> E[ChromaDB Vector Store]
    E --> F[Retriever]
    F --> G[LLM - Groq API]
    G --> H[Final Response]

```

---

## 🌐 Frontend

- React (Vite)
- TypeScript
- Tailwind CSS
- Lucide Icons
- Responsive UI

---

## ⚙️ Backend

- FastAPI
- Python 3.11
- Async ingestion pipeline
- RESTful API architecture
- Modular service design

---

## 🧠 AI / ML Layer

- Retrieval-Augmented Generation (RAG)
- Code embedding model
- Sentence embedding model
- Groq LLM API
- Prompt engineering with hallucination control

---

## 🗄️ Database

- ChromaDB (Persistent Vector Database)
- Metadata-based filtering
- Separate collections for code and text embeddings

---

# 📈 Progress

---

## ✅ Fully Implemented Features

### 🔹 Intelligent Q&A System
- Natural language repository queries  
- Context-aware retrieval  
- Grounded LLM responses  
- Controlled inference without hallucination  

### 🔹 Automatic Documentation Generator
- Structured documentation generation  
- Overview, architecture, modules  
- Tech stack detection  
- Setup and usage instructions  

### 🔹 Repository Comparison Engine
- Side-by-side metadata comparison  
- LLM-based architectural analysis  
- Strengths, trade-offs, verdict  
- Feature comparison table  

### 🔹 Version-Aware Ingestion
- Detects repository updates  
- Avoids redundant embeddings  
- Maintains ingestion consistency  

---

## 🚧 Work in Progress

- Advanced tech stack inference
- AST-based deeper code analysis
- Performance optimization for large repositories
- Query caching system

---

# 🔮 Future Scope

- Cloud deployment with scalable vector storage  
- Multi-repository cross-analysis  
- Visual architecture diagram generation  
- Authentication & saved workspaces  
- Enterprise-level CI/CD integration  

---

# 💸 Applications

1. **Developer Onboarding** – Understand unfamiliar codebases quickly  
2. **Open Source Exploration** – Analyze large repositories before contributing  
3. **Code Review Support** – Gain instant architectural insights  
4. **Academic Learning** – Explore algorithm-heavy repositories  
5. **Technical Interviews** – Evaluate GitHub projects efficiently  

---

# 🛠 Project Setup

## 📌 Prerequisites

- Python 3.11+
- Node.js 18+ and npm
- Groq API Key
- GitHub Personal Access Token (PAT)

Create a `.env` file inside the `backend/` folder:

```bash
GROQ_API_KEY=your_groq_api_key
GITHUB_PAT=your_github_pat
```

---

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/GitSage.git
cd GitSage
```

---

## 2️⃣ Backend Setup

```bash
cd backend
python3.11 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
```

Backend runs at:
```
http://127.0.0.1:8000
```

---

## 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at:
```
http://localhost:5173
```

---

# 👨‍💻 Team Members

- **Ankita Sagar** – https://github.com/Sagarankita  
- **Rudrakshi Chincholkar** – https://github.com/RudrakshiChincholkar  

---

# 👨‍🏫 Mentors

- **Soham Rane** – https://github.com/soham30rane
- **Harshal Kamble** – https://github.com/xyz-harshal
- **Sakshi Bhirud** – https://github.com/bsakshiii

---

# 💎 Why GitSage?

- Modular AI architecture  
- Persistent vector search  
- Dual embedding pipeline  
- Structured LLM reasoning  
- Real-world developer problem solving  
- End-to-end full-stack system  

---

⭐ Built with intelligence. Powered by code understanding.
