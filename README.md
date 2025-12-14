# EcoInnovators_Ideathon_2026_Void_Crew
A YOLOv8s-seg based model that detects solar panels installed on roofs in a 640x640 tile map. This model was used for the EcoInnovator Ideathon of 2026 by Team Void Crew

# How To Use
Clone the repo and run on your preferred python IDE

# Docker
premithius/ecoinnovators_ideathon_2026_void_crew:latest

# Credits
## Data Attribution

Imagery source:
**Esri World Imagery**

Service URL:
https://services.arcgisonline.com/ArcGIS/rest/services/World_Imagery/MapServer

© Esri, Maxar, Earthstar Geographics, CNES/Airbus DS, USDA, USGS, AeroGRID, IGN, and the GIS User Community.

## Model Attribution

The solar panel segmentation model used in this project is based on the following open-source work:

**YOLOv8 Solar Panel Segmentation**
- Repository: https://github.com/finloop/yolov8s-seg-solar-panels
- Architecture: YOLOv8 Segmentation
- Task: Solar panel instance segmentation

This project uses the pretrained weights and inference pipeline provided by the above repository.
All credit for model architecture, training, and dataset preparation belongs to the original authors.
