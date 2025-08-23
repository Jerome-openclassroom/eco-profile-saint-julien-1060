# 🌿 Eco-Profile: Saint-Julien Chapteuil 1060 m (Haute-Loire, France)

This repository documents a detailed eco-climatological inventory of a 1-hectare site located at 1060 m elevation, in the eastern foothills of the Massif Central. The project blends field observations from 2017–2018 with interdisciplinary scientific interpretation: climatology, botany, fauna, and instrumental meteorology.

## 📍 Location & Context

- **Nearest village**: Saint-Julien-Chapteuil (860 m)
- **Elevation**: 1060 m, above typical winter inversion layers
- **Terrain**: Semi-natural bocage meadow, near stream, beech-fir forest and volcanic features
- **Soil**: Granite-basalt substrate, slightly acidic to neutral pH, oligotrophic
- **Surrounding forest type**: Mixed beech-fir forest (*Fagus sylvatica* and *Abies alba*) — typical of mid-elevation montane zones, providing shade, organic matter, and ecological corridors.

## 🌦️ Climatic Data

### Sources
- **Manual observations** (2017–2018): daily rainfall and weather notes
- **Supplementary temperature data**: Mazet-Saint-Voy station (12 km, same elevation) source : https://www.infoclimat.fr

### **Average Daily Temperature (1991–2021)**

This plot shows the average daily temperature for the site, computed over the standard climatological period (1991–2021).  
It provides a robust thermal baseline to complement the personal rainfall data and field observations.  
Seasonal patterns clearly highlight the typical cold winters, moderate springs, and warm summers with frequent thunderstorms characteristic of Haute-Loire’s mid-mountain climate.

### Notable Events
- Summer 2017: storms (up to 38 mm in 24h)
- September 21st 2017: early frost
- October 2017: dry (20 mm), gusts up to 76 km/h
- Mean temperature estimate: ~8.5°C; frequent frost; strong day/night amplitude

## 📸 Weather Event – Hailstorm of July 3rd, 2022

A violent hailstorm struck Saint-Julien-Chapteuil (Haute-Loire, France) on **July 3rd, 2022**, causing severe damage to homes, vehicles, public buildings, and agricultural structures. This short but intense event (~30 minutes) was locally unprecedented.

A **hailstone measuring 37 mm in diameter** was collected and photographed immediately after the event. The image (available in the `weather_picture/` folder) was analyzed using **ImageJ**. After grayscale conversion and axis alignment, a linear plot profile was extracted across its diameter.

🧪 **Result**:  
The profile revealed approximately **10 distinct internal layers**, indicating successive cycles of supercooling and accretion. Each layer likely corresponds to a vertical thermal oscillation during the convective uplift of the hail embryo within the cumulonimbus cell.

📊 This hailstone can be considered a **natural stratigraphic tracer** of intracloud convection. It offers insight into the storm’s vertical dynamics and complements meteorological observations from that day.

📁 *Image, plot profile, and source data are stored in:*  
`weather_picture/hailstone_37mm_july2022.png/`

🧭 Sensory observation – Electric–sulfur transition

A distinct smell was noticed after the hailstorm of July 3rd, 2022:  
**not as sharp as the metallic “arc” odor** detected during the 2018 heatwave storm,  
but also **more sulfurous and burnt than simple ozone**.

Closest analogy: **burning the head of a vintage matchstick**.

This places the olfactory signature between:
- **Arc discharge / ozone odor** (like welding or a nearby transformer)
- and **sulfur combustion trace** (typical of old match ignition)

🌩️ Such sensory events may indicate:
- intense electrical discharges during hail formation,
- high oxidation of atmospheric compounds (N/S/O),
- and vertical movement of trace gases from cloud core to ground.


## 🌿 Floristic Inventory (April–May 2018)

