Automatic Scenario creation in BeamNG.Tech using OSM data

What it does

This script downloads a drivable road network from OpenStreetMap around Hochschule Neu-Ulm, converts the road geometry into local coordinates, and creates a BeamNG.tech scenario from it. It also spawns a vehicle, reads its position using an IMU sensor, and converts the simulated position back into geographic coordinates.

What it helps for
	•	Testing OSM-based road import into BeamNG.tech
	•	Map-based driving simulation
	•	Localization and GPS position checks
	•	Prototyping route planning and road-network experiments

Requirements
	•	Python 3.9+
	•	BeamNG.tech installed locally
	•	Python packages:
	•	osmnx
	•	networkx
	•	shapely
	•	pyproj
	•	beamngpy

Install dependencies

pip install osmnx networkx shapely pyproj beamngpy

Note

Update the BeamNG installation path in the script before running it:

home=r"C:\\BeamNG.tech.v0.37.6.0\\BeamNG.tech.v0.37.6.0"
