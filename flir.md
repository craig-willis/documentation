# Infrared heat imaging data

Infrared heat imaging data is collected using a FLIR SC615 thermal sensor.

### Level

Raw FLIR thermal imaging output is Level 0 data.

### Sensor information

* [Datasheet](https://terraref.ncsa.illinois.edu/clowder-dev/files/57eae632e4b00b25cabfa4a5?dataset=57eae625e4b00b25cabfa4a1&space=)
* [Calibration certificate](https://terraref.ncsa.illinois.edu/clowder-dev/files/57eae632e4b00b25cabfa4ad?dataset=57eae625e4b00b25cabfa4a1&space=)

### Data format

* Raw data format

* Gantry and sensor variable metadata

### Transformations

* FLIR data is converted to PNG thumbnail and GeoTIFF using the multispectral extractor
  * https:\/\/github.com\/terraref\/extractors-multispectral


### Data access

Thermal imaging data is available via Clowder and Globus:

* Clowder:

  * https:\/\/terraref.ncsa.illinois.edu\/clowder\/collection\/57278c4de4b03269d7053865


* Globus: 
  * \/sites\/ua-mac\/raw\_data\/flirIrCamera


For details about using this data via Clowder or Globus, please see [Data Access](/how-to-access-data.md) section.
