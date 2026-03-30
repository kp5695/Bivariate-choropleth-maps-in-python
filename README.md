# Bivariate Climate Map - Temperature × Precipitation

This project visualises the relationship between two climate variables simultaneously using a bivariate choropleth map, originally created for North America and adapted here for the contiguous United States. Rather than mapping temperature and precipitation separately, a 4×4 colour matrix encodes both dimensions at once, revealing patterns like the hot-dry Southwest, the cold-wet Pacific Northwest, and the humid Southeast in a single glance.

## Data & Tools

- **Climate data** sourced from TerraClimate 2025 (University of Idaho — Abatzoglou et al.), a high-resolution global monthly climate dataset
- **Country/state boundaries** from Natural Earth (1:10m Admin-0)
- **Built in Python** using xarray and rioxarray for NetCDF raster handling, geopandas for vector clipping, scipy for Gaussian smoothing, and matplotlib for rendering
- **Binning method:** asymmetric quantile classification to balance colour distribution across the map

## Credits

I adapted the original work by @milanjanosov by focusing on the North American Region and United States.
