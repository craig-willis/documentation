# Infrared heat imaging data

Infrared head imaging data is collected using a FLIR SC615 thermal sensor.

## Level

Raw FLIR thermal imaging output is Level 0 data.

## Sensor information

* [Datasheet](https://terraref.ncsa.illinois.edu/clowder-dev/files/57eae632e4b00b25cabfa4a5?dataset=57eae625e4b00b25cabfa4a1&space=)
* [Calibration certificate](https://terraref.ncsa.illinois.edu/clowder-dev/files/57eae632e4b00b25cabfa4ad?dataset=57eae625e4b00b25cabfa4a1&space=)

## Data format

Description of the FLIR raw data.

### Metadata

* Gantry and sensor variable metadata

### Image data

* Binary image format

### Transformations

* FLIR data is converted to PNG thumbnail and GeoTIFF
  * https:\/\/github.com\/terraref\/extractors-multispectral


## Data access

### Clowder

* https:\/\/terraref.ncsa.illinois.edu\/clowder\/collection\/57278c4de4b03269d7053865

### Globus

Raw output from the FLIR infrared sensor is available in:

* \/sites\/ua-mac\/raw\_data\/flirIrCamera

