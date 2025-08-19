These files are from a 2023 project processing Landsat data from the USGS API and likely are no longer compatible. The downloader, filters, and api files are not original and minorly amended from another user.

The pipeline folder includes three files. 
The first file queries the API for the correct scenes and filters by quality, cloud coverage, type of satellite, and year.
The second file identifies and processes the tif files by growing season for respective crops.
The third file crops and aligns the files and build a panel of peak NDVI during growing season over time.

This project was eventually abandoned due to issues with canopy and cloud coverge, lack of crop versus wild crop maps, and poor temporal coverage of early Landsat imagery.

