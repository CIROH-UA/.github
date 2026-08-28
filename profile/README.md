<div align="center">
  
# CIROH-UA
### Cooperative Institute for Research to Operations in Hydrology
#### The University of Alabama - Alabama Water Institute

[![GitHub followers](https://img.shields.io/github/followers/CIROH-UA?style=social)](https://github.com/CIROH-UA)
[![Website](https://img.shields.io/badge/Website-ciroh.org-blue)](https://ciroh.org)
[![Hub](https://img.shields.io/badge/Hub-hub.ciroh.org-green)](https://hub.ciroh.org)
</div>

---

## 🎯 Mission
Advancing hydrology through open-source tools, community collaboration, and cutting-edge research.

## 🏆 Community NextGen Ecosystem
Containerized solutions for running the NextGen Water Resources Modeling Framework locally

### 🧊 NextGen in a Box
The NextGen Framework, run in any environment with as little as an hour of setup
- **[NGIAB-CloudInfra](https://github.com/CIROH-UA/NGIAB-CloudInfra)** - Docker distribution for wide compatibility
- **[NGIAB-HPCInfra](https://github.com/CIROH-UA/NGIAB-HPCInfra)** - Singularity distribution for HPC-optimized modeling
- **[NGIAB Data Preprocess](https://github.com/CIROH-UA/NGIAB_data_preprocess)** - Data preparation tools
- **[NGIAB-TEEHR](https://github.com/CIROH-UA/ngiab-teehr)** - NGIAB TEEHR integration
- **[NGIAB-Client](https://github.com/CIROH-UA/ngiab-client)** - NGIAB Visualizer based on Tethys platform
- **[NGIAB Calibration](https://github.com/CIROH-UA/ngiab-cal)** - Calibration tools
- **[NGIAB 101 Training](https://docs.ciroh.org/training-NGIAB-101/)** - A comprehensive guide to getting started with NGIAB Ecosystem
- **[Documentation on CIROH Hub](https://hub.ciroh.org/docs/products/ngiab/)** - In-depth information on NGIAB and related tools
- **[Community Hydrofabric Patcher](https://github.com/CIROH-UA/community_hf_patcher)** - Source for patched hydrofabric files retrieved by Data Preprocess
- **[NGIAB Website](https://github.com/CIROH-UA/ngiab-website)** - NGIAB product portfoio website - ngiab.ciroh.org

### 📊 NextGen Research DataStream (NRDS)
Automated system for continuous hydrologic predictions
- **[forcingprocessor](https://github.com/CIROH-UA/forcingprocessor)** - Forcingprocessor converts National Water Model (NWM) forcing data into Next Generation National Water Model (NextGen) forcing data
- **[ngen-datastream](https://github.com/CIROH-UA/ngen-datastream)** - Infrastructure and tooling for the NextGen Research DataStream (NRDS) - Datastream Orchestration on AWS
- **[datastreamcli](https://github.com/CIROH-UA/datastreamcli)** - DataStreamCLI is a stand alone tool that automates the complete workflow from preprocessing input data for NextGen to execution of the NextGen simulation through NextGen In a Box (NGIAB)
- **[NRDS Visualizer](https://github.com/CIROH-UA/nrds-client)** - Online visualization of NRDS outputs, accessible via [nrds.ciroh.org](https://nrds.ciroh.org)
- **S3 bucket** - [datastream.ciroh.org](https://datastream.ciroh.org) - README.html provides more details
- Community parameter integration capability (in-progress)

### 📖 CIROH Community NextGen Hub (CCNH)
Instant access to NextGen in a JupyterHub notebook environment
- **[CCNH on CIROH Hub](https://hub.ciroh.org/docs/products/ngiab-ecosystem/nextgen-2i2c/)** - Instructions to run CCNH from CIROH-2i2c JupyterHub
- **[PyNGIAB](https://github.com/CIROH-UA/ciroh_pyngiab)** - Software foundation for CCNH

### 💧 NextGen Framework Core Components
Essential modeling engines powering the NextGen Water Resources Modeling Framework
- **[ngen](https://github.com/CIROH-UA/ngen)** - NextGen Water Resources Modeling Framework Engine *(fork from NOAA-OWP repo)* (ngiab branch integrated into NGIAB)
- **[t-route](https://github.com/CIROH-UA/t-route)** - Tree-based hydrologic routing engine for river network flow *(fork from NOAA-OWP repo)* (ngiab branch integreated into NGIAB)
- **[rs_route](https://github.com/CIROH-UA/rs_route)** - Rust-based Muskingum-Cunge channel routing; designed for similar functionality to t-route
- **[lstm](https://github.com/CIROH-UA/lstm)** - Basic Model Interface (BMI) for streamflow prediction using Long Short-Term Memory (LSTM) networks (main branch - integrated into NGIAB)
- **[rust-lstm](https://github.com/CIROH-UA/rust-lstm)** - A Rust implementation of a BMI adapter for LSTM-based streamflow prediction
- **[bmi_dummy](https://github.com/CIROH-UA/bmi_dummy)** - A basic no-op implementation of the BMI interface
- **[hf_pmtiles](https://github.com/CIROH-UA/hf_pmtiles)** - Conversion from GeoPackages to Protomaps PMTiles

## 🤝 Community Resources

### CIROH Hub
- **[CIROH Hub website](https://hub.ciroh.org)** - Central resource for CIROH research, documentation, services, and news 
- **[ciroh_hub](https://github.com/CIROH-UA/ciroh_hub)** - Repository for updating and maintaining CIROH Hub

### CIROH RIVR
- **[RIVR](https://github.com/CIROH-UA/RIVR)** - Public-focused mobile app for monitoring river flow and flood risk, powered by the NWM

### Data Access
- **[api-nwm-gcp](https://github.com/CIROH-UA/api-nwm-gcp)** - NWM BigQuery API - REST API backed by National Water Model data, developed and deployed on Google Cloud Platform
- **[nwmurl](https://github.com/CIROH-UA/nwmurl)** - It provides utility functions specifically designed to subset and generate National Water Model (NWM) data URLs
- **[nwm_kerchunk](https://github.com/CIROH-UA/NWM_Kerchunk)** - It provides National Water Model (NWM) output, which is stored as .nc files, into JSON headers and upload them to an AWS S3 bucket.
- **[forecast_data_overlay](https://github.com/CIROH-UA/forecast_data_overlay)** - Standalone utility to visually overlay and compare multiple forecasts data sources

### CIROH-2i2c JupyterHub
- **[awi-ciroh-image](https://github.com/CIROH-UA/awi-ciroh-image)** - CIROH JupyterHub Image repository

### Education and Outreach
- **[Conferences](https://github.com/CIROH-UA/conferences)** - Archive of CIROH presentations from conferences, workshops, and more

## Acknowledgments

This research was supported by the Cooperative Institute for Research to Operations in Hydrology (CIROH) with funding under award NA22NWS4320003 from the NOAA Cooperative Institute Program. The statements, findings, conclusions, and recommendations are those of the author(s) and do not necessarily reflect the opinions of NOAA.

