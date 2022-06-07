# AW3D30-RGB-NY
RGB elevation tile (ZL4-11) from AW3D30  for New York City and its surroundings

# Spec
* RGB elevation tile compatible with Mapbox/MapLibre RGB elevation tile.
	* base: -10000
	* interval: 0.1
	* Terefore, height = -10000 + ((R * 256 * 256 + G * 256 + B) * 0.1)
* Zoom level: from 4 to 11
* Coverage: 5 degree by 5 degree around New York City (W75-70, N40-45)
* Disclaimer
	* The coverage of this data does not necessarily imply any territory border among countries. 
	* We hold no liability for any consequence caused by the use of the Data or by the quality thereof. 

# About AW3D30
* Name: ALOS Global Digital Surface Model "ALOS World 3D - 30m (AW3D30)"
* One arc second (approximately 30 meter) resolution global digital surface model
* Downloaded in June 2022
https://www.eorc.jaxa.jp/ALOS/en/dataset/aw3d30/aw3d30_e.htm

# Data Source
The original data used for this product have been supplied by JAXA (the Japan Aerospace Exploration Agency).  
Please indicate the data source when you the data from this repository.   
**"RGB Elevation tile from AW3D30 (JAXA)"**  

We hold no liability for any consequence caused by the use of the Data or by the quality thereof.   
For details, please check: https://earth.jaxa.jp/en/data/policy/

# Tile URL
https://ubukawa.github.io/AW3D30-RGB-NY/zxy/{z}/{x}/{y}.png

# How to make RGB tile?
https://qiita.com/T-ubu/items/dc5022e15f2b770429b3
