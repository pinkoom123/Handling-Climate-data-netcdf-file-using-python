## 🌡️ Handling Climate Data: NetCDF Files with Python

**Step-by-step guide for processing CHIRPS rainfall and ERA5 temperature NetCDF files** using `xarray`, `matplotlib`, and `cartopy`. Covers data quality checks, temporal filtering (2009-2020), spatial plotting, and point extractions across Ghana.

[

## 📁 Files

| File | Purpose | Format |
|------|---------|--------|
| `Handling-Climate-data-NetCDF-file-using-python.ipynb` | **Complete NetCDF processing workflow** - CHIRPS + ERA5 analysis | Jupyter Notebook |
| `README.md` | Documentation & setup guide | Markdown |

## 🎯 Workflow Overview

1. **Import libraries**: `xarray`, `matplotlib`, `cartopy`
2. **Load NetCDF**: CHIRPS rainfall + ERA5 temperature datasets
3. **Data quality**: Identify & count missing values
4. **Temporal filter**: 2009-2020 period
5. **Annual averages**: Group by year
6. **Spatial plots**: Ghana rainfall/temperature maps (2009-2020)
7. **Statistics**: Mean annual/monthly averages (1991-2020)
8. **Point extraction**: Specific Ghana locations

## 🚀 Quick Start

**1. Install dependencies:**
```bash
pip install xarray netcdf4 matplotlib cartopy cf-units
```

**2. Launch Jupyter:**
```bash
jupyter notebook Handling-Climate-data-NetCDF-file-using-python.ipynb
```

**3. Run all cells** → Generate spatial maps + time series

## 📊 Key Outputs

| Analysis | Time Period | Visualization |
|----------|-------------|---------------|
| **Annual rainfall maps** | 2009-2020 | Spatial plots over Ghana |
| **Annual temperature maps** | 2009-2020 | Spatial plots over Ghana |
| **30-year mean rainfall** | 1991-2020 | Long-term average map |
| **30-year mean temperature** | 1991-2020 | Long-term average map |
| **Monthly climatology** | 1991-2020 | Seasonal patterns |

## 🔧 Data Sources

| Dataset | Variable | Source | Period |
|---------|----------|--------|--------|
| **CHIRPS** | Rainfall | CHIRPS (Satellite) | 1991-2020 |
| **ERA5** | Temperature | ECMWF Reanalysis | 1991-2020 |



## 📄 NO License
Free for academic research.

## 🏷️ Repository Settings
```
Repository name: Handling-Climate-data-NetCDF-file-using-python
Description: 🌡️ Process CHIRPS rainfall + ERA5 temperature NetCDF files with xarray/cartopy 
Topics: climate-data, netcdf, xarray, cartopy, ERA5, CHIRPS
```

**Professional climate data analysis template** - Perfect companion to your thesis work ! 🌍💻
