## Identifying Parking lots using OpenStreetMap Building data

:boom: [Demo](https://venkanna37.github.io/parking_lots/)

**How we can identify parking lots using building data**

  * We can observe more parking lots in places that attract a large number of people like offices, shopping malls etc. Area of building footprints and parking space depends on the number of people visiting.

  * Also if we go through major cities on OpenStreetMap, we can observe large building footprints near parking lots. Using area of building as a filter, we can identify parking lots. 

**Why Building data**
  
  * Compared to POIs, building data is more. This is because for mapping buildings ground observation is not required as opposed POI mapping.
  
**Analysis**
  
  * I took three samples from each of New York, Chicago, and  Los Angeles.
  * Area of each sample is 2.25 sq. km.
  * Area of each building to identify parking lot is greater than 600 sq. m.
  
**Observations**

  * Buildings which are more than 600 sq.m. in area covers 79.63 % of parking lots.
  * 78% of the the buildings did not have big parking lots in its vicinity.
  * POIs were able to identify only 16.7 % of total parking lots.
  * 20.36 % of parking lots were missed using building data.

**How this data useful**

  * It can be used to detect more parking lots.
  
**Tools used to create map**

  * Leaflet
  * Mapbox Studio
  * QGIS for filtering building data

