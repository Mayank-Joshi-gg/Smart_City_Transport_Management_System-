# Smart_City_Transport_Management_System
A Streamlit-based Smart Transport System that provides real-time route planning, interactive map visualization, and nearby hospital detection using multiple geospatial APIs.

📌 Features
📍 Convert location names into coordinates (Geocoding)
🛣️ Fetch multiple routes between source and destination
🗺️ Interactive map visualization using Folium
🏥 Display nearby hospitals using Overpass API
🔄 Fallback hospital data for reliability
⚡ Session-based dynamic updates in Streamlit
🌐 Real-time API integration (OSRM, Nominatim, Overpass)
🏗️ Project Structure
Smart-Transport-System/
│
├── app.py              # Main Streamlit application
├── routing.py          # Route generation logic (OSRM API)
├── hospital.py         # Hospital detection module
├── geocoding.py        # Location to coordinates conversion
├── utils.py            # Map creation & visualization
├── config.py           # Default settings
└── README.md           # Project documentation
🚀 How It Works
User enters source and destination
System converts locations → coordinates (Geocoding)
Routes are fetched using OSRM API
Nearby hospitals are fetched using Overpass API
Everything is plotted on an interactive Folium map
Streamlit displays results in real time
🛠️ Technologies Used
Python 🐍
Streamlit 🎨
Folium 🗺️
OSRM API 🛣️
Nominatim (OpenStreetMap) 🌍
Overpass API 🏥
Geopy 📍
⚙️ Installation & Setup
1. Clone Repository
git clone https://github.com/Mayank-Joshi-gg/smart-transport-system.git
cd smart-transport-system
2. Install Dependencies
pip install streamlit folium streamlit-folium geopy requests polyline
3. Run Application
streamlit run app.py
📷 Output
Interactive route maps
Multiple route options
Hospital locations nearby
Real-time updates
⚠️ Limitations
Depends on external APIs
No real-time traffic data
Requires stable internet connection
Limited public transport integration
🚀 Future Improvements
Add real-time traffic analysis
Integrate AI-based route optimization
Mobile application version
Public transport support
Emergency ambulance tracking system
