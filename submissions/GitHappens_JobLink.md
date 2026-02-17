
<h1 align="center">
  <a href="https://github.com/CommunityOfCoders/Inheritance2k25">
    CoC Inheritance 2025
  </a>
  <br>
  [Job-Link]: [AI-Powered Resume Screening & Smart Candidate Matching]
</h1>

<div align="center">
By [Git-Happens]
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

[JobLink is an AI-powered recruitment platform that streamlines the hiring process by automatically analyzing resumes and matching candidates to job requirements. It solves the problem of manual screening and inefficient shortlisting by using intelligent resume parsing and candidate ranking. The platform is built with React, Tailwind CSS, and Vite on the frontend, and uses Node.js, Express, Supabase, PostgreSQL, JWT authentication, and AI/ML services on the backend.]

## 🔗 Links

- [GitHub Repository]([https://github.com/d-mahi14/JobLink-Inheritance])
- [Demo Video]([https://drive.google.com/file/d/1wwpKIkGOv9dnkLZVD04wSObGkiDwq0nx/view?usp=drivesdk])
- [Project Screenshots/Drive]([https://drive.google.com/file/d/1wwpKIkGOv9dnkLZVD04wSObGkiDwq0nx/view?usp=drivesdk])
- [Hosted Website]([job-link-inheritance.vercel.app/])

## 🤖 Tech-Stack

### 🏗️ System Architecture

```mermaid
graph LR
    U[User/Source] --> F[React Frontend]
    F --> B[Express Backend]
    B --> D[Supabase]
    B --> AI[Resume Parsing and matching]
    AI --> B
    B --> F

```

### Front-end
- React(Vite)
- Tailwind CSS

### Back-end
- Node.js
- Express.js
- JWT Authentication
- REST APIs

### Database / Blockchain / ML (Optional Sections)
- Supabase
- Resume Parsing
- Candidate Matching Algorithm

## 📈 Progress

### Fully Implemented Features

* **User Authentication**: [Secure login and signup system for both recruiters and candidates using JWT-based authentication.].
* **Resume Upload System**: [Candidates can upload resumes which are stored and processed for job matching.].
* **Job Posting**: [Recruiters can create and manage job postings with role descriptions and requirements.].
* **Recruiter Dashboard**: [Recruiters can view applicants and manage hiring decisions.].
* **Candidate Dashboard**: [Candidates can track job applications and uploaded resumes.].

---

### Partially Implemented Features / Work in Progress

* **Google Aunthentication**: [Sign In through google directly].
* **AI-based resume ranking improvements**: [Improving the resume ranking system].

## 🔮 Future Scope

* [Email notifications for job updates].
* [Interview scheduling integration].
* [Resume feedback suggestions for candidates].

## 💸 Applications

1. **College Placement Systems** - [Helps institutions manage student applications efficiently].
2. **Recruitment Platforms** - [Automates resume screening and candidate shortlisting].

## 🛠 Project Setup

JobLink can be accessed by [this link] job-link-inheritance.vercel.app/

1. Clone the GitHub repo.

```bash
git clone [https://github.com/d-mahi14/JobLink-Inheritance.git]
cd JobLink-Inheritance

```

2. Enter the project directory and install dependencies.

```bash
cd backend
npm install

cd frontend
npm install

```

3. Configuration

```bash
Frontend Environment Variables
Create a .env file in the frontend directory:

# API Configuration
VITE_API_URL=http://localhost:5000/api

# For production
# VITE_API_URL=https://your-api-domain.com/api

Supabase Configuration (if using Supabase directly)
VITE_SUPABASE_URL=https://your-project-ref.supabase.co
VITE_SUPABASE_ANON_KEY=your-anon-key-here
Backend Environment Variables (Example)
Create a .env file in the backend directory:

# Database
DATABASE_URL=postgresql://user:password@localhost:5432/joblink

# JWT
JWT_SECRET=your-jwt-secret-key

# Server
PORT=5000
NODE_ENV=development

# Google OAuth (Optional)
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
GOOGLE_CALLBACK_URL=http://localhost:5000/api/auth/google/callback

```

4. Start the application.

```bash
Frontend:

cd frontend
npm run dev
The app will run at http://localhost:3000

Backend:

cd backend
npm run dev
The API will run at http://localhost:5000

```

## 👨‍💻 Team Members

* **[Mokshi Shah]**: [https://github.com/Mokshii46]
* **[Mahi Desai]**: [https://github.com/d-mahi14]
* **[Gaurang Upadhyay]**: [https://github.com/gaurang-2305]
* **[Akshat Chauhan]**: [https://github.com/akshat280706]

## 👨‍🏫 Mentors

* **[Santrupt]**: [https://github.com/santrupt29]
* **[Akash]**: [https://github.com/shinymack]

