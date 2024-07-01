# Chapter 7: Access to Banking Spatial Indicators based on Floating Catchment Area approach

Earlier versions of this chapter have been included in the following presentations: 
- ``Dynamic mapping of access to banking in Wales. A path to closing the banking deserts." Symposium on Spatiotemporal Data Science 2023, Center for Geographic Analysis, Harvard Universit"y;
- ``Modified floating catchment area for measuring access to banking. The case of Wales." Equitable, Accessible, Sustainable Mobility Workshop. GIScience Conference, Leeds, 2023

This folder contains:
- a branch location shapefile to be used as an example. Extraction from 202307. It contains only the Wales points.
- a notebook showing how the calculation of the access indicator has been done. In order to run this botebook one would also need:
     - a detailed spatial tesellation (Output Areas here) and their population weighted centroids
     - Population for these areas. If demographic characteristics are available, the analysis can be run for specific categorises which are mostly affected by poor access (i.e. oder people)
     - an Origin Destination Matrix between the points of demand (PWC) and points of service. Here I used a Distance `matrix calculated in QGIS but OD Matrix with real distances & modes of transportation could be used without a change in code
     - other impedance funtions than the ones I used here can be easily embedded too.
