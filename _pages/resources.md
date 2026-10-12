---
layout: page
title: resources
permalink: /resources/
description: open-source code, datasets, and useful websites for cryosphere research
nav: true
nav_order: 3
---

## code and data

- **Hands-on tutorial to retrieve glacier surface temperature (GST) from MODIS archive using [Xee](https://github.com/google/Xee/tree/main/examples) in Python** — [Jupyter Notebook](https://github.com/arindan/GST_tutorial) - _with this code example, one can analyze the entire MODIS satellite data archive, within a internet-based cloud environment, for land (glacier) surface temperature time series analysis at native temporal resolution or customized requirement_.

  
- **Codes for snow-glacier turbulent heat flux calculation (and surface energy balance model, sublimation, etc.) using weather station data** — [GitHub repository](https://github.com/arindan/Winter-sublimation-at-the-Chhota-Shigri-Glacier-India) - _this can be used to understand or model surface energy balance at snow/glacier surfaces to quantify surface mass loss/gain at a point/AWS location or developing it further to a distributed grid-wise mass balance model_.


- **Codes for glacier geodetic mass balance and error estimation using remote-sensing-based DEM differencing or DoD method** — [GitHub repository and notebooks](https://github.com/arindan/Geodetic-MBs-Large-Glaciers) - _these notebooks can be used to understand and estimate glacier elevation changes (volume changes) employing remote sensing-based DEM differencing method. In addition, processing steps of ICESat-2 altimeter data, in cloud environment [SlideRule](https://slideruleearth.io/), are also given which is useful for comparing various data/methods for evaluating the mass balance results_.  

---

## useful websites for cryosphere research

- **[OGGM](https://oggm.org/)** — _Open Global Glacier Model - an open source glacier model in Python - relatively easy to employ to a single or region-wide or global glaciers_.

  
- **[ITS_LIVE Global Glacier Ice Velocity Products](https://nsidc.org/apps/itslive/)** — _open-data, provides glacier ice velocities at 120 m spatial resolution for all global glaciers since 1985. Once can play with the online [ice velocity browser](https://its-live.jpl.nasa.gov/app/index.html?z=9) to know about the ice velocity of any glacier in the world. Here is the example of the browser showing [ice velocity time series for the largest glacier in India, Siachen Glacier, Ladakh](https://its-live.jpl.nasa.gov/app/index.html?z=12&lat=35.5199&lon=76.9661&lat=35.3535&lon=77.1724&x=1985-01-23&x=2026-10-12&y=-500&y=2605&int=1&int=85)_.


- **[Ames Stereo Pipeline](https://stereopipeline.readthedocs.io/en/latest/introduction.html)** - _free and open source automated geodesy and stereogrammetry tool, runs in Python, designed for processing stereo images captured from satellites, such as [ASTER_L1A uncorrected stereo images](https://stereopipeline.readthedocs.io/en/latest/examples/aster.html). This tool can be used to generate DEM of any region for a given/recent date at 30 m spatial resolution with sufficient accuracy (a very nice example jupyter notebook is provided [here](https://github.com/uw-cryo/asp_tutorials)). Once such DEM is created for two different time periods over glaciated areas (landslide/mass-flow areas), glacier elevation change and mass loss (subsidence/volume loss) can be estimated using the codes given_.

- **[Geospatial Data Analysis with Python from University of Washington](https://uwgda-jupyterbook.readthedocs.io/en/latest/intro.html)** - very useful resource to learn Python for various climate and geospatial data analysis workflow in easy and intuitive ways. For Python beginners, going over the modules from the staring is highly recommended. 

