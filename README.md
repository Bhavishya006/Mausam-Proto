# Mausam Pulse 🌦️
### Personal Weather Intelligence & Operational Decision System

[![React](https://img.shields.io/badge/React-18.3.1-61DAFB?logo=react&logoColor=black)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.6.3-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-5.4.10-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**Mausam Pulse** transforms raw atmospheric data into personalized, operational decisions. Designed to bridge meteorological science and everyday life, it connects real-time IMD observation stations, Doppler radar feeds, and diurnal forecasting to individual risk tolerances and schedules.

---

## 🌟 Key Features

- **🔐 Role-Based Access & Authorization**:
  - Secure credential-based sign in and account registration.
  - Role clearance profiles: *Senior Meteorologist (IMD)*, *Agri & Field Officer*, *Urban Commuter*, *Standard Citizen*, and *Disaster Response Administrator*.
  - Clearance-tailored recommendations and telemetry permissions.

- **🛰️ Live Doppler & Synoptic Telemetry**:
  - Real-time weather and Air Quality Index (AQI) synchronization with Open-Meteo & IMD observation networks.
  - Major regional meteorological hubs: New Delhi, Mumbai, Bengaluru, Ahmedabad, Pune, Hyderabad, Kolkata, Chennai, Jaipur, and Goa.
  - Precise GPS geolocation support for hyperlocal weather.

- **🤖 Mausam Copilot (AI Weather Intelligence)**:
  - Natural language decision assistant grounded in live atmospheric conditions.
  - Instant answers on hydration, outdoor windows, travel gear, air quality advisories, and crop irrigation.

- **⏱️ Activity Planner & Diurnal "What-If" Simulator**:
  - Algorithmic evaluation of weather windows for running, commuting, travel, sports, and farming.
  - Hour-by-hour multi-variable simulation (temperature, wet-bulb humidity, wind velocity, precipitation probability, and UV index).

- **🚨 Active Weather Bulletins & Warning Subscriptions**:
  - Live IMD nowcasts, convective warnings, and heat/UV advisories.
  - Granular notification subscriptions for severe storms, rain nowcasts, and air quality spikes.

---

## 🚀 Quick Start

### 1. Prerequisites
- [Node.js](https://nodejs.org/) (version 18.0.0 or higher recommended)
- `npm` or `yarn`

### 2. Installation
Clone the repository and install the dependencies:
```bash
git clone https://github.com/<your-username>/mausam-pulse.git
cd mausam-pulse
npm install
```

### 3. Running Development Server
```bash
npm run dev
```
Open [http://localhost:5173/](http://localhost:5173/) in your browser.

### 4. Building for Production
```bash
npm run build
```
Creates an optimized production bundle in the `dist/` directory.

---

## 🛠️ Tech Stack

- **Framework**: React 18
- **Language**: TypeScript
- **Bundler & Tooling**: Vite
- **Icons**: Lucide React
- **Styling**: Modern CSS3 (Glassmorphism & Responsive Layouts)
- **Data Providers**: Open-Meteo Forecast & Air Quality API, Synoptic Station Registry

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
