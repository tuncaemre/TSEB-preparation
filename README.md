# TSEB-preparation
TSEB prep for sorghum.

Necessary Inputs
1-Grid shp file/n
2-Hc, High Res NDVI and Low Res NDVI
3-LAI is calculated based on NDVI and Hc (ndvi_low_res.read(1) * hc.read(1)) * 6.0825 + 1.19134)
