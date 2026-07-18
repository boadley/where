7.1323118372039165, 3.3893350073217796</name> <Point> <coordinates>3.38933500732178,7.132311837203917,0


Identify unmet business demand in specific geographic regions using free

google maps places is the ultimate alpha, overlay with google maps

NG
Goal: identify the next urban hotspot in currently underpopulated areas

- development plan of regions etc
- surrounding population
- purchasing power of surrounding population


NFL
Goal: ID location business demand gap based on existing POIS

- draw an isochrone starting from fixed point, i.e burton's pond
- count and group all POI within isochrone
- rank all POIS by highest occurring

what do you observe locally?


----------------
- look for clearly stated demand not inferred demand [job board, classified local only job/gig boards]


----------duckdb
Tool 1: FOR a specified AOI, Download OSM/Geofabrik POI, Download Overture Maps POIS, Download Foursqaure OS Places, merge by proximity, and use Foursquare as the primary source where records conflict.

Tool 2: Draw an Isochrone around a specified AOI, count all POI within Isochrone, scrape google maps for reviews et.c for each POI in ischrone, group all POI ...