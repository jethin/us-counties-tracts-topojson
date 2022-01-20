# us-counties-tracts-topojson
This repository contains individual topojson files for 1) all counties in a US state and 2) all Census tracts in a county. Files are named using the numerical FIPS id for each <a href="https://www.nrcs.usda.gov/wps/portal/nrcs/detail/?cid=nrcs143_013696">state</a> or <a href="https://www.nrcs.usda.gov/wps/portal/nrcs/detail/national/home/?cid=nrcs143_013697">county</a> + ".topo.json". For instance, the file "01.topo.json" would contain the county boundaries for Alabama.

The source shapefiles are from the 2018 Census. The topojson geographic boundaries are unprojected and have been simplified. County and tract boundaries do not match precisely as each level has slightly different levels of simplification. Only geographic areas within the continental US are included.

There are approximately 3,147 county topojson files in  the"tracts.zip" archive.
