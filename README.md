# 🗺️ Khojo Mapping System

> **Discover and explore locations with precision**

Khojo (meaning *"Search/Find"* in Hindi) is an interactive web-based mapping application built during summer training. It allows users to explore geographic locations, add custom markers, switch between map layers, and save frequently visited places — all within a clean, intuitive interface.

---

## 📸 Preview

![Khojo Mapping System](./)

---

## 🚀 Features

- **📍 Locate Me** — Instantly centers the map on the user's current GPS location
- **📌 Add Markers** — Drop custom markers anywhere on the map with a single click
- **🗑️ Clear Markers** — Remove all placed markers from the map at once
- **🔍 Search Location** — Search for any address or place name to navigate the map
- **🗺️ Map Layers** — Switch between three different views:
  - Streets — Standard road and label view
  - Satellite — High-resolution aerial imagery (powered by Esri)
  - Topography — Terrain and elevation-based view
- **💾 Saved Locations** — Save and manage a list of favorite or important locations
- **➕ / ➖ Zoom Controls** — Smooth zoom in and out controls

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure and markup |
| **CSS3** | Styling and responsive layout |
| **JavaScript (Vanilla)** | Application logic and interactivity |
| **Leaflet.js** | Open-source interactive map rendering |
| **OpenStreetMap** | Map tile data (Streets layer) |
| **Esri / ArcGIS** | Satellite and topography tile layers |
| **Geolocation API** | Browser-based "Locate Me" functionality |

---

## 📂 Project Structure

```
khojo-mapping-system/
│
├── index.html          # all code here 

---

## ⚙️ How to Run

No build tools or dependencies required. Just run it in a browser!

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/your-username/khojo-mapping-system.git
   ```

2. **Open** `index.html` in any modern web browser:
   ```bash
   # Option 1: Open directly
   open index.html

   # Option 2: Use a local server (recommended for Geolocation API)
   npx live-server
   # or
   python -m http.server 3000
   ```

3. Visit `http://localhost:3000` in your browser.

> ⚠️ **Note:** The "Locate Me" feature requires the app to be served over `localhost` or `HTTPS` due to browser Geolocation API security restrictions.

---

## 🧭 Usage Guide

| Action | How To |
|--------|--------|
| Find your location | Click **Locate Me** |
| Place a marker | Click **Add Marker**, then click on the map |
| Remove all markers | Click **Clear Markers** |
| Search a place | Type in the search box and click **Search** |
| Change map style | Click **Streets**, **Satellite**, or **Topography** |
| Save a location | Search or navigate to it, then save it |
| Remove saved location | Click the ✕ button next to the saved location |

---

## 🌍 Map Layers

- **Streets** — Powered by OpenStreetMap; shows roads, labels, and points of interest
- **Satellite** — High-resolution imagery from Esri/ArcGIS covering the entire globe
- **Topography** — Shows elevation contours and terrain features

---

## 🎓 About This Project

This project was developed as part of my **Summer Training** during college. The goal was to apply core web development skills — HTML, CSS, and JavaScript — to build a real-world, interactive application using the **Leaflet.js** mapping library.

**Key learnings from this project:**
- Integrating third-party JavaScript libraries (Leaflet.js)
- Working with browser APIs (Geolocation)
- Consuming external tile services (OpenStreetMap, Esri)
- DOM manipulation and event-driven programming
- Building a responsive, user-friendly interface

---

## 🔮 Future Improvements

- [ ] Route planning between two or more locations
- [ ] Export saved locations as a file (JSON / CSV)
- [ ] Custom marker icons and labels
- [ ] Distance measurement tool
- [ ] Offline map support using service workers
- [ ] Mobile-responsive design improvements

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [Leaflet.js](https://leafletjs.com/) — The open-source JavaScript library for interactive maps
- [OpenStreetMap](https://www.openstreetmap.org/) — Map data contributors
- [Esri / ArcGIS](https://www.esri.com/) — Satellite and topography tile services

---

*Built with ❤️ during Summer Training*
