# tra/hte-data-new
The complete data repository for The Rebalancing Act/Hacking The Election
It will, in time, contain both 2010 and 2020 data for all 50 states' election results, geodata, and demographics
at both the block and precinct/block group levels. 

# Data 
Sources:
* [DRA](https://github.com/dra2020/vtd_data) - precinct election and population files
* Harvard Voting and Election Database 
* MIT Election Data Database
* U.S. Census - 2010 precinct boundaries and 2010/2020 block boundaries
* [Redistricting Data Hub](https://redistrictingdatahub.org/) - 2020 precinct boundaries 

# Demographics

* demographics.csv - Precinct population/racial breakdown files.

* block_group_demographics.csv - Block group population/racial breakdown files (CA, MT, OR, RI in 2010 and CA, HI, OR, WV in 2020)

* block_demographics.csv - Census block population/racial breakdown files.

# Geodata

* geodata.7z- Compressed precinct geodata files. (2010 blocks if 2010, 2020 blocks if 2020.)

* block_group_geodata.7z - Compressed block group geodata files (CA, MT, OR, RI in 2010 and CA, HI, OR, WV in 2020)

* block_geodata.7z - Compressed [census](https://www2.census.gov/geo/tiger/TIGER2020/) block geodata files. (2010 blocks if 2010, 2020 blocks if 2020.)
    * Note: Due to Github's limits on file size, All the 2010 and 2020 CA/TX files contained simplified (to 20%) geodata to reduce their size, which does not significantly affect the geometry but makes them not completely accurate.

# Election data

* election_data.csv - Precinct election data.

* block_group_election_data.csv - Block group election data (CA, MT, OR, RI in 2010 and CA, HI, OR, WV in 2020)
