# heat-api-client
Example client key and usage for the Heat Stress API

## About This Key and Dataset

This repository provides an example client key and code for querying the Heat Stress API, which returns daily values for Heat Index and Wet Bulb Globe Temperature (WBGT) at high spatial resolution.

Current coverage is limited to data from the year 1990 and includes only the summer months (May–September). Additional years will be made available in the near future.

The file `heat-api-client-key.json` is a restricted Google Cloud service account key that grants invoke-only access to a single Cloud Run API endpoint. It cannot access any other Google Cloud resources or services.

---
For a full example Python script using this client key, download and open `heat_api_example.ipynb`.
---
## Security Notice

GitHub secret scanning may flag this repository due to the inclusion of a service account key. This is an intentional inclusion to support transparency and reproducibility.

This key:
- Is limited in scope to a single API service
- Grants read-only access
- Is monitored and may be rotated or revoked if abused

For questions or to request a personalized access key, contact:

rouzbeh@cornell.edu

