# DenseMatching
- Radargrammetric stereo subset extracted from Sentinel-1 SAR data 
# Sentinel-1 SAR Processing  Data

This repository provides a set of stereo pairs for radargrammetry

## 📦 Features

- Preprocessing of Sentinel-1 GRD products
- Dense matching for radargrammetric DSM generation
- Visualization of SAR amplitude
- Rectified

## 📁 Data Source

The SAR datasets used in this project are acquired from the **Copernicus Sentinel-1 mission**, operated by the European Space Agency (ESA).  
You can freely access Sentinel-1 data via:

- [Copernicus Open Access Hub](https://scihub.copernicus.eu/)
- [Alaska Satellite Facility (ASF)](https://search.asf.alaska.edu/)
- [Sentinel EO Browser](https://apps.sentinel-hub.com/eo-browser/)

Typical products used:
- **SLC (Single Look Complex)** for interferometric and radargrammetric analysis
- **GRD (Ground Range Detected)** for amplitude-based applications

## 🔤 Abbreviations

| Abbreviation | Full Meaning                           | Description                                      |
|--------------|----------------------------------------|--------------------------------------------------|
| s1l          | subset 1 left image                    | GRD intensity image at original 10 m resolution  |
| s1r          | subset 1 right image                   | GRD intensity image at original 10 m resolution  |
