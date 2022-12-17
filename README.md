# L.esri.geosearch using custom `<input>`

This plugin demonstrates how to create a custom plugin which wires address search (and autocomplete) to your own html `<input>`.

```html
<input id="address-search" />
```

```js
var search = L.esri.BootstrapGeocoder.search({
  inputTag: "address-search",
  placeholder: "ex. LAX",
}).addTo(map);
```

# API Reference

### `L.esri.BoostrapGeocoder.search`

Supports all the constructor options of [`L.esri.Geocoding.geosearch`](http://esri.github.io/esri-leaflet/api-reference/controls/geosearch.html).

Also expects an `inputTag`.

## Resources

- [Geocoding Service Documentation](http://resources.arcgis.com/en/help/arcgis-rest-api/#/Single_input_field_geocoding/02r300000015000000/)
- [ArcGIS for Developers](http://developers.arcgis.com)
- [ArcGIS REST Services](http://resources.arcgis.com/en/help/arcgis-rest-api/)
- [twitter@geogangster](http://twitter.com/geogangster)

## Licensing

Copyright 2016 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

> http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](https://raw.github.com/Esri/esri-leaflet-geocoder/master/license.txt) file.
