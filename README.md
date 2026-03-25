# Weather as Motion

An interactive 3D visualization that transforms real-time weather data across the United States into motion, color, and form.

This project maps 64 U.S. cities onto a geographic grid. Each rod represents one city and responds to live weather conditions, turning atmospheric data into a kinetic visual system.

## How it works

- **Height** reflects temperature
- **Color** reflects temperature, from cool blue to warm orange
- **Rotation** reflects wind speed
- **Top glow** pulses purple when precipitation is present

Hover over a rod to view city-specific weather details.

## Why I built this

I wanted to explore how live data could feel sculptural rather than purely informational. Instead of presenting weather as a chart or dashboard, this project turns it into a spatial, animated experience.

## Tech stack

- HTML
- CSS
- JavaScript
- Three.js
- Open-Meteo API

## Running locally

Because this project uses live API requests, it should be served from a local server rather than opened directly as a `file://` page.

### VS Code Live Server
Open the folder in VS Code and use **Open with Live Server** on `index.html`.

### Python
```bash
python -m http.server 8000
