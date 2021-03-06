# Marxan
[Marxan](http://marxan.org/) is a suite of tools designed to help decision makers find good solutions to conservation planning problems. This includes free software that can be used to solve several types of planning problems. Marxan is the most frequently used conservation planning software and has been applied to hundreds of spatial conservation planning problems around the world.

Despite its usefulness, the Marxan process can be challenging. Throughout my process of working with Marxan to create conservation priority zones in South America, I have tried develop models and documentation to help other users more easily create their own Marxan input parameters, including ArcPy (ArcGIS) python library and R scripts for creating **species distribution models, abundance tables, and cost tables**. These tools are meant to supplement the running of Marxan using the [CLUZ](https://anotherbobsmith.wordpress.com/software/cluz/) support plugin in QGIS.

**(1) SSDM package** - run-through example for creating species distribution models based on presence point data <br>
**(2) Zonal Statistics in R** - only use for very small datasets (<100 planning units/zones, <50 distribution models), for large datasets see ArcPy script <br>
**(3) Zonal Statistics in ArcPy** - this method is much faster than the R code, but does require an extra step for merging output tables together to make the final abundance table<br>
**(4) Merge zonal statistics** output tables to final abundance table - if using ArcPy code

Better documentation is in the works...
