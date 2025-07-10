## Overview

Soil moisture is a key indicator of desertification patterns. In this project, I used satellite data and geospatial techniques to assess environmental change in the Sudan-Sahel.

## Study Area

- **Region**: Sudan-Sahel Belt 
- **Countries Covered**: Khartoum, Red Sea, South Kordofan
- **Key Characteristics**: Semi-arid climate, strong seasonality, prone to desertification and drought.

---

## Tools & Technologies

- **Google Earth Engine (GEE)**
- **Python (ee, geemap, matplotlib, seaborn, sklearn, and pandas)**
- **QGIS**
- **MODIS / SMAP / GPM** datasets

---

## Methodology

1. **Data Collection** via Google Earth Engine API
2. **Preprocessing**: Cloud masking, reprojection/resampling, clipping to AOI
3. **Soil Moisture Analysis**: Time series trend and seasonal variation analysis
4. **Change Detection**: Between different years/periods (e.g., 2000 vs 2020)
5. **Visualization & Mapping** using QGIS and Python libraries

---

## Key Findings

- MODIS data shows more pronounced surface drying, especially in February, suggesting sensitivity to vegetation and surface conditions.
- SMAP, which captures topsoil moisture more directly, reveals a broader pattern of increasing moisture, but also identifies localized drying, particularly during the wet season in October.
- In Khartoum, both MODIS and SMAP agree on a general decline in soil moisture during February, aligning well with time-series data. October patterns are mixed, indicating variability in seasonal responses.
- In South Kordofan, MODIS and SMAP show general drying in February. In October, MODIS indicates increasing moisture, while SMAP shows mixed signals, pointing to localized variability in moisture retention and possibly the impact of land use.
