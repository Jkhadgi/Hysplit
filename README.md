
# HYSPLIT Back Trajectory Analysis Tool

This Python script generates back trajectories using HYSPLIT (Hybrid Single-Particle Lagrangian Integrated Trajectory) model through the PySPLIT interface. 

## Features
- Generates x-day back trajectories using GDAS1 meteorological data
- Configurable for multiple years, months, and starting hours
- Customizable trajectory heights and locations
- Automated batch processing of multiple trajectories

## Requirements
- Python with packages:
  - pysplit
  - matplotlib
  - pandas
  - numpy
  - basemap
- HYSPLIT model installation
- GDAS meteorological data

## Directory Structure
You need to set up the following directories:
- HYSPLIT working directory
- Trajectory storage directory
- GDAS meteorological data directory

## Usage
1. Install required dependencies
2. Configure directory paths in the script
3. Set desired parameters (years, months, hours, altitude)
4. Run the script to generate trajectories


## Credit 
Source: https://github.com/mscross/pysplit/tree/master/pysplit
