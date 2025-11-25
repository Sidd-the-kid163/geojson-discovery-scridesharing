# geojson-discovery-scridesharing
Exploring the Google Map API by finding ways to categorize coordinates based on other coordinates. For example, finding point between two locations or creating a radius of circle entrapping some localities.

## onrouteRevised
Using GeoJson (mainly for coordinate purposes), we are able to extract the points that fall between two locations and create a polygon using an upper and lower bound to identify a said point would fall in that shape.

## near1
Creates a certain radius from a location to extract localities to identify if Google Map is able to effectively identify all city/town names.

## near2
Uses distance matrix to find distance between two points and extract their addresses. This is used to compare between multiple points for ridesharing research.
