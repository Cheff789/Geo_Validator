# GeofencingValidator
Deployment Guide

### Description
* Compares address to lat/long and outputs where the lat/long are compared to the address
* Inputs an input.csv containing "address",latitude,longitude
* Outputs an output.csv containing "address",latitude,longitude,"result"

## Prerequisites
1. Python 3.x
  1. GoogleMaps Api 2.5.2
  
## Local Deployment
```bash
pip install Geo-validator
```
<img src="docs/1.jpg" />

<img src="docs/2.jpg" />

```bash
Geofencingvalidator
```
<img src="docs/3.jpg" />

<img src="docs/4.jpg" />
* Open config.cfg and edit values:
    * Key=yourkey
        * This is your Googlemaps Api key
    * noise=.001
        * Range to concider the correct location smaller = more accurate
    * debug=False
        * if set to True Geofencingvalidator will output to console and output range

```bash
Geofencingvalidator <input.csv> <output.csv>
```

<img src="docs/5.jpg" />

<img src="docs/6.jpg" /><img src="docs/7.jpg" />





