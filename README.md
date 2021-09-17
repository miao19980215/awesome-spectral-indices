<p align="center">
  <a href="https://github.com/davemlz/awesome-spectral-indices"><img src="https://raw.githubusercontent.com/davemlz/awesome-spectral-indices/main/docs/_static/asi.png" alt="Awesome Spectral Indices"></a>
</p>
<p align="center">
    <em>A ready-to-use curated list of Spectral Indices for Remote Sensing applications.</em>
</p>
<p align="center">
<a href="https://github.com/sindresorhus/awesome" target="_blank">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome">
</a>
<a href="https://github.com/davemlz/awesome-ee-spectral-indices/blob/main/output/spectral-indices-dict.json" target="_blank">
    <img src="https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/davemlz/5e9f08fa6a45d9d486e29d9d85ad5c84/raw/spectral.json" alt="Awesome Spectral Indices">
</a>
<a href="https://github.com/davemlz/awesome-ee-spectral-indices/actions/workflows/tests.yml" target="_blank">
    <img src="https://github.com/davemlz/awesome-ee-spectral-indices/actions/workflows/tests.yml/badge.svg" alt="Tests">
</a>
<a href="https://awesome-ee-spectral-indices.readthedocs.io/en/latest/?badge=latest" target="_blank">
    <img src="https://readthedocs.org/projects/awesome-ee-spectral-indices/badge/?version=latest" alt="Documentation">
</a>
<a href="https://zenodo.org/badge/latestdoi/355720108"><img src="https://zenodo.org/badge/355720108.svg" alt="DOI"></a>
<a href="https://github.com/sponsors/davemlz" target="_blank">
    <img src="https://img.shields.io/badge/GitHub%20Sponsors-Donate-ff69b4.svg" alt="GitHub Sponsors">
</a>
<a href="https://www.buymeacoffee.com/davemlz" target="_blank">
    <img src="https://img.shields.io/badge/Buy%20me%20a%20coffee-Donate-ff69b4.svg" alt="Buy me a coffee">
</a>
<a href="https://ko-fi.com/davemlz" target="_blank">
    <img src="https://img.shields.io/badge/kofi-Donate-ff69b4.svg" alt="Ko-fi">
</a>
<a href="https://twitter.com/dmlmont" target="_blank">
    <img src="https://img.shields.io/twitter/follow/dmlmont?style=social" alt="Twitter">
</a>
<a href="https://github.com/psf/black" target="_blank">
    <img src="https://img.shields.io/badge/code%20style-black-000000.svg" alt="Black">
</a>
</p>

---

**GitHub**: <a href="https://github.com/davemlz/awesome-ee-spectral-indices" target="_blank">https://github.com/davemlz/awesome-ee-spectral-indices</a>

**Documentation**: <a href="https://awesome-ee-spectral-indices.readthedocs.io/" target="_blank">https://awesome-ee-spectral-indices.readthedocs.io/</a>

---

# Spectral Indices

