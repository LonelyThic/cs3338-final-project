# CS3338 Final Project:
# SUAS Flight Path Visualization

A web-based mission planning and simulation tool for Small Unmanned Aircraft Systems (SUAS), developed for the Army Research Lab. This system allows users to visualize drone flight paths, analyze stealth profiles, and simulate telemetry data in 2.5D environments.

## 📌 Project Features
- Mission upload (CSV/JSON) with map rendering
- 3D flight path visualization using Mapbox
- Real-time/simulated telemetry analytics (speed, altitude, battery)
- Geofencing with alert system and emergency failsafe
- Secure user authentication
- Modular plugin-based architecture for future expansion


## 🐳 Getting Started (Docker)
```bash
git clone https://github.com/your-org/suas-project.git
cd suas-project
docker-compose up