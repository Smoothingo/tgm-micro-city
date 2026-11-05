# TGM Micro-City — Interactive 3D Campus & Industrial Harbor

An interactive, high-detail 3D digital-twin campus and multimodal logistics hub built in **Three.js** as a single self-contained application.

![Three.js](https://img.shields.io/badge/Three.js-r164.1-000000?logo=three.js)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

---

## 🌟 Key Features

### 🏙️ Expanded Mainland & Coastal Geography
- **Vast Continental Terrain**: An expansive regional landmass (`266m × 480m`) replacing floating voids with realistic coastal topography, retaining walls, riprap granite breakwaters, and rolling mountain ridges.
- **Ocean Bay Basin**: Dynamic procedural water plane with real-time sinusoidal wave displacement, deep maritime shading, and specular reflections.
- **Harbor Jetty & Lighthouse**: A 55m breakwater spit crowned by an authentic 16m coastal lighthouse featuring a rotating 3D spotlight beam.
- **Maritime Shipping Channel**: Starboard (green), port (red), and hazard navigation buoys with bobbing physics and flashing beacons.
- **Regional Highways & Infrastructure**: Elevated 4-lane East Highway overpass with cruising vehicles and overhead gantry signage, alongside high-voltage transmission power pylons and distant industrial tank farms.

---

### 🏭 Dramatically Enlarged Industrial Architecture
- **Smart Factory**:
  - Multi-bay fabrication complex with heavy assembly portal frames.
  - Four sawtooth roof skylight ridges with interior warm illumination.
  - Precision CNC machining annex connected via an enclosed overhead service & piping bridge.
  - Outdoor process farm with three vertical stainless steel silos and spiraling cage ladders.
  - Electrical transformer substation yard with safety mesh fence.
  - Twin industrial chimneys with procedural particle smoke.
- **Hackathon Hub / Server Farm**:
  - Central soaring glass atrium with visible diagonal space-frame trusses.
  - Cantilevered innovation prototype pods and dark louvered server farm cooling wing with pulsed blue data louvers.
  - Arena entrance portico with curved glowing cyan live ticker.
  - 15m rooftop telecommunications lattice mast with microwave dishes and blinking aviation hazard beacons.
- **Business Tower / Corporate HQ**:
  - Multi-tiered corporate skyscraper (30m+ height) with double-height glass lobby.
  - Vertical warm-gold illuminated architectural glass fins and floor bands.
  - Cantilevered executive skybridge.
  - Reinforced rooftop helipad with glowing "H", perimeter green/amber aviation lights, and facade maintenance crane (BMU).
- **Logistics Hub**:
  - Mega multimodal cross-docking terminal with automated high-bay warehouse (ASRS) featuring glowing racking silhouettes.
  - Six full-depth truck loading docks equipped with rubber bumpers, yellow alignment stripes, and dock status lights.
  - Overhead automated sorting conveyor bridge crossing over to the container terminal.
  - Outdoor container staging yard with multi-tier container stacks and transport trailers.

---

### 🚢 High-Resolution Container Cargo Ship ("TGM TITAN")
- **Contoured 58m Hull**: Anti-fouling red underwater bottom, navy topsides, raked clipper bow, submerged bulbous bow cylinder, forecastle wave breakwater, anchor hawseholes with 3D anchors, and stepped cruiser stern with balanced rudder.
- **110+ Individually Rendered ISO Containers**: Spanning 7 longitudinal cargo bays and 4 rows across in authentic global shipping liveries:
  - Maersk Line (Sky Cyan)
  - Hapag-Lloyd (Orange)
  - Evergreen Marine (Emerald Green)
  - MSC (Amber Yellow)
  - ONE Network (Pink)
  - CMA CGM (Royal Blue)
  - Hamburg Süd (Crimson Red)
  - Reefer refrigerated units with front compressor grills and active green status LEDs.
- **Steel Lashing Bridges**: Structural cross-braced towers erected between bays with catwalks, ladders, and diagonal steel turnbuckles.
- **Superstructure & Navigation Castle**: 6-tier bridge house with cantilevered bridge wings, wrap-around illuminated observation windows, monkey island with dual spinning radar scanners, satellite communication radomes, navigation lights, freefall lifeboats on stern transom ramps, and twin streamlined exhaust funnels.
- **Deepwater Wharf & STS Cranes**: 64m concrete quay with dual crane rail tracks, rubber cylindrical dock fenders, high-mast floodlights, escort tugboat, and two massive Ship-to-Shore (STS) container gantry cranes with moving trolleys and active hoists.

---

### 🚶 Seamless Walk-In 3D Interiors
Click any district or use the top navigation buttons to physically fly into fully realized 3D interiors:
1. **Hackathon Arena**: Elevated cyan-lit stage, presenter avatar with microphone, live 42:00 countdown timer and scoreboard, tiered amphitheater seating with beanbags, hacker pods with typing developers.
2. **Smart Factory Machine Hall**: High-bay traveling overhead crane with moving hoist, dual CNC machines, industrial lathe with spinning chuck, 6-axis articulated robot arm, spark particles, and safety paths.
3. **Business Tower Office**: Executive boardroom desk, panoramic city skyline window, and animated floating 3D holographic KPI telemetry bar charts.
4. **Logistics Warehouse**: Floor-to-ceiling panoramic harbor window, heavy structural roof trusses, multi-tier pallet racking, automated aisle crane, three moving forklifts, and four automated guided vehicles (AGVs).

---

### 🏎️ Interactive Steerable Cyber-Transporter
- Press <kbd>V</kbd> or click **Drive Mode** in the top navigation bar to pilot the campus cyber-transporter.
- **Controls**:
  - <kbd>W</kbd> / <kbd>↑</kbd> — Accelerate forward
  - <kbd>S</kbd> / <kbd>↓</kbd> — Reverse
  - <kbd>A</kbd> / <kbd>←</kbd> — Steer left
  - <kbd>D</kbd> / <kbd>→</kbd> — Steer right
  - <kbd>Space</kbd> — Hydraulic brake & bright brake lights
  - <kbd>ESC</kbd> or <kbd>V</kbd> — Exit Drive Mode
- Dynamic chase camera, rolling tires with animated front steering pivots, forward spotlights, and digital speedometer / gear HUD (`[D]` / `[R]`).

---

### 🚗 Boulevard Traffic & Collision Avoidance
- Expanded 56m × 56m dual-lane ring road boulevard with a generous 8.5m buffer clearance from all building envelopes.
- 24 precision-engineered Catmull-Rom spline waypoints ensuring **zero clipping or collisions** through walls.
- Autonomous vehicle fleet including delivery trucks, cars, and cyber-vans.

---

## 🚀 Running Locally

Because this project is packaged as a single self-contained HTML file using standard ECMAScript modules, you can serve it with any HTTP server:

```bash
# Python 3
python3 -m http.server 8000

# Node.js
npx serve .
```

Then open `http://localhost:8000` in any modern WebGL2-compatible browser (Chrome, Firefox, Safari, Edge).

---

## 🛠️ Technology Stack
- **Three.js** `r164.1` (loaded via CDN ESM importmap)
- **100% Procedural**: No external 3D models (GLTF/OBJ) or static raster image assets. All textures, canvases, screens, shaders, and geometry are procedurally generated in real time.
- **Smooth Camera Tweens**: Custom lerp tween engine with cubic ease-in-out interpolation and dynamic FOV adjustment.

---

## 📄 License
MIT License. Created for the TGM Micro-City Project.
