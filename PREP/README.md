Pre-processing Tools
========

## Overview
The following programs are provided to process and prepare input data for the CMAQ Chemistry Transport Model.  Documentation for these programs is provided in README files within each foler.  

## Pre-processing Programs
* **[bcon](bcon/README.md)**: prepares lateral chemical boundary conditions (BCs) for CCTM from either ASCII vertical profiles or from an existing CCTM output concentration (CONC) file
* **[bcon_gefs_aerosols](bcon_gefs_aerosols/README.md)**: prepares lateral chemical boundary conditions (BCs) for CCTM from an existing GEFS-Aerosols output concentration history file
* **[icon](icon/README.md)**: prepares chemical initial conditions (ICs) for CCTM from either ASCII vertical profiles or from an existing CCTM output concentration (CONC) file
data
* **[nacc](nacc/README.md)**: processes meteorological model output from either WRF-ARW or FV3GFSv16 model into I/O API-formatted files that are compatible with CMAQ and SMOKE
* **[create_omi](create_omi/README.md)**: produces an OMI input file that supports CMAQ CCTM's in-line calculation of photolysis rates.
 
