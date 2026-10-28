# Assets and data sources

The visual interface, CSS, JavaScript, timeline, and event-marker styling are bundled in `index.html`. There are no separate local image or script files. These external resources are requested by the page while it runs, so the site requires an internet connection.

## Runtime assets and services

- **Basemap imagery:** Esri World Imagery tiles (`services.arcgisonline.com`). Esri, Maxar, Earthstar Geographics, and the GIS User Community attribution is displayed in the map.
- **Map library:** Leaflet 1.9.4, loaded from `unpkg.com`.
- **Fonts:** DM Sans, DM Mono, and Manrope, loaded from Google Fonts.
- **Global historical tsunami records:** NOAA National Centers for Environmental Information / World Data Service ArcGIS service (`gis.ngdc.noaa.gov`). The page also links to NOAA's [Global Historical Tsunami Database](https://www.ncei.noaa.gov/products/natural-hazards/tsunamis-earthquakes-volcanoes/tsunamis/global-historical-data).
- **Active warning feed:** U.S. National Weather Service alerts API (`api.weather.gov`). The interface labels this feed as U.S.-only and links to UNESCO-IOC's [global warning systems](https://tsunami.ioc.unesco.org/en/warningsystems).
- **Editorial imagery:** NASA Earth Observatory and NASA Earth observatory assets, plus linked public-interest reporting and agency sources. Individual story cards link to their source pages.
- **Reference material:** NOAA, UNESCO-IOC, USGS, NIDM, and other linked public information sources in the page's About, Archive, and event-story views.

This package includes the source page and an attribution guide, not copies of third-party hosted imagery, map tiles, fonts, or libraries. Their providers continue to serve those resources under their own terms.

