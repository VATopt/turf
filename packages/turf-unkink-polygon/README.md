# @turf/unkink-polygon

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

## unkinkPolygon

Takes a kinked polygon and returns a feature collection of polygons that have no kinks.
Uses [simplepolygon][1] internally.

### Parameters

*   `geojson` **([FeatureCollection][2] | [Feature][3]<([Polygon][4] | [MultiPolygon][5])>)** GeoJSON Polygon or MultiPolygon

### Examples

```javascript
var poly = turf.polygon([[[0, 0], [2, 0], [0, 2], [2, 2], [0, 0]]]);

var result = turf.unkinkPolygon(poly);

//addToMap
var addToMap = [poly, result]
```

Returns **[FeatureCollection][2]<[Polygon][4]>** Unkinked polygons

[1]: https://github.com/mclaeysb/simplepolygon

[2]: https://tools.ietf.org/html/rfc7946#section-3.3

[3]: https://tools.ietf.org/html/rfc7946#section-3.2

[4]: https://tools.ietf.org/html/rfc7946#section-3.1.6

[5]: https://tools.ietf.org/html/rfc7946#section-3.1.7

<!-- This file is automatically generated. Please don't edit it directly:
if you find an error, edit the source file (likely index.js), and re-run
./scripts/generate-readmes in the turf project. -->

---

This module is part of the [Turfjs project](http://turfjs.org/), an open source
module collection dedicated to geographic algorithms. It is maintained in the
[Turfjs/turf](https://github.com/Turfjs/turf) repository, where you can create
PRs and issues.

### Installation

Install this module individually:

```sh
$ npm install @turf/unkink-polygon
```

Or install the Turf module that includes it as a function:

```sh
$ npm install @turf/turf
```
