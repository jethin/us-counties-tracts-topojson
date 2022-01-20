<h2>US Counties and Tracts Topojson</h2>

This repository contains individual topojson files for 1) all counties in a US state and 2) all Census tracts in a county. Files are named using the numerical FIPS id for each <a href="https://www.nrcs.usda.gov/wps/portal/nrcs/detail/?cid=nrcs143_013696">state</a> or <a href="https://www.nrcs.usda.gov/wps/portal/nrcs/detail/national/home/?cid=nrcs143_013697">county</a> + ".topo.json". For instance, the file "<a href="https://github.com/jethin/us-counties-tracts-topojson/blob/main/counties/01.topo.json">01.topo.json</a>" contains the county boundaries for Alabama.

The source shapefiles are from the 2018 Census. Counties contain "name" and "id" properties, whic tracts contain only an 11 digit "id" property. The topojson geographic boundaries are unprojected and have been simplified to reduce file size. Note that county and tract boundaries do not match precisely as each has slightly different levels of simplification. Only geographic areas within the continental US are included.

There are approximately 3,147 county topojson files in the "tracts.zip" archive. The individual files have been zipped in order to share them here.
