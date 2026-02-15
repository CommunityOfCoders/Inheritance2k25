<h1 align="center">
  <a href="https://github.com/Pranjal-Ghadge/PowerSenseAI">
    PowerSenseAI
  </a>
  <br>
  Intelligent Energy Monitoring & Analytics Dashboard
</h1>

<div align="center">
By Algorithm Addicts Team
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

##  Description

PowerSenseAI is an intelligent energy monitoring and analytics platform that provides real-time insights into power consumption patterns. The system leverages machine learning models to predict energy usage, detect anomalies, and optimize consumption for residential and commercial users. Built with a modern full-stack architecture, it features interactive dashboards, user authentication, and comprehensive data visualization tools.

## Links

- [GitHub Repository](https://github.com/Pranjal-Ghadge/PowerSenseAI)
- Project Demo Link : https://drive.google.com/drive/u/0/folders/1b5NvxB6eibCCVAbZe2xhfHq4svQ4TG8V
- [Project Screenshots]https://drive.google.com/drive/u/0/folders/1FKHxRuAg3q8wKSy-dR9iuEatMT9ynFMF


## Tech-Stack

### System Architecture

```mermaid
graph LR
    A[User Interface] --> B[Next.js Frontend]
    B --> C[Node.js Backend API]
    C --> D[MongoDB Database]
    C --> E[Python ML Models]
    D --> F[User Data Storage]
    E --> G[Predictive Analytics]
    G --> H[Energy Insights]
    H --> A
```

### Front-end

- **Next.js 16** - React framework with server-side rendering
- **TypeScript** - Type-safe JavaScript development
- **TailwindCSS** - Utility-first CSS framework
- **Chart.js** - Interactive data visualization
- **Shadcn/ui** - Modern UI component library
- **React Hooks** - State management and lifecycle handling

### Back-end

- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database for user data
- **Mongoose** - MongoDB object modeling
- **bcryptjs** - Password hashing and authentication
- **JWT** - Secure token-based authentication
- **Axios** - HTTP client for API requests

### Database / ML

- **MongoDB** - Cloud-hosted database
- **Python** - Machine learning model development
- **TensorFlow** - Deep learning framework
- **scikit-learn** - Machine learning algorithms
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing

## 📈 Progress

### Fully Implemented Features

* **User Authentication System**: Complete login/register functionality with secure password hashing and JWT tokens.
* **Dynamic User Dashboard**: Personalized dashboard displaying user information and energy consumption data.
* **Real-time Energy Analytics**: Interactive charts showing power consumption patterns, predictions, and anomalies.
* **Multiple Chart Types**: Line charts, bar charts, heatmaps, and scatter plots for comprehensive data visualization.
* **MongoDB Integration**: Robust database storage with fallback mechanisms for reliability.
* **Responsive Design**: Mobile-friendly interface that works seamlessly across all devices.

---

### Partially Implemented Features / Work in Progress

* **Machine Learning Predictions**: Basic LSTM and Prophet models implemented, with advanced model training in progress.
* **Anomaly Detection**: Framework established, currently being refined for higher accuracy.
* **Real-time Data Streaming**: Backend API ready, WebSocket integration for live updates pending.

## 🔮 Future Scope

* **Integration of IoT Devices**: Connect smart meters and sensors for real-time data collection.
* **Mobile Application**: Native iOS and Android apps for on-the-go energy monitoring.
* **Advanced Analytics Dashboard**: Enhanced ML models for more accurate predictions and insights.
* **Energy Optimization Recommendations**: AI-powered suggestions for reducing energy consumption.
* **Multi-tenant Support**: Enable organizations to manage multiple buildings or facilities.

## 💸 Applications

1. **Residential Energy Management** - Homeowners can monitor daily energy usage, identify peak consumption times, and reduce electricity bills through informed decisions.
2. **Commercial Building Analytics** - Businesses can optimize energy consumption across facilities, track carbon footprint, and implement sustainability initiatives.
3. **Smart Grid Integration** - Utility companies can leverage the platform for demand forecasting and load balancing across their networks.

## 🛠 Project Setup

1. Clone the GitHub repo.

```bash
git clone https://github.com/Pranjal-Ghadge/PowerSenseAI.git
```

2. Enter the project directory and install dependencies.

```bash
cd PowerSense_In/powersense_inside
# Install frontend dependencies
cd frontend
npm install
# Install backend dependencies
cd ../backend
npm install
```

3. Set up environment variables.

```bash
# In backend directory, create .env file
MONGO_URI=mongodb+srv://admin:admin123@cluster0.zhkj2qi.mongodb.net/?appName=Cluster0
PORT=5000
JWT_SECRET=your_jwt_secret_here
```

4. Start the application.

```bash
# Start backend server (from backend directory)
npm start

# Start frontend development server (from frontend directory)
npm run dev
```

5. Access the application.

- Frontend: http://localhost:3003
- Backend API: http://localhost:5000
- Dashboard: http://localhost:3003/dashboard

## 👨‍💻 Team Members

* Pranjal Ghadge: https://github.com/Pranjal-Ghadge
* Shravani Shelke: https://github.com/sforshravani
* Hrithik Lukade: https://github.com/hrithiklukade
* Trupti Naukarkar: https://github.com/truptinaukarkar

## 👨‍🏫 Mentors

* Mahi Palimkar: https://github.com/mahipalimkar
* Aadit Pujari: https://github.com/pipinstallaadit

---

<div align="center">
  <p>Made with ❤️ by the Algorithm Addicts Team</p>
  <p>© 2025 PowerSenseAI. All rights reserved.</p>
</div>