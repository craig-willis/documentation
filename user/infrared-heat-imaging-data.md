# Infrared heat imaging data

### Summary

Infrared heat imaging data is collected collected using the FLIR SC615 thermal sensor.

### Raw data access

Thermal imaging data is available via Clowder and Globus:

* **Clowder**: [flirIrCamera collection](https://terraref.ncsa.illinois.edu/clowder/collection/57278c4de4b03269d7053865)
* **Globus**:  `/ua-mac/raw_data/flirIrCamera`
* **Sensor information**: [FLIR Thermal Camera collection](https://terraref.ncsa.illinois.edu/clowder/datasets/5817877a4f0ce77b6655b320)

For details about using this data via Clowder or Globus, please see [Data Access](/how-to-access-data.md) section.

### Computational pipeline

**[Multispectral extractor](https://github.com/terraref/extractors-multispectral)**

* **Description**: Raw sensor output is converted to PNG and GeoTIFF format
* **Output**: `/ua-mac/Level_1/flirIrCamera`

### See also

* [Geospatial information](/user/geospatial-information.md)
