# os-data-hub

os-data-hub contains sample code for using [Ordnance Survey Data Hub APIs](https://osdatahub.os.uk/) with [ArcGIS API for Javascript v4](https://developers.arcgis.com/javascript/).

## What is the OS Data Hub?

The Ordnance Survey Data Hub is a collection of APIs that provide access to a range of Open data and OS Premium data to support developers building apps.

The code samples in this repo demonstrate how a developer using the ArcGIS API for JavaScript v4 can get started with three of the APIs:

- [OS Maps API](https://osdatahub.os.uk/docs/wmts/overview) - access raster tiles via OGC standard WMTS or RESTful ZXY.
- [OS Vector Tile API](https://osdatahub.os.uk/docs/vts/overview) - highly customisable vector tiles.
- [OS Features API](https://osdatahub.os.uk/docs/wfs/overview) - run spatial and attribute queries against a web feature service.

## The code samples

- [Switch between the different basemaps available from the Maps API]().
- [Use client-side code to style the vector tiles provided by the Vector Tile API]().
- [Query the OS Features API for all hospitals within the current map extent](https://github.com/EsriUK/os-data-hub/blob/master/os-features-api/wfs-hospitals.html).
- [Query the OS Features API for all sites within the current map extent. Use smart mapping to classify sites and adapt the legend colours to the selected basemap](https://github.com/EsriUK/os-data-hub/blob/master/os-features-api/wfs-legend.html).

## How to use the samples

To use the samples you first need to sign up to the service and generate an API key.

Information about how to sign up can be found on the [OS Data Hub Plans & Pricing](https://osdatahub.os.uk/plans) page. See the [Getting Started Guide](https://osdatahub.os.uk/docs/wfs/gettingStarted) for instructions about how to set up an API Project and obtaining the API key.

In the sample code replace `INSERT_API_KEY_HERE` with your API key.

## Further resources and examples

The OS Data Hub provides detailed [documentation](https://osdatahub.os.uk/docs) and [examples](https://labs.os.uk/public/os-data-hub-examples/) about all three services.

## License

This project uses the following license: [Apache License 2.0](https://github.com/EsriUK/os-data-hub/blob/master/LICENSE).
