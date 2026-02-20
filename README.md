ICESat-2 Data Acquisition

A specialised Python toolkit for the acquisition of ICESat-2 (Inland Surface Water Data) products. This repository provides automated workflows to downlouding the ICESat-2 data in h5 format.  

🛰️ Project Overview:

The ICESat-2 data is the worldwide elevation data of the Earth’s surface from the ATLAS
instrument. The dataset is provided by the NASA National Snow and Ice Data Center
Distributed Active Archive Center (NSIDC DAAC). Downloading data is possible using
Python code by importing the icepyx library. The icepyx is a software library for
obtaining ICESat-2 data for future operations with them. Also, it is the community of
developers, scientific and ICESat-2 data users (Development Team, n.d. ).

ICESat-2 collects data using its ATLAS, which measures the travel time of laser pulses
to determine surface heights. Processing data from ICESat-2 involves converting raw
satellite observations into usable information.

### A Table of Main Specifications of ICESat-2 Mission

| Specification | Characterization |
| :--- | :--- |
| **Platform** | ICESat-2 |
| **Launch Date** | on 15 February 2018 |
| **Temporal Extent** | 2018 - present |
| **Height information** | Thickness of ice sheets, Elevations of glaciers, Water height, Forest canopies, and Urban areas |
| **Instrument** | Advanced Topographic Laser Altimeter System (ATLAS) |
| **Orbit Type** | Near-circular, near-polar, low-Earth orbit |
| **Altitude** | 498 km |
| **Inclination angle** | 92° |
| **Special resolution** | 20 m, 60 m, 280 m, 1 degree, 2 degrees, 25 km |
| **Spectral resolution** | 532 nm |
| **Temporal resolution** | 91 days |
| **Laser Pulses** | 10000 laser pulses per second |
| **Coverage** | Global coverage |

In this project, was using the ATL13 mission. However, on the stage of identifying the mission name or satellite product, need to specify the mission for acquisition.

<img width="1032" height="676" alt="icesat-2_data_products" src="https://github.com/user-attachments/assets/d42863f2-59c7-4ae9-b370-bbac9663ce1a" />


📊 Data Source:

Data provided by the National Snow and Ice Data Center (NSIDC).
Dataset Reference: [ICESat-2 L3A Inland Surface Water Data (ATL13)](https://nsidc.org/data/atl13/versions/7#anchor-overview)
