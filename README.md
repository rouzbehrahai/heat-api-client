# heat-api-client

Example code and usage instructions for querying the **Heat Stress API**, a public endpoint that returns daily values for Heat Index and Wet Bulb Globe Temperature (WBGT) at 1km by 1km spatial resolution.

---

## About This API and Dataset

The Heat Stress API provides climate stress data based on NASA Daymet and ERA5-Land, including calculations for:

- Heat Index (HI) min, mean, max (°C)
- Wet Bulb Globe Temperature (WBGT) min, mean, max (°C)

Each query returns data from a specific day and geographic point (lat/lon), selecting the encompassing grid cell.

**Current coverage** is limited to:
- **Year:** 1990
- **Dates:** May 1 – September 30
- **Format:** 1km resolution `.parquet` files stored in Google Cloud Storage

---

## Public API Access (No Key Required)

You can access the API directly — no authentication is required.

you can use this URL: https://heat-api-public-612792994315.us-central1.run.app/query

in this example format: https://heat-api-public-612792994315.us-central1.run.app/query?year=1990&date=1990-05-01&lat=26.0&lon=-97.4

or reference the python code in this repository called **query_heat_api.py**

