# Pix4D-VI-library

A collection of Vegetation Indicies for direct use in Pix4Dmapper. 

This has been developed with the Micasense MX in mind. Contributions are welcome! 

# How to use
In the Index Calculator, go to the Index List:

![image](https://user-images.githubusercontent.com/1574585/154044051-7c419878-a7d6-434d-95ed-6b0916faccd7.png)

And you can copy/paste into the list

![image](https://user-images.githubusercontent.com/1574585/154043962-1081540f-3903-4d5c-a4e5-afcb9106939b.png)

# List of indices

| Spectral Index                               | Acronym | Equation | Pix4D                                                  | References                              | Usage     |
|----------------------------------------------|---------|----------|--------------------------------------------------------|-----------------------------------------|-----------|
| Normalized Difference Vegetation Index       | NDVI    |          | (nir - red) / (nir + red)                              | (Rouse et al., 1974)                    | Structure |
| Green Normalized Difference Vegetation Index | GNDVI   |          | (nir - green) / (nir + green)                          | (Gitelson et al., 1996)                 |           |
| Green Leaf Index                             | GLI     |          | ((green - red) + (green - blue))/(2*gree + red + blue) | (Gobron et al., 2000; Hunt et al. 2013) |           |
| Visiable Atmospherically Resistance Index    | VARI    |          | (green - red) / (green + red - blue)                   | (Gitelson et al. 2002)                  |           |
| Triangular Greeness Index                    | TGI     |          | green - 0.39 * red - 0.61 * blue                       | (Hunt et al. 2013)                      |           |
