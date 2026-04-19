# ES-04: Reading the Land
## Earth Science — Module 4: Remote Sensing, GIS & Earth from Space

**Core concept:** Geographic Information Systems · Satellite remote sensing · LANDSAT · SRTM elevation models · Jamaica's coordinate system  
**Duration:** 90 minutes  
**Grade level:** Grades 9–12 / First Year University  
**Standards:** NEPA Jamaica · NSF Earth Science · UWI Dept. of Geography & Geology · Dr. Valrie Grant (WIS-09)

---

### Opening Statement

> *"The satellite does not lie. It records what is there."*

For most of human history, understanding a landscape required standing in it. You could only know what you could see.

On July 23, 1972, NASA launched **LANDSAT-1** — the first satellite dedicated to the systematic observation of Earth's land surface. For the first time, it was possible to monitor changes in vegetation, water, soil, and urban growth across entire continents repeatedly, over decades.

Today, Jamaica is continuously observed by multiple satellite systems. Every significant land-cover change — deforestation in the Blue Mountains, coastal erosion in Portland, mangrove loss in the South Coast, expansion of Kingston — is visible in the satellite archive.

This archive is the scientific foundation of modern environmental management. And it was Jamaican scientist **Dr. Valrie Grant** who pioneered its application to Caribbean land use policy.

---

### 1. What Remote Sensing Is

**Remote sensing** is the science of acquiring information about an object or phenomenon without making physical contact.

In the context of Earth observation, it means: measuring electromagnetic radiation reflected or emitted by the Earth's surface from instruments on aircraft or satellites.

**The electromagnetic spectrum:**

Satellite sensors measure different portions of the spectrum, each revealing different information:

| Wavelength Range | Information Revealed |
|-----------------|---------------------|
| Visible (0.4–0.7 µm) | Surface colour, vegetation, water extent |
| Near-Infrared (0.7–1.3 µm) | Vegetation health (NIR reflects strongly from healthy leaves) |
| Short-Wave Infrared (1.3–3 µm) | Soil moisture, mineral composition |
| Thermal Infrared (8–14 µm) | Land surface temperature, heat islands |
| Microwave (SAR) | All-weather imaging through clouds; elevation mapping |

**Why infrared matters:**

Healthy green vegetation reflects strongly in the near-infrared (NIR) band. Stressed or dead vegetation reflects less. This is the basis of the **Normalized Difference Vegetation Index (NDVI)**:

```
NDVI = (NIR - Red) / (NIR + Red)
```

NDVI ranges from -1 to +1:
- -1 to 0: water, barren rock
- 0 to 0.2: sparse vegetation, bare soil
- 0.2 to 0.5: moderate vegetation
- 0.5 to 1.0: dense, healthy vegetation

NDVI derived from LANDSAT imagery allows scientists to track deforestation, monitor crop health, and assess post-hurricane vegetation recovery across all of Jamaica simultaneously, from a satellite 705 km above the surface.

---

### 2. Key Satellites Monitoring the Caribbean

**LANDSAT (NASA/USGS):**
- Continuous record from 1972 to present (LANDSAT 1 through LANDSAT 9)
- 30-metre spatial resolution (30m pixel size) — each pixel covers a 30×30 metre square
- 16-day revisit period
- Free and publicly accessible at earthexplorer.usgs.gov
- The world's longest continuous record of land surface change

**Sentinel-2 (ESA — European Space Agency):**
- 10-metre spatial resolution in visible/NIR bands
- 5-day revisit period
- Free access; increasingly used for Caribbean monitoring
- Bands from visible to short-wave infrared

**Copernicus Emergency Management Service:**
- Provides rapid-response satellite mapping after disasters (hurricanes, floods, earthquakes)
- After Hurricane Beryl (2024): Sentinel imagery was used to map flood extent and infrastructure damage within 48 hours

