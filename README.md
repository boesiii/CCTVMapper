# CCTVMapper
This plugin plots points along lines from a CSV file by matching an ID column in CSV and a line feature ID. The point is plotted based on the digitized direction of the line (pipe) which is assumed to be upstream point to downstream point.  The CSV file needs to have specific column headings, a sample CSV file and a lines shapefile are included.  The primary purpose for its creation was for plotting sanitary sewer pipe inspection data from CCTV projects.  The resulting point file is a memory layer and will need to be saved out another type of format.

![Screenshot](images/dialog.png)
