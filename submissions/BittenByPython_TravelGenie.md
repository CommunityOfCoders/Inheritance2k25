<h1 align="center">
  <a href="https://github.com/CommunityOfCoders/Inheritance2k25">
    CoC Inheritance 2025
  </a>
  <br>
  TravelGenie: AI-Powered Smart Travel Planning System
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

## 📝 Description

TravelGenie is an AI-powered smart travel planning system that generates personalized, structured, and optimized travel itineraries using a locally deployed Large Language Model. The system solves the problem of generic and unrealistic travel suggestions by combining structured dataset filtering with context-aware LLM generation. Built using React, FastAPI, and Mistral 7B Instruct with GPU acceleration, TravelGenie delivers realistic, budget-aware, and city-restricted travel plans.

## 🔗 Links

- [GitHub Repository](https://github.com/Rehan1604/Travel_Genie-Inheritance-)
- [Demo Video]https://drive.google.com/file/d/17rnifMKwYDJi85VA_xYY3rXyMjG5T3Hy/view?usp=drive_link
- [Project Screenshots/Drive] https://drive.google.com/drive/folders/1NHrsDFPxkjYD7yWH67OHcHFVX3k0ld5h?usp=drive_link
- [Hosted Website](Not Deployed Yet)

## 🤖 Tech-Stack

### 🏗️ System Architecture

```mermaid
graph LR
    A[User Input] --> B[React Frontend Vite]
    B --> C[Axios API Request]
    C --> D[FastAPI Backend]
    D --> E[CSV Dataset Filtering]
    E --> F[Structured Prompt Injection]
    F --> G[Mistral 7B Instruct 4bit Quantized]
    G --> H[RTX 4060 GPU CUDA 12.7]
    H --> I[Day-wise Structured Itinerary Output]
    I --> B

Front-end
React.js (Vite)

Axios

Dynamic Chat Interface

localStorage for itinerary persistence

Back-end
FastAPI

HuggingFace Transformers

Accelerate

Mistral 7B Instruct

Database / ML
Structured CSV dataset (Cities from India, USA, Iran)

Includes climate data, pricing ranges, and category metadata

4-bit quantization for optimized inference

NVIDIA RTX 4060 GPU with CUDA 12.7

📈 Progress
Fully Implemented Features
Personalized Day-wise Itinerary Generation: Automatically generates structured travel plans divided by day.

Budget-Aware Dataset Filtering: Filters attractions based on user-defined budget constraints.

City-Restricted Recommendation System: Ensures no cross-city or irrelevant outputs are generated.

Partially Implemented Features / Work in Progress
Cloud Deployment: Currently running locally; deployment to cloud environment planned.

External API Integrations: Weather, hotel, and flight APIs to enhance itinerary realism.

🔮 Future Scope
Integration of real-time weather APIs.

Expansion to multi-city itinerary planning.

User authentication and persistent trip storage.

Cloud-based LLM deployment.

Advanced retrieval mechanisms for scalable systems.

💸 Applications
Personalized Travel Planning - Generates realistic, budget-aware, and structured travel itineraries.

AI Travel Assistant Systems - Demonstrates practical local LLM deployment for smart recommendation engines.

🛠 Project Setup
Clone the GitHub repo.

git clone https://github.com/Rehan1604/Travel_Genie-Inheritance-.git
Enter the project directory and install dependencies.

Backend Setup:

cd Travel_Genie-Inheritance-/backend
pip install -r requirements.txt
uvicorn main:app --reload
Frontend Setup:

cd ../frontend
npm install
npm run dev
Start the application.

Frontend runs on local development server after npm run dev.
Backend runs via uvicorn main:app --reload.

👨‍💻 Team Members
Rehan Mehta: https://github.com/Rehan1604

Devansh Mehta: https://github.com/Devansh270

Bhavya Gothi: https://github.com/Bhavya4523

Jehan Bheda: https://github.com/jehanbheda

👨‍🏫 Mentors
Harsh Ogale: https://github.com/harshogale04

Piyush Patil: https://github.com/MAVERICK-111