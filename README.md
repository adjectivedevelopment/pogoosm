# POGO OSM
An overpass turbo query that highlights the features that Pokemon Go uses from OSM.

# Usage (same as https://github.com/SNiLD/PokemonGoBiomes)
1. Open [pogoosm.txt](pogoosm.txt) file
2. Copy and paste the file contents to http://overpass-turbo.eu/
3. Move the overpass-turbo map to the area where you want (you can also click the small circle to center to your current location)
4. Click **Run** on the top left corner

# Notes
I used this post for a list of the map features used in POGO: https://www.reddit.com/r/TheSilphRoad/comments/4tbvnc/mapping_of_biomeshabitats/.  I used this github repository for help with the query and for inspiration: https://github.com/SNiLD/PokemonGoBiomes.  Also used this thread for help with the query: https://www.reddit.com/r/TheSilphRoad/comments/54sy36/osm_query_to_identify_possible_nests/.  I used this page for the Feature reference: http://wiki.openstreetmap.org/wiki/Map_Features.

I tried to make the colors helpful and currently have two layers of features, but both could be changed.

Here's my mapping of the POGO list to the OSM features, subject to change as others have input
* BASIN
  * landuse=basin
* CANAL
  * waterway=canal
* CEMETERY
  * landuse=cemetery
  * amenity=grave_yard (not sure on this one)
* CINEMA
  * amenity=cinema
* COLLEGE
  * amenity=college
* COMMERCIAL
  * landuse=commercial
* COMMON
  * leisure=common
* DAM
  * waterway=dam
* DITCH
  * waterway=ditch
* DOCK
  * waterway=dock
* DRAIN
  * waterway=drain
* FARM
  * building=farm
* FARMLAND
  * landuse=farmland
* FARMYARD
  * landuse=farmyard
* FOOTWAY
  * highway=footway
* FOREST
  * landuse=forest
* GARDEN
  * leisure=garden
* GLACIER
  * natural=glacier
* GOLF_COURSE
  * leisure=golf_course
* GRASS
  * landuse=grass
* HIGHWAY
  * Not included currently, highway is an entire category, or could be highway=motorway
* HOSPITAL
  * amenity=hospital
* HOTEL
  * tourism=hotel
* INDUSTRIAL
  * landuse=industrial
* LAKE
  * natural=water (this is my interpretation, doesn't match exactly)
* LAND
  * Not included currently, not sure how to interpret
* LIBRARY
  * amenity=library
* MAJOR_ROAD
  * Not included currently, could be highway=primary
* MEADOW
  * landuse=meadow
* MINOR_ROAD
  * Not included currently, could be highway=secondary
* NATURE_RESERVE
  * leisure=nature_reserve
* OCEAN
  * Not included currently, nothing seems to match
* PARK
  * leisure=park
* PARKING
  * amenity=parking
* PATH
  * highway=path
* PEDESTRIAN
  * highway=pedestrian
* PITCH
  * leisure=pitch
* PLACE_OF_WORSHIP
  * amenity=place_of_worship
* PLAYA
  * natural=beach (playa is the spanish word for beach)
* PLAYGROUND
  * leisure=playground
* QUARRY
  * landuse=quarry
* RAILWAY
  * landuse=railway
* RECREATION_AREA
  * landuse=recreation_ground
* RESERVOIR
  * landuse=reservoir
* RESIDENTIAL
  * landuse=residential
* RETAIL
  * landuse=retai
* RIVER
  * waterway=river
* RIVERBANK
  * waterway=riverbank
* RUNWAY
  * aeroway=runway
* SCHOOL
  * amenity=school
* SPORTS_CENTER
  * leisure=sports_centre
* STADIUM
  * leisure=stadium
* STREAM
  * waterway=stream
* TAXIWAY
  * aeroway=taxiway
* THEATRE
  * amenity=theatre
* UNIVERSITY
  * amenity=university
* URBAN_AREA
  * Not included currently, nothing seems to match 
* WETLAND
  * natural=wetland
* WOOD
  * natural=wood
