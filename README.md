# Enhanced Professional Network Analysis System

An interactive web-based system for managing, analyzing, and visualizing complex networks such as transportation, telecommunications, social, supply chain, and utility networks. The application uses **Leaflet.js** for mapping, **Leaflet Routing Machine** for route calculations, and integrates rich user interface controls for data management, analysis, and reporting.

---

## Features

### 1. Location & Service Area
- Set your location automatically (via browser geolocation) or manually by clicking on the map.
- Display and customize your service area radius.
- Switch between tabs to:
  - Search and list nearest facilities (hospitals, schools, banks, etc.).
  - Analyze service area coverage and density.

### 2. Network Timetable
- Create schedules with name, time slot, duration, and description.
- Manage multiple time slots with add, delete, activate, and clear options.
- Apply timetable constraints to network analysis for time-based evaluations.

### 3. Enhanced Node Management
- Add, delete, and randomly generate network nodes (critical, standard, optimal).
- Select and batch-delete nodes.
- View node details and manage selection states.

### 4. Network Configuration
- Choose analysis type: Routing, Coverage, Clustering, Connectivity, Flow, Shortest Path, Service Area.
- Select network type: Transportation, Telecommunications, Social Network, Supply Chain, Utility Network.
- Set analysis radius and run network analysis.

### 5. Network Metrics Dashboard
- Displays total nodes, total connections, average connection distance, and network density.

### 6. Advanced Analysis Tools
- Service area network analysis (connectivity, quality, coverage efficiency).
- Centrality metrics, anomaly detection, and heatmap generation.
- Time-based traffic analysis and route optimization.
- Facility access analysis for distance and accessibility ratings.

### 7. Export & Import
- Export the complete network state (nodes, facilities, timetable, configuration) as a JSON file.
- Import saved network configurations.

### 8. Interactive Map Features
- Facilities and nodes have clickable markers with popups for details and actions.
- Routing between your location and selected facilities.
- Real-time metrics update and auto-activation of timetable slots.

---

## Technologies Used
- **HTML5**, **CSS3**, **JavaScript**
- **Leaflet.js** for interactive mapping
- **Leaflet Routing Machine** for routing and navigation
- **Font Awesome** for icons
- **OpenStreetMap** tiles as the base map layer

---

## How to Use
1. Open the `enhanced_network_analysis.html` file in your browser.
2. Allow location access (optional) to auto-detect your position.
3. Set your service area radius and run facility searches or analysis.
4. Add nodes manually or randomly to build your network.
5. Choose an analysis type and click **Run Analysis**.
6. Use export/import to save or load your work.

---

## Keyboard Shortcuts
| Shortcut      | Action                        |
|---------------|--------------------------------|
| **Ctrl + L**  | Set my location               |
| **Ctrl + S**  | Show service area             |
| **Ctrl + F**  | Find nearest facilities       |
| **Ctrl + R**  | Run network analysis          |
| **Escape**    | Exit node placement/deletion  |

---

## License
This project is released under the MIT License. You are free to use, modify, and distribute it with attribution.
