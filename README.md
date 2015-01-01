This repository shows off a transit agency's stops as commits in a git repository.  This repository was generated from publicly availbale NextBus data.  Various data is encoded into each commit.  The name of the stop is the commit body, distance from the center point is represented in seconds past the start date (January 1st, 2015), routes served by each stop are included as the commit author, the agency is represented by the author's email address.  Each route is represented by one or more branches (with one branch per 'direction').  Tags are placed at the start of a branch to facilitate identification in a graph view. 

|Settings||
|---|---|
|agency|sfmta|
|routes|all|
|directions|all|
|center|37.783333, -122.416667|

