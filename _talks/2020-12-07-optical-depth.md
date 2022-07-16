---
title: "Development and Validation of an Alternative Column Optical Depth Parameter for ICESat-2 and its Use for Evaluating Ground Surface Signal Retrieval Quality"
collection: talks
type: "Conference proceeding"
permalink: /talks/2020-12-07-optical-depth.md
venue: "American Geophysical Union, Fall Meeting 2020"
date: 2020-12-07
location: "Virtual"
---

**Presenter**: Dr. Brad Klotz

This presentation is based in part on a project I conducted as an undergraduate researcher in the fall of 2019 where I developed a random-forest model to predict the affect of cloud layers on ICESat-2 signal attenuation.

**Abstract**: The Ice, Cloud, and land Elevation Satellite 2 (ICESat-2) is an exceptional remote sensing tool designed to provide high-resolution height estimates of the Earth's surface. The photon counting LiDAR instrument onboard collects data over various surfaces and provides detailed information on regions where present observations are sparse or non-existent. One vital component of the lidar's suite of observations is atmospheric column properties, including cloud and aerosol layer detection as well as total column and integrated backscatter properties. Because the atmosphere attenuates the electromagnetic radiation sent from ICESat-2, ground surface signal retrievals are subsequently affected by the reduced signal quantity and quality. Column optical depth typically conveys an amount of attenuation expected for a given region on the ground, but the built-in functionality for column optical depth is to use the apparent surface reflectance. This dependence requires at a minimum a daytime environment and is limited by other factors as well. A method for bypassing the apparent surface reflectance is to match CALIPSO lidar data with ICESat-2, develop a relationship between integrated backscatter and optical depth from CALIPSO, and use probability matching to relate ICESat-2's integrated backscatter to CALIPSO. This allows for determination of the optical depth for ICESat-2. Once this methodology is in place, we use a machine learning approach to determine the most prominent factors affecting surface signal returns and use this information to predict the expected amount of signal. A specific relationship is developed between the column optical depth and surface signal when the signal is available. The quality of the land surface product within these circumstances is evaluated. Initial results indicate the model predictions of surface signal are accurate to within ~200-500 photons per 280 m along-track segment and that column optical depth is directly related to the reduced signal.
