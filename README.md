# Pix4D-VI-library

A collection of Vegetation Indicies for direct use in Pix4Dmapper. 

This has been developed with the Micasense MX in mind. Contributions are welcome! 

# How to use
In the Index Calculator, go to the Index List:

![image](https://user-images.githubusercontent.com/1574585/154044051-7c419878-a7d6-434d-95ed-6b0916faccd7.png)

And you can copy/paste into the list

![image](https://user-images.githubusercontent.com/1574585/154043962-1081540f-3903-4d5c-a4e5-afcb9106939b.png)

# List of indices

| Spectral Index                               | Acronym | Pix4D equation                                                     | References                              | Usage       |
|----------------------------------------------|---------|--------------------------------------------------------------------|-----------------------------------------|-------------|
| Normalized Difference Vegetation Index       | NDVI    | (nir - red) / (nir + red)                                          | (Rouse et al., 1974)                    | Structure   |
| Green Normalized Difference Vegetation Index | GNDVI   | (nir - green) / (nir + green)                                      | (Gitelson et al., 1996)                 | Structure   |
| Green Leaf Index                             | GLI     | ((green - red) + (green - blue))/(2 * green + red + blue)          | (Gobron et al., 2000; Hunt et al. 2013) |             |
| Visible Atmospherically Resistance Index     | VARI    | (green - red) / (green + red - blue)                               | (Gitelson et al. 2002)                  |             |
| Triangular Greeness Index                    | TGI     | green - 0.39 * red - 0.61 * blue                                   | (Hunt et al. 2013)                      |             |
| Normalized Difference Red Edge               | NDRE    | (nir - red_edge) / (nir + red_edge)                                | (Barnes et al., 2000)                   | Chlorophyll |
| Optimized Soil-Adjusted Vegetation Index     | OSAVI   | (1+0.16)*(nir - red)/(nir + red + 0.16)                            | (Haboudane et al., 2002)                | Structure   |
| Simplified canopy chlorophyll content index  | SCCCI   | ((nir - red_edge) / (nir + red_edge))/((nir - red) / (nir + red))  | (Raper and Varco, 2015)                 | Nitrogen    |
| Transformed Chlorophyll Absorbtion Ratio     | TCARI   | 3*((red_edge - red) - 0.2 * (red_edge - green) * (red_edge / red)) | (Haboudane et al. 2002)                 | Chlorophyll |
