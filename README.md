# AeroGuide: Independence Redefined 🛰️👨‍🦯

**AeroGuide** is a software-first drone service platform designed to act as a "Flying Service Dog" for the visually impaired. Developed for the **Drone-Based Startup Challenge (March 2026)**, our platform bridges the gap between traditional navigation tools and the dynamic challenges of urban environments like the McGill University campus in Montreal.

---

## 🚀 The Problem: The "Overhead" Gap
Current assistive technologies for the 253 million people with visual impairments have critical failure points:
- **White Canes:** Only detect ground-level obstacles; users remain vulnerable to low-hanging branches, construction signs, and open truck tailgates.
- **Service Dogs:** Cost upwards of **$50,000** to train and require high maintenance.
- **Static Navigation:** Traditional GPS apps are "blind" to dynamic hazards like e-scooters, temporary construction, or winter icy patches common in Montreal.

## ✨ The Solution: Aerial Intelligence
AeroGuide leverages advanced AI Vision and autonomous drone technology to provide a hands-free, end-to-end navigation experience.

### 🌟 Core Product Workflow
1. **Voice-to-Destination:** User initiates a trip via voice (e.g., *"Take me to the McGill Arts Building"*).
2. **Optimal Routing:** **Gemini**, integrated with the **Google Maps API**, calculates the most accessible pedestrian route.
3. **Real-Time Hazard Scanning:** A drone hovers 8 feet ahead, acting as a forward-scouting sensor.
4. **Adaptive Audio Feedback:** Real-time instructions (e.g., *"Stop. Construction barrier ahead. Pivot left"*) are delivered via **ElevenLabs**.

---

## 🛠️ Technology Stack & Sponsor Integrations

We have functionally integrated the following sponsor tools to power our platform:

### 🧠 Google Gemini API (Visual Reasoning)
Gemini 1.5 Flash serves as the "Visual Cortex" of AeroGuide. It processes the drone's live feed to differentiate between harmless shadows and dangerous obstacles, providing the semantic data required for safe navigation.

### 🗣️ ElevenLabs (Natural Audio Interface)
Safety depends on trust. We use ElevenLabs to provide high-fidelity, natural human voices for guidance. This ensures a calm and professional user experience, even in noisy city environments.

### 💾 MongoDB Atlas (Safe-Path Caching)
We utilize MongoDB Atlas to store "Path Signatures." Frequently traveled routes (e.g., McGill Metro to Roddick Gates) are cached, allowing for instant safety data retrieval and reduced latency.

### ⛓️ Solana (Decentralized Micro-Payments)
AeroGuide uses a "Pay-as-you-fly" model. Solana handles ultra-low-cost micro-transactions, allowing users to pay for AI compute credits in real-time with sub-second finality.

### ❄️ Snowflake (Predictive Hazard Analytics)
Telemetry from all active drones is aggregated into a Snowflake Data Cloud to create a "Live Safety Map" of Montreal, allowing us to predict dangerous intersections before a user even arrives.

---

## 🛠️ Key Features
- **Aerial Pathfinding:** Identifying walk-zones from a perspective white canes cannot reach.
- **Dynamic Obstacle Avoidance:** Real-time tracking of cyclists, pedestrians, and vehicles.
- **McGill-Ready Localization:** Optimized for the unique street layouts and construction challenges of Downtown Montreal.

## 📈 Business Model
- **Hardware-as-a-Service (HaaS):** A $49/month subscription providing the drone, insurance, and unlimited AI processing.
- **B2G Partnerships:** Working with the Ville de Montréal to integrate AeroGuide into municipal accessibility initiatives.
- **Data Licensing:** Providing sidewalk-level hazard data to urban planners via the Snowflake Data Cloud.

---

## 💻 How to Run the Prototype
1. Clone this repository.
2. Open `index.html` in a modern web browser.
3. Grant **Camera Permissions** to simulate the Drone Eye.
4. Use the **"Set Destination"** button to initiate the McGill navigation logic.
5. Use the **"Process Environment"** button to trigger the Gemini-powered hazard detection.

---
**Developed for the Drone-Based Startup Challenge (March 2026)**  
*Empowering independence through autonomous flight.*
