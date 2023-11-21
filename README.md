# RopeWiki Scraper

## Description

This is a scraper designed to regularly export data from the open source website RopeWiki, a canyoneering database. This data will be integrated into the Canyoneer app on the Apple Store.

## Using this Scraper

### Parts that work well
Any user can run IMPORTS and GET CANYON DATA

### Experimental sections
KML data is still under construction

## To do
1. Finish KML data extraction and conversion
 * Loop through all KML files
 * Maybe explore alternative pulling method?
 * How to link back to PAGEID?
 * Modify GeoJson according to Brice's request
2. Determine how to integrate with Canyoneer
 * Lambda that puts data into public S3 bucket?