| Date       | Species |
|------------|---------|
| April 25   | Ficaria verna, Taraxacum officinale, Glechoma hederacea |
| May 11     | Prunella vulgaris, Saxifraga granulata, Silene dioica, Myosotis sylvatica, Conium maculatum |
| May 12     | Ranunculus repens |

**Features**: Vernal plants, mesophilic indicators, transitional humid-lisière habitats

## 🐾 Fauna Observed

- **Mammals**: roe deer, hares, wild boar, foxes, bats.
- **Birds**: red kite, owls (undetermined)
- **Herpetofauna**: amphibians, vipers or grass snakes
- **Small mammals**: voles, moles.
- **Insects**: zygoptera, anisoptera, probable hummingbird hawk-moth

**Additionnal note :**
Confirmed presence of the fox (*Vulpes vulpes*) and reported presence of the wolf (*Canis lupus*) indicate that the site supports a fully functional trophic chain, from microfauna to top predators. This highlights the value of the surrounding forest-prairie mosaic as a corridor and refuge for species requiring large, connected habitats.

## 🔬 Soil Microfauna (Berlèse Funnel Extraction)

Three specimens were extracted from leaf litter collected in the adjacent mixed beech–fir forest. A Berlèse funnel was used to isolate the microarthropods, which were then imaged under a stereomicroscope using digiscoping with a millimetric grid for scale reference (note: slight shape deformation may occur due to alcohol preservation).

- **Collembola.JPG** — Typical Collembola (springtail), abundant in moist organic layers.
- **Oribatida.JPG** — Oribatid mite, indicative of active litter decomposition.
- **Pseudoscorpionida.JPG** — Pseudoscorpion, small predatory arthropod, marker of well-balanced soil biodiversity.

This microfaunal set provides a snapshot of soil ecosystem health and trophic interactions in semi-natural montane litter.


## 🔧 Instruments & Observational Tools

| Tool | Description | Use |
|------|-------------|-----|
| GFS model (open interface) | Synoptic pattern analysis | Fronts, air masses |
| DIY nephoscope | Visual cloud direction tracker | Low-level airflow |
| Manual anemometer | Handheld rotating | Local wind estimation |
| Naudet barometer | Aneroid capsule | Pressure trend |
| Psychrometer | Paired thermometers | Humidity & evaporation |
| Conceptual tools | Airflow, inversion, foehn | Applied interpretation |
| Manual rain gauge | Graduated container with funnel | Daily rainfall logging (2017–2018), manually recorded |
| Minimum–maximum thermometer | Alcohol-based, U-shaped (Six type) | Recorded daily thermal extremes at site (reset manually) |

## 🧠 Scientific Purpose

This site illustrates a high-altitude microclimate and ecosystem in transition between Mediterranean, Atlantic, and montane influences.

### Goals:
- Foster **high-resolution citizen science**
- Serve as input to **environment-aware AI or AGI systems**
- Demonstrate **fieldwork competence beyond institutional frameworks**

## 📁 Repository Contents

```plaintext

eco-profile-saint-julien-1060/
│
├── climate_curves/              # Climatic plots and charts
│   ├── Average Daily temp.png   # Daily mean temperatures (1991–2021)
│   ├── Average max temp.png     # Average maximum temperature
│   ├── Average min temp.png     # Average minimum temperature
│   ├── Monthly_rainfall.png     # Monthly precipitation totals
│
├── english_summary/
│   ├── eco_summary_english.pdf  # Printable 2-page summary (English)
│
├── microfauna/                  # Soil microarthropods photos
│   ├── Collembola.JPG           # Springtail (indicator of moist litter)
│   ├── Oribatida.JPG            # Oribatid mite (litter decomposer)
│   ├── Pseudoscorpionida.JPG    # Pseudoscorpion (small predator)
│
├── raw_data_observations/       # Original field data
│   ├── Observations.xlsx        # Field notes (flora, fauna, weather)
│   ├── Pluviométrie.xlsx        # Manually recorded rainfall data
│
├── weather_pictures/            # Local weather and extreme events
│   ├── big_hail_centimeters_1.JPG  # Large hailstones (scale reference)
│   ├── big_hail_centimeters_2.JPG  # Another view of large hailstones
│   ├── cumulonimbus_incus.JPG      # Mature thunderstorm cloud (anvil)
│   ├── freezing_mist_ice_needles.JPG # Ice needles from freezing mist
│   ├── mammatus_storm.JPG          # Mammatus clouds (severe storm sign)
│   ├── rainbow_at_sunset.JPG       # Rainbow over the bocage at sunset
│   ├── sunset_inversion_layer.JPG  # Sunset with visible thermal inversion
│   ├── hailstone_37mm_july2022.png # ImageJ plot profile of internal grayscale intensity across a 37 mm hailstone
│   ├── 📑 **Metadata:** [weather_pictures/metadata.json](weather_pictures/metadata.json)
│
│
└── README.md                   # Project description and context english version
│
└── README_fr.md                # Project description and context french version

```