**NASA IMERG (Integrated Multi-satellitE Retrievals for GPM):**
- Precipitation mapping from the Global Precipitation Measurement satellite constellation
- Near-real-time rainfall estimates at 0.1° spatial resolution (approximately 11 km at Jamaica's latitude)
- Data used in the JUICY HYD-500 module for Jamaica-wide rainfall characterisation

---

### 3. Elevation — Reading the Third Dimension

A 2D map shows where things are. An elevation model shows how high.

**SRTM (Shuttle Radar Topography Mission, February 2000):**

A NASA Space Shuttle mission used radar interferometry to produce a near-global digital elevation model (DEM) at 30-metre horizontal resolution. The Shuttle carried two radar antennas separated by a 60-metre mast — the parallax between the two antenna positions allowed precise 3D elevation reconstruction.

SRTM data is the foundation of most Caribbean elevation maps:
- Identifies flood-prone low-lying areas (coastal Jamaica: below 5 m elevation is at risk)
- Watershed delineation: water flows downhill along paths determined by elevation gradient
- Landslide risk assessment: steep slopes with appropriate geology

**Reading a Jamaica elevation cross-section:**

West→East through the centre of the island:
- Westmoreland: 0–50 m (flat coastal lowland)
- Cockpit Country: 200–900 m (karst topography, rounded hills and depressions)
- Manchester Plateau: 600–800 m (limestone plateau)
- Blue Mountains: rise steeply from 500 to 2,256 m (Blue Mountain Peak)
- Eastern coast: drops rapidly back to sea level

This topographic profile explains Jamaica's climate: the northeast trade winds load moisture from the Caribbean Sea, rising over the Blue Mountains, cooling and precipitating on the windward slopes (Port Antonio receives ~3,000 mm/year), then descending dry on the leeward slopes (Kingston receives ~800 mm/year).

---

### 4. GIS — Geographic Information Systems

A **GIS** is a system for capturing, storing, analysing, and visualising spatially referenced data.

GIS combines:
- **Raster data**: grids of values (satellite images, elevation models, rainfall maps)
- **Vector data**: points, lines, polygons representing discrete features (roads, rivers, parish boundaries, buildings)
- **Attribute data**: non-spatial information linked to spatial features (population of a district, water quality at a sampling site)

**What GIS enables:**

Overlay analysis: combining multiple data layers to answer spatial questions.

*Example:* Which schools in Jamaica are:
- Within 500 metres of a flood-prone area (elevation < 5 m)? AND
- In a parish with test scores below the national average? AND
- Within 1 km of a health clinic?

This intersection is impossible to answer without GIS. With GIS, it is a 5-minute spatial query.

**Jamaica GIS resources:**
- The **Land Information Council of Jamaica (LICJ)**: national GIS data clearing house
- **STATIN (Statistical Institute of Jamaica)**: census data linked to enumeration district polygons
- **NEPA (National Environment and Planning Agency)**: environmental and protected area boundaries

---

### 5. Dr. Valrie Grant — Caribbean Remote Sensing Pioneer

**Dr. Valrie Grant**, Jamaican remote sensing scientist. (See WIS-09 for full biography.)

Dr. Grant applied satellite remote sensing to Jamaican land management when the technology was new and the Caribbean was not considered a priority for its application. Her work established that satellite imagery could provide reliable, reproducible, and timely data for:
- Monitoring deforestation in protected areas
- Mapping agricultural land use changes
- Assessing hurricane damage extent
- Supporting watershed management decisions

Her methodological contribution: demonstrating that LANDSAT data (designed for temperate regions) could be calibrated and interpreted accurately for tropical Caribbean landscapes, where cloud cover, humidity, and vegetation density create challenges not present in the U.S. or European contexts the sensors were originally designed for.

The satellite monitoring that informs every serious environmental assessment in Jamaica today follows the methodological framework she helped establish.

---

### 6. Practical Applications in Jamaica

**Deforestation monitoring:**
- Blue Mountains: LANDSAT time series shows forest loss driven by smallholder agriculture encroachment at upper elevations
- Cockpit Country: boundary incursion detectable via annual NDVI analysis
- NEPA enforcement actions are now informed by satellite evidence

**Hurricane damage assessment:**
- After Hurricane Dean (2007): Copernicus-derived imagery was used to map landslide locations across the Blue Mountains
- Ground truth surveys were then targeted at the highest-priority areas identified remotely

**Coastal change:**
- Annual LANDSAT composites reveal shoreline retreat rates at Negril (western beach), Portland Bight, and other areas
- Sea level rise, storm erosion, and sand mining are all visible in the multidecadal archive

**Urban expansion:**
- Kingston's urban footprint can be extracted from LANDSAT using the built-up index
- The Liguanea Plain's residential expansion into formerly agricultural land is mapped from the 1972 archive to present

---

### 7. Coordinate Systems — Speaking the Language of Space

Every location on Earth must be described precisely. Two coordinate systems are fundamental:

**Geographic coordinates (degrees):**
- Latitude: 0° at equator, 90°N at North Pole
- Longitude: 0° at Prime Meridian (Greenwich), 180°W/E at International Date Line
- Jamaica: approximately 17°–18°N latitude, 76°–78°W longitude

**UTM (Universal Transverse Mercator):**
- Divides the world into 60 zones, each 6° wide in longitude
- Jamaica falls in UTM Zone 18N
- Coordinates expressed in metres from a reference point
- More accurate for distance and area calculations at local/regional scale than geographic coordinates

**Why it matters:** GIS analysis requires all layers to be in the same coordinate system. Mixing geographic and projected coordinates is a common beginner error that produces subtly wrong results.

---

### Field Exercise: Jamaica NDVI Analysis

Using NASA Worldview (worldview.earthdata.nasa.gov) or USGS EarthExplorer:

1. Find a cloud-free LANDSAT 9 image of Jamaica from August 2023. Display the false-colour NIR composite (NIR = Red, Red = Green, Green = Blue). Healthy vegetation appears red.

2. Visually identify: where is vegetation densest? What parishes show lowest vegetation cover?

3. Compare the same area in August 2017 (before Hurricane Maria's regional impact) and August 2018. Can you see any difference in vegetation cover?

4. Using the NDVI layer in NASA Worldview, compare St. Elizabeth (Black River basin) to Kingston. Which has higher NDVI? Why?

---

### Review Questions

1. What is NDVI and how is it calculated? What physical property of healthy plants makes this index work?

2. Jamaica receives very different rainfall on its north and south coasts. How could LANDSAT data (specifically NDVI time series) confirm this climatic asymmetry without a single rain gauge?

3. A 30-metre resolution DEM means each pixel represents a 30×30 m area. How many pixels would cover all of Jamaica (10,990 km²)?

4. What is the difference between raster data and vector data in a GIS? Give one example of each in a Jamaican environmental context.

5. Dr. Valrie Grant had to adapt LANDSAT methodology developed for temperate regions to work in Jamaica. What specific challenges would a tropical island present compared to a temperate continental environment?

---

### Glossary

| Term | Definition |
|------|-----------|
| Remote sensing | Measurement of Earth's surface using sensors not in physical contact with it |
| NDVI | Normalized Difference Vegetation Index; measures vegetation health from NIR and Red bands |
| LANDSAT | NASA/USGS satellite series providing continuous Earth observation from 1972 |
| SRTM | Shuttle Radar Topography Mission; global 30m digital elevation model |
| DEM | Digital Elevation Model; gridded dataset of terrain heights |
| GIS | Geographic Information System; software for spatial data capture, analysis, and display |
| Raster data | Grid-based spatial data (images, DEMs) |
| Vector data | Point, line, or polygon spatial data |
| UTM | Universal Transverse Mercator; a projected coordinate system using metres |
| Spatial resolution | Smallest feature detectable by a sensor (pixel size on the ground) |

---

*JUICY Academy — ES-04 — Luminous Works LLC*  
*Standards: NEPA Jamaica · NSF Earth Science · UWI Geography · STATIN*
