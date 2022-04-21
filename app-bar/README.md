# PDS App Bar
Self-contained JavaScript widget that acts as an application bar for the PDS and PDS-affiliated websites. Currently has:
-  links to PDS nodes, accessed as a drop down list
-  basic information on PDS and the nodes, accessed by hovering over the `i`

Refer to https://pds.nasa.gov/ for a working example.

# Installation

There are two methods of installation:
1. (preferred) Refer to the JS and CSS files as deployed by pds.nasa.gov, e.g.
```
<script src="https://pds.nasa.gov/pds-app-bar/pds-app-bar.js" type="text/javascript"></script>
<link href="https://pds.nasa.gov/pds-app-bar/pds-app-bar.css" type="text/css" rel="stylesheet">
```
2. Download the [package](https://github.com/NASA-PDS/pds-wds-web/releases/latest), upload the `pds-app-bar` folder and its contents to the root directory of the target website, and refer to the JS and CSS files as deployed by the target website, e.g.
```
<script src="/pds-app-bar/pds-app-bar.js" type="text/javascript"></script>
<link href="/pds-app-bar/pds-app-bar.css" type="text/css" rel="stylesheet">
```
