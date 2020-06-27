# eppy and geomeppy_intro

This intro includes:
#### Intro to eppy and geomeppy_tutorial and Intro to eppy and geomeppy_demo

The source documentation of eppy could be found here: https://eppy.readthedocs.io/en/latest/index.html
The source documentation of geomeppy could be found here: https://geomeppy.readthedocs.io/en/latest/

----
#### Intro to eppy_tutorial

Eppy is a scripting language to Energyplus. Eppy puts the idd and idf file into a python data structure, and uses the power of python to edit idf files. 
This tutorial is intended to help you take the first step in using eppy to access idf files and run Energyplus. The demo file is a quick introduction of some tasks that eppy could achive:
* read an idf file with eppy
* access idf objects: **material, consatruction, buidling surfaces, building and zone**
    * view these idf objects
    * add new idf objects
    * modify idf objects
* check range with **for** loop
* batch edit with **eppy_json**
* save modified idf files
* run energy plus on eppy
------

#### Intro to geomeppy_tutorial
---
As mentioned in eppy tutorial that eppy is a scripting language to Energyplus. Eppy puts the idd and idf file into a python data structure, and uses the power of python to edit idf files. Addition to Eppy, GeomEppy is a scripting language to Energyplus, primarily focuses on IDF geometry (zones, surfaces, constructions, etc.)
This tutorial is intended to help you take the first step in using GeomEppy. The demo file is a quick introduction of using GeomEppy to build geometries for idf files:
* access an idf file with geomeppy
* build blocks for the idf file, with zoning specified
* make window with wwr
* import construction from other idf files, and apply construction to the objects
* modified the built geomety: scaling, rotating, etc. 
* visualize and save the built geometry as obj file
* run energy plus on geomeppy
------
