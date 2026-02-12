<div align="center">
  
# CIROH-UA
### Cooperative Institute for Research to Operations in Hydrology
#### The University of Alabama - Alabama Water Institute

[![GitHub followers](https://img.shields.io/github/followers/CIROH-UA?style=social)](https://github.com/CIROH-UA)
[![Website](https://img.shields.io/badge/Website-ciroh.org-blue)](https://ciroh.org)
[![Documentation](https://img.shields.io/badge/Docs-docs.ciroh.org-green)](https://docs.ciroh.org)
[![Portal](https://img.shields.io/badge/Portal-portal.ciroh.org-green)](https://portal.ciroh.org)
</div>

---

## 🎯 Mission
Advancing hydrology through open-source tools, community collaboration, and cutting-edge research.

## 🚀 Featured Projects

### 🏆 NextGen In A Box (NGIAB) Ecosystem
Containerized solution for running the NextGen Water Resources Modeling Framework locally
- **[NGIAB-CloudInfra](https://github.com/CIROH-UA/NGIAB-CloudInfra)** - Docker distribution for wide compatibility
- **[NGIAB-HPCInfra](https://github.com/CIROH-UA/NGIAB-HPCInfra)** - Singularity distribution for HPC-optimized modeling
- **[NGIAB Data Preprocess](https://github.com/CIROH-UA/NGIAB_data_preprocess)** - Data preparation tools
- **[NGIAB-TEEHR](https://github.com/CIROH-UA/ngiab-teehr)** - NGIAB TEEHR integration
- **[NGIAB-Client](https://github.com/CIROH-UA/ngiab-client)** - NGIAB Visualizer based on Tethys platform
- **[NGIAB Calibration](https://github.com/CIROH-UA/ngiab-cal)** - Calibration tools
- **[NGIAB 101 Training](https://docs.ciroh.org/training-NGIAB-101/)** - A comprehensive guide to getting started with NGIAB Ecosystem
- **[Documentation](https://docs.ciroh.org/docs/products/ngiab/)** - In-depth information on NGIAB and related tools
- **[PyNGIAB](https://github.com/CIROH-UA/ciroh_pyngiab)** - Community NextGen Hub on 2i2c JupyterHub
- **[NGIAB Website](https://github.com/CIROH-UA/ngiab-website)** - NGIAB product portfoio website - ngiab.ciroh.org

### 📊 NextGen Research DataStream (NRDS)
Automated system for continuous hydrologic predictions
- **[forcingprocessor](https://github.com/CIROH-UA/forcingprocessor)** - Forcingprocessor converts National Water Model (NWM) forcing data into Next Generation National Water Model (NextGen) forcing data
- **[ngen-datastream](https://github.com/CIROH-UA/ngen-datastream)** - Infrastructure and tooling for the NextGen Research DataStream (NRDS) - Datastream Orchestration on AWS
- **[datastreamcli](https://github.com/CIROH-UA/datastreamcli)** - DataStreamCLI is a stand alone tool that automates the complete workflow from preprocessing input data for NextGen to execution of the NextGen simulation through NextGen In a Box (NGIAB)
- S3 bucket - datastream.ciroh.org - README.html provides more details
- NRDS Visualizer - nrds.ciroh.org
- Community parameter integration capability (in-progress)

### 💧 NextGen Framework Core Components
Essential modeling engines powering the NextGen Water Resources Modeling Framework
- **[ngen](https://github.com/CIROH-UA/ngen)** - NextGen Water Resources Modeling Framework Engine *(fork from NOAA-OWP repo)* (ngiab branch integrated into NGIAB)
- **[t-route](https://github.com/CIROH-UA/t-route)** - Tree-based hydrologic routing engine for river network flow *(fork from NOAA-OWP repo)* (ngiab branch integreated into NGIAB)
- **[lstm](https://github.com/CIROH-UA/lstm)** - Basic Model Interface (BMI) for streamflow prediction using Long Short-Term Memory (LSTM) networks (main branch - integrated into NGIAB)
- **[rust-lstm](https://github.com/CIROH-UA/rust-lstm)** - A Rust implementation of a BMI adapter for LSTM-based streamflow prediction

### Data Access
- **[api-nwm-gcp](https://github.com/CIROH-UA/api-nwm-gcp)** - NWM BigQuery API - REST API backed by National Water Model data, developed and deployed on Google Cloud Platform
- **[nwmurl](https://github.com/CIROH-UA/nwmurl)** - It provides utility functions specifically designed to subset and generate National Water Model (NWM) data URLs
- **[nwm_kerchunk](https://github.com/CIROH-UA/NWM_Kerchunk)** - It provides National Water Model (NWM) output, which is stored as .nc files, into JSON headers and upload them to an AWS S3 bucket.

### CIROH-2i2c JupyterHub
- **[awi-ciroh-image](https://github.com/CIROH-UA/awi-ciroh-image)** - CIROH JupyterHub Image repository

### CIROH DocuHub and Portal
- **[ciroh-ua_website](https://github.com/CIROH-UA/ciroh-ua_website)** - technical documentation of few of the CIROH's projects, services, policies, latest blogs and news.
- **[ciroh-portal](https://github.com/CIROH-UA/ciroh-portal)** - CIROH portal for products, publications and courses

## Acknowledgments

This research was supported by the Cooperative Institute for Research to Operations in Hydrology (CIROH) with funding under award NA22NWS4320003 from the NOAA Cooperative Institute Program. The statements, findings, conclusions, and recommendations are those of the author(s) and do not necessarily reflect the opinions of NOAA.

