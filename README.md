# AirAid: Personal AI Drone Navigator

AirAid is a software platform that converts drone technology into a comprehensive navigation service for the visually impaired. 

## 🌟 Core Product Workflow
Our system provides a hands-free, end-to-end navigation experience:
1. **Voice-to-Destination:** User speaks their destination into the app (e.g., "Take me to the pharmacy").
2. **Optimal Routing:** Using **Gemini** in conjunction with **Google Maps API**, AirAid calculates the most accessible pedestrian route.
3. **Real-Time Hazard Scanning:** The drone hovers ahead, using **Gemini 1.5 Flash Vision** to monitor for real-time obstacles (scooters, branches, puddles).
4. **Adaptive Audio Feedback:** Instructions are sent to the user via **ElevenLabs**, providing natural guidance like "Walk straight," "Hazard ahead, stop," or "Turn left in 10 steps."

## 🛠️ Key Features
- **Aerial Pathfinding:** Unlike ground GPS, the drone sees the path from 8 feet up, identifying clear walk-zones before the user arrives.
- **Smart Hazard Detection:** Leverages Google Gemini to differentiate between a static object (a trash can) and a moving hazard (a cyclist).
- **Decentralized Infrastructure:** 
    - **Solana:** Securely handles micro-payments for drone flight credits.
    - **MongoDB Atlas:** Caches "User History" for recurring routes (e.g., Home to Grocery Store).
    - **Snowflake:** Aggregates hazard data across multiple drones to create a city-wide "Blind-Safe" heat map.

## 🚀 The Problem
- **Ground-Level Limitation:** White canes only detect what is at the user's feet. Low-hanging branches, construction signs, and open truck tailgates are frequent causes of injury.
- **High Cost of Entry:** Service dogs cost upwards of $50,000 to train and require significant maintenance.
- **Static Navigation:** Current GPS apps don't account for real-time hazards like temporary construction or sidewalk crowds.

## ✨ The Solution
AirAid is a software-first platform that leverages advanced AI Vision to process drone video feeds in real-time. 
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
**Created for the Drone-Based Startup Challenge (March 2026)**