The ready-to-use curated list of spectral indices ([check the list here](https://github.com/davemlz/awesome-ee-spectral-indices/blob/main/output/spectral-indices-table.csv)) for remote sensing applications is presented here. The list is available in two formats ([CSV](https://raw.githubusercontent.com/davemlz/awesome-ee-spectral-indices/main/output/spectral-indices-table.csv), [JSON](https://raw.githubusercontent.com/davemlz/awesome-ee-spectral-indices/main/output/spectral-indices-dict.json)) so it can be easily used in any programming language.

## Attributes

Each item of the list has the following attributes:

- `short_name`: Short name of the index (e.g. `"NDWI"`).
- `long_name`: Long name of the index (e.g. `"Normalized Difference Water Index"`).
- `formula`: Expression/formula of the index (e.g. `"(G - N)/(G + N)"`).
- `bands`: List of required bands/parameters for the index computation (e.g. `["N","G"]`).
- `reference`: Link to the index reference/paper/doi (e.g. `"https://doi.org/10.1080/01431169608948714"`).
- `type`: Type/application of the index (e.g. `"water"`).
- `date_of_addition`: Date of addition to the list (e.g. `"2021-04-07"`).
- `contributor`: GitHub user link of the contributor (e.g. `"https://github.com/davemlz"`).

## Expressions

The formula of the index is presented as a string/expression (e.g. `"(N - R)/(N + R)"`) that can be easily evaluated. The parameters used in the expression for each index follow this standard:

<table>

<tr>

<th> Description </th>
<th> Standard </th>
<th> Sentinel-2 </th>
<th> Landsat-8 </th>
<th> Landsat-457 </th>
<th> MODIS </th>

</tr>

<tr>

<td>Aerosols</td>
<td>A</td>
<td>B1</td>
<td>B1</td>
<td></td>
<td></td>

</tr>

<tr>

<td>Blue</td>
<td>B</td>
<td>B2</td>
<td>B2</td>
<td>B1</td>
<td>B3</td>

</tr>

<tr>

<td>Green</td>
<td>G</td>
<td>B3</td>
<td>B3</td>
<td>B2</td>
<td>B4</td>

</tr>

<tr>

<td>Red</td>
<td>R</td>
<td>B4</td>
<td>B4</td>
<td>B3</td>
<td>B1</td>

</tr>

<tr>

<td>Red Edge 1</td>
<td>RE1</td>
<td>B5</td>
<td></td>
<td></td>
<td></td>

</tr>

<tr>

<td>Red Edge 2</td>
<td>RE2</td>
<td>B6</td>
<td></td>
<td></td>
<td></td>

</tr>

<tr>

<td>Red Edge 3</td>
<td>RE3</td>
<td>B7</td>
<td></td>
<td></td>
<td></td>

</tr>

<tr>

<td>Red Edge 4</td>
<td>RE4</td>
<td>B8A</td>
<td></td>
<td></td>
<td></td>

</tr>

<tr>

<td>NIR</td>
<td>N</td>
<td>B8</td>
<td>B5</td>
<td>B4</td>
<td>B2</td>

</tr>

<tr>

<td>SWIR 1</td>
<td>S1</td>
<td>B11</td>
<td>B6</td>
<td>B5</td>
<td>B6</td>

</tr>

<tr>

<td>SWIR 2</td>
<td>S2</td>
<td>B12</td>
<td>B7</td>
<td>B7</td>
<td>B7</td>

</tr>

<tr>

<td>Thermal 1</td>
<td>T1</td>
<td></td>
<td>B10</td>
<td>B6</td>
<td></td>

</tr>

<tr>

<td>Thermal 2</td>
<td>T2</td>
<td></td>
<td>B11</td>
<td></td>
<td></td>

</tr>

</table>

Additional index parameters also follow a standard:

- `g`: Gain factor (e.g. Used for EVI).
- `L`: Canopy background adjustment (e.g. Used for SAVI and EVI).
- `C1`: Coefficient 1 for the aerosol resistance term (e.g. Used for EVI).
- `C2`: Coefficient 2 for the aerosol resistance term (e.g. Used for EVI).
- `cexp`: Exponent used for OCVI.
- `nexp`: Exponent used for GDVI.
- `alpha`: Weighting coefficient used for WDRVI.
- `sla`: Soil line slope.
- `slb`: Soil line intercept.

The kernel indices are constructed using a special type of parameters:

- `kAB`: Kernel of bands/parameters `A` and `B` (e.g. `kNR` means `k(N,R)`, where `k` is the kernel function).
- `p`: Kernel degree (used for the polynomial kernel).
- `c`: Free parameter that trades off the influence of higher-order versus lower-order terms (used for the polynomial kernel).

# Used by

## JavaScript

- [spectral](https://github.com/davemlz/spectral): Awesome Spectral Indices for the Google Earth Engine JavaScript API (Code Editor).

## Python

- [eemont](https://github.com/davemlz/eemont): A python package that extends Google Earth Engine.
- [eeExtra](https://github.com/r-earthengine/ee_extra): A ninja Python package behind rgee, rgeeExtra and eemont.
- [spyndex](https://github.com/davemlz/spyndex): Awesome Spectral Indices in Python.

## R

- [rgeeExtra](https://github.com/r-earthengine/rgeeExtra): High-level functions to process spatial and simple Earth Engine objects. Popular Third-party GEE algorithms are re-coded from Javascript and Python to R.

# Spectral Indices by Type

## Vegetation 🌱

### A

- [ARVI](https://doi.org/10.1109/36.134076): Atmospherically Resistant Vegetation Index.
- [ATSAVI](https://doi.org/10.1016/0034-4257(91)90009-U): Adjusted Transformed Soil-Adjusted Vegetation Index.

### B

- [BNDVI](https://www.indexdatabase.de/db/i-single.php?id=135): Blue Normalized Difference Vegetation Index.

### C

- [CIG](https://doi.org/10.1078/0176-1617-00887): Chlorophyll Index Green.
- [CIRE](https://doi.org/10.1078/0176-1617-00887): Chlorophyll Index Red Edge.
- [CVI](https://www.cabdirect.org/cabdirect/abstract/20073176046): Chlorophyll Vegetation Index. 

### D

- [DVI](https://doi.org/10.2307/1936256): Difference Vegetation Index.  

### E

- [EVI](https://doi.org/10.1016/S0034-4257(96)00112-5): Enhanced Vegetation Index. 
- [EVI2](https://doi.org/10.1016/j.rse.2008.06.006): Two-Band Enhanced Vegetation Index. 
- [ExG](https://doi.org/10.13031/2013.27838): Excess Green Index. 

### G

- [GARI](https://www.indexdatabase.de/db/i-single.php?id=363): Green Atmospherically Resistant Vegetation Index.
- [GBNDVI](https://www.indexdatabase.de/db/i-single.php?id=186): Green-Blue Normalized Difference Vegetation Index.
- [GDVI](https://doi.org/10.3390/rs6021211): Generalized Difference Vegetation Index. 
- [GEMI](http://dx.doi.org/10.1007/bf00031911): Global Environment Monitoring Index. 
- [GLI](http://dx.doi.org/10.1080/10106040108542184): Green Leaf Index. 
- [GNDVI](https://doi.org/10.1016/S0034-4257(96)00072-7): Green Normalized Difference Vegetation Index. 
- [GRNDVI](https://www.indexdatabase.de/db/i-single.php?id=185): Green-Red Normalized Difference Vegetation Index. 
- [GVMI](https://doi.org/10.1016/S0034-4257(02)00037-8): Global Vegetation Moisture Index. 

### I

- [IRECI](https://doi.org/10.1016/j.isprsjprs.2013.04.007): Inverted Red-Edge Chlorophyll Index. 

### M

- [MCARI](http://dx.doi.org/10.1016/S0034-4257(00)00113-9): Modified Chlorophyll Absorption in Reflectance Index. 
- [MCARI1](https://doi.org/10.1016/j.rse.2003.12.013): Modified Chlorophyll Absorption in Reflectance Index 1.
- [MCARI2](https://doi.org/10.1016/j.rse.2003.12.013): Modified Chlorophyll Absorption in Reflectance Index 2. 
- [MGRVI](https://doi.org/10.1016/j.jag.2015.02.012): Modified Green Red Vegetation Index.  
- [MNDVI](https://doi.org/10.1080/014311697216810): Modified Normalized Difference Vegetation Index.
- [MNLI](https://doi.org/10.1109/TGRS.2003.812910): Modified Non-Linear Vegetation Index.
- [MSAVI](https://doi.org/10.1016/0034-4257(94)90134-1): Modified Soil-Adjusted Vegetation Index.
- [MSR](https://doi.org/10.1080/07038992.1996.10855178): Modified Simple Ratio.
- [MTCI](https://doi.org/10.1080/0143116042000274015): MERIS Terrestrial Chlorophyll Index.
- [MTVI1](https://doi.org/10.1016/j.rse.2003.12.013): Modified Triangular Vegetation Index 1.
- [MTVI2](https://doi.org/10.1016/j.rse.2003.12.013): Modified Triangular Vegetation Index 2.

### N

- [NDREI](https://doi.org/10.1016/1011-1344(93)06963-4): Normalized Difference Red Edge Index.
- [NDVI](https://doi.org/10.1016/0034-4257(79)90013-0): Normalized Difference Vegetation Index.
- [NGRDI](https://doi.org/10.1016/0034-4257(79)90013-0): Normalized Green Red Difference Index.
- [NLI](https://doi.org/10.1080/02757259409532252): Non-Linear Vegetation Index.

### O

- [OCVI](http://dx.doi.org/10.1007/s11119-008-9075-z): Optimized Chlorophyll Vegetation Index.
- [OSAVI](https://doi.org/10.1016/0034-4257(95)00186-7): Optimized Soil-Adjusted Vegetation Index.

### R

- [RDVI](https://doi.org/10.1016/0034-4257(94)00114-3): Renormalized Difference Vegetation Index.
- [RVI](https://doi.org/10.2134/agronj1968.00021962006000060016x): Ratio Vegetation Index.

### S

- [S2REP](https://doi.org/10.1016/j.isprsjprs.2013.04.007): Sentinel-2 Red-Edge Position.
- [SARVI](https://doi.org/10.1109/36.134076): Soil Adjusted and Atmospherically Resistant Vegetation Index.
- [SAVI](https://doi.org/10.1016/0034-4257(88)90106-X): Soil-Adjusted Vegetation Index.
- [SAVI2](https://doi.org/10.1080/01431169008955053): Soil-Adjusted Vegetation Index 2.
- [SeLI](https://doi.org/10.3390/s19040904): Sentinel-2 LAI Green Index.

### T

- [TCARI](https://doi.org/10.1016/S0034-4257(02)00018-4): Transformed Chlorophyll Absorption in Reflectance Index.
- [TCI](http://dx.doi.org/10.1109/TGRS.2007.904836): Triangular Chlorophyll Index.
- [TGI](http://dx.doi.org/10.1016/j.jag.2012.07.020): Triangular Greenness Index.
- [TSAVI](https://doi.org/10.1109/IGARSS.1989.576128): Transformed Soil-Adjusted Vegetation Index.
- [TVI](http://dx.doi.org/10.1016/S0034-4257(00)00197-8): Triangular Vegetation Index.

### V

- [VARI](https://doi.org/10.1016/S0034-4257(01)00289-9): Visible Atmospherically Resistant Index.

### W

- [WDRVI](https://doi.org/10.1078/0176-1617-01176): Wide Dynamic Range Vegetation Index.
- [WDVI](https://doi.org/10.1016/0034-4257(89)90076-X): Weighted Difference Vegetation Index.

## Burn 🔥

### B

- [BAI](https://digital.csic.es/bitstream/10261/6426/1/Martin_Isabel_Serie_Geografica.pdf): Burned Area Index.
- [BAIS2](https://doi.org/10.3390/ecrs-2-05177): Burned Area Index for Sentinel 2.

### C

- [CSIT](https://doi.org/10.1080/01431160600954704): Char Soil Index Thermal.

### N

- [NBR](https://www.indexdatabase.de/db/i-single.php?id=53): Normalized Burn Ratio.
- [NBRT](https://doi.org/10.1080/01431160600954704): Normalized Burn Ratio Thermal.
- [NDVIT](https://doi.org/10.1080/01431160600954704): Normalized Difference Vegetation Index Thermal.

### S

- [SAVIT](https://doi.org/10.1080/01431160600954704): Soil-Adjusted Vegetation Index Thermal.

## Water 🌊

- [MNDWI](https://doi.org/10.1080/01431160600589179): Modified Normalized Difference Water Index.
- [NDWI](https://doi.org/10.1080/01431169608948714): Normalized Difference Water Index.

## Snow ⛄

- [NDSI](https://doi.org/10.1109/IGARSS.1994.399618): Normalized Difference Snow Index.

## Drought 🏜️

- [NDDI](https://doi.org/10.1029/2006GL029127): Normalized Difference Drought Index.
- [NMDI](https://doi.org/10.1029/2007GL031021): Normalized Multi‐band Drought Index.

## Urban 🏙️

- [EBBI](https://doi.org/10.3390/rs4102957): Enhanced Built-Up and Bareness Index.
- [NDBaI](https://doi.org/10.1109/IGARSS.2005.1526319): Normalized Difference Bareness Index.
- [NDBI](http://dx.doi.org/10.1080/01431160304987): Normalized Difference Built-Up Index.

## Kernel 🎯

- [kEVI](https://doi.org/10.1126/sciadv.abc7447): Kernel Enhanced Vegetation Index.
- [kNDVI](https://doi.org/10.1126/sciadv.abc7447): Kernel Normalized Difference Vegetation Index.
- [kRVI](https://doi.org/10.1126/sciadv.abc7447): Kernel Ratio Vegetation Index.
- [kVARI](https://doi.org/10.1126/sciadv.abc7447): Kernel Visible Atmospherically Resistant Index.

# List

Check the full list of spectral indices with their formulas [here](https://github.com/davemlz/awesome-ee-spectral-indices/blob/main/output/spectral-indices-table.csv).

# Download Raw Files

You can download or clone the repository:

```
git clone https://github.com/davemlz/awesome-ee-spectral-indices.git
```

Or you can download the single files here (right-click > Save link as...):

- JSON: [Raw list](https://raw.githubusercontent.com/davemlz/awesome-ee-spectral-indices/main/output/spectral-indices-dict.json)
- CSV: [Raw list](https://raw.githubusercontent.com/davemlz/awesome-ee-spectral-indices/main/output/spectral-indices-table.csv)

# Credits

- [César Aybar](https://github.com/csaybar): The formidable [pydantic](https://github.com/samuelcolvin/pydantic/) expert and creator of [rgee](https://github.com/r-spatial/rgee).