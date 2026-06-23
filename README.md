�
� VayuDrishti — AI-Powered
Urban Air Quality Intelligence
ET AI Hackathon 2.0 — 2026 | Phase 2: Build
Sprint
Problem Statement 5: AI-Powered Urban Air
Quality Intelligence for Smart City Intervention
🏆 Problem Statement
India's air quality crisis affects 24 of its 50 most
polluted cities. Despite 900+ CAAQMS monitoring
stations under the National Clean Air Programme,
only 31% of cities have actionable multi-agency
response protocols. The data exists — the
intelligence layer to act on it does not.
💡 Our Solution: VayuDrishti
VayuDrishti (वायुदृ — "Vision of Air") is an AI-powered
Urban Air Quality Intelligence platform that moves city
administrations from reactive monitoring to
proactive, evidence-based intervention.
Key Features
Feature
Description
🗺 Ward-Level
AQI Map
🔮 24–72hr AI
Forecast
Real-time geospatial heatmap
across all city wards
LSTM + Random Forest
ensemble prediction at 1km
grid resolution
🏭 Source
Attribution
🚔 Enforcement
Intelligence
ML model identifying pollution
sources (vehicles, industry,
construction, burning)
AI-ranked enforcement
priorities with auto-generated
evidence packages
🌍 Multilingual
Advisory
📊 Multi-City
Dashboard
Citizen alerts in English, Telugu,
Hindi, Kannada (12 languages
planned)
Compare trends across Delhi,
Mumbai, Bengaluru, Kolkata,
Chennai
🏗 System Architecture
DATA SOURCES          INGESTION            
AI MODELS           INTELLIGENCE         
OUTPUT
─────────────         
─────────           
──────
CAAQMS Sensors   
LSTM Forecast   
Dashboard
Sentinel-5P      
Random Forest   
Mobile App
IMD Weather      
─────────           
────────────         
→    Apache Kafka    
→   Source Agent    
→    TimescaleDB     
Dispersion Mdl  →   Enforcement     
Reports
Traffic Data     
LLM Advisory    
Open API
Permit Registry  →
See 
→    Data Cleaning   
→   Forecast Agent  →    
→    PostGIS         
→   Alert Dispatch  →    
    Feature Eng.    
Ensemble Model  →   Multi-Agent AI  →    
IVR/SMS
→    
→    
→    
→    
→    
→    
→    
architecture.html
 for the full visual diagram.
🚀 Live Demo
Open 
index.html
 in any browser — no server
required.
What to try:
1. Switch cities (top right) — Delhi, Mumbai,
Bengaluru, Kolkata, Chennai
2. View ward-level AQI hotspot map
3. Check 24-hour AI forecast chart
4. Read pollution source attribution
5. Switch advisory languages — English / Telugu /
Hindi / Kannada
6. Review enforcement priorities
📁 Project Structure
et-ai-hackathon-ps5-airquality/
│
├── index.html              # Main working 
prototype (dashboard)
├── architecture.html       # System 
architecture diagram
├── README.md               # This file
└── docs/
└── VayuDrishti_Report.pdf   # 
Detailed solution document
🛠 Tech Stack
Frontend: HTML5, CSS3, JavaScript, Chart.js
AI/ML (planned full build): Python, scikit-learn,
TensorFlow/Keras (LSTM), LangChain
Data: CPCB CAAQMS API, Sentinel-5P (Copernicus),
IMD OpenData
Geospatial: GeoPandas, PostGIS, Leaflet.js
Backend: FastAPI, TimescaleDB, Apache Kafka
LLM: Claude API / GPT-4 for multilingual citizen
advisory
📈 Judging Criteria Coverage
Criteria
How We Address It
Innovation
(25%)
Business
Impact (25%)
Multi-agent AI fusing satellite +
IoT + weather for hyperlocal 1km
forecasts
Technical
Excellence
(20%)
Direct link to NCAP targets;
enforcement tool reduces
response time
LSTM + RF ensemble;
atmospheric dispersion
modelling; RAG advisory
Scalability
(15%)
Kafka-based pipeline; API-first
design; deployable across all
132 NCAP cities
Criteria
User
Experience
(15%)
How We Address It
Multilingual, mobile-first, citizen
+ admin dual interface
👤 Team
Bala Karnayana — Team Leader
B.Tech CSE, Mohan Babu University
AI/ML Intern @ SmartBridge | Data Analytics Intern @
ApexPlanet
GitHub: 
@karnayanaBala
📄 License
MIT License — Built for ET AI Hackathon 2026
