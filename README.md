# 🛫 Belfry Lite v3.5

**Belfry Lite** is a lightweight, browser-based flight tracking platform that visualizes real-time air traffic with an elegant and responsive UI.  
Built with **FastAPI**, **Leaflet.js**, and **Vanilla JavaScript**, it provides a clean foundation for integrating live aviation data from multiple sources.

---

## ✈️ Features

- **Real-Time Aircraft Tracking**  
  Visualizes aircraft positions, headings, and trails in near real-time using multiple data providers.

- **Multi-Source Support**  
  Fetch data from **OpenSky**, **ADS-B Exchange**, or **AeroDataBox**, with built-in dummy data fallback.

- **Follow Mode**  
  Automatically centers on a selected aircraft and follows it as it moves.

- **Smart Marker Clustering**  
  Efficiently renders large datasets of planes without cluttering the map.

- **Flight Search & Filters**  
  Search by flight ID, origin, or destination; filter by aircraft type or region.

- **Dark/Light Theme Toggle**  
  Switches map tiles and UI dynamically with smooth transitions.

- **Control Panel**  
  Adjust refresh intervals, toggle live updates, change data source, and recenter the map.

- **Live Stats Display**  
  Real-time counters for commercial, private, military, and test aircraft.

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | Leaflet.js, HTML5, Vanilla JS, CSS |
| **Backend** | FastAPI (Python) |
| **Data Sources** | OpenSky Network, ADS-B Exchange, AeroDataBox |
| **Environment** | Python 3.10+, Uvicorn, REST API integration |

---


```bash
