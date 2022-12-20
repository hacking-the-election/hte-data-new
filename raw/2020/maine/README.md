# Maine

Maine is a special case because of its lack of complete VTD data, which makes it impossible to run the 
standard data parsing algorithm on. 

Instead, the [Harvard Dataverse file](https://dataverse.harvard.edu/file.xhtml?fileId=5739920&version=40.0) with
its own precincts and election results is used. Since these are not Census precincts, they have no GEOID20. 
In serialization, a FAKE GEOID20 is added for consistency and standardization, preserving the state and county segments of a real census GEOID20 but not the precinct ids. 

Since it comes with geodata as well as election results, there is no separate election data file. The geodata is named geodata.json.

For demographics data, the block demographics are aggregated upwards, since no VTD demographic data exists.  