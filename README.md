# HeroX-GIS
Java Code for HeroX challenge solution

The solution consists of two separate JAR files.  Both files have the same input format on the command line.  The arguments are the input .csv file, the input .shp file, and the output .csv file.  The input .csv file should contain a comma separated list of the latitude and longitude of the points used in the comparison.  A header line is expected at the top of the file.  The shapefile should have the standard sidecar files in the same directory. 

The output for the PointInPoly program will be a comma separate values list of each polygon with the number of times a point was inside each polygon.  The programs includes points completely inside the polygon and points on the boundary in the count.

The output for the geodistance program is a comma separated values list of the input points with the name of the closest area and the distance in meters.  The program calculates the distance from the point to the closest edge of the polygon and not the centroid of hte polygon.

The source code in java is include for each program as well as a pom.xml file with the necessary dependencies if manipulation of the programs is desired.
