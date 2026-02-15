<h1 align="center">
  <a href="https://github.com/CommunityOfCoders/Inheritance2k25">
    CoC Inheritance 2025
  </a>
  <br>
  TravelGenie : AI-Powered Smart Travel Planning System
</h1>

<div align="center">
By Bitten By Python
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

<a name="description"></a>

## 📝 Description

TravelGenie is an AI-powered smart travel planning system that generates personalized, structured, and optimized travel itineraries using a locally deployed Large Language Model.

It bridges the gap between generic travel suggestions and realistic, budget-aware planning by combining structured dataset filtering with contextual LLM generation. Built with React, FastAPI, and Mistral 7B Instruct running locally with GPU acceleration, TravelGenie delivers city-restricted and logically sequenced day-wise travel plans.

---

<a name="links"></a>

## 🔗 Links

- [GitHub Repository](https://github.com/Rehan1604/Travel_Genie-Inheritance-)
- [Demo Video](https://drive.google.com/file/d/17rnifMKwYDJi85VA_xYY3rXyMjG5T3Hy/view?usp=drive_link)
- [Project Screenshots/Drive](https://drive.google.com/drive/folders/1NHrsDFPxkjYD7yWH67OHcHFVX3k0ld5h?usp=drive_link)
- Hosted Website: Not Deployed Yet

---

<a name="tech-stack"></a>

## 🤖 Tech-Stack

### 🏗️ System Architecture

```mermaid
graph TD
    User[User Input] --> Frontend
    Frontend[React Frontend] --> Backend
    Backend[FastAPI Backend] --> Dataset
    Dataset[CSV Dataset Filtering] --> LLM
    LLM[Mistral 7B Instruct] --> GPU
    GPU[RTX 4060 GPU CUDA 12.7] --> Output
    Output[Day-wise Structured Itinerary]
Front-end
The user interface is built for clarity and interactivity, ensuring seamless itinerary generation.

Framework: React.js (Vite)
Communication: Axios
Storage: Browser localStorage

Key Features
Dynamic chat-based input interface

Real-time itinerary rendering

Editable travel plans

Persistent storage of generated itineraries

Back-end
The backend handles dataset filtering, LLM orchestration, and structured output formatting.

Framework: FastAPI
Model Runtime: HuggingFace Transformers + Accelerate

Core Components
Dataset filtering engine (CSV-based)

Prompt construction logic

LLM inference pipeline

Structured response formatter

Database & Machine Learning
Data Layer: Structured CSV dataset (India, USA, Iran cities)
Includes: Climate data, pricing ranges, category metadata

AI Infrastructure
Mistral 7B Instruct

4-bit quantization

NVIDIA RTX 4060 GPU

CUDA 12.7

<a name="progress"></a>

📈 Progress
Fully Implemented Features
Personalized Day-wise Itinerary Generation: Automatically generates structured travel plans divided by day.

Budget-Aware Filtering: Ensures recommendations align with user budget constraints.

City-Restricted Recommendations: Prevents cross-city irrelevant suggestions.

Climate Summary Integration: Displays contextual weather information.

Local GPU Inference: Efficient 4-bit quantized LLM execution.

Partially Implemented Features / Work in Progress
Cloud Deployment: Currently optimized for local GPU execution.

External API Integrations: Planned integration with weather, hotel, and flight APIs.

Multi-city Route Optimization: Under development.

<a name="future-scope"></a>

🔮 Future Scope
Integration of real-time travel APIs

Multi-city itinerary optimization

User authentication and cloud-based trip saving

Deployment of scalable LLM infrastructure

Advanced retrieval and personalization mechanisms

<a name="applications"></a>

💸 Applications
Personalized Travel Planning - Structured, budget-aware itinerary generation.

AI Travel Assistant Systems - Demonstrates practical local LLM deployment.

Academic AI Demonstration - Showcases prompt engineering and GPU optimization.

<a name="project-setup"></a>

🛠 Project Setup
Clone the GitHub repository:

git clone https://github.com/Rehan1604/Travel_Genie-Inheritance-.git
cd Travel_Genie-Inheritance-
Backend setup:

cd backend
pip install -r requirements.txt
uvicorn main:app --reload
Frontend setup:

cd frontend
npm install
npm run dev
Frontend runs via npm run dev.
Backend runs via uvicorn main:app --reload.

<a name="team-members"></a>

👨‍💻 Team Members
Rehan Mehta: https://github.com/Rehan1604

Devansh Mehta: https://github.com/Devansh270

Bhavya Gothi: https://github.com/Bhavya4523

Jehan Bheda: https://github.com/jehanbheda

<a name="mentors"></a>

👨‍🏫 Mentors
Harsh Ogale: https://github.com/harshogale04

Piyush Patil: https://github.com/MAVERICK-111