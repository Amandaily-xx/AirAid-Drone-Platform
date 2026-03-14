# AeroGuide: AI-Powered Autonomous Drone Navigation for the Visually Impaired

**AeroGuide** is a drone-powered service platform designed to provide independence to the 253 million people worldwide living with visual impairments. While traditional tools like white canes and service dogs detect ground-level obstacles, they fail to identify overhead hazards, fast-moving traffic, or complex environmental changes. 

AeroGuide turns drones into "Flying Service Dogs" that scan the environment and provide real-time, natural language audio guidance to the user.

---

## 🚀 The Problem
- **Ground-Level Limitation:** White canes only detect what is at the user's feet. Low-hanging branches, construction signs, and open truck tailgates are frequent causes of injury.
- **High Cost of Entry:** Service dogs cost upwards of $50,000 to train and require significant maintenance.
- **Static Navigation:** Current GPS apps don't account for real-time hazards like temporary construction or sidewalk crowds.

## ✨ The Solution
AeroGuide is a software-first platform that leverages advanced AI Vision to process drone video feeds in real-time. 
1. **Scene Understanding:** Identifying hazards, doorways, crosswalks, and people.
2. **Audio Feedback:** Providing calm, human-like instructions via Bluetooth earpieces.
3. **Safety Analysis:** Pre-fetching "Safe Paths" using historical city data.

---

## 🛠️ Technology Stack & Sponsor Integrations

To be eligible for sponsor tracks, we have functionally integrated the following tools:

### 1. Google Gemini API (Visual Reasoning)
Used as the "eyes" of the platform. Gemini 1.5 Flash processes the drone's camera frames to describe the environment and identify specific hazards that a white cane would miss.

### 2. ElevenLabs (Human-Like Voice)
Used to convert AI-generated navigation instructions into natural, comforting speech. This ensures the user receives guidance that feels professional and easy to understand in noisy city environments.

### 3. MongoDB Atlas (Safe-Path Database)
We use MongoDB Atlas to store "Safe Path" logs. When a drone scans a route, the coordinates and hazards are cached so that future users on the same path receive instant navigation without re-processing the entire scene.

### 4. Solana (Micro-Payments)
Integrated as our "Pay-as-you-fly" layer. Using Solana’s low-latency blockchain, users pay for AI processing power in real-time using micro-transactions, making the service affordable and transparent.

### 5. Snowflake (City Safety Analytics)
Snowflake acts as our data warehouse, aggregating hazard data from thousands of drones to create a "Live Safety Map." This allows city planners to identify dangerous intersections based on real drone telemetry.

---

## 💻 How to Run the Prototype

1. Clone this repository.
2. Open `index.html` in any modern web browser (Chrome/Edge recommended).
3. Ensure you have granted Camera Permissions.
4. (Optional) Insert your **Gemini** and **ElevenLabs** API keys in the configuration section of the script.
5. Point the camera at an object and click **"Scan Path"**.

---

## 📈 Business Model
- **Subscription (SaaS):** $49/month for hardware lease and unlimited AI navigation.
- **B2B / Government:** Partnering with municipal "Smart City" initiatives to provide the service as a public utility.
- **Data Licensing:** Selling anonymized sidewalk-level hazard data to urban planners.

## 🔮 Future Roadmap
- **V2:** Indoor navigation using LiDAR for airports and shopping malls.
- **V3:** Integration with smart traffic lights (V2X) to tell users exactly when it is safe to cross.

---
**Created for the Drone-Based Startup Challenge (March 2026)**