🔗 Related project:

## 🌿 Part of the Lyra Ecosystem

- [Lyra_Sentinel_MODIS_Site_HauteLoire](https://github.com/Jerome-openclassroom/Lyra_Sentinel_MODIS_Site_HauteLoire) — Combined Sentinel-2 NDVI and MODIS LST for a semi-natural site in Haute-Loire (France): ROI clipping, map visualization, and reproducible notebook.
- [Lyra_Leaf_SPAD_Calibration](https://github.com/Jerome-openclassroom/Lyra_Leaf_SPAD_Calibration) — SPAD sensor calibration for estimating chlorophyll density in leaves.
- [Lyra_LowCost_Soil_Leaf](https://github.com/Jerome-openclassroom/Lyra_LowCost_Soil_Leaf) — Integrated low-cost soil and leaf model for terrestrial primary productivity.
- [Leaf_Chlorose_CNN_Training](https://github.com/Jerome-openclassroom/Leaf_Chlorose_CNN_Training) — CNN-based classification of chlorotic vs. healthy leaves from scanned images.
- [TurbiditySensor_OpenScience](https://github.com/Jerome-openclassroom/TurbiditySensor_OpenScience) — A low-cost optical turbidity sensor calibrated in JTU, illustrating an open science approach for accessible, field-based water quality monitoring.
- [AI_Assisted_Lake_Ecology](https://github.com/Jerome-openclassroom/AI_Assisted_Lake_Ecology) — Full-scale NPP model combining field measurements, physical modeling, and GPT-4o-assisted ecological interpretation. Includes empirical correction for realistic annual productivity in clear lakes.
- [LimonTree_NPP_Model](https://github.com/Jerome-openclassroom/LimonTree_NPP_Model) — Low-cost water and NPP model for a potted lemon tree.
- [Lyra_DO_Green_Mesurim](https://github.com/Jerome-openclassroom/Lyra_DO_Green_Mesurim) — Low-tech protocol combining MesurimPro and ImageJ to estimate chlorophyll levels from scanned leaves, with validation against SPAD readings and AI-assisted correlation analysis.
- [Mountain_Bocage_Soil_Analysis](https://github.com/Jerome-openclassroom/Mountain_Bocage_Soil_Analysis) — Complete soil dataset for a mid-mountain bocage site (Haute-Loire, France): texture, CEC, pH, nitrates, structural stability, and Berlèse funnel microfauna extraction. Ready for AI-assisted ecological modeling.
- For field-based plant identification and LLM-assisted inference of ecological co-occurrence:  
[**Lyra_Botanical_Protocol**](https://github.com/Jerome-openclassroom/lyra-botanical-protocol) —  
*Protocol for probabilistic GPT-based species identification from photos and context (southern France, spring flora).*


## 📫 Contact

**Author**: Jérôme Frasson (Jerome-X1)  
**Email**: jerome.frasson.vsi@gmail.com  

