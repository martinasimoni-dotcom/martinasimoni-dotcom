# Martina Simoni

**Architect · Building Engineer · AI Researcher**

I spent 5 years in Dutch architecture firms designing buildings. Then I realised the most interesting problems weren't on the drawing board — they were in the gap between what architects know and what the tools can do. So I went back to school (IAAC Barcelona) and spent a year building AI tools to close that gap.

Turns out you can train models on 1,691 buildings, route pedestrians through the coolest streets in Vienna, automate the part of a project manager's day they hate most, and predict crowd stampede risk from a satellite image. Who knew.

Now I sit somewhere between architect and developer — which means I'm too technical for most architecture offices and too obsessed with buildings for most tech companies. I consider this a feature, not a bug.

---

## What I've built

| Project | What it does | Stack |
|---------|-------------|-------|
| [GigAI](https://github.com/martinasimoni-dotcom/gigai) | Project managers spend 45 minutes per RFI doing coordination work a machine could do in 30 seconds. GigAI reads the RFI, generates a full proposal, and waits for a human to tap approve. 99% time reduction. Validated with 15 PMs (including one from MVRDV). | Python · FastAPI · Claude AI · ACC API · PostgreSQL · React · Revit .NET |
| [Treeat](https://github.com/martinasimoni-dotcom/Treeat) | Cities are getting hotter. Treeat simulates street-level heat (UTCI) for any district, finds where trees cool the most per euro spent, and routes pedestrians home through the shadiest streets. No LiDAR. No expensive data. Built in 48 hours. Live at treeat.vercel.app | Python · FastAPI · OSMnx · Infrared SDK · React · Neon Postgres |
| [Disperse](https://github.com/martinasimoni-dotcom/disperse) | 80 people died at Maha Kumbh Mela in 2025. Disperse lets you click any location on a satellite map, draw crowd obstructions, and get an AI-generated density heatmap. No sensors. No field data. Just a map and two Keras models. | Python · FastAPI · Keras · TensorFlow · U-Net · React · Mapbox · OpenCV |
| SURROUND | 70% of design decisions that affect a building's carbon are made at the concept stage — when nobody's running a carbon analysis. SURROUND does it automatically: upload your Rhino model, it scans 1,691 surrounding buildings and tells you your upfront carbon before you've even picked a material. | Python · GIS · ML · Mapbox · Rhino Plugin · React |
| Bloom Brick | Parametric brick walls look great in Grasshopper. They're nearly impossible to build on site because every brick sits at a different angle and 92% of firms can't find workers who can read that. Bloom Brick puts the angle into the brick itself — factory-scored, mason-proof. | Grasshopper · Rhino · Speckle · CNC |
| ArchiMesa | A table with a depth camera and a projector. You put LEGO blocks on a 3D-printed city model. It projects solar, shadow and wind analysis directly onto the physical model in real time. Clients love it. Detection was hard. We tried 5 different approaches. 4 failed. | Python · OpenNI2 · Orbbec Astra · Grasshopper · ArUco |
| Compl-AI | Checks whether a residential building complies with building codes using AI. Because apparently someone needs to. | Python · ANN · CNN · Object Detection · K-Means · IFC |
| G.R.A.S.S. | Design a park with your hands. No mouse. No keyboard. Just gestures and voice commands in mid-air. The name is a backronym. We are not sorry. | Python · MediaPipe · Google Speech API · Pygame |
| Urban Amenities — Istanbul | Is Istanbul actually a 15-minute city? We mapped every amenity, ran shortest-walk algorithms across the historical centre, and found out. All in Grasshopper. | Grasshopper · OSM · Shortest Walk |
| Flap-alona | Butterfly and pollinator mapping across Barcelona's gardens. Because biodiversity matters and someone should be counting the butterflies. | Python · urban data · open datasets |
| ComforTECH | A room that adjusts itself. Temperature, humidity, light, occupancy — ESP32 reads all of it and responds. Hardware is harder than it looks. | ESP32 · Arduino · sensors · circuit design |

---

## Skills

**AI / ML** — Python · TensorFlow · Keras · scikit-learn · Claude API (Haiku + Sonnet) · RAG · ANN · CNN · Object Detection · K-Means

**Computer Vision** — OpenCV · depth cameras · ArUco markers · U-Net segmentation

**Backend** — FastAPI · PostgreSQL · WebSockets · REST APIs · SQLAlchemy · Google Cloud · Railway

**Frontend** — React · Vite · Mapbox GL JS · JavaScript

**BIM / Fabrication** — Revit · Revit API (.NET / C#) · IFC · IfcOpenShell · Grasshopper · Rhino · Speckle

**Geospatial** — GIS · GeoPandas · OSMnx · UTCI simulation · Ladybug · Honeybee · Infrared SDK

**Hardware** — ESP32 · Arduino · sensor integration · circuit design

**Design** — AutoCAD · SketchUp · Enscape · V-Ray · InDesign · Photoshop · Illustrator

---

## Before all this

5 years delivering actual buildings in the Netherlands and Italy:

- **Studio for New Realities** (Rotterdam, 2024–2025) — Residential projects + 15-minute city research for Brussels
- **LAP Landscape & Urban Design** (Rotterdam, 2023) — Led design for De Groene Loper: 92 climate-adaptive homes with smart water management and biodiversity integration
- **Burton Hamfelt Urban Architecture** (Amsterdam, 2021–2023) — De Optopper modular prefab system (exhibited Provada 2022) + Peninsula Wasserstadt masterplan, Hannover
- **Maria Grazia D'Ascanio Ingegneria** (L'Aquila, 2020–2021) — Energy and seismic renovation of social housing in a post-earthquake zone

**Education:**
Integrated Master in Architecture and Building Engineering — Università degli Studi di L'Aquila · 110/110 cum laude
Master in AI for Architecture and the Built Environment — IAAC Barcelona · 2024–2026
Erasmus+ — Politechnika Krakowska, Poland · 2019–2020

---

## Find me

📧 martina.simoni20@gmail.com · 📍 Barcelona, Spain · [LinkedIn](https://linkedin.com/in/martina-simoni)
