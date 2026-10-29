# sptiotempo_course_viz
Spatio-Temporal Campus Course &amp; Building Occupancy Visualization

# Project title: Spatio-Temporal Campus Course & Building Occupancy Visualization
Context: UNC Charlotte | Geographic Information Science & Technology (GIST) — Fall 2026
Live Demo | Kepler.gl | WebGL Engine | Python 3

Project Overview & Objectives:

Details how course schedule data and campus coordinates were modeled to visualize pedestrian movement, building capacity, and hourly occupancy fluctuations across campus (e.g., Fretwell, Woodward Hall, CHHS, Friday).

Live Interactive Map Section: https://biswasjayanta.github.io/sptiotempo_course_viz

Feature: Temporal time-playback slider, 3D building extrusion/choropleth layers, and interactive tooltips.

Repository Structure:
Full tree explaining every file, including the data pipeline script aggregate_courses.py, raw data, and all 4 aggregated CSV outputs (hourly, exact_times, daily, building_overall).

Data Pipeline & Methodology:

Formulas: 
`Enrolled Students = Total Enrolled − Open Enrolled`

Temporal ISO 8601 formatting with -04:00 (EDT) timezone offsets to prevent browser playback shifts.

Local Execution:
Instructions for running the Python aggregation pipeline and launching a local HTTP test server (python3 -m http.server 8000).

Author & Course Information:

`Jayanta Biswas, UNC Charlotte, GIST Course Fall 2026`

`Doug Meyer, UNC Charlotte, GIST Course Fall 2026`

`Alden Sanderson, UNC Charlotte, GIST Course Fall 2026`

`Grace Kissel, UNC Charlotte, GIST Course Fall 2026`

`Scott Do, UNC Charlotte, GIST Course Fall 2026`

`GarreA Perez Benton, UNC Charlotte, GIST Course Fall 2026`
