# Crowd Dynamics at Fringe Festival 2024

Understanding and visualizing crowd patterns at the Edinburgh Fringe Festival to improve accessibility and optimize visitor flow.

## Project Overview

The Edinburgh Fringe Festival attracts a massive influx of visitors each year, often causing congestion at key venues and limiting accessibility for both locals and tourists. This project explores how spatio-temporal data analysis and interactive visualization can reveal patterns in crowd dynamics — and inform better crowd management strategies.

We developed a dynamic model that combines digital heatmaps and a physical interface to visualize how foot traffic varies across time and space during the festival.

## Objectives

- Analyze visitor density and congestion patterns across Edinburgh during Fringe 2024.
- Identify peak crowd zones and times using real ticket and event location data.
- Create a physical-digital interactive model for public or planning use.

## Dataset & Preprocessing

- **Source:** Edinburgh Fringe Society (2024)  
- **Data Used:**  
  - Event locations and time slots  
  - Ticket sales per event  
  - Venue coordinates and metadata  

- **Preprocessing Steps:**  
  - Cleaned and merged datasets  
  - Removed nulls and duplicates  
  - Converted and formatted timestamps  
  - Mapped events to geospatial coordinates
 
## Spatio-Temporal Heatmaps

Used [Folium](https://python-visualization.github.io/folium/) and `HeatMapWithTime` to generate:

- **Hourly heatmaps** showing crowd density changes throughout the day  
- **Layered visualizations** aligned in physical model  
- **Interactive scroll-based playback** to observe flow over time

## Key Insights

✅ Identified crowd hotspots by time of day  
✅ Mapped congestion at major zones (e.g., Royal Mile, Pleasance)  
✅ Suggested off-peak exploration windows for less-crowded routes  
✅ Demonstrated a hybrid interaction model combining digital data with physical overlays

## Impact & Future Use

This prototype can help:

- Event organizers adjust programming or signage  
- Local authorities optimize transport and footpath flow  
- Tourists plan routes that avoid peak congestion  

It also serves as a creative tool for exploring urban behavior through data storytelling.

## Tech Stack

- Python, Pandas, Folium, Jupyter  
- GeoJSON, HTML, JavaScript (for prototype interface)  
- Laser-cut physical overlay (optional for hybrid demo)

<img width="486" alt="Screenshot 2025-02-10 at 9 56 37 pm" src="https://github.com/user-attachments/assets/d0f3678b-ae65-409a-a59c-9ec165928ec5" /> 

![ezgif com-crop](https://github.com/user-attachments/assets/856863fc-ff97-44ce-b8fc-a9f5eb7b7940)


## Dataset Information

The dataset used in this project is from the Fringe Society 2024 dataset (provided to us by TRAVELTECH FOR SCOTLAND), which contains ticket sales and event location data. Due to its large size, it is not included in this repository.
