# address_geocoding
Address geocoding workflows using Python

This notebook provides a detailed workflow for geocoding addresses from tabular data such as CSV files. It covers data import, address data cleaning, resolving unmatched addresses, visualizing results on a map, QC operations, and exporting results to GIS format. Nominatim and Google Maps API are the primary geocoders used however other ones may be used from the geopy.geocoders library. Please note you must have your own Google Maps API key to use that service. Nominatim does not require an API key. This notebook is based upon https://youtu.be/N6itC6hbOvo?si=gY-hNBpRieMCEYqu youtube video but modified with additional features and capabilities.
