# 3D Vedic Sky Explorer

A fully interactive, browser-based 3D celestial sphere and astrological calculator. This tool visualizes the Navagraha (planets), Rashis (zodiac signs), and Nakshatras (lunar mansions) in real-time against the local horizon, providing a unique spatial perspective on Vedic astrology.

## Features
* **Interactive 3D Celestial Sphere:** Drag, pan, and zoom to explore the astrological sky. Click on any star, planet, or house cusp for detailed data.
* **Time Machine Engine:** Fast-forward or rewind time by hours, days, weeks, or months to watch planetary transits in motion.
* **Dynamic 2D Charts:** Live overlays of traditional South Indian and North Indian birth charts.
* **High-Resolution Panorama Export:** Generate 4K equirectangular projections of the ecliptic, perfectly centered on the Lagna (Ascendant).
* **PDF Reports:** Export standard 2D charts along with complete planetary degree and rulership tables.
* **Custom Calculations:** Support for Sidereal/Tropical zodiacs and multiple Ayanamsas, including Lahiri (Chitra Paksha) and Pushya Paksha (P.V.R.).

## How to Use
This application is entirely client-side. There is no backend server or database required.
1. Download or clone this repository.
2. Open the `index.html` file in any modern web browser.
3. Use the control panel to input your date, time, and location to render the sky.

## Acknowledgments & Open Source Licenses
This project was built for educational and astrological exploration and relies on the following incredible open-source projects:

* **[Three.js](https://threejs.org/)** (MIT License) - Used for the 3D WebGL celestial sphere rendering.
* **[Astronomy Engine](https://github.com/cosinekitty/astronomy)** (MIT License) - Created by Don Cross. Used for precise astronomical calculations and planetary ephemerides. 
* **[jsPDF](https://parall.ax/products/jspdf) & [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable)** (MIT License) - Used for generating downloadable PDF astrological reports.
* **[OpenStreetMap Nominatim API](https://nominatim.org/)** (ODbL) - Used for the location search autocomplete. Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright).

## Disclaimer of Liability
This application is provided "as-is" for educational, research, and entertainment purposes only. The developer makes no warranties, express or implied, regarding the accuracy, reliability, or completeness of the astronomical calculations, mathematical offsets, or astrological data presented. 

Astrology is a subjective discipline, and this tool should not be used as a substitute for professional financial, medical, legal, or personal advice. By using this tool, you agree that the developer, the creators of the underlying open-source libraries, and any referenced astrological researchers assume no liability for any actions, losses, or decisions made based on the output of this software.

---
*Designed and built with a passion for Vedic astrology in Bengaluru by Kishor Narayan.*
