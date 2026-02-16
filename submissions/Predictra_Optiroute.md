
<h1 align="center">
  <a href="https://github.com/CommunityOfCoders/Inheritance2k25">
    CoC Inheritance 2025
  </a>
  <br>
  Optiroute: Flood risk route planner
</h1>

<div align="center">
By Predictra
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
A smart web-based flood-aware route planning system that calculates **real-world road routes** and integrates **flood risk scoring** to help users choose the safest path during heavy rainfall or waterlogging conditions.

Built using **Next.js, Leaflet (OpenStreetMap), Mapbox APIs, and MongoDB**.

<a name="link"></a>
## 🔗 Links

- [GitHub Repository](https://github.com/ap6458/flood-risk-score-routing-map.git)
- [Demo Video](https://drive.google.com/file/d/1S0w_d-i7nakl6yh5uKN_lwVs9lK6WESI/view?usp=drivesdk)
- [Project Screenshots/Drive](https://drive.google.com/drive/folders/1fnPG_TP159gvcEsdqOLZJNo-JOjYWISr)
- [Hosted Website](https://flood-risk-score-routing-map.vercel.app/)

## 🤖 Tech-Stack
- Next.js 16
- React
- Leaflet.js
- OpenStreetMap Tiles
- TypeScript
- Next.js API Routes
- MongoDB
- Mapbox Directions API
- Mapbox Geocoding API
- Scikit Learn

### 🏗️ System Architecture

```mermaid
graph LR
    User inputs source and destination --> Mapbox Geocoding API at backend fetches the coordinates
    Coordinates --> Mapbox Directions API is called which displays alternate routes on the website
    Mapbox Routing--> Risk score is calculated based on which safest route is shown
    User can add flood reports either using their location or manually entering location --> Flood reports are saved in mongodb database at the backend
    User Report --> The risk score gets updated and safest route is shown


```

### Front-end
- Next.js 16
- React
- Leaflet.js
- OpenStreetMap Tiles
- TypeScript

### Back-end
- Next.js API Routes
- MongoDB

### External APIs
- Mapbox Directions API
- Mapbox Geocoding API


## 📈 Progress

### Fully Implemented Features

* **Flood Risk Scoring Algorithm**: Each route is evaluated using:
Distance from known waterlogging points
Severity weighting (Low / Moderate / High)
Distance-based risk multiplier
Proximity to live user-reported flood points
Output:
Each route gets a numerical risk score
Routes are sorted from lowest to highest risk
Safest route is highlighted in the sidebar
* **Location & Autocomplete**: Mapbox Geocoding API integration
Autocomplete search suggestions
Restricted to Mumbai region
Manual coordinate input supported
Voice Input supported
“Use My Location” feature
Dark Mode Toggle Feature
* **Multi-Mode Route Planning**: Driving 🚗
Walking 🚶
Cycling 🚴
Real ETA calculation
Distance calculation (km)
Multiple route alternatives
Automatic safest route prioritization
Routes are fetched using Mapbox API and rendered on Leaflet (OpenStreetMap).

---

### Partially Implemented Features / Work in Progress

* **Real-Time Rainfall Data Integration**: Enhance route risk scoring using:
Real-time rainfall intensity
Short-term rainfall prediction
Zone-wise rain severity mapping
Planned Implementation
Integrate OpenWeather / IMD API
Map rainfall intensity to flood probability
Dynamically increase risk score during heavy rainfall
Display rainfall overlay layer on map

## 🔮 Future Scope

* User authentication system
* Save favorite routes
* Mobile optimized UI
* Can be upgraded for the whole country if dataset of flood points is obtained
## 💸 Applications

1. **Urban Disaster Management Systems** - Where It Applies
Municipal corporations
Smart City projects
Disaster management authorities
Traffic control departments
How It Helps
Identifies high-risk flooded road segments
Suggests safer alternative routes in real time
Supports emergency vehicle routing during heavy rainfall
Assists in flood-prone zone monitoring
2. **Public Transportation & Logistics Optimization** - Where It Applies
Cab aggregators (e.g., ride-sharing services)
Delivery & logistics companies
Bus and public transport systems
Fleet management systems
How It Helps
Avoids waterlogged routes
Minimizes vehicle damage due to flooding
Improves on-time delivery rates
Reduces fuel consumption from rerouting
## 🛠 Project Setup

1. Clone the GitHub repo.

```bash
git clone https://github.com/ap6458/flood-risk-score-routing-map.git
```

2. Enter the project directory and install dependencies.

```bash
cd flood-risk-score-routing-map

```
3. Configure Environment Variables

Create a file named:

```
.env.local
```

Add the following:

```env
NEXT_PUBLIC_MAPBOX_TOKEN=YOUR_MAPBOX_TOKEN
MONGODB_URI=mongodb+srv://flooduser:flood12345@cluster0.5i4banq.mongodb.net/?appName=Cluster0

```

Where to get:
*Mapbox Token*
1. Go to https://account.mapbox.com
2. Create a Public Token
3. Ensure Directions API & Geocoding API are enabled


- Example Local format for mongodb uri:

```
mongodb://127.0.0.1:27017/floodDB
```

---
Install node.js

```bash
npm install
```
4. Run Development Server

```bash

npm run dev
```

Open in browser:

```
http://localhost:3000
```
## Website Hosted on Vercel
https://flood-risk-score-routing-map.vercel.app/





## 👨‍💻 Team Members

* **Aryan Parab**: [https://github.com/ap6458]
* **Arya Shirke**: [https://github.com/AryaShirke16]
* **Rayon Biswas**: [https://github.com/RayonBiswas]
* **Nihar Shah**
## 👨‍🏫 Mentors

* **Soham Rane**:[https://www.linkedin.com/in/sohamrane301]
* **Harshal Kamble**: [https://www.linkedin.com/in/harshal-ishere]